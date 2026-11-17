# AI Ansible Generator

MVP inicial para transformar requerimientos en proyectos Ansible revisables.

## Alcance
- Interfaz Streamlit con lenguaje natural y formulario guiado.
- Especificación estructurada con Pydantic.
- Generación inicial de un playbook de diagnóstico para RHEL 8/9.
- No ejecuta playbooks ni se conecta a servidores.
- Integraciones con IA, GitHub y AAP previstas para siguientes etapas.

## Requisitos
Python 3.11+ y Git.

## Instalación
```bash
python -m venv .venv
source .venv/bin/activate
# Windows PowerShell: .venv\\Scripts\\Activate.ps1
pip install -r requirements.txt
streamlit run app/main.py
```

Toda automatización generada requiere revisión humana antes de publicarse o ejecutarse.
No incluyas secretos ni datos sensibles en prompts o repositorios.
