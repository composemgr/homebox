## 👋 Welcome to homebox 🚀

Inventory and organization system for your home

## 📋 Description

Inventory and organization system for your home

## 🚀 Services

- **homebox**: ghcr.io/hay-kot/homebox:latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/homebox/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/homebox" ~/.local/srv/docker/homebox
cd ~/.local/srv/docker/homebox
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install homebox
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
SERVICE_USER=1000
SERVICE_GROUP=1000
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:8074

## 📂 Volumes

- `./volumes/config/homebox` - Data storage
- `./volumes/data/homebox` - Data storage

## 🔍 Logging

```shell
docker compose logs -f homebox
```

## 🛠️ Management

```bash
# Start services
docker compose up -d

# Stop services
docker compose down

# Update to latest images
docker compose pull && docker compose up -d

# View logs
docker compose logs -f

# Restart services
docker compose restart
```

## 📋 Requirements

- Docker Engine 20.10+
- Docker Compose V2+

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
