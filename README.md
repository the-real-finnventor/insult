# Quickstart
## Installation
```
pip3 install pyyaml
git clone git@github.com:the-real-finnventor/insult.git
echo alias insult-path="$PWD"/insult/insult >> ~/.zprofile
echo alias insult="python3 insult-path" >> ~/.
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
echo alias insult="python3 insult-path" >> ~/.
```

## Run (at any time open a terminal and run)
```
insult
```
