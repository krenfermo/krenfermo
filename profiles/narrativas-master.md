    # narrativas-master

    **Repositorio:** [https://github.com/krenfermo/narrativas-master](https://github.com/krenfermo/narrativas-master)

    Descripción pendiente.

    ---
    ## 🧩 Stack / Tecnologías
    Flask · Docker · Python

    ## 🔌 Endpoints (detección heurística)
    - `/`
- `/process`
- `/text-to-speech`

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
