# A Django Discussion Board



![Django Boards Screenshot](https://d26dzxoao6i3hh.cloudfront.net/items/0j1J2s300f1b2y1Y3p3k/django-boards.png?v=3ec9d7f5)


## Running the Project Locally

First, clone the repository to your local machine:

```bash
git clone git@github.com:sibtc/django-beginners-guide.git
```

Install the requirements:

```bash
pip install -r requirements.txt
```

Setup the local configurations:

```bash
cp .env.example .env
```

Create the database:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The project will be available at **127.0.0.1:8000**.


## License

The source code is released under the [MIT License](https://github.com/sibtc/django-beginners-guide/blob/master/LICENSE).

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/3.0/)

The tutorials, documentations, comics are licensed under the
[Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License](https://creativecommons.org/licenses/by-nc-sa/3.0/).
