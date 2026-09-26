
This directory includes a "docker compose" file that lets you stand up an entire Grafana Stack (Grafana, Alloy, Loki, and Tempo) alongside Prometheus. Metrics from the ShoeHub application and traces from the example microservices (OrderService and PaymentService) are automatically sent to Prometheus and Tempo. A sample dashboard is also provided.

- Ensure that Docker Desktop is installed on your computer.
- Run ``docker compose up -d`` to start the services.
- Once the script is run successfully, visit Grafana via ``HTTP://localhost:3000``
- Use "admin" for both username and password.

- Run ``docker compose down`` to stop it.
