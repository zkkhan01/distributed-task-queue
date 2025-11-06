# Distributed Task Queue (FastAPI + Redis Workers)
Distributed Task Queue (Real-World: Uber, Airbnb, DoorDash)

Real use case: background job processing, ETAs, notifications, heavy computations.


A distributed system with:

FastAPI job submission API
Redis message broker
Worker nodes with retry + exponential backoff
Job status dashboard
Task lifecycle tracking (queued → running → complete → failed)
