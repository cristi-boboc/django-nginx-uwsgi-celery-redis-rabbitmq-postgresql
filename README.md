# django-nginx-uwsgi-celery-redis-rabbitmq-postgresql
A one-click install for a django project using piginhost.com resources

## Required steps
1. Create an account on https://www.pidginhost.com/en/
2. Complete the steps when deploying an app:
    - If the repository is private you need to add the public key given to you to the deploy keys(only read access is required)
    - Set the dns entry of A record of the domain to point to the provided IP
    - Create a phspec.json file in the root of your project specifying the resources required for your project
3. If all the previous steps are met, then your project will be checked and deployed.

1
