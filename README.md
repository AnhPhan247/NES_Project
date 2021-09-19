# NES_Project

Installation instruction:

1. Get Ubuntu 14.04 32bit: ubuntu-14.04.6-desktop-i386.iso 
https://releases.ubuntu.com/14.04/
2. sudo apt-get install build-essential
3. sudo apt install openjdk-7-jdk openjdk-7-jre
4. add $JAVA_HOME to PATH: https://stackoverflow.com/questions/24641536/how-to-set-java-home-in-linux-for-all-users

Add these lines to /etc/profile: \
export JAVA_HOME=/usr/lib/jvm/java-7-openjdk-i386 \
export PATH=$PATH:$JAVA_HOME

5. git clone https://github.com/contiki-os/contiki
6. cd contiki/tools/cooja
7. git submodule update --init
8. git apt install ant
9. ant run

Futher information: https://github.com/contiki-os/contiki/wiki/An-Introduction-to-Cooja

NOTE: Do not use Ubuntu 64-bit, I havent tried Ubuntu 16.04, but you may give it a try.
