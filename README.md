# django-nginx-uwsgi-celery-redis-rabbitmq-postgresql
Base project for using www.pidginhost.com custom app deployment for django.

## Required steps
1. Create an account on https://www.pidginhost.com/en/
2. Complete the 3 steps when deploying an app on the following link https://www.pidginhost.com/en/panel/apps/add:
    
    Step 1:
        Enter your project repo 

        https://github.com/cristi-boboc/django-nginx-uwsgi-celery-redis-rabbitmq-postgresql
    
    Step 2
        
        Enter the desired domain name which should point to the specified ip
    Step 3
    
        Select the desired applications, in this case (Postgresql, RabbitMQ, Redis)    
3. You can now point your browser to the domain and you will have a server deployed with ssl enabled and activated.

