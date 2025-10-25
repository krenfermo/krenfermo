    # meli-stack-dev

    **Repositorio:** [https://github.com/krenfermo/meli-stack-dev](https://github.com/krenfermo/meli-stack-dev)

    # RAG Service con MinIO (sin storage local)

    ---
    ## 🧩 Stack / Tecnologías
    Celery · FastAPI · MinIO · PostgreSQL · React · Redis

    ## 🔌 Endpoints (detección heurística)
    - `/dataset/stats`
- `/examples`
- `/examples/generate`
- `/examples/{example_id}`
- `/feedback`
- `/history`
- `/history/{session_id}`
- `/jobs/create`
- `/jobs/{job_id}/events`
- `/jobs/{job_id}/status`
- `/models`
- `/session/new`

    ## 🚀 Cómo ejecutar (plantilla)
    ```bash
    # Opción Docker
    docker compose up --build

    # Opción Python
    python -m venv .venv
    source .venv/bin/activate
    pip install -r requirements.txt
    uvicorn app.main:app --host 0.0.0.0 --port 8000
    ```

    ## 📂 Estructura sugerida (ejemplo)
    ```
    app/
      ├── main.py
      ├── routers/
      ├── models.py
      ├── schemas.py
      └── services/
    ```

    ## 👤 Mi rol
    - Diseño y desarrollo
    - Integraciones / ETL / DevOps (ajustar)
