# Multilingual Assistant 


# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n llmapp python=3.8 -y
```

```bash
conda activate llmapp
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your GOOGLE_API_KEY credentials as follows:

```ini
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# Finally run the following command
streamlit run app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- Google API
- Streamlit
- PaLM2
- s2t
- t2s


### git commands

```bash
git init
```
```bash
git add README.md
```
```bash
git commit -m "first commit"
```
```bash
git branch -M main
```
```bash
git remote add origin https://github.com/rabingit/Multiligual-AI-Assistant.git
```
```bash
git push -u origin main
```

```bash
git remote -v
```

```bash
git remote set-url origin https://github.com/rabingit/Multiligual-AI-Assistant.git
```