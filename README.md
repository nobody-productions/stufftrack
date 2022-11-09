# Stufftrack
stufftrack main runnable project

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
