# Node Docker Hello

A simple "Hello World" Node.js app running in a Docker container.

## How to Run

```bash
docker build -t node-hello .
docker run -d -p 5000:5000 --name hello-container node-hello
```