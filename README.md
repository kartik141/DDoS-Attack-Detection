# DDoS-Attack-Detection
A python written ddos attack script to detect and alert in your discord server and send the dump file.

## Check Default Python Version

```
You can check python version on Ubuntu from command line

python --version
```

## Dependencies:

> sudo apt update

> sudo apt upgrade

> sudo apt install build-essential checkinstall

> sudo apt install libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev

> sudo wget https://www.python.org/ftp/python/3.10.0/Python-3.10.0.tar.xz

> tar xvf Python-3.10.0.tar.xz

> cd Python-3.10.0/

> ./configure

> sudo make altinstall

```
make altinstall command skips creating symlink, so /usr/bin/python still points to the old version of Python and your Ubuntu system won’t break.

Once that’s done, you can use Python 3.10.0 shell by typing the following command:

python3.10.0


To exit the Python 3.10.0 shell, type

quit()
```

## Check Version:

> python3.10.0 -V

Output:
```
Python 3.10.0
```

## Installation

> 1. Edit the script and configure how you want it. (Ex.: sudo nano attackdetect.py)

> 2. Then run the python script. (Ex: python attackdetect.py)
