# EV Insights Flask Web Integration
## Run locally
Windows CMD: `python -m venv .venv` → `.venv\\Scripts\\activate` → `pip install -r requirements.txt` → `python app.py`. Browse http://127.0.0.1:5000.
## Deploy on Render
Connect GitHub repository in Render as a Web Service. Root Directory: `flask-website` if stored there. Build command `pip install -r requirements.txt`; Start command `gunicorn app:app`. Deploy and test the generated `onrender.com` URL in a private browser.
If the Tableau embed does not show, use Tableau Public Share → Embed Code and replace iframe src in templates/index.html. The dataset is synthetic; conclusions are illustrative.
