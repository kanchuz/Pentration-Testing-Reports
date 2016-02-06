## Bandit Level 0 ##
level goal: Access the server

Steps:

1. Open Terminal in root access.
2. access level 0 of the bandit.labs.overthewire.org using SSH.
  `ssh bandit0@bandit.labs.overthewire.org`
3. pw is `bandit0`


##Bandit Level 0 → Level 1
level goal: find the readme file get password

Steps:

1. `ls`.
2. `cat readme`.
3. copy the password.

##Bandit Level 1 → Level 2
level goal: get the password from file `-` 

Steps:

1. access level 1 using ssh.
 `ssh bandit1@bandit.labs.overthewire.org`
2. use the copied password.
3. open the file "-".
	`cat ./-`
4. copy the password.

##Bandit Level 2 → Level 3##
level goal: open the file that has spaces in the file name and get pw 

Steps:

1. access level 2 using ssh.
 `ssh bandit2@bandit.labs.overthewire.org`
2. use the copied password.
3. open the file.
`cat spaces/ in/ this/ filename`
or
`cat "spaces in this filename"`
4. copy the password

##Bandit Level 3 → Level 4  
level goal: get pw from hidden file
Steps:

1. access level 3 using ssh.
 `ssh bandit2@bandit.labs.overthewire.org`
2. use the copied password.
3. open move to directory.
`cd inhere`
4. find available files in the directory.
`find`
5. open the hidden file.
`cat ./.hidden`
6. copy the password.

##Bandit Level 4 → Level 5  
level goal: get pw from human readable file
Steps:

1. access level 4 using ssh.
 `ssh bandit4@bandit.labs.overthewire.org`
2. use the copied password.
3. open move to directory.
`cd inhere`
4. find available files in the directory.
`find`
5. open file named "file07".
`cat ./-file07`
6. copy the password. 

