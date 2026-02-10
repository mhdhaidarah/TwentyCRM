# Twenty CRM

A modern open-source CRM.

---

## Step-1 Installation
```bash
git clone https://github.com/mhdhaidarah/TwentyCRM.git
cd TwentyCRM/
```

## Step-2 Edit the .env file to set your device IP and other settings
```bash
sudo nano .env
```
## Step-3 Just Run it Up
```bash
docker compose up -d
```

## Optional Auto Start
```bash
docker update --restart=always twenty-db-1
docker update --restart=always twenty-redis-1
docker update --restart=always twenty-server-1
docker update --restart=always twenty-worker-1
```
