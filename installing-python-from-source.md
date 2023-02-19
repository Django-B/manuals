# installing python from source

## 1. Download the version you want
* Open https://www.python.org/downloads/source/
* Find the right version
* Download this version

### Example
`wget https://www.python.org/ftp/python/3.6.9/Python-3.6.9.tgz`

## 2. Unpack the archive
`tar xvf Python-3.6.9.tgz`

## 3. Go to the directory
`cd Python-3.6.9`

## 4. Create a directory for all dependencies
`mkdir ~/.python`

## 5. Installing in our directory
`./configure --enable-optimizations --prefix=/home/user/.python`
* Before the next command, you must install make
`make -j8`

## If you want to install python on your system
`sudo make altinstall`
