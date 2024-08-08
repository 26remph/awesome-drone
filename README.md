<img height="240" src="./media/header.png" width="890"/>

# Context
List of awesome , libraries, software and resources for drone create.

<!-- TOC -->
* [Context](#context)
  * [Media manipulation](#media-manipulation)
    * [Image Processing](#image-processing)
    * [Video](#video)
    * [Audio](#audio)
  * [Learn drone](#learn-drone)
    * [Computer Vision](#computer-vision)
    * [Machine Learning](#machine-learning)
    * [Deep Learning](#deep-learning)
  * [Distributed Computing](#distributed-computing)
  * [Data Analysis](#data-analysis)
  * [Data Visualization](#data-visualization)
  * [Geolocation](#geolocation)
  * [Drone Backend](#drone-backend)
    * [Asynchronous Programming](#asynchronous-programming)
    * [Admin Panels](#admin-panels)
    * [Authentication](#authentication)
    * [RESTful API](#restful-api)
    * [Data Validation](#data-validation)
    * [HTTP Clients](#http-clients)
    * [Cryptography](#cryptography)
    * [Caching](#caching)
    * [Database Drivers](#database-drivers)
    * [ORM](#orm)
    * [Task Queues](#task-queues)
    * [WebSocket](#websocket)
    * [ASGI Servers](#asgi-servers)
  * [Code helpers](#code-helpers)
    * [Code Analysis](#code-analysis)
    * [Command-line Interface Development](#command-line-interface-development)
    * [Environment Management](#environment-management)
  * [File Manipulation](#file-manipulation)
  * [GUI Development](#gui-development)
  * [Testing](#testing)
* [Robotics](#robotics)
* [Resources](#resources)
  * [Newsletters](#newsletters)
  * [Podcasts](#podcasts)
* [Contributing](#contributing)
<!-- TOC -->


## Media manipulation
### Image Processing

*Libraries for manipulating images.*

* [pillow](https://github.com/python-pillow/Pillow) - Pillow is the friendly [PIL](http://www.pythonware.com/products/pil/) fork.
* [python-barcode](https://github.com/WhyNotHugo/python-barcode) - Create barcodes in Python with no extra dependencies.
* [pymatting](http://github.com/pymatting/pymatting) - A library for alpha matting.
* [python-qrcode](https://github.com/lincolnloop/python-qrcode) - A pure Python QR Code generator.
* [pywal](https://github.com/dylanaraps/pywal) - A tool that generates color schemes from images.
* [pyvips](https://github.com/libvips/pyvips) - A fast image processing library with low memory needs.
* [quads](https://github.com/fogleman/Quads) - Computer art based on quadtrees.
* [scikit-image](http://scikit-image.org/) - A Python library for (scientific) image processing.
* [thumbor](https://github.com/thumbor/thumbor) - A smart imaging service. It enables on-demand crop, re-sizing and flipping of images.
* [wand](https://github.com/emcconville/wand) - Python bindings for [MagickWand](http://www.imagemagick.org/script/magick-wand.php), C API for ImageMagick.

### Video

*Libraries for manipulating video and GIFs.*

* [moviepy](https://zulko.github.io/moviepy/) - A module for script-based movie editing with many formats, including animated GIFs.
* [scikit-video](https://github.com/aizvorski/scikit-video) - Video processing routines for SciPy.
* [vidgear](https://github.com/abhiTronix/vidgear) - Most Powerful multi-threaded Video Processing framework.

### Audio

*Libraries for manipulating audio and its metadata.*

*Libraries for manipulating audio and its metadata.*

* Audio
    * [audioread](https://github.com/beetbox/audioread) - Cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding.
    * [audioFlux](https://github.com/libAudioFlux/audioFlux) - A library for audio and music analysis, feature extraction.
    * [dejavu](https://github.com/worldveil/dejavu) - Audio fingerprinting and recognition.
    * [kapre](https://github.com/keunwoochoi/kapre) - Keras Audio Preprocessors.
    * [librosa](https://github.com/librosa/librosa) - Python library for audio and music analysis.
    * [matchering](https://github.com/sergree/matchering) - A library for automated reference audio mastering.
    * [mingus](http://bspaans.github.io/python-mingus/) - An advanced music theory and notation package with MIDI file and playback support.
    * [pyaudioanalysis](https://github.com/tyiannak/pyAudioAnalysis) - Audio feature extraction, classification, segmentation and applications.
    * [pydub](https://github.com/jiaaro/pydub) - Manipulate audio with a simple and easy high level interface.
    * [timeside](https://github.com/Parisson/TimeSide) - Open web audio processing framework.
* Metadata
    * [beets](https://github.com/beetbox/beets) - A music library manager and [MusicBrainz](https://musicbrainz.org/) tagger.
    * [eyed3](https://github.com/nicfit/eyeD3) - A tool for working with audio files, specifically MP3 files containing ID3 metadata.
    * [mutagen](https://github.com/quodlibet/mutagen) - A Python module to handle audio metadata.
    * [tinytag](https://github.com/devsnd/tinytag) - A library for reading music meta data of MP3, OGG, FLAC and Wave files.
  
## Learn drone

### Computer Vision

*Libraries for Computer Vision.*

* [easyocr](https://github.com/JaidedAI/EasyOCR) - Ready-to-use OCR with 40+ languages supported.
* [kornia](https://github.com/kornia/kornia/) - Open Source Differentiable Computer Vision Library for PyTorch.
* [opencv](https://opencv.org/) - Open Source Computer Vision Library.
* [pytesseract](https://github.com/madmaze/pytesseract) - A wrapper for [Google Tesseract OCR](https://github.com/tesseract-ocr).
* [tesserocr](https://github.com/sirfz/tesserocr) - Another simple, Pillow-friendly, wrapper around the `tesseract-ocr` API for OCR.

### Machine Learning

*Libraries for Machine Learning. Also see [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python).*

* [gym](https://github.com/openai/gym) - A toolkit for developing and comparing reinforcement learning algorithms.
* [H2O](https://github.com/h2oai/h2o-3) - Open Source Fast Scalable Machine Learning Platform.
* [Metrics](https://github.com/benhamner/Metrics) - Machine learning evaluation metrics.
* [NuPIC](https://github.com/numenta/nupic) - Numenta Platform for Intelligent Computing.
* [scikit-learn](http://scikit-learn.org/) - The most popular Python library for Machine Learning.
* [Spark ML](http://spark.apache.org/docs/latest/ml-guide.html) - [Apache Spark](http://spark.apache.org/)'s scalable Machine Learning library.
* [vowpal_porpoise](https://github.com/josephreisinger/vowpal_porpoise) - A lightweight Python wrapper for [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/).
* [xgboost](https://github.com/dmlc/xgboost) - A scalable, portable, and distributed gradient boosting library.
* [MindsDB](https://github.com/mindsdb/mindsdb) - MindsDB is an open source AI layer for existing databases that allows you to effortlessly develop, train and deploy state-of-the-art machine learning models using standard queries.

### Deep Learning

*Frameworks for Neural Networks and Deep Learning. Also see [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning).*

* [keras](https://github.com/keras-team/keras) - A high-level neural networks library and capable of running on top of either TensorFlow or Theano.
* [pytorch](https://github.com/pytorch/pytorch) - Tensors and Dynamic neural networks in Python with strong GPU acceleration.
* [pytorch-lightning](https://github.com/Lightning-AI/pytorch-lightning) - Deep learning framework to train, deploy, and ship AI products Lightning fast.
* [stable-baselines3](https://github.com/DLR-RM/stable-baselines3) - PyTorch implementations of Stable Baselines (deep) reinforcement learning algorithms.
* [tensorflow](https://github.com/tensorflow/tensorflow) - The most popular Deep Learning framework created by Google.
* [theano](https://github.com/Theano/Theano) - A library for fast numerical computation.

## Distributed Computing

*Frameworks and libraries for Distributed Computing.*

* Batch Processing
    * [dask](https://github.com/dask/dask) - A flexible parallel computing library for analytic computing.
    * [luigi](https://github.com/spotify/luigi) - A module that helps you build complex pipelines of batch jobs.
    * [PySpark](https://github.com/apache/spark) - [Apache Spark](https://spark.apache.org/) Python API.
    * [Ray](https://github.com/ray-project/ray/) - A system for parallel and distributed Python that unifies the machine learning ecosystem.
* Stream Processing
    * [faust](https://github.com/robinhood/faust) - A stream processing library, porting the ideas from [Kafka Streams](https://kafka.apache.org/documentation/streams/) to Python.
    * [streamparse](https://github.com/Parsely/streamparse) - Run Python code against real-time streams of data via [Apache Storm](http://storm.apache.org/).

## Data Analysis

*Libraries for data analyzing.*

* [pandas](http://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.
* [aws-sdk-pandas](https://github.com/aws/aws-sdk-pandas) - Pandas on AWS.
* [datasette](https://github.com/simonw/datasette) - An open source multi-tool for exploring and publishing data.
* [optimus](https://github.com/hi-primus/optimus) - Agile Data Science Workflows made easy with PySpark.

## Data Visualization

*Libraries for visualizing data. Also see [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization).*

* [matplotlib](https://github.com/matplotlib/matplotlib) - A Python 2D plotting library.
* [seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization using Matplotlib.


## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [django-countries](https://github.com/SmileyChris/django-countries) - A Django app that provides a country field for models and forms.
* [geodjango](https://docs.djangoproject.com/en/dev/ref/contrib/gis/) - A world-class geographic web framework.
* [geojson](https://github.com/jazzband/geojson) - Python bindings and utilities for GeoJSON.
* [geopy](https://github.com/geopy/geopy) - Python Geocoding Toolbox.


## Drone Backend

*Main stream python libraries for build drone backend.*

### Asynchronous Programming

*Libraries for asynchronous, concurrent and parallel execution. Also see [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio).*

* [asyncio](https://docs.python.org/3/library/asyncio.html) - (Python standard library) Asynchronous I/O, event loop, coroutines and tasks.
    - [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio)
* [concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) - (Python standard library) A high-level interface for asynchronously executing callables.
* [multiprocessing](https://docs.python.org/3/library/multiprocessing.html) - (Python standard library) Process-based parallelism.
* [uvloop](https://github.com/MagicStack/uvloop) - Ultra fast asyncio event loop.

### Admin Panels

*Libraries for administrative interfaces.*

* [ajenti](https://github.com/ajenti/ajenti) - The admin panel your servers deserve.
* [django-grappelli](https://github.com/sehmaschine/django-grappelli) - A jazzy skin for the Django Admin-Interface.
* [jet-bridge](https://github.com/jet-admin/jet-bridge) - Admin panel framework for any application with nice UI (ex Jet Django).
* [wooey](https://github.com/wooey/wooey) - A Django app which creates automatic web UIs for Python scripts.
* [streamlit](https://github.com/streamlit/streamlit) - A framework which lets you build dashboards, generate reports, or create chat apps in minutes.
* [django-jet](https://github.com/geex-arts/django-jet.git) - Modern template for Django admin interface with improved functionality.

### Authentication

*Libraries for implementing authentications schemes.*

* OAuth
    * [authlib](https://github.com/lepture/authlib) - JavaScript Object Signing and Encryption draft implementation.
* JWT
    * [pyjwt](https://github.com/jpadilla/pyjwt) - JSON Web Token implementation in Python.
    * [python-jose](https://github.com/mpdavis/python-jose/) - A JOSE implementation in Python.
* SSO with machine auth support
   * [keycloak-sso](https://github.com/keycloak/keycloak) - Open Source Identity and Access Management.
   * [zitadel](https://github.com/zitadel/zitadel.git) - Offers everything you need for a customer identity (CIAM) use case. Support Machine-to-machine with JWT profile, Personal Access Tokens (PAT), and Client Credentials

### RESTful API

*Libraries for building RESTful APIs.*

* Framework agnostic
    * [fastapi](https://github.com/tiangolo/fastapi) - A modern, fast, web framework for building APIs with Python 3.6+ based on standard Python type hints.
    * [sanic](https://github.com/sanic-org/sanic) - A Python 3.6+ web server and web framework that's written to go fast.

### Data Validation

*Libraries for validating data. Used for forms in many cases.*
* [pydantic](https://github.com/pydantic/pydantic) - Data validation using Python type hints.

### HTTP Clients

*Libraries for working with HTTP.*

* [httpx](https://github.com/encode/httpx) - A next generation HTTP client for Python.

### Cryptography
* [cryptography](https://github.com/pyca/cryptography) - A package designed to expose cryptographic primitives and recipes to Python


### Caching

*Libraries for caching data.*

* [python-diskcache](https://github.com/grantjenks/python-diskcache) - SQLite and file backed cache backend with faster lookups than memcached and redis.
* [redis](https://github.com/redis/redis) - Redis is often referred to as a data structures server.
* [memcached](https://github.com/memcached/memcached) - Memcached is a high performance multithreaded event-based key/value cache store intended to be used in a distributed system.

### Database Drivers

*Libraries for connecting and operating databases.*

* MySQL - [awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/)
    * [mysqlclient](https://github.com/PyMySQL/mysqlclient) - MySQL connector with Python 3 support ([mysql-python](https://sourceforge.net/projects/mysql-python/) fork).
    * [pymysql](https://github.com/PyMySQL/PyMySQL) - A pure Python MySQL driver compatible to mysql-python.
* PostgreSQL - [awesome-postgres](https://github.com/dhamaniasad/awesome-postgres)
    * [psycopg](https://github.com/psycopg/psycopg) - The most popular PostgreSQL adapter for Python.
* SQlite - [awesome-sqlite](https://github.com/planetopendata/awesome-sqlite)
    * [sqlite3](https://docs.python.org/3/library/sqlite3.html) - (Python standard library) SQlite interface compliant with DB-API 2.0.
    * [sqlite-utils](https://github.com/simonw/sqlite-utils) - Python CLI utility and library for manipulating SQLite databases.
* Other Relational Databases
    * [pymssql](https://github.com/pymssql/pymssql) - A simple database interface to Microsoft SQL Server.
    * [clickhouse-driver](https://github.com/mymarilyn/clickhouse-driver) - Python driver with native interface for ClickHouse.
* NoSQL Databases
    * [cassandra-driver](https://github.com/datastax/python-driver) - The Python Driver for Apache Cassandra.
    * [happybase](https://github.com/python-happybase/happybase) - A developer-friendly library for Apache HBase.
    * [kafka-python](https://github.com/dpkp/kafka-python) - The Python client for Apache Kafka.
    * [pymongo](https://github.com/mongodb/mongo-python-driver) - The official Python client for MongoDB.
    * [motor](https://github.com/mongodb/motor) - The async Python driver for MongoDB.
    * [redis-py](https://github.com/redis/redis-py) - The Python client for Redis.

### ORM

*Libraries that implement Object-Relational Mapping or data mapping techniques.*

* Relational Databases
    * [SQLAlchemy](https://www.sqlalchemy.org/) - The Python SQL Toolkit and Object Relational Mapper.
        * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy)
* NoSQL Databases
    * [hot-redis](https://github.com/stephenmcd/hot-redis) - Rich Python data types for Redis.
    * [redisco](https://github.com/kiddouk/redisco) - A Python Library for Simple Models and Containers Persisted in Redis.

### Task Queues

*Libraries for working with task queues.*

* [celery](https://docs.celeryproject.org/en/stable/) - An asynchronous task queue/job queue based on distributed message passing.
* [dramatiq](https://github.com/Bogdanp/dramatiq) - A fast and reliable background task processing library for Python 3.
* [huey](https://github.com/coleifer/huey) - Little multi-threaded task queue.
* [mrq](https://github.com/pricingassistant/mrq) - A distributed worker task queue in Python using Redis & gevent.
* [rq](https://github.com/rq/rq) - Simple job queues for Python.

### WebSocket

*Libraries for working with WebSocket.*

* [autobahn-python](https://github.com/crossbario/autobahn-python) - WebSocket & WAMP for Python on Twisted and [asyncio](https://docs.python.org/3/library/asyncio.html).
* [channels](https://github.com/django/channels) - Developer-friendly asynchrony for Django.
* [websockets](https://github.com/aaugustin/websockets) - A library for building WebSocket servers and clients with a focus on correctness and simplicity.

### ASGI Servers

*[ASGI](https://asgi.readthedocs.io/en/latest/)-compatible web servers.*

* [daphne](https://github.com/django/daphne) - A HTTP, HTTP2 and WebSocket protocol server for ASGI and ASGI-HTTP.
* [uvicorn](https://github.com/encode/uvicorn) - A lightning-fast ASGI server implementation, using uvloop and httptools.
* [hypercorn](https://github.com/pgjones/hypercorn) - An ASGI and WSGI Server based on Hyper libraries and inspired by Gunicorn.

## Code helpers
### Code Analysis

*Tools of static analysis, linters and code quality checkers.*

* Code Linters & formatters and type checkers
    * [ruff](https://github.com/astral-sh/ruff) - An extremely fast Python linter and code formatter, written in Rust.
    * [mypy](https://github.com/python/mypy) - Check variable types during compile time.

### Command-line Interface Development

*Libraries for building command-line applications.*

* Terminal Rendering
    * [tqdm](https://github.com/tqdm/tqdm) - Fast, extensible progress bar for loops and CLI.

### Environment Management

*Libraries for Python version and virtual environment management.*

* [poetry](https://github.com/python-poetry/poetry.git) - Poetry helps you declare, manage and install dependencies of Python projects, ensuring you have the right stack everywhere.

## File Manipulation

*Libraries for file manipulation.*

* [mimetypes](https://docs.python.org/3/library/mimetypes.html) - (Python standard library) Map filenames to MIME types.
* [pathlib](https://docs.python.org/3/library/pathlib.html) - (Python standard library) An cross-platform, object-oriented path library.
* [path.py](https://github.com/jaraco/path.py) - A module wrapper for [os.path](https://docs.python.org/3/library/os.path.html).
* [python-magic](https://github.com/ahupp/python-magic) - A Python interface to the libmagic file type identification library.
* [watchdog](https://github.com/gorakhargosh/watchdog) - API and shell utilities to monitor file system events.
* [aiofiles](https://github.com/Tinche/aiofiles) - aiofiles is an Apache2 licensed library, written in Python, for handling local disk files in asyncio applications..

## GUI Development

*Libraries for working with graphical user interface applications.*

* [curses](https://docs.python.org/3/library/curses.html) - Built-in wrapper for [ncurses](http://www.gnu.org/software/ncurses/) used to create terminal GUI applications.
* [Eel](https://github.com/ChrisKnott/Eel) - A library for making simple Electron-like offline HTML/JS GUI apps.
* [enaml](https://github.com/nucleic/enaml) - Creating beautiful user-interfaces with Declarative Syntax like QML.
* [Flexx](https://github.com/zoofIO/flexx) - Flexx is a pure Python toolkit for creating GUI's, that uses web technology for its rendering.
* [Gooey](https://github.com/chriskiehl/Gooey) - Turn command line programs into a full GUI application with one line.
* [kivy](https://kivy.org/) - A library for creating NUI applications, running on Windows, Linux, Mac OS X, Android and iOS.
* [pyglet](https://github.com/pyglet/pyglet) - A cross-platform windowing and multimedia library for Python.
* [PyGObject](https://pygobject.readthedocs.io/) - Python Bindings for GLib/GObject/GIO/GTK+ (GTK+3).
* [PyQt](https://doc.qt.io/qtforpython/) - Python bindings for the [Qt](https://www.qt.io/) cross-platform application and UI framework.
* [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI) - Wrapper for tkinter, Qt, WxPython and Remi.
* [pywebview](https://github.com/r0x0r/pywebview/) - A lightweight cross-platform native wrapper around a webview component.
* [Tkinter](https://wiki.python.org/moin/TkInter) - Tkinter is Python's de-facto standard GUI package.
* [Toga](https://github.com/pybee/toga) - A Python native, OS native GUI toolkit.
* [urwid](http://urwid.org/) - A library for creating terminal GUI applications with strong support for widgets, events, rich colors, etc.
* [wxPython](https://wxpython.org/) - A blending of the wxWidgets C++ class library with the Python.
* [DearPyGui](https://github.com/RaylockLLC/DearPyGui/) - A Simple GPU accelerated Python GUI framework

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [pytest](https://docs.pytest.org/en/latest/) - A mature full-featured Python testing tool.
* GUI / Web Testing
    * [Selenium](https://pypi.org/project/selenium/) - Python bindings for [Selenium](http://www.seleniumhq.org/) WebDriver.
* Mock
    * [doublex](https://pypi.org/project/doublex/) - Powerful test doubles framework for Python.
    * [freezegun](https://github.com/spulec/freezegun) - Travel through time by mocking the datetime module.
    * [httmock](https://github.com/patrys/httmock) - A mocking library for requests for Python 2.6+ and 3.2+.
    * [httpretty](https://github.com/gabrielfalcao/HTTPretty) - HTTP request mock tool for Python.
    * [mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.
    * [mocket](https://github.com/mindflayer/python-mocket) - A socket mock framework with gevent/asyncio/SSL support.
    * [responses](https://github.com/getsentry/responses) - A utility library for mocking out the requests Python library.
    * [VCR.py](https://github.com/kevin1024/vcrpy) - Record and replay HTTP interactions on your tests.
* Object Factories
    * [factory_boy](https://github.com/FactoryBoy/factory_boy) - A test fixtures replacement for Python.
    * [mixer](https://github.com/klen/mixer) - Another fixtures replacement. Supports Django, Flask, SQLAlchemy, Peewee and etc.
    * [model_mommy](https://github.com/vandersonmota/model_mommy) - Creating random fixtures for testing in Django.
* Code Coverage
    * [coverage](https://pypi.org/project/coverage/) - Code coverage measurement.
* Fake Data
    * [fake2db](https://github.com/emirozer/fake2db) - Fake database generator.
    * [faker](https://github.com/joke2k/faker) - A Python package that generates fake data.
    * [mimesis](https://github.com/lk-geimfari/mimesis) - is a Python library that help you generate fake data.
    * [radar](https://pypi.org/project/radar/) - Generate random datetime / time.

# Robotics

*Libraries for robotics.*

* [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) - This is a compilation of various robotics algorithms with visualizations.
* [rospy](http://wiki.ros.org/rospy) - This is a library for ROS (Robot Operating System).

# Resources

Where to discover learning resources or new Python libraries.

## Newsletters

## Podcasts

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/26Remph/awesome-drone/blob/master/CONTRIBUTING.md) first.

- - -

If you have any question about this opinionated list, do not hesitate to contact me [@vvbars](https://t.me/vvbars) on Telegram or open an issue on GitHub.