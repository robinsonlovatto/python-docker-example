## Starting the project from scratch
```bash
pyenv local 3.12.1   
poetry init    
poetry env use 3.12.1     
poetry shell     
poetry add streamlit    
```

## Cloning the project
```bash
git clone https://github.com/robinsonlovatto/python-docker-example.git
cd python-docker-example
poetry shell
poetry install
```

## Building Docker image and running it
```bash
docker build -t my-python-image .
docker run -d -p 8501:8501 --name my-python-container my-python-image
```






