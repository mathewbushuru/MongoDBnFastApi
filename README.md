 - A CRUD App that integrates MongoDB with a FastAPI project

 # To Run

 - First set this environment variable in terminal before running app.py
 ```
export MONGODB_URL="mongodb+srv://<username>:<password>@<url>/<db>?retryWrites=true&w=majority"
 ```

 - Run this to start server
 ```
uvicorn final:app --reload
 ```
 to see final result. Using app.py to build to this incrementally

 - see application under http://127.0.0.0/docs