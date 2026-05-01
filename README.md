# Personal API

A minimal REST API built with Node.js and Express, deployed on AWS EC2 with Nginx reverse proxy and PM2.

## Run Locally

```bash
npm install
node index.js
# API runs on http://localhost:3000
```

## Endpoints

| Endpoint | Method | Response |
|----------|--------|----------|
| `/` | GET | `{"message": "API is running"}` |
| `/health` | GET | `{"message": "healthy"}` |
| `/me` | GET | `{"name": "Akinlolu Olaniyan", "email": "akinlolufly@gmail.com", "github": "https://github.com/akinfly19-alt"}` |

## Live URL

http://54.174.140.208
