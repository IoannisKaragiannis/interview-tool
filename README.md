# Setup Virtual Environment

```
cd interview-tool
./requirements/setup_venv.sh interview
```


# Run tool

```
# activate environment
source ~/python_venv/interview/bin/activate

# add your openai key in the secrets.toml file

# make sure you no longer track changes of this file as 
# it's not wise to publish your API key
git update-index --skip-worktree .streamlit/secrets.toml

# run app
(interview) streamlit run app.py
```

