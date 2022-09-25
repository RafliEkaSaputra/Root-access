# Root-access

1. add new user

        sudo adduser {user name}

2. create file in sudoers.d

        nano {file name}
     
3. chmod the file 

        chmod 440 {file name}

4. add user to Sudo group 

        usermod -aG sudo pretest
