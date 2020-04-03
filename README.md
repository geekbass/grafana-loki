# Granfana Loki 
Messing around with Grafana Loki. This is specifically for Docker logs.

# Usage
1. Run compose up.
```bash
docker-compose up -d
```

2. Go to [Kibana](http://localhost:3000) and login with admin/admin defaults.

3. Go to Data Sources and add Loki. URL = `http://loki:3100`

4. Now checkout the Explore tab to begin playing with Query. 

# Remove
```bash
docker-compose down 
```