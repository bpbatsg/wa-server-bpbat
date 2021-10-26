### SERVER SETUP

#### Change User
logout dulu di icon github ~> di kiri bawah user ~> logout ~> sync
```bash
git config --global user.email "serverbpbatsg@gmail.com"
git config --global user.name bpbatsg
```

#### Stater Github
```bash
git init && git add README.md && git commit -m "first commit" && git branch -M main
git remote add origin https://github.com/bpbatsg/wa-server.git
git push -u origin main
```

#### Push Github
```bash
git add . && git commit -m "bismillah" && git push -u origin main
```

#### Stater Heroku
```bash
git add . && git commit -m "bismillah" && git push -u origin main
```

### ALL PUSH
```bash
git add . && git branch -M main  && git commit -m "bismillah" && git push -f origin main && git push heroku HEAD:master
```

### ON/OFF SERVER
```bash
heroku ps:scale web=0
```