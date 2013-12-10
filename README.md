django-cms-boilerplate
======================

django-cms-boiler plate for a <b>hassle free Django-CMS installation</b>

<h3>INSTALLATION</h3>
This assumes you are using pip to manage your python packages!

<ul>
<li>Creates a new SECRET_KEY for every installation.</li>
<li>Works wherever you clone it.</li>
<li>settings.py comes configured to the standard Django-CMS + django-filer installation as described in the <a href="http://docs.django-cms.org/en/2.4.3/index.html">documentation</a>.</li>
</ul>

```bash
git clone https://github.com/caisbalderas/django-cms-boilerplate.git
cd django-cms-boilerplate
pip install -r requirements.txt
python manage.py syncdb —all
python manage.py migrage —fake
python manage.py runserver
```

There you go! <b>A django CMS install in 3 minutes</b> (depending on your internet speed).
