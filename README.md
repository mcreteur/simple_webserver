# simple_webserver

Simple implementation of a multithreaded webserver following the last chapter of the Rust introductory book : https://doc.rust-lang.org/book/ch20-00-final-project-a-web-server.html.

The webserver can start listening on ___127.0.0.1:7878___ by using the command : 
```
cargo run
```

- The ```/``` route will return a basic "hello" page
- The ```/sleep``` route can be used to observe the multithreading capabilities of the server by pausing the request processing for 5 seconds
- Every other routes will return an error page
