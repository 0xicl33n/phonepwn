phone_dogs
==========

After playing watch_dogs... i thought to myself there had to be a way to implement the "hacking" mechanic in real life...Well it totally is possible..


Using Cortana.

http://www.fastandeasyhacking.com/download/cortana/cortana_tutorial.pdf


This is my attempt at doing just that.

Place GenIP.sh in /opt


OS: Debian

HOW TO USE
==========


I recommend trying to run this from within kali linux.


1. Git clone 
2. Move files to /usr/share/armitage/scripts
3. Make the directory if it isnt there (mkdir /usr/share/armitage/scripts)
4. Fire up the teamserver, or armitage.
5. Load up another terminal and type:

java -jar cortana.jar local.prop ./scripts/custom.cna
