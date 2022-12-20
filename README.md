
```
$ curl -v 'localhost:8080/github.com/login?client_id=Iv1.54a5bb15ca67fca5&return_to=/login/oauth/authorize?client_id=Iv1.54a5bb15ca67fca5&redirect_uri=https%3A%2F%2Fapp.uffizzi.com%2Fauth%2Fgithub%2Fcallback&response_type=code&scope=user%3Aemail&state=977a8e111a9ed3f11b1391ed502f476efad21afbdaba02fa'
```

```
< HTTP/1.1 302 Moved Temporarily
< Location: https://github.com/login?client_id=Iv1.54a5bb15ca67fca5&return_to=/login/oauth/authorize?client_id=Iv1.54a5bb15ca67fca5&redirect_uri=https%3A%2F%2FlocalhostFauth%2Fgithub%2Fcallback&response_type=code&scope=user%3Aemail&state=https%3A%2F%2Fapp.uffizzi.com%2Fauth%2Fgithub%2Fcallback977a8e111a9ed3f11b1391ed502f476efad21afbdaba02fa
```
