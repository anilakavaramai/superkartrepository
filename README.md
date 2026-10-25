# superkartrepository
SuperKart sales forecasting: ML model with a Flask backend API and Streamlit frontend, containerized with Docker

## Run with Docker Compose

From the repository root, run:

```sh
docker compose up --build
```

Open the Streamlit app at http://localhost:8502. The backend API is published at http://localhost:7861, and Compose waits for its health check before starting the frontend. To stop the services, press Ctrl+C and run `docker compose down`.
