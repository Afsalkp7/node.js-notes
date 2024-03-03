# node.js-notes

 - "Node js is a non-blocking javascript runtime environment ,<br />
 You can concurrently run an HTTP Server, read files from disk, <br />
 send UDP datagrams, accept TCP connections from clients <br /> and still have room
 to execute JavaScript code operations without blocking."

* Run time environment ? <br />
    - That means node js allow you to execute javascript codes out side the web browser
* Non-blocking ? <br />
    - That refers the asyncronous nature of node js . unlike treditional synchronous programming , where one operation must be complete before another one starts, Node js allow multiple operation to be executed concurrently without waiting for each other to finish (parallel execution).
* HTTP server ? <br />
    - You can create a webserver that listen http requests and response to them.
* Reading files from disk ? <br />
    - You can read files from file system with out waitng each file operation to be completed
* UDP datagram (User Datagram Protocol) ? <br />
    - Which allow you to sent data through network asynchronously.

<hr />
# Event Loop in node js <br />

<br />
