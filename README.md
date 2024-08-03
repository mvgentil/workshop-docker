# workshop-docker

### Passo a passo para rodar o projeto:

```
    git clone ...
    cd ...
    docker build -t streamlit-app
    docker run -d -p 8501:8501 --name streamlit-container streamlit-app
```