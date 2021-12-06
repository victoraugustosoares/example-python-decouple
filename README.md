# Example Python Decouple

Instruções para utilizar [Python Decouple](https://github.com/henriquebastos/python-decouple) no projeto Django para
gerenciar variáveis de ambiente.

### Passos:

Criar ambiente virtual:

```
python -m venv .venv
```

Ativar ```.venv``` e instalar dependências:

```
source .venv/bin/activate

pip install -r requirements.txt
```

(Opcional) Ativar ```.venv``` e instalar dependências de desenvolvimento:

```
source .venv/bin/activate

pip install -r requirements-dev.txt
```

Criar arquivo ```.env``` para gerenciar variáveis de ambiente:

```
cp contrib/env-sample .env
```

Rodar servidor Django:

```
python manage.py runserver
```