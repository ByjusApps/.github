### Para instalar o flask:

`pip install flask`

Obviamente o Python já precisa estar instalado
<br>

---

### Formatador automático de código Python:

https://github.com/psf/black

```
from flask import Flask  # Importa o módulo flask


app = Flask(__name__)  # Cria o app


@app.route("/")  # Cria a rota '/'
def principal():  # Função da rota '/' (Pode ter qualquer nome)
    """Pagina Inicial"""

    return "Esta é a página inicial"  # Retorna essa mensagem


app.run(port=10000, debug=True)  # Executa o app
```
