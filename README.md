# README
Clone the above repository and open using sbt.

#Run the following commands

## Install sbt
```bash
echo "deb https://repo.scala-sbt.org/scalasbt/debian all main" | sudo tee /etc/apt/sources.list.d/sbt.list
echo "deb https://repo.scala-sbt.org/scalasbt/debian /" | sudo tee /etc/apt/sources.list.d/sbt_old.list
curl -sL "https://keyserver.ubuntu.com/pks/lookupop=get&search=0x2EE0EA64E40A89B84B2DF73499E82A75642AC823" | sudo apt-key add
sudo apt-get update
sudo apt-get install sbt
```
## Clone the Github Repository
Use the clone command to clone the repository.
```bash
Clone this git repo using git clone
```

##### Change the working directory to the cloned directory
```bash
using cd ..(directory name)
```
##### Run the following commands

```bash
sbt clean
sbt compile
sbt package
```
