This tutorial helps you to change your default shell from ksh to bash. 

First, let's start by examining your default shell.

1. Type the following command in terminal:
```unix
echo $SHELL
```

2. If your default shell is bash, you should see the console output something similar to this:
```unix
/bin/bash
```

3. If not, run the following command to change your current shell to bash.  
```unix
chsh -s /bin/bash <EID>
```

4. Now log out and back in for the new setting to take effect. 

5. Repeat step 1. 
