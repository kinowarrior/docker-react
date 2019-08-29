
### Docker Commands

```
docker build -f Dockerfile.dev .
docker run -it 5c26b5bfeed7 npm run test

docker run -p 3000:3000 c4e9f82aa908
docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app 95c604a8ce01
```
