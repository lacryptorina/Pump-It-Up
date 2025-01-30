# My Flask App

This is a simple Flask application.

## How to Run

1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the app: `python main.py`.

## Docker

You can also run this app using Docker:

```bash
docker build -t my-flask-app .
docker run -p 5000:5000 my-flask-app
```