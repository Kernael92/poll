=====
Polls
=====

Polls is a simple Django app to conduct Web-bassed polls. For each question, visitors can choose between a fixed number of answers.

Detailed documentation is in the "docs" directory.

Quick start
------------

1. Add "polls" to your INSTALLED_APPS setting like this::

        INSTALLED_APPS = [
            ...
            'Polls'
        ]

2. Include the polls URLConf in your project urls.py like this::

        url(r'^polls/', include('polls.urls)),

3. Run 'python manage.py migrate' to create the polls models.

4. Start the development server and visit http://127.0.0.1:8000/polls/ to participate in the poll.