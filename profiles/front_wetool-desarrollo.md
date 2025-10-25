    # front_wetool-desarrollo

    **Repositorio:** [https://github.com/krenfermo/front_wetool-desarrollo](https://github.com/krenfermo/front_wetool-desarrollo)

    gunicorn -c guniconf.py app:app --timeout 600

    ---
    ## 🧩 Stack / Tecnologías
    Flask · MinIO · JavaScript/TypeScript · PHP · Python · Ruby

    ## 🔌 Endpoints (detección heurística)
    - `/accordions-collapse`
- `/index10`
- `/index11`
- `/index12`
- `/index2`
- `/index3`
- `/index4`
- `/index5`
- `/index6`
- `/index7`
- `/index8`
- `/index9`

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
