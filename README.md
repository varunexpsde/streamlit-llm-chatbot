# streamlit-llm-chatbot

### What you need?

1. OpenAI App Sceret Key
2. Streamlit Account to create app and deploy.

### What are the files?

1. `app.py` -> Chatbot app backend code should go here.
2. `response_generator.py` -> Your response generator logic should go here.
3. `package.txt` -> Anything you would like to apt-get install needs to go here.
4. `requirements.txt` -> Any Python package that you need should go here.
5. `.streamlit/secrets.toml` -> Your OpenAI Key should be here as:
    
    ```
    OPENAI_API_KEY = ""
    ```


### How to run locally?

1. Create a Python virtual environment.

    ```
    Windows:

    python -m venv ./proj-venv

    ```

2. Activate the Python virtual environment.

    ```
    Windows:

    ./proj-venv/Scripts/activate

    ```

3. Install packages.

    ```
    pip install streamlit openai
    ```

4. Run the app locally.

    ```
    streamlit run app.py
    ```

### Deploying your app on Streamlit

#### Note: To Deploy your application through github you need to go to settings in Streamlit and Authorize it to access the private repos.

1. Click on `Creat app`
2. Answer do you already have an app?
3. Switch to `Paste Github Url`
4. Paste the `app.py` url from github.
5. Give a name to your app url.
6. Got to `Advanced Settings`, add your `./streamlit/secrets.toml` content.
7. Hit `Deploy`


