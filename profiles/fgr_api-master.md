    # fgr_api-master

    **Repositorio:** [https://github.com/krenfermo/fgr_api-master](https://github.com/krenfermo/fgr_api-master)

    gunicorn -c config_gunicorn.py main:app -k uvicorn.workers.UvicornWorker

    ---
    ## 🧩 Stack / Tecnologías
    Celery · FastAPI · PostgreSQL · Redis · SAS · Python

    ## 🔌 Endpoints (detección heurística)
    - `/AREAS`
- `/ROLES`
- `/buscar_detenidos`
- `/buscar_ficha`
- `/fichas/`
- `/generar-fichas`
- `/generar-pdf`
- `/login`
- `/logout`
- `/procesa_excel_recaf`
- `/register`
- `/reporte_armas`

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
