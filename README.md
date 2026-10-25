# superkartrepository
SuperKart sales forecasting: ML model with a Flask backend API and Streamlit frontend, containerized with Docker

## Run with Docker Compose

From the repository root, run:

```sh
docker compose up --build
```

Open the Streamlit app at http://localhost:8502. Compose starts the backend on the shared service network and waits for its health check before starting the frontend. To stop the services, press Ctrl+C and run `docker compose down`.
