# 🎨 drawing

O **drawing** é um package Python simples e educativo que demonstra a estrutura moderna de um pacote usando `pyproject.toml` e a organização recomendada em `src/`.  
Inclui duas funcionalidades principais:

- **colors** — funções relacionadas com cores  
- **shapes** — funções relacionadas com formas geométricas  

É ideal para aprendizagem de packaging, organização modular e distribuição de código Python.

---

## 📚 Funcionalidades

### Módulo `colors`

```python
def red():
    print("vermelho")
```

### Módulo `shapes`

```python
def oval():
    print("oval")
```

## 📁 Estrutura do Projeto
```
drawing/
│
├── src/
│   └── drawing/
│       ├── __init__.py
│       ├── colors.py
│       └── shapes.py
├── .gitignore
├── README.md
├── main.py
└── pyproject.toml
```

## 🚀 Instalação
Instalação normal

```bash
pip install .
```

Instalação em modo de desenvolvimento (editable)

```bash
pip install -e .
```

## 🛠️ Uso
```python
from drawing.colors import red
from drawing.shapes import oval

red()   # Output: "vermelho"
oval()  # Output: "oval"
```

📝 Requisitos

O package não possui dependências externas.
Se adicionares futuras dependências, inclui-as em requirements.txt ou em [project.dependencies] no pyproject.toml.

🧑‍💻 Autor

Ricardo Campos

GitHub: https://github.com/

Email: ricardo.campos@

📄 Licença

Este projeto é disponibilizado sob a MIT License.