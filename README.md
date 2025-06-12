

py -3.10 -m venv venv310

Ative a venv pelo Shell do vscode:

.\venv310\Scripts\activate

pip install fastapi[standard]

fastapi dev main.py --port 8085

uvicorn app.main:app --host 0.0.0.0 --port 8000 --reload
