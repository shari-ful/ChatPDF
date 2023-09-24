## Chat with PDF

### create virtual Environment
>>> python -m venv venv

### Activate Virtual Environment
>>> source venv/bin/activate (Mac, Linux)
>>> venv\Scripts\activate (Windows)

### install dependencies
>>> pip install -r requirements.txt

### ingest with pdf data
>>> python ingest.py

### Run chainlit App
>>> chainlit run app.py -w