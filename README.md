# pingsshtool 
python 2.7 
a nest multi-threaded ping and ssh tool
pingtool.py will scan a network then create a ipname.txt file

The startpingssh.py file will call the pingtool.py script and loop over all the IPs it found on the network and attempt to ssh into each one using the usernames and password stored in the pass.txt file.

