# Quickstart
## Installation
```
pip3 install pyyaml
git clone git@github.com:the-real-finnventor/insult.git
echo alias insult-path="$PWD"/insult/insult >> ~/.zprofile
echo alias insult="python3 insult-path" >> ~/.zprofile
```

If you are getting errors like:
```
Cloning into 'insult'...
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
```

Then try:
```
git clone https://github.com/the-real-finnventor/insult.git
echo alias insult-path="$PWD"/insult/insult >> ~/.zprofile
echo alias insult="python3 insult-path" >> ~/.zprofile
```
## Installation (if you don't care about the settings)
```
pip3 install finnsult
open ~/.zprofile
```
Now find `${PATH}`. Put your cursor before that and paste this: `/Users/INSERT_YOUR_USERNAME_HERE/Library/Python/3.9/bin:`. Then replace `INSERT_YOUR_USERNAME_HERE` with your username (eg. finneverspaugh). If you are unsure of you username at any time in the terminal (unless the terminal is actively doing something) it should say `username@computername`.
> Note: If you install using this method, the `insult --update` (or `-u`) will not work. you would have to use `pip3 install --update finnsult`
## Run (at any time open a terminal and run)
```
insult
```
