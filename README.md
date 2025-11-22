# Afido-task_3
Password Cracking
✅ Password Cracking in Kali Linux using JSON – Simple Explanation

Kali Linux is used for ethical hacking and security testing.
Password cracking usually uses tools like:

John the Ripper

Hydra

Hashcat


These tools normally use wordlists or hash files.

But where does JSON come in?

JSON is not used directly for cracking a password, but JSON can be used in three ways:

##Task Command 
Crack MD5 hash	john --wordlist=rockyou.txt hash.txt
Show result	john --show hash.txt
Crack ZIP password	zip2john file.zip > hash.txt then john hash.txt
Crack Linux passwords	unshadow /etc/passwd /etc/shadow > hash.txt then john hash.txt
Resume session	john --restore
