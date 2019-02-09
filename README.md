# uHTTP
An HTTP server written in BrainFuck

Don't try this at home kids.

## Requirements
Most computers will not run the version of systemf that is included with this project. If your system is one of these, [build systemf yourself](https://github.com/ajyoon/systemf/), then replace `bin/systemf` with the output of that process. While you are at it, why not give the systemf page a star?

## Usage
On linux, run this in your terminal:
```sh
chmod 755 ./bin/systemf && cd web && ../bin/systemf ../src/server.bf
cd ..
```

Now, head over to [http://localhost:4000](http://localhost:4000)