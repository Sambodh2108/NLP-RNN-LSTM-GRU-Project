# NLP RNN/LSTM/GRU Project

An emotion-classification web app that serves predictions from a trained BiGRU model.

## Run the API

Install the dependencies:

```powershell
pip install -r requirements.txt
```

Start the application from the project directory:

```powershell
uvicorn main:app --reload
```

Open `http://127.0.0.1:8000` to use the interface. The API also provides `/health` and `/predict` endpoints.

The trained model and tokenizer are loaded from `Artifacts/`.
