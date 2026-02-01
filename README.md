# City Temperature Management API

This project is a FastAPI-based REST API for managing city data and automatically tracking their current temperatures.

## Features
- **City CRUD**: Create, retrieve, and delete cities.
- **Temperature Updates**: Asynchronously fetch the current temperature for all cities in the database via the Open-Meteo API.
- **Temperature History**: View the history of temperature records (general list or filtered by `city_id`).

## Tech Stack
- **FastAPI** — main framework.
- **SQLAlchemy** — ORM for working with the SQLite database.
- **HTTPX** — asynchronous client for requests to external APIs.
- **Pydantic** — models for data validation.

## How to Run

1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
