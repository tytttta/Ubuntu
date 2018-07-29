# Ubuntu 18.04 安装java8
## 1: 添加ppa

sudo add-apt-repository ppa:webupd8team/java
sudo apt-get update

## 2: 安装oracle-java-installer

sudo apt-get install oracle-java8-installer
## 3: 设置系统默认jdk

sudo update-java-alternatives -s java-8-oracle

## 4: java安装测试

java -version
javac -version

