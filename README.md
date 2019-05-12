# java8
Installation of Java 8 on Ubuntu 18

    1  sudo apt install default-jre
    2  sudo apt install default-jdk
    3  sudo apt install openjdk-8-jdk
    4  sudo add-apt-repository ppa:webupd8team/java
    5  sudo apt install oracle-java8-installer
    6  sudo update-alternatives --config java
    7  java -version
    8  wget -q -O - https://pkg.jenkins.io/debian/jenkins-ci.org.key | sudo apt-key add -
    9  echo deb https://pkg.jenkins.io/debian-stable binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list
   10  sudo apt-get update
   11  sudo apt-get install jenkins
   12  sudo systemctl status jenkins
