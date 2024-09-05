# Technical instructions

## Create and activate Python virtual environment
```bash
    python -m venv venv
    .venv/bin/Activate
```

## Activar permisos para inicia el entorno, solo sino lo 
´´´bash
    Set-ExecutionPolicy RemoteSigned
    Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
´´´

## Install dependencies
Create file *requirements.txt*

```bash
    pip install -r requirements.txt
```

## Run streamlit project

```bash
    streamlit run app.py 
```
## Install openpyxl
```
    pip install openpyxl
```

# Utilities
## Steps to remove virtual environment
```bash
    deactivate
    rm -rf venv
```