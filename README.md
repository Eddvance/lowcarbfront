# 🌱 LowCarb Frontend

**Part of the [LowCarb](https://github.com/Eddvance/LowCarb) application**

Static frontend for the LowCarb energy calculator.

## 🎯 Role

Simple web interface allowing users to:
- Enter their energy consumption (kWh)
- Compare green vs carbon energy costs
- View calculation results

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript

## 🚀 Running

This frontend is part of the LowCarb microservices ecosystem. See the main [LowCarb repository](https://github.com/Eddvance/LowCarb) for full setup instructions with Docker Compose.

**Standalone:**
```bash
# Served via Docker on port 3002
docker build -t lowcarb-frontend .
docker run -p 3002:80 lowcarb-frontend
```

**Access:** http://localhost:3002

## 📝 License

MIT License - see [LICENSE](LICENSE) for details.
