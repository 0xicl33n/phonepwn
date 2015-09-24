phonepwn
==========

This is a real world implementation of the hacking mechanic in the game Watch_Dogs by using a scriptable AI called Cortana:

http://www.fastandeasyhacking.com/download/cortana/cortana_tutorial.pdf


This is my attempt at doing just that.

Place GenIP.sh in /opt


OS: Kali (any version)

Requires:
- Metasploit
- Armitage
-
HOW TO USE
==========

1. Git clone 
2. Move files to /usr/share/armitage/scripts
3. Make the directory if it isnt there (mkdir /usr/share/armitage/scripts)
4. Fire up the teamserver, or armitage.
5. Load up another terminal and type:

`java -jar cortana.jar local.prop ./scripts/custom.cna`
