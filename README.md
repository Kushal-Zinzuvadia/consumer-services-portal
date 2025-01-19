# consumer-services-portal
Django application to provide consumer services for gas utilities

Refer "Case_study_solution.pdf" for detailed solution. 

Directory structure:
└── kushal-zinzuvadia-consumer-services-portal/
    ├── README.md
    ├── LICENSE
    ├── db.sqlite3
    ├── manage.py
    ├── customer_service/
    │   ├── __init__.py
    │   ├── admin.py
    │   ├── apps.py
    │   ├── models.py
    │   ├── tests.py
    │   ├── urls.py
    │   ├── views.py
    │   ├── __pycache__/
    │   ├── forms/
    │   │   ├── __init__.py
    │   │   ├── customer_edit_form.py
    │   │   ├── request_form.py
    │   │   └── __pycache__/
    │   ├── migrations/
    │   │   ├── 0001_initial.py
    │   │   ├── 0002_remove_servicerequest_customer_name_customer_address_and_more.py
    │   │   ├── 0003_rename_phone_number_customer_phone_and_more.py
    │   │   ├── __init__.py
    │   │   └── __pycache__/
    │   ├── models/
    │   │   ├── __init__.py
    │   │   ├── customer.py
    │   │   ├── service_request.py
    │   │   └── __pycache__/
    │   ├── templates/
    │   │   └── customer_service/
    │   │       ├── customer_account.html
    │   │       ├── customer_login.html
    │   │       ├── edit_customer_account.html
    │   │       ├── submit_request.html
    │   │       └── track_request.html
    │   └── views/
    │       ├── __init__.py
    │       ├── customer_views.py
    │       ├── track_request.py
    │       └── __pycache__/
    └── gas_utility_service/
        ├── __init__.py
        ├── asgi.py
        ├── settings.py
        ├── urls.py
        ├── wsgi.py
        └── __pycache__/
