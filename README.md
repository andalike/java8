# java8
Installation of Java 8 on Ubuntu 18


    1  sudo apt update
    2  java -version
    3  sudo apt install default-jre
    4  java -version
    5  sudo apt install default-jdk
    6  sudo apt install openjdk-8-jdk
    7  java -version
    8  sudo apt install openjdk-8-jdk
    9  java -version
   10  sudo add-apt-repository ppa:webupd8team/java
   11  sudo apt update
   12  sudo apt install oracle-java8-installer
   13  sudo update-alternatives --config java
   14  java --version
   15  java -version
   16  history
   17  wget -q -O - https://pkg.jenkins.io/debian/jenkins-ci.org.key | sudo apt-key add -
   18  echo deb https://pkg.jenkins.io/debian-stable binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list
   19  sudo apt-get update
   20  sudo apt-get install jenkins
   21  sudo systemctl status jenkins
   22  sudo nano /var/lib/jenkins/secrets/initialAdminPassword
   23  history
