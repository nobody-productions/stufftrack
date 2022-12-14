# Stufftrack
stufftrack main runnable project

## What is stufftrack
A simple **tracker** for your stuff.

As long as an integration has been developed, you can track whatever you prefer, for now it only tracks **videogames** and **books**

Since it was developed as a PoC, you will have a local database with a list of default videogames and books. 

This feature will change as long as we find a way to integrate other systems.

## What is made of
Three parts:
- [stufftrack-backend](https://github.com/nobody-productions/stufftrack-backend)
- [stufftrack-frontend](https://github.com/nobody-productions/stufftrack-frontend).
- postgre database

## Requirements
Git, Docker and Docker Compose

## Steps
1. Run in your terminal
```
git clone https://github.com/nobody-productions/stufftrack &&
cd stufftrack &&
git clone https://github.com/nobody-productions/stufftrack-frontend &&
git clone https://github.com/nobody-productions/stufftrack-backend
```

2. Edit .env file in stufftrack-backend (we use nano, because it's more friendly for new users)
```
cp stufftrack-backend/.env.sample stufftrack-backend/.env
nano stufftrack-backend/.env
```

Fill the .env with your stuff, CTRL+S to save.


3. Then, run
```
docker compose up
```

4. If everything is working, you should be able to access Stufftrack on `localhost:8000`

Simply signup for a new account (if no error succeed it will redirects you to a login page) or login with default credentials.

## Default credentials
```
damiano@gmail.com:BackendistaSenzaSosta11
lorenzo@gmail.com:TelefoniChePassione!
misterkrub@gmail.com:INeedADollar$!
spongebob@gmail.com:Gary4832930382749274
patrickstella@gmail.com:Blargh
squidditentacolo@gmail.com:Clarinetto63
theshadow2030@gmail.com:SplatoonIsMyLife
```
