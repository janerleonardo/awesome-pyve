## Recursos compartidos vía la comunidad de Python Venezuela

- Índice:
    - [Recursos para aprender y estudiar Python](#recursos-para-aprender-y-estudiar-python)
    - [Análisis científico con Python](#análisis-científico-con-python)
    - [Frameworks basados en Python](#frameworks-basados-en-python)
    - [CMS basados en Python](#cms-basados-en-python)
    - [Hardware libre con Python](#hardware-libre-con-python)
    - [Herramientas para desarrollo y depuración de código](#herramientas-para-desarrollo-y-depuración-de-código)
    - [Herramientas para gestión de proyectos](#herramientas-para-gestión-de-proyectos)
    - [Recursos para el desarrollo de backends](#recursos-para-el-desarrollo-de-backends)
    - [Recursos para el manejo de bases de datos](#recursos-para-el-manejo-de-bases-de-datos)
    - [Recursos para el desarrollo de front-ends](#recursos-para-el-desarrollo-de-front-ends)
    - [Recursos para poner a pruebas sistemas](#recursos-para-poner-a-pruebas-sistemas)
    - [Recursos para el despliegue de aplicaciones](#recursos-para-el-despliegue-de-aplicaciones)
    - [Servicios para el control de versiones](#servicios-para-el-control-de-versiones)
    - [Recursos para crear interfaces gráficas](#recursos-para-crear-interfaces-gráficas)
    - [Otros recursos útiles](#otros-recursos-útiles)
    - [Blog posts](#blog-posts)

- - -

## Recursos para aprender y estudiar Python

### Libros

* [Dive into Python 3](https://www.diveinto.org/python3/) - Es el libro ideal
  para quien quiera aprender Python pero ya sabe programar. Comienza presentando
  un programa completo escrito en Python el cual analiza parte a parte en la
  medida en la que explica los elementos de Python. El finalizar, el lector
  podrá entender claramente todo el programa.

## Análisis científico con Python

### Paquetes básicos

* [Numpy](http://www.numpy.org/) - Es el paquete fundamental en python para el
cómputo numérico. Permite definir arreglos y matrices numéricas
multidimensionales y realizar operaciones sobre estos.

* [Scipy](http://www.scipy.org/) - La biblioteca SciPy es una colección de
algoritmos numéricos y cajas de herramientas para dominios específicos que
incluyen procesamiento de señales, optimización, estadística y mucho mas.

* [Pandas](http://pandas.pydata.org/) - Biblioteca de alto rendimiento y simple
de usar para realizar análisis y modelado de datos *(en inglés)*.

* [SymPy](http://www.sympy.org/) - es una biblioteca para matemática simbólica.
Tiene el objetivo de convertirse en un sistema completo de álgebra computacional
implementado totalmente en Python.

### Gráficos

* [Matplotlib](http://matplotlib.org/) - es un paquete de gráficos científicos
que se ha convertido en el estándar de facto en Python, provee capacidad de
graficación 2D y 3D en diversos formatos, entornos de interfaces gráficas, y
servidores de aplicación web. Existe un modo especial de IPython que se
integra con Matplotlib.

* [GraphLab Create](https://pypi.python.org/pypi/GraphLab-Create) - Biblioteca
programada en c++ de alto rendimiento para construcción de gráficos de con data
de gran escala *(en inglés)*.

### Extensiones

* [Scikits](http://scikits.appspot.com/scikits) - Los scikits son paquetes extra
de Scipy que proveen funcionalidad mas específica. scikit-image para
procesamiento de imágenes y scikit-learn para aprendizaje automático y minería
de datos son dos de los mas destacados.

### Recursos

* [Scipy lecture notes](https://scipy-lectures.github.io) - Conjunto de
materiales sobre las herramientas del ecosistema científico de Python.

* [Software Carpentry](https://software-carpentry.org/) -es una organización de
voluntarios sin fines de lucro cuyos miembros enseñan destrezas informáticas
básicas a investigadores. En la sección
[lecciones](https://software-carpentry.org/lessons.html) se encuentra excelente
material de buenas prácticas de desarrollo y Python, y otras herramientas como
bases de datos y sistemas de control de versiones.

- - -

## [Frameworks](https://es.wikipedia.org/wiki/Framework) basados en Python

### Frameworks para desarrollo web

* [Django](https://www.djangoproject.com/) - Framework web de alto nivel, desarrollo rápido con diseño
limpio y pragmático

    * Tutoriales

        * [django start](https://www.djangoproject.com/start/) - Tutorial Django
          *(en inglés)*

        * [Write your first Django app](https://docs.djangoproject.com/en/1.8/intro/tutorial01/) - Programe tu
          primera aplicación con Django *(en inglés)*

        * [Escribe tu primera aplicación con Django](http://djangotutorial.readthedocs.org/es/1.8/index.html) -
          Tutorial Django *(en español)*

        * [Python Django Starter Kit](http://code.techandstartup.com/django/) - Conjunto de tutoriales
          prácticos enfocado en casos de uso básicos en construcción de aplicaciones web *(en inglés)*

    * Complementos para Django

        * [django-rest-framework](http://www.django-rest-framework.org/) - Framework para
          desarrollar [API](https://es.wikipedia.org/wiki/Interfaz_de_programaci%C3%B3n_de_aplicaciones)
          basado en [REST](https://es.wikipedia.org/wiki/Representational_State_Transfer)  *(en inglés)*.

        * [django-rest-framework-gis](https://github.com/djangonauts/django-rest-framework-gis) -
          django-rest-framework con agregados para el manejo de datos geográficos con *Django*.

        * [django-model-utils](https://django-model-utils.readthedocs.org/en/latest/) -
          Utilidades para simplificar el uso de modelos en *Django (en inglés)* .

        * [celery](http://celery.readthedocs.org/en/latest/django/first-steps-with-django.html) - 
          Tareas asincrónicas distribuidas en tiempo real con *Django (en inglés)* .

        * [Lettuce y Django](http://lettuce.it/recipes/django-lxml.html) - [BDD](GLOSARIO.md#b) Desarrollo dirigido por comportamientos con *Django*.

* [Flask](http://flask.pocoo.org/) – Flask es un micro framework que sirve para
construir aplicaciones web.

    * Tutoriales

        * [Flask Quickstart](http://flask.pocoo.org/docs/1.0/quickstart/) - Tutorial Flask
          *(en inglés)*

    * Complementos para Flask

        * [Flask-RESTful](https://flask-restful.readthedocs.io/) - Framework para
          desarrollar [API](https://es.wikipedia.org/wiki/Interfaz_de_programaci%C3%B3n_de_aplicaciones)
          basado en [REST](https://es.wikipedia.org/wiki/Representational_State_Transfer)  *(en inglés)*.

        * [Flask-SQLAlchemy](http://flask-sqlalchemy.pocoo.org/) - Librería ORM para
          desarrollar en Flask *(en inglés)*.

        * [Flask-Admin](https://flask-admin.readthedocs.io/en/latest/) - Librería la cual resuelve 
          el aburrido problema de construir una interfaz de administrador sobre un modelo de datos 
          existente al desarrollar en Flask *(en inglés)*.

        * [Flask-Security](https://flask-security.readthedocs.io/) - Librería la cual le permite 
          agregar rápidamente mecanismos de seguridad comunes a su aplicación Flask *(en inglés)*.

* [Pyramid](http://www.pylonsproject.org/projects/pyramid/about) - Pyramid es
un framework web general. Sus principios son la simplicidad, minimalismo,
documentación, velocidad, confiabilidad y apertura.

    * Tutoriales

        * [Quick Tutorial for Pyramid](https://docs.pylonsproject.org/projects/pyramid/en/latest/quick_tutorial/) - Tutorial Pyramid
          *(en inglés)*

    * Complementos para Pyramid

        * [Extending Pyramid](https://trypyramid.com/extending-pyramid.html) - Más de 470 paquetes Pyramid 
          disponibles para extender sus funcionalidades a través de complementos y entornos de desarrollo de 
          Pyramid. *(en inglés)*.

        * [pyramid_sacrud](https://pyramid-sacrud.readthedocs.io/) - Librería la cual construye una interfaz de 
          administrador sobre un modelo de datos existente al desarrollar en Pyramid y trabaja con varios 
          backends *(en inglés)*.

        * [pyramid-restful-framework](https://pyramid-restful-framework.readthedocs.io/) - Framework para
          desarrollar [API](https://es.wikipedia.org/wiki/Interfaz_de_programaci%C3%B3n_de_aplicaciones)
          basado en [REST](https://es.wikipedia.org/wiki/Representational_State_Transfer) *(en inglés)*.

* [Zope](https://www.zope.org/) - Zope es un servidor de aplicaciones web gratuito y de código abierto escrito en el lenguaje de programación orientado a objetos "Python". Desde su lanzamiento en 1998, Zope continúa creciendo en muchas aplicaciones, marcos, bibliotecas y herramientas distintas.

    * Tutoriales

        * [Zope Products Tutorial](https://zope.readthedocs.io/en/latest/zdgbook/Products.html) - Tutorial de Productos (Addon) en Zope *(en inglés)*.

        * [Zope Documentation](https://www.zope.org/documentation/index.html) - Documentación de Zope *(en inglés)*.

    * Complementos para Zope

        * [Extending Zope](https://pypi.org/search/?q=&o=&c=Framework+%3A%3A+Zope) - Más de 1660 paquetes Zope en sus diversas versiones (Zope2, Zope3 y Zope4) disponibles para extender sus funcionalidades a través de complementos y entornos de desarrollo de Zope. *(en inglés)*.

        * [Download Zope Products](https://old.zope.org/Products/index.html) - La página ANTIGUA de Productos Zope en las versiones Zope2 y Zope3 disponibles en ese entonces, para extender sus funcionalidades a través de complementos y entornos de desarrollo de Zope. *(en inglés)*.

        * [zope.sqlalchemy](https://pypi.org/project/zope.sqlalchemy/) - Librería ORM para
          desarrollar en Zope usando librería SQLAlchemy *(en inglés)*.

        * [lazr.restful](https://pypi.org/project/lazr.restful/) - Framework para
          desarrollar [API](https://es.wikipedia.org/wiki/Interfaz_de_programaci%C3%B3n_de_aplicaciones)
          basado en [REST](https://es.wikipedia.org/wiki/Representational_State_Transfer) *(en inglés)*.

        * [plone.rest](https://pypi.org/project/plone.rest/) - le permite usar verbos HTTP 
          como GET, POST, PUT, DELETE, etc en Plone sobre Zope para desarrollar 
          [API](https://es.wikipedia.org/wiki/Interfaz_de_programaci%C3%B3n_de_aplicaciones)
          basado en [REST](https://es.wikipedia.org/wiki/Representational_State_Transfer) *(en inglés)*.

* [Ramses](https://ramses.readthedocs.org/) - Biblioteca que genera una API
RESTful usando RAML.

* [Nefertari](https://nefertari.readthedocs.org/) - Framework para API
RESTful que usa ElasticSearch para la lectura y MongoDB o PostgreSQL
para escritura.

* [web.py](http://webpy.org/) - Es un micro framework tan simple como potente desarrollado originalmente por [Aaron Swartz](https://es.wikipedia.org/wiki/Aaron_Swartz).
web.py trata de ser un framework lo menos intrusivo posible, es "un framework anti framework".

- - -

## [CMS](https://es.wikipedia.org/wiki/Sistema_de_gestión_de_contenidos) basados en Python

### Frameworks para desarrollo de CMS

* [Plone](https://plone.com/) - es el más longevo, poderoso, flexible, seguro y premiado sistema de gestión de contenido escrito en Python.

    * Tutoriales

        * [Plone Documentation](https://docs.plone.org) - Documentación de Plone *(en inglés)*.

        * [Mastering Plone Development](https://training.plone.org/5/mastering-plone/index.html) - Desarrollo profesional en Plone *(en inglés)*.

        * [Plone Theming](https://training.plone.org/5/theming/index.html) - Desarrollo de temas en Plone *(en inglés)*.

        * [JavaScript For Plone Developers](https://training.plone.org/5/javascript/index.html) - Programe JavaScript en sus desarrollos en Plone *(en inglés)*.

        * [Automating Plone Deployment](https://training.plone.org/5/deployment/index.html) - Implementando Plone con Ansible y OpsWorks *(en inglés)*.

        * [Plone Deployments With Amazon OpsWorks](https://training.plone.org/5/deployment/opsworks/index.html) - Implementaciones Plone con Amazon OpsWorks *(en inglés)*.

        * [“Through-The-Web” Plone Customization](https://training.plone.org/5/ttw/index.html) - Personalización de Plone a través de la web *(en inglés)*.

        * [Plone Training Solr](https://training.plone.org/5/solr/index.html) - IPotencia la búsqueda de sitios como Twitter, las tiendas de Apple e iTunes, Wikipedia, Netflix y más usando Apache Solr se basa en Lucene y es el motor de búsqueda de código abierto para empresas *(en inglés)*.

        * [Plone Workflow](https://training.plone.org/5/workflow/index.html) - Entedimiento y personalizar los flujo de trabajo se utiliza en Plone *(en inglés)*.

        * [Angular SDK para Plone](https://training.plone.org/5/angular/index.html) - Creación de aplicaciones Angular 4 utilizando la API de REST de Plone *(en inglés)*.

        * [React](https://training.plone.org/5/react/index.html) - Conozca las bases de React, Redux y React-Router *(en inglés)*.

        * [Volto](https://training.plone.org/5/volto/index.html) - Aprende cómo crear tu propio sitio web basado en Volto y React *(en inglés)*.

        * [Migrating Content with Transmogrifier](https://training.plone.org/5/transmogrifier/index.html) - Migración del contenido del sitio web a un sitio Plone usando Transmogrifier *(en inglés)*.

        * [How to build your own webframework from scracth](https://training.plone.org/5/advanced-python/index.html) - Migración del contenido del sitio web a un sitio Plone usando Transmogrifier *(en inglés)*.

        * [GatsbyJS](https://training.plone.org/5/gatsby/index.html) - Migración del contenido del sitio web a un sitio Plone usando Transmogrifier *(en inglés)*.

    * Complementos para Plone

        * [awesome-plone](https://github.com/collective/awesome-plone) - Awesome list for Plone *(en inglés)*.

        * [plone.restapi](https://plonerestapi.readthedocs.io/) - Framework para
          desarrollar [API](https://es.wikipedia.org/wiki/Interfaz_de_programaci%C3%B3n_de_aplicaciones)
          basado en [REST](https://es.wikipedia.org/wiki/Representational_State_Transfer)  *(en inglés)*.

* [django-cms](https://www.django-cms.org/) - es el sistema de gestión de contenido basado en Django framework.

    * Tutoriales

        * [Tutorials — django cms documentation](http://docs.django-cms.org/en/latest/introduction/) - Tutorial de django-cms *(en inglés)*.

        * [django cms documentation](http://docs.django-cms.org/en/latest/) - Documentación de django-cms *(en inglés)*.

    * Complementos para django-cms

        * [awesome-django-cms](https://github.com/mishbahr/awesome-django-cms) - Awesome list for django-cms *(en inglés)*.

* [Wagtail](https://wagtail.io/) - Wagtail, el poderoso CMS rapido, elegante y open source para sitios web modernos basado en Django framework.

    * Tutoriales

        * [Getting started — Wagtail documentation](http://docs.wagtail.io/en/v2.5.1/getting_started/index.html) - Primeros pasos de Wagtail CMS *(en inglés)*.

        * [Wagtail documentation](http://docs.wagtail.io/en/) - Documentación de Wagtail CMS *(en inglés)*.

    * Complementos para Wagtail

        * [awesome-wagtail](https://github.com/springload/awesome-wagtail) - Awesome list for Wagtail CMS *(en inglés)*.

* [mezzanine](http://mezzanine.jupo.org/) - es una plataforma de administración de contenido potente, consistente y flexible construido con el framework de Django.

    * Tutoriales

        * [OVERVIEW — mezzanine documentation](http://mezzanine.jupo.org/docs/overview.html) - Descripción general *(en inglés)*.

        * [mezzanine documentation](http://mezzanine.jupo.org/docs/) - Documentación de mezzanine *(en inglés)*.

    * Complementos para mezzanine

        * [Projects for "mezzanine"](https://pypi.org/search/?q=mezzanine) - lista de proyectos mezzanine en PyPI *(en inglés)*.

* [Quokka CMS](http://quokkaproject.org/) – es una plataforma de gestión de contenido flexible desarrollada por Python, Flask y MongoDB.

    * Tutoriales

        * [Flexible, extensible, small CMS powered by Flask and MongoDB](https://pythonawesome.com/flexible-extensible-small-cms-powered-by-flask-and-mongodb/) - un CMS flexible, extensible y pequeño con tecnología de Flask y MongoDB *(en inglés)*

    * Complementos para Quokka CMS

        * [Projects for "Quokka"](https://pypi.org/search/?q=Quokka) - lista de proyectos Quokka en PyPI *(en inglés)*.

* [kotti](http://kotti.pylonsproject.org) - es un framework de aplicaciones web Pythonico de alto nivel. Incluye un Sistema de gestión de contenido extensible llamado Kotti CMS.

    * Tutoriales

        * [Tutorial — Kotti documentation](https://kotti.readthedocs.io/en/latest/first_steps/tutorial.html) - Tutorial de Kotti *(en inglés)*.

        * [Kotti documentation](https://kotti.readthedocs.io/) - Documentación de Kotti *(en inglés)*.

- - -

## Hardware libre con Python

### Bibliotecas para el desarrollo con [Arduino](https://www.arduino.cc/)

* [Arduino y Python](http://playground.arduino.cc/Interfacing/Python) -
Herramientas para establecer comunicación vía puerto serial con Arduino a través
de Python *(en inglés)*.

* [Arduino y Python Videos](http://playground.arduino.cc/Interfacing/Python) -
17 videotutoriales para manejar Arduino con Python *(en inglés)*.

### Bibliotecas para el desarrollo con [Raspberry Pi](https://www.raspberrypi.org/)

* [Raspberry Pi Teach](https://www.raspberrypi.org/resources/teach/) - Recursos
para aprender a programar Raspberry Py con Python *(en inglés)*.

- - -

## Herramientas para desarrollo y depuración de código
* [IPython](http://ipython.org/) - Poderoso shell interactivo; cuenta con
interfaz gráfica basada en Qt e interfaz basada en navegador notebook con
soporte para código, texto enriquecido, expresiones matemáticas, generador de
gráficos entre otros.

* [pdb](https://docs.python.org/2/library/pdb.html/) - Depurador de *Python*
acrónimo ingles pdb: Python Debugger. Soporta punto de interrupción
condicionales y seguimiento paso a paso del código.

* [Lettuce](http://lettuce.it/) - [BDD](GLOSARIO.md#b) Desarrollo dirigido por comportamientos
con *Python*.

- - -

## Herramientas para gestión de proyectos

* [Trello](https://trello.com) - Herramienta de pizarras y tarjetas para
organizar el trabajo.

* [Pivotal Traker](https://www.pivotaltracker.com) - Herramienta que simplifica
el trabajo de colaboración enfocando prioridades del proyecto y equipo de
trabajo.

* [Taiga.io](https://taiga.io) - Plataforma libre y gratuita para gestión de
proyectos con mecanismos ágiles.

* [Jira](https://www.atlassian.com/software/jira) - Herramienta para seguimiento
de equipos de trabajo, flible y extensible.

* [waffle.io](https://waffle.io) - Crea una solución de gestión de proyectos a
partir de repositorios GitHub.

- - -

## Recursos para el desarrollo de [backends](https://es.wikipedia.org/wiki/Front-end_y_back-end)

*Recursos para desarrollar componentes y servidores de backend*

* [celery](http://www.celeryproject.org/) - Biblioteca para el manejo de tareas
asincrónicas mediante mensajes distribuidos en tiempo real.

* [requests](http://docs.python-requests.org/en/latest/) – Una hermosa biblioteca
para manejar peticiones HTTP.

* [rq](http://python-rq.org/) – Biblioteca para implementar colas de tareas usando
Redis

* [Zato](https://zato.io) - Middleware basado en Python y servidor de
aplicaciones para ESB (Enterprise Service Bus), SOA, REST, APIs, e
integraciones con la nube.

- - -

## Recursos para el manejo de bases de datos

* [ZODB](http://www.zodb.org/) - Base de Datos Orientada a Objetos nativa para *Python*.

### Conectores

* [psycopg2](http://initd.org/psycopg/) - *Psycopg* es el adaptador de
*PostgreSQL* más popular.

* [pymongo](http://api.mongodb.org/python/current/) - Conector para *MongoDB*
desde *Python*.

* [MySQL Connector](http://dev.mysql.com/doc/connector-python/en/) - Conector
para *MySQL* desde *Python*.

### Herramientas y Mapeadores Objeto-Relacionales

* [SQLAlchemy][sqlalchemy] - SQLAlchemy es un
[ORM](https://es.wikipedia.org/wiki/Mapeo_objeto-relacional) para python que incluye soporte
para SQLite, MySQL, PostgreSQL, Oracle, MS SQL, entre otros que facilita la
programación orientada a objetos con los motores base de datos relacionales *(en inglés)*

* [Alembic](http://alembic.readthedocs.org/) - Herramienta ligera de migración
de bases de datos para [SQLAlchemy][sqlalchemy].

[sqlalchemy]: http://www.sqlalchemy.org/

### Otras bibliotecas útiles

* [Records](https://github.com/kennethreitz/records) – Records es una biblioteca simple pero
poderosa para hacer consultas SQL (puras) a bases de datos Postgres.

- - -

## Recursos para el desarrollo de [front-ends](https://es.wikipedia.org/wiki/Front-end_y_back-end)

*Los siguientes son recursos no tienen ninguna relación con Python pero son
sumamente útiles para el desarrollo de interfaces web.*

* [Bootstrap](http://getbootstrap.com/) – Es un framework HTML, CSS y JS para
crear aplicaciones web responsivas

* [Foundation](http://foundation.zurb.com/) – Es otro framework HTML, CSS y JS
para el desarrollo de aplicaciones web responsivas

* [PureCSS](http://purecss.io/) – Es un conjunto de módulos CSS muy pequeño que
se usa para desarrollar aplicaciones web responsivas. A diferencia de Bootstrap
y Foundation, PureCSS no contiene ningún módulo Javascript.

- - -

## Recursos para poner a pruebas sistemas

* [aioload](https://github.com/sonic182/aioload) - Pruebas de carga asíncronas
mínimas y rápidas con aiohttp + pandas para dibujar los gráficos.

- - -

## Recursos para el despliegue de aplicaciones

* [fabric](http://www.fabfile.org/) – Es una biblioteca Python basado en
línea de comandos para ejecutar aplicaciones o tareas administrativas locales
o remotas través de [SSH](https://es.wikipedia.org/wiki/Secure_Shell)

- - -

## Servicios para el control de versiones

* [GitHub](https://github.com/) – Es uno de los servicios web más populares
que ofrece hosting gratuito para repositorios en Git, seguimiento de errores,
solicitudes de cambios y wikis. Ofrece repositorios privados pero de pago.

* [GitLab](https://gitlab.com/) – Es otro servicio web que ofrece hosting
gratuito para repositorios en Git, seguimiento de errores, solicitudes de
cambios y wikis. A diferencia de GitHub, GitLab ofrece repositorios privados
de forma gratuita (pero limitados)

* [Bitbucket](https://bitbucket.org/) – Es un servicio web que ofrece hosting
gratuito para no sólo para repositorios en Git sino también en Mercurial,
ofrece seguimiento de errores, solicitudes de cambios y wikis. También ofrece
repositorios privados de forma gratuita (pero limitados)
- - -

## Recursos para crear interfaces gráficas

* [pyqt](https://wiki.python.org/moin/PyQt) – Biblioteca para crear interfaces
gráficas de escritorio usando Qt 4.x o Qt 5.x

* [PySide](https://wiki.qt.io/PySide) – Biblioteca para crear interfaces gráficas
de escritorio usando Qt.

* [python-gtk3](http://python-gtk-3-tutorial.readthedocs.org/en/latest/) –
Biblioteca para crear interfaces gráficas de escritorio usando Gtk+ 3

- - -

## Otros recursos útiles

* [click](http://click.pocoo.org/4/) – Click es una biblioteca para manejar la
línea de comandos desde Python.

* [SaltStack](http://saltstack.com/community/) – Herramienta para gestión de
infraestructuras y despliegue de aplicaciones.

* [pillow](https://python-pillow.github.io/) - El fork amistoso de PIL, es la
biblioteca de procesamiento de imágenes mas utilizada en proyectos Python.

- - -

## Blog posts

* [Drastically Improve Your Python: Understanding Python's Execution Model (inglés)](http://www.jeffknupp.com/blog/2013/02/14/drastically-improve-your-python-understanding-pythons-execution-model/) -
Este post te ayudará a entender qué sucede internamente cuando se realizan tareas
comunes como crear variables o llamar a una función.

* [Open Sourcing a Python Project The Right Way (inglés)](http://www.jeffknupp.com/blog/2013/08/16/open-sourcing-a-python-project-the-right-way/) –
Pasos para hacer tu proyecto open source de la mejor manera.

## Licencia

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

Este trabajo tiene licencia [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
