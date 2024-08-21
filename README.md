# OverTheWire-Bandit
overthewrite the bandit challange for bios club 
#

## Level-0
>ssh bandit0@bandit.labs.overthewire.org -p 2220
>Password- bandit0

## Level-1
>ssh bandit0@bandit.labs.overthewire.org -p 2220
>Password- ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

## Level-2
>ssh bandit1@bandit.labs.overthewire.org -p 2220
>ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
>ls
>cat readme
>Password- 263JGJPfgU6LtdEvgfWU1XP5yac29mFx

## Level-3
>ssh bandit2@bandit.labs.overthewire.org -p 2220
>263JGJPfgU6LtdEvgfWU1XP5yac29mFx
>ls
>cat "spaces in thsi filename"
>Password- Mnk8KNH3Usiio41PRUEoDFPqfxLPlSmx

## Level-4
>ssh bandit3@bandit.labs.overthewire.org -p 2220
>Mnk8KNH3Usiio41PRUEoDFPqfxLPlSmx
>ls
>cd inhere
>ls
>ls -a
...Hiding-From-You
>ls
>cat ...Hiding-From-You
>password- 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

## Level-5
>ssh bandit4@bandit.labs.overthewire.org -p 2220
>2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
>ls
>cd inhere
>ls
7 files have shown
>Cat <-file07
>Password- 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw

## Level-6
>ssh bandit5@bandit.labs.overthewire.org -p 2220
>4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
>ls
>cd inhere
>ls -l
Total 80 files have shown
>find . -readable -size 1033c ! executable
>cat maybehere07/.file2
>Password- HwasnPhtq9AVKe0dmk45nxy20cvUa6EG

## Level-7
>ssh bandit6@bandit.labs.overthewire.org -p 2220
>HwasnPhtq9AVKe0dmk45nxy20cvUa6EG
>ls -a
>find / -user bandit7 -group bandit6 -size 33c
find the file whose passward is not denied
>cat /var/lib/dpkg/info/bandit7.password
>Password- morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

## Level-8
>ssh bandit7@bandit.labs.overthewire.org -p 2220
>morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
>ls
>cat data.txt
>greb millionth data.txt
>Prassword- dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc

## level-9
>ssh bandit8@bandit.labs.overthewire.org -p 2220
>dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
>ls
>cat data.txt
>sort data.txt | uniq -u
>Password- 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

## Level-10
>ssh bandit9@bandit.labs.overthewire.org -p 2220
>4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
>ls
>cat data.txt
>strings data.txt | grep "=="
>Password- FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

## Level-11
>ssh bandit10@bandit.labs.overthewire.org -p 2220
>FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
>ls
>cat data.txt
>base64 -d data.txt
>Password-dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr

## Level-12
>ssh bandit11@bandit.labs.overthewire.org -p 2220
>dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
>ls
>cat data.txt
>cat data.txt | tr A-Za-z N-ZA-Mn-za-m
>Password-7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4

## Level-13
>ssh bandit12@bandit.labs.overthewire.org -p 2220
>7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
>id
>ls
>cat data.txt
>cp data.txt /tmp/sh/
>cd /tmp/sh
>ls
>xxd -r data.txt > bandit
>ls
>file bandit
>mv bandit bandit.gz
>ls
>file bandit
>mv bandit bandit.bz2
>ls
>bzip2-d bandit.bz2
>ls
>file bandit
>mv bandit bandit.gz
>ls
>file bandit
>mv bandit bandit.tar
>ls
>tar -xf bandit.tar
>ls
>file data5.bin
>mv data5.bin data5.tar
>ls
>tar -xf data5.tar
>ls
>file data6.bin
>mv data6.bin data6.bz2
>bzip2-d data6.bz2
>ls
>file data6
>mv data6 .data6.tar
>tar -xf data6.tar
>ls
>file data8.bin
>mv data8.bin data8.gz
>gunzip data8.gz
>ls
>file data8
>cat data8
>Password- FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn

## Level-14
>ssh bandit13@bandit.labs.overthewire.org -p 2220
>FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
>ls
>cat sshkey.private
>ssh -HostKeyAlgorithms=+ssh-dss -i sshkey.privatebandit14@localhsot -p 2220
>yes
>id
>cat/etc/bandit_pass/bandit14
>Password-MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS

## level-15
>ssh bandit14@bandit.labs.overthewire.org -p 2220
>MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
>id
>ls
>nc localhost 30000
>MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
>Password-8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo

## Level-16
>ssh bandit15@bandit.labs.overthewire.org -p 2220
>8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
>id
>ls
>openssl s_client -connect localhost:30001
>8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
correct
>Password-kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx

## Level-17
>ssh bandit16@bandit.labs.overthewire.org -p 2220
>kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx
>nc -nv -w 1 -z 127.0.0.1 31000-32000 2&>1 | grep succeeded
>openssl s_client -connect localhost:31790
>kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx
>correct
>cd /tmp/mytmp66666
>nano sshkey
>chmod 600 sshkey
>ssh -HostKeyAlgorithms=+ssh-dss -i sshkey.privatebandit17@localhsot -p 2220
>yes
>ls /etc/bandit_pass/
>cat /etc/bandit_pass/bandit17
>Password-EReVavePLFHtFlFsjn3hyzMlvSuSAcRD

## Level-18
>ssh bandit17@bandit.labs.overthewire.org -p 2220
>EReVavePLFHtFlFsjn3hyzMlvSuSAcRD
>id
>ls
>diff passwords.new password.old
>Password- x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO

## Level-19
>ssh bandit18@bandit.labs.overthewire.org -p 2220
>x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO
>ssh -HostKeyAlgorithms=+ssh-dss -i sshkey.privatebandit17@localhsot -p 2220 /bin/sh
>id
>ls
>readme
>cat readme
>cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8

## level-20
>ssh bandit19@bandit.labs.overthewire.org -p 2220
>cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8
>id
>ls -l
>./bandit20-do
>./bandit20-do id
>cat /etc/bandit_pass/bandit20
>./bandit20-do cat /etc/bandit_pass/bandit20
>Password- 0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO

## Level-21
>First open 2 windows in termial
>on the first terminal
>ssh bandit20@bandit.labs.overthewire.org -p 2220
>0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO
>ssh -HostKeyAlgorithms=+ssh-dss -i sshkey.privatebandit17@localhsot -p 2220
>0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO
>nc -lvp 2341

>on the second terminal
>ls
suconnect
>ls -la
>./suconnect
>./suconnect 2341

>Again on First terminal after connection is sucessfull
>connected
>0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO
Password matches
>EeoULMCra2q0dSkYj561DX7s1CpBuOBt

>Exit
>Clear
