# Grafana and Zabbix Local Testing

This repository provides a simple way to test Grafana and Zabbix locally using Docker containers. It includes all necessary configurations and Dockerfiles to get you started quickly.

## Prerequisites

- Docker installed on your machine
- Docker Compose installed

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/grafana-zabbix-local.git
   cd grafana-zabbix-local
   ```

2. **Build and start the containers:**

   ```bash
   docker-compose up --build
   ```

3. **Access Grafana:**

   `http://localhost:3000`
   login credentials are:
   - Username: `admin`
   - Password: `admin`

4. **Access Zabbix:**

   `http://localhost:8080`
   login credentials are:
   - Username: `Admin`
   - Password: `zabbix`




## stop
```bash
docker-compose down
```

