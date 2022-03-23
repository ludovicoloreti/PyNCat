# PyNCat
Simple NetCat client/server written in Python

# Basic Usage

`python3 pyncat.py --help`

# Usage

```
### Listen to a specific port and then execute shell when client connect

pyncat.py -t IP -p PORT -l -c 

### Listen to a specific port and then upload a file

pyncat.py -t IP -p PORT -l -u=file.txt

### Listen to a specific port and execute a shell command

pyncat.py -t IP -p PORT -l -e=\"cat /etc/passwd\" 

### Print a local text to a server using port $PORT

echo 'ABCDEFGHI' | ./pyncat.py -t IP -p PORT # echo local text to server port $PORT

### Client used to connect to a server

pyncat.py -t IP -p PORT # connect to server
```
