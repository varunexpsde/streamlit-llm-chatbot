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

### Deploying the app


