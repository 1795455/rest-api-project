<!-- environnement creation -->
python3 -m venv .venv

<!-- activation venv -->
https://stackoverflow.com/questions/18713086/virtualenv-wont-activate-on-windows

<!-- install requirements -->
pip install flask

<!-- Insomnia for windows -->
<!-- automatisated test -->
<!-- passphrasse -->
Morita2023*.

https://insomnia.rest/download

pip install -r requirements.txt

<!-- Docker -->
docker build -t flask-smorest-api . 
docker run -dp 5000:5000 flask-smorest-api

<!-- Use de docker volume to run the code in our local directory -->
<!-- linux -->
docker run -dp 5000:5000 -w /app -v "$(pwd):/app" flask-smorest-api
<!-- windows -->
docker run -dp 5000:5000 -w /app -v "${PWD}:/app" flask-smorest-api

<!-- Git commands -->
git init
git status

git add . 

git rm --cached schemas.py


