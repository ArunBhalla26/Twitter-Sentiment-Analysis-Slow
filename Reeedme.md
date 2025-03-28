pip install virtualenv
virtualenv env

./env./s./activate

python install -r new_requirements.txt

python manage.py makemigrations
python manage.py migrate
