# Proxy-WebServer
Proxy web servers crafted using different programming languages. (Just for fun, not for comparing!) 😉

## Python Proxy Server
Inorder to run the server:
`python3 server.py --max_conn=10 --buffer_size=8192`

## Explanation
#### `python3`: This command invokes the Python 3 interpreter to run the specified script.
#### `server.py`: This is the name of the Python script that you want to execute.
#### `--max_conn=10`: This is a command-line argument passed to the server.py script. It sets the maximum number of connections that the server can handle to 10.
#### `--buffer_size=8192`: This is another command-line argument passed to the server.py script. It sets the buffer size for data transmission to 8192 bytes (or 8 KB).

# To send the request:
`curl -x http://localhost:8080 http://wikipeadia.org`
