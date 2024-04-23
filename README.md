Starting
pyenv local 3.12.1
poetry init
poetry env use 3.12.1
poetry shell
poetry add streamlit


docker build -t my-python-image .
docker run -d -p 8501:8501 --name my-python-container my-python-image





