    # SAAS-main

    **Repositorio:** [https://github.com/krenfermo/SAAS-main](https://github.com/krenfermo/SAAS-main)

    # WhatsApp SaaS Final

    ---
    ## 🧩 Stack / Tecnologías
    Celery · FastAPI · PostgreSQL · React · Redis · Docker

    ## 🔌 Endpoints (detección heurística)
    - `/`
- `/conversations`
- `/login`
- `/me`
- `/messages/{conversation_id}`
- `/quick-reply`
- `/register`
- `/send-message`
- `/widget/{client_id}`
- `/{appointment_id}`
- `/{appointment_id}/confirm`
- `/{appointment_id}/status`

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
