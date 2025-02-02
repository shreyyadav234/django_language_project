README: Multilingual FAQ Management System
This Django project provides a multilingual FAQ management system with WYSIWYG editor support, API integration, caching, and automatic translations.

Features:
Model Design – The FAQ model stores FAQs with multilingual question fields (question_hi, question_bn) and an answer using django-ckeditor.
Translation Support – Uses googletrans for automatic translation of questions asynchronously via Celery.
API Development – Provides a REST API using Django REST Framework, supporting language-based retrieval via ?lang= query parameter.
Caching Mechanism – Implements Django caching with Redis to improve API performance.
Admin Panel – Registers the FAQ model in Django Admin for easy management.
Testing & Code Quality – Implements unit tests following PEP8 standards and uses flake8 for linting.
Deployment & Version Control – Dockerized setup with Git-based version control and structured commit messages.
Bulk FAQ Addition – API supports bulk FAQ creation using bulk_create() for efficiency.
This project ensures efficient FAQ retrieval with caching, seamless language translations, and a user-friendly interface.
