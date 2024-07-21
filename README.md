# devcontainer-nodejs-template

```bash
mkdir hello
```

```bash
cd hello
```

```bash
npm init -y
```

```bash
echo '// app.js
const http = require("http");

const hostname = "127.0.0.1";
const port = 3000;

const server = http.createServer((req, res) => {
  res.statusCode = 200;
  res.setHeader("Content-Type", "text/plain");
  res.end("Hello, World!");
});

server.listen(port, hostname, () => {
  console.log(`Server running at http://${hostname}:${port}/`);
});' > app.js
```

```bash
node app.js
```
