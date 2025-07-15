# Portfolio Flask Backend

Yeh backend aapke portfolio ke liye hai. Is mein do endpoints hain:

- `/projects` (GET): Projects ka data JSON format mein deta hai.
- `/contact` (POST): Contact form data accept karta hai aur file mein save karta hai.

## Run kaise karein

1. Python 3 install karein.
2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
3. Flask app run karein:
   ```bash
   python app.py
   ```

## Endpoints

- **GET /projects**
- **POST /contact**
  - JSON body: `{ "name": "Aap ka naam", "email": "Aap ka email", "message": "Aap ka paighaam" }` 