# zeromq
steps to run the server and client files

  1. create virtua environment in pyhton3
  ```
  virtualenv -p python3 <env name>
  ```
  2. install ZeroMQ
  ```
     pip install pyzmq
  ```
    
  3. activate environment
  ```
  ```
  
  4.run server file
  ```
    python server.py
  ```
  
  5. run client file with string argument
  ```
    python client.py 'hello jomon'
  ```
  
  Nb: run server and client in two terminals you can seee the outputs
  
  ## Notes:
  
  Here I using 
  
  Request/Reply Pattern: Used for sending a request and receiving subsequent replies for each one sent.
  
  Use-cases:

    -For simple communications between a server and client(s).

    -Checking information and requesting updates.

    -Sending checks and updates to the server.

    -Echo or ping/pong implementations.

Socket type(s) used:

    -zmq.REP
    -zmq.REQ


  
