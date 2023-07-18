# md5
This is a linux command line utility for md5 hashing algorthim

# How to run md5 linux command line utility:

  You can run the command in two ways:
    1. You can use the php interpreters to run the commands
    2. Else you use the following commands to execute the commands

## First way to the run the md5 linux command

` git clone https://github.com/sathiskumar-saravanan/md5.git`

` php md5 "<string>"`

## Second way to run the md5 linux command

1. First clone the repo
  ` git clone https://github.com/sathiskumar-saravanan/md5.git`

2. Goto inside the code directory
   `pwd`
   
3. Copy the directory getting the output of the above command
    `export PATH="$PATH: The path you getting output from the above command"`
   The 3rd step is only the make the path variable is temporary. It means when you close the terminal windows the PATH you will be destroyed. So, If you want to make that permanent then add that command into .bashrc file.
   i. `nano .bashrc`
   ii. paste the 3rd command
   iii. `source .bashrc`
   Doing the above step make your files or in that directory accessible anywhere in the system.

4. Change the file permission should be executable
   `chmod +x *`
5. Execute the command
   `md5 "<string>"`






