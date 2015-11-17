# Node mulicore

This is a test case copy pasted from https://dzone.com/articles/multicore-programming-in-nodejs by [
Dursun Ko�](https://dzone.com/users/874141/dursunKoc.html)

## Usage

```bash
git clone https://github.com/SirRagnar/node-multicore.git && cd node-multicore
npm install
node cluster.js
```

This should show something like this in console:
```
forked -> Worker 1
forked -> Worker 2
Application started! Worker 1 started!, process 2604
Application started! Worker 2 started!, process 5824
```

If you go to http://localhost:8080 and refresh repeatedly you could see how request are attended by the non busy worker at each time.
