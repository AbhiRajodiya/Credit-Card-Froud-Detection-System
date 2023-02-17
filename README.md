Dataset Link :- https://www.kaggle.com/mlg-ulb/creditcardfraud

1)  First  Create virtualenvironment with following COMMAND:-

        virtualenv venv

 NOTE:- venv is name of name of virtualenvironment. we can give any name which we want.

2) Then Activate venv:-

        venv\Scripts\activate

3) Then Install requirements.txt with following COMMAND:-

        pip install -r requirements.txt


4)  create superuser by following COMMAND in your root directory:-

        python manage.py createsuperuser

5)  Then start your server by typing following COMMAND:-

        python manage.py runserver







    NOTE:- If you are adding some model in models.py or changing something don't forget to make migrations 

        python manage.py makemigrations

    and migrate it to database

        python manage.py migrate
        
        

![screencapture-127-0-0-1-8000-2023-02-17-18_11_52](https://user-images.githubusercontent.com/110282564/219656614-dcd48ab6-fff8-4b09-bf99-32edb69ca0ba.png)

![screencapture-127-0-0-1-8000-dashboard-2023-02-17-18_12_31](https://user-images.githubusercontent.com/110282564/219656631-4c099cc8-2677-4ad5-89af-b48954d96d23.png)
![screencapture-127-0-0-1-8000-reports-2023-02-17-18_13_00](https://user-images.githubusercontent.com/110282564/219656663-6e73f1b1-faf5-4d92-af3d-0ddf0fb2feda.png)
