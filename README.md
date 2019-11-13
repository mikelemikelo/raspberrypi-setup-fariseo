
# raspberrypi-setup-fariseo
Fariseo raspberry setup

### ssh into rasp:

ssh pi@LOCAL_IP 

sudo apt-get update

### Mvn

cd /opt

sudo wget http://www.mirrorservice.org/sites/ftp.apache.org/maven/maven-3/3.2.5/binaries/apache-maven-3.2.5-bin.tar.gz

sudo tar -xzvf /path/to/apache-maven-3.2.5-bin.tar.gz

rm apache-maven-3.2.5-bin.tar.gz

sudo sudoedit /etc/profile.d/maven.sh


Add to nano:
```
export M2_HOME=/opt/apache-maven-3.2.5
export "PATH=$PATH:$M2_HOME/bin"
```

To save , hold Control and X, confirm and enter.

Restart shell to confirm updates.



jro-> edoyqqpstv-> xzf
