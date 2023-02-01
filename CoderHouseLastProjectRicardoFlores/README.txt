1)Instalar el ambiente virtual 
virtualenv -p python env           gitbash

2)activar ambiente virtual
source env/Scripts/activate

3)instalar requirements
 pip install -r requirements.txt

4)hacer las migraciones
python manage.py makemigrations
python manage.py migrate

5)correr el servidor 
python manage.py runserver

DATO
para crear el primer blog por favor crearse un superusuario
luego en el panel de admin los usuarios tienen que tener el mark de staff 
para que puedan agregar blogs