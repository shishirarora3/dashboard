# dashboard

Flowchart
1. Edge gateway
2. Read and write traffic cqrs pattern
3. Read to read read replicas, eventual sync with write db
4. Write operations go through scheduler, dB with pending commands eventsourcing, message broker, workers, then db.
