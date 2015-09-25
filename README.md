phonepwn
==========

This is a real world implementation of the hacking mechanic in the game Watch_Dogs by using a scriptable AI called Cortana:

http://www.fastandeasyhacking.com/download/cortana/cortana_tutorial.pdf


This is my attempt at doing just that.



OS: Kali Linux Nethunter (or kali on chroot on any other phone)

Requires:
- A working Kali environment
- Metasploit
- Armitage


HOW TO USE
==========

1. Git clone
2. Be sure to put GenIP.sh in `/opt`
3. Move files to `/usr/share/armitage/scripts`
4. Make the directory if it isnt there (`mkdir /usr/share/armitage/scripts`)
5. Fire up the teamserver, or armitage.
6. Load up another terminal and type:

`java -jar cortana.jar local.prop ./scripts/custom.cna`
