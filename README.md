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

   Use Docker Compose to build and run the services defined in the `docker-compose.yml` file.

   ```bash
   docker-compose up --build
   ```

3. **Access Grafana:**

   Once the containers are running, you can access Grafana by navigating to `http://localhost:3000` in your web browser. The default login credentials are:
   - Username: `admin`
   - Password: `admin`

4. **Access Zabbix:**

   You can access the Zabbix frontend at `http://localhost:8080`. The default login credentials are:
   - Username: `Admin`
   - Password: `zabbix`

## Configuration

- The Grafana configuration can be found in `grafana/config/grafana.ini`.
- The Zabbix server configuration is located in `zabbix/config/zabbix_server.conf`.

## Stopping the Containers

To stop the running containers, you can use:

```bash
docker-compose down
```

## License

This project is licensed under the MIT License. See the LICENSE file for details.