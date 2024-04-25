It is a simple HTTPS server which can serve three kinds of requests. After running using `cargo run`, go to `localhost:7878/` or `localhost:7878/sleep` or any garbage address after the `/`, you will get an appropriate response in reture.
It is a multithreaded server, using a threadpool of 4 worker threads to serve the requests.

Resources:
[The Rust Programming Language](https://doc.rust-lang.org/stable/book/)

