# 1. Clone Repo

```sh
git clone https://github.com/antheiz/example-services.git
cd example-services
```


# 2. Create Environtment and Install dependencies

```sh
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

# 3. Run Services

```sh
uvicorn users:app --reload --port 8080
uvicorn carts:app --reload --port 8081
```
