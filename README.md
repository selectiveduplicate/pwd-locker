# Password-Locker
An insecure password locker/manager program written using Python.

Provided Python is installed and the two files are in the same folder and in the "system PATH" on Windows, the script can be run by pressing WIN+R on Windows and typing:

```
pw account_name
```
If the account_name exists, then the password will be copied to clipboard and a relevent message will be displayed.

Of course the dictionary used in the script may be modified to store passwords of more user accounts and can be accessed in the same way. 

I will be porting this project to Linux as soon as I can to learn how things can be done there, and will update the instructions.

On Linux, for convenience, the Python script should be in the /home/username folder. Then the .py file's permission must be changed to make it executable by typing:

```bash
chmod +x pw.py
```
Then the script can be run simply by typing:

```bash
./pw.py account_name
```
***Note:*** There might be a "Pyperclip could not find a copy/paste mechanism for your system" message. To solve this, xclip or xsel needs to be installed by typing:
```bash
sudo apt-get install xsel utility
```
