`NOTE: Anything here wasn't made by me. 
        I forked and hosted this web app to test it so that I can run my own streamlit web app. 
        I had problems with installation of fbprophet so the files here would help me host the webapp I made.`

# covid-forecast

## Dev Instructions
Run `pipenv install --dev` to install the env.  
Run `pipenv run pre-commit install` to initialize the git hooks.  
Run `pipenv run pre-commit run --all-files` if there are file that were committed before adding the git hooks.  
Activate the shell with: `pipenv shell`  
Lint with: `pylint app/`

## Run the App
Run the app: `streamlit run app/app.py --server.port 8000`
