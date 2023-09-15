# AIBot - Predict Language
Model to predict language based on input string.
Deploy ML models with FastAPI, Docker, and Render

### 1. Develop and save the model with this Colab

[Open Colab](https://colab.research.google.com/drive/1uaALcaatvxOu42IhQA4r0bahfdpw-Z7v?usp=sharing)

### 2. Create Docker container, you can run it locally on CPU

```bash
docker build -t app-name .

docker run -p 80:80 app-name
```

### 3. Create Git repo

If you clone this repo this step is not needed. Or you can delete this git repo with `rm -rf .git` and start with a new one:

```bash
git init
git add .
git commit -m "initial commit"
git branch -M main
git add remote origin <your remote repo>
git push main
```

### 4. LLM-backed API hosted on Render 
[Predict-Language API](https://predict-language.onrender.com/docs)

