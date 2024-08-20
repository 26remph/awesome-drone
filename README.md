<img height="240" src="./media/header.png" width="890"/>


# Intro
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

List of awesome , libraries, software and resources for drone create, conforming to the [Awesome Manifesto](awesome.md)

Contributions *very welcome* but first see [Contributing](#contributing)
See En-Ru [glossary](GLOSSARY_EN-RU.md) for translate.

# Context
<!-- TOC -->
* [Drone construction](#drone-construction)
  * [Simulators](#simulators)
  * [Software and Libraries](#software-and-libraries)
    * [Libraries](#libraries)
    * [Ground Control Stations](#ground-control-stations)
  * [Firmware](#firmware)
    * [Transmitters](#transmitters)
    * [Flight Controllers](#flight-controllers)
  * [Hardware and Components](#hardware-and-components)
    * [Platforms](#platforms)
    * [Drone Frames](#drone-frames)
  * [Visual Localization](#visual-localization)
  * [Robotics](#robotics)
* [Learn drone](#learn-drone)
  * [Computer Vision](#computer-vision)
  * [Machine Learning](#machine-learning)
  * [Deep Learning](#deep-learning)
  * [Distributed Computing](#distributed-computing)
  * [Geolocation](#geolocation)
  * [Data Analysis](#data-analysis)
  * [Data Visualization](#data-visualization)
  * [Science](#science)
* [Media manipulation](#media-manipulation)
  * [Image Processing](#image-processing)
  * [Video](#video)
  * [Audio](#audio)
* [Drone Backend](#drone-backend)
  * [Asynchronous Programming](#asynchronous-programming)
  * [Admin Panels](#admin-panels)
  * [Authentication](#authentication)
  * [Cryptography](#cryptography)
  * [Web Frameworks & RESTful API](#web-frameworks--restful-api)
    * [Data Validation](#data-validation)
    * [Caching](#caching)
    * [ORM](#orm)
    * [WebSocket](#websocket)
    * [ASGI Servers](#asgi-servers)
  * [Database Drivers](#database-drivers)
  * [Task Queues](#task-queues)
  * [Helpers](#helpers)
    * [Code Analysis](#code-analysis)
    * [Command-line Interface Development](#command-line-interface-development)
    * [Environment Management](#environment-management)
    * [Logging](#logging)
    * [HTML Manipulation](#html-manipulation)
    * [HTTP Clients](#http-clients)
  * [File Manipulation](#file-manipulation)
* [GUI Development](#gui-development)
* [Testing](#testing)
* [Resources](#resources)
  * [Courses](#courses)
    * [Udemy](#udemy)
  * [Services](#services)
  * [Newsletters](#newsletters)
    * [Remote Control Transmitters](#remote-control-transmitters)
    * [Headsets](#headsets)
    * [Video Receivers](#video-receivers)
      * [1.3GHz](#13ghz)
      * [2.4GHz](#24ghz)
      * [5.8GHz](#58ghz)
    * [Electronics and Motors](#electronics-and-motors)
    * [Cameras](#cameras)
    * [Vendors](#vendors)
      * [Consumer](#consumer)
      * [Military Vendors](#military-vendors)
    * [Unmanned Ground Vehicles](#unmanned-ground-vehicles)
      * [Autonomous Ground Vehicles](#autonomous-ground-vehicles)
    * [Unmanned Underwater Vehicles](#unmanned-underwater-vehicles)
  * [Podcasts](#podcasts)
* [Contributing](#contributing)
<!-- TOC -->

# Drone construction
*Software, libraries, firmware and hardware part for drone construct.*

## Simulators

* [AirSim](https://github.com/Microsoft/AirSim) - Open source simulator based on Unreal Engine for autonomous vehicles.
* [Drone Racing Arcade](https://thedroneracingleague.com/arcade/) - Mobile based FPV racing game
* [DRL Drone Racing Simulator](https://thedroneracingleague.com/drlsim/) - FPV Racing game and simulator with official DRL tracks.
* [FPV Air 2](https://store.steampowered.com/app/889040/FPV_Air_2/) - :dollar: - Basic FPV simulator, runs on slower hardware. Available on Steam.
* [FPV Freerider](https://fpv-freerider.itch.io/fpv-freerider) - :dollar: FPV (first person view) and LOS (line of sight) racing simulator.
* [FPV Freerider Recharged](https://fpv-freerider.itch.io/fpv-freerider-recharged) - :dollar: FPV (first person view) and LOS (line of sight) racing simulator.
* [LiftOff](https://www.immersionrc.com/fpv-products/liftoff-drone-race-simulator/) - :dollar: FPV racing simulator with realistic OSD (on-screen display) experience.
* [Orqa FPV.SkyDive](https://skydive.orqafpv.com/) - Orqa FPV's racing and freestyle simulator.
* [RotorRush](http://rotorrush.com/) - :dollar: Formerly known as FPV Event. Subscription based simulator.
* [VelociDrone](https://www.velocidrone.com/) - :dollar: Multiplayer FPV racing simulator.

## Software and Libraries

* [ArduPilot Mission Planner](https://github.com/ArduPilot/MissionPlanner) - Mission planner software.
* [Paparazzi](http://wiki.paparazziuav.org/wiki/Main_Page) - Software suite for UAVs, including ground control and autopilot.
* [QGroundControl](http://qgroundcontrol.com/) - Ground Control Station for PX4 and ArduPilot based UAVs.

### Libraries

* [DJI Onboard SDK](https://github.com/dji-sdk/Onboard-SDK) - The Onboard SDK allows you to connect to a supported DJI flight controller using a serial port (TTL UART).
* [GoBot](https://github.com/hybridgroup/gobot) - Golang framework for robotics, drones, and the Internet of Things (IoT).
* [Libcyphal](https://github.com/OpenCyphal-Garage/libcyphal) - Portable reference implementation of the Cyphal protocol stack in C++ for embedded systems and Linux. Formerly known as LibUAVCAN.
* [MAVLink](https://github.com/mavlink/mavlink) - Micro Air Vehicle Message Marshalling Library.
* [MAVROS](https://github.com/mavlink/mavros) - MAVLink to ROS gateway with a proxy for Ground Control Station.

### Ground Control Stations

* [QGroundControl](https://github.com/mavlink/qgroundcontrol) - Cross-platform ground control station for drones (Android, iOS, Mac OS, Linux, Windows).
* [MAVProxy](http://ardupilot.github.io/MAVProxy/) - A UAV ground station software package for MAVLink based systems.
* [Ardupilot Mission Planner](https://ardupilot.org/planner/index.html) - A full-featured ground station application for the ArduPilot open source autopilot project.
* [APM Planner 2](https://ardupilot.org/planner2/) - An open-source ground station application for MAVlink based autopilots including APM and PX4/Pixhawk that can be run on Windows, Mac OSX, and Linux.

## Firmware
### Transmitters

* [FreedomTX](https://github.com/tbs-fpv/freedomtx) - Custom firmware for TBS Tango 2 based on OpenTX.
* [OpenTX](http://www.open-tx.org/) - Highly configurable open source firmware for RC radio transmitters.

### Flight Controllers

* [Ardupilot](https://github.com/ArduPilot/ardupilot)
* [BaseFlight](https://github.com/multiwii/baseflight) - :ghost:
* [Betaflight](https://github.com/betaflight/betaflight) - Fork of Cleanflight.
* [ButterFlight](https://github.com/ButterFlight/butterflight) - :ghost: Fork of Betaflight. Firmware focusing on Mini Quads.
* [Cleanflight](https://github.com/cleanflight/cleanflight) - :ghost: Fork of BaseFlight. Supports more FCs and has additional PID contollers.
* [dRonin](https://dronin.org) - :ghost: Autopilot/flight controller firmware for controllers in the OpenPilot/Tau Labs family.
* [EmuFlight](https://github.com/emuflight/EmuFlight) - FC Firmware focusing on flight performance, innovative filtering, leading-edge feature additions, and wide target support.
* [FalcoX](https://flightone.com/download.php?version=stable) - Formerly known as Raceflight one, FlightOne.
* [INAV](https://github.com/iNavFlight/inav)
* [Kiss](https://www.flyduino.net/en_US/page/downloads) - Firmware for KISS FCs.
* [LibrePilot](https://github.com/librepilot/LibrePilot) - :ghost: (GitHub fork is Outdated/Inactive)
* [Open Source Rover Control Code](https://github.com/nasa-jpl/osr-rover-code) - Nasa JPL command firmware for the OSR.
* [PX4 Autopilot](https://github.com/PX4/PX4-Autopilot) - Rebranded to AutoPilot from Firmware
* [SilverWare](https://github.com/silver13/BoldClash-BWHOOP-B-03) - :ghost: Firmware for BoldClash BWHOOP B-03 mini drone
* [SilverWare(NFE)](https://github.com/NotFastEnuf/NFE_Silverware) - :ghost: Firmware for Alienwhoop ZER0, E011, BWHOOP B-03, H8mini, and BETA FPV LITE flight controllers with NotFastEnuf settings and experimental features

## Hardware and Components

### Platforms

* [OpenUAV](https://openuav.eava.ee) - Open-souce UAV platform for research and development

### Drone Frames

* [Source One by TBS](https://github.com/tbs-trappy/source_one) - Open Source freestyle FPV drone frame.
* [Source Two by TBS](https://github.com/ps915/source_two) - Open Source racing FPV drone frame.
* [Source Micro by TBS](https://github.com/ps915/source_micro) - Open Source mini drone frame.
* [Source PodRacer](https://github.com/ps915/source_podracer) - Open source ultra-light drone frame.
* [Source V by TBS](https://github.com/ps915/source_v) - Open Source ultra-stiff drone frame.
* [Source X by TBS](https://github.com/ps915/source_x) - Open Source giant racing drone frame.

## Visual Localization
*   [Drone-Satellite-Ground Three Platiform Localization](https://github.com/layumi/University1652-Baseline) 
*   [ACM MM2023 Workshop: UAV in Multimedia](https://www.zdzheng.xyz/ACMMM2023Workshop/)
*   [Visual Localization Leaderboard](https://github.com/layumi/University1652-Baseline/tree/master/State-of-the-art)


## Robotics

*Libraries for robotics.*

* [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) - This is a compilation of various robotics algorithms with visualizations.
* [rospy](http://wiki.ros.org/rospy) - This is a library for ROS (Robot Operating System).
* [ros2](https://github.com/ros2) - This is a library for ROS2 (Robot Operating System).
  * Also see [awesome-ros2](https://github.com/fkromer/awesome-ros2#readme)

* [micropython](https://github.com/micropython/micropython) - Implementation of Python 3.x on microcontrollers and small embedded systems
  * Also see [awesome-micropython](https://github.com/mcauser/awesome-micropython#readme)
  * Also see [awesome-raspberry-pi](https://github.com/thibmaek/awesome-raspberry-pi?tab=readme-ov-file#models).  

 
# Learn drone

*libraries for create drone looks like biological life*

## Computer Vision

*Libraries for Computer Vision.*

* [easyocr](https://github.com/JaidedAI/EasyOCR) - Ready-to-use OCR with 40+ languages supported.
* [kornia](https://github.com/kornia/kornia/) - Open Source Differentiable Computer Vision Library for PyTorch.
* [opencv](https://opencv.org/) - Open Source Computer Vision Library.
* [pytesseract](https://github.com/madmaze/pytesseract) - A wrapper for [Google Tesseract OCR](https://github.com/tesseract-ocr).
* [tesserocr](https://github.com/sirfz/tesserocr) - Another simple, Pillow-friendly, wrapper around the `tesseract-ocr` API for OCR.

## Machine Learning

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

## Deep Learning

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

## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [django-countries](https://github.com/SmileyChris/django-countries) - A Django app that provides a country field for models and forms.
* [geodjango](https://docs.djangoproject.com/en/dev/ref/contrib/gis/) - A world-class geographic web framework.
* [geojson](https://github.com/jazzband/geojson) - Python bindings and utilities for GeoJSON.
* [geopy](https://github.com/geopy/geopy) - Python Geocoding Toolbox.

## Data Analysis

*Libraries for data analyzing.*

* [pandas](http://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.
* [aws-sdk-pandas](https://github.com/aws/aws-sdk-pandas) - Pandas on AWS.
* [datasette](https://github.com/simonw/datasette) - An open source multi-tool for exploring and publishing data.
* [optimus](https://github.com/hi-primus/optimus) - Agile Data Science Workflows made easy with PySpark.

## Data Visualization

*Libraries for visualizing data.*

* [matplotlib](https://github.com/matplotlib/matplotlib) - A Python 2D plotting library.
* [seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization using Matplotlib.

## Science

*Libraries for scientific computing. Also see [Python-for-Scientists](https://github.com/TomNicholas/Python-for-Scientists).*

* [NumPy](http://www.numpy.org/) - A fundamental package for scientific computing with Python.
* [SciPy](https://www.scipy.org/) - A Python-based ecosystem of open-source software for mathematics, science, and engineering.

# Media manipulation
## Image Processing

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

## Video

*Libraries for manipulating video and GIFs.*

* [moviepy](https://zulko.github.io/moviepy/) - A module for script-based movie editing with many formats, including animated GIFs.
* [scikit-video](https://github.com/aizvorski/scikit-video) - Video processing routines for SciPy.
* [vidgear](https://github.com/abhiTronix/vidgear) - Most Powerful multi-threaded Video Processing framework.

## Audio

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

# Drone Backend

*Main stream python libraries for build drone backend.*

## Asynchronous Programming

*Libraries for asynchronous, concurrent and parallel execution. Also see [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio).*

* [asyncio](https://docs.python.org/3/library/asyncio.html) - (Python standard library) Asynchronous I/O, event loop, coroutines and tasks.
    - [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio)
* [concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) - (Python standard library) A high-level interface for asynchronously executing callables.
* [multiprocessing](https://docs.python.org/3/library/multiprocessing.html) - (Python standard library) Process-based parallelism.
* [uvloop](https://github.com/MagicStack/uvloop) - Ultra fast asyncio event loop.

## Admin Panels

*Libraries for administrative interfaces.*

* [ajenti](https://github.com/ajenti/ajenti) - The admin panel your servers deserve.
* [django-grappelli](https://github.com/sehmaschine/django-grappelli) - A jazzy skin for the Django Admin-Interface.
* [jet-bridge](https://github.com/jet-admin/jet-bridge) - Admin panel framework for any application with nice UI (ex Jet Django).
* [wooey](https://github.com/wooey/wooey) - A Django app which creates automatic web UIs for Python scripts.
* [streamlit](https://github.com/streamlit/streamlit) - A framework which lets you build dashboards, generate reports, or create chat apps in minutes.
* [django-jet](https://github.com/geex-arts/django-jet.git) - Modern template for Django admin interface with improved functionality.
* [flask-admin](https://github.com/flask-admin/flask-admin) - Simple and extensible administrative interface framework for Flask.

## Authentication

*Libraries for implementing authentications schemes.*

* OAuth
    * [authlib](https://github.com/lepture/authlib) - JavaScript Object Signing and Encryption draft implementation.
* JWT
    * [pyjwt](https://github.com/jpadilla/pyjwt) - JSON Web Token implementation in Python.
    * [python-jose](https://github.com/mpdavis/python-jose/) - A JOSE implementation in Python.
* SSO with machine auth support
   * [keycloak-sso](https://github.com/keycloak/keycloak) - Open Source Identity and Access Management.
   * [zitadel](https://github.com/zitadel/zitadel.git) - Offers everything you need for a customer identity (CIAM) use case. Support Machine-to-machine with JWT profile, Personal Access Tokens (PAT), and Client Credentials

## Cryptography
* [cryptography](https://github.com/pyca/cryptography) - A package designed to expose cryptographic primitives and recipes to Python

## Web Frameworks & RESTful API

*Traditional full stack web frameworks. *
*Libraries for building RESTful APIs. *

* Synchronous
    * [flask](https://github.com/pallets/flask) - A microframework for Python.
        * [awesome-flask](https://github.com/humiaozuzu/awesome-flask)
    * [flask-debugtoolbar](https://github.com/pallets-eco/flask-debugtoolbar) - A port of the django-debug-toolbar to flask.
    * [flask-api](https://github.com/flask-api/flask-api) - Browsable Web APIs for Flask.
    * [flask-restful](https://github.com/flask-restful/flask-restful) - Quickly building REST APIs for Flask.

* Asynchronous
    * [fastapi](https://github.com/tiangolo/fastapi) - A modern, fast, web framework for building APIs with Python 3.6+ based on standard Python type hints. Also see [Awesome FastAPI](https://github.com/mjhea0/awesome-fastapi)

### Data Validation

*Libraries for validating data. Used for forms in many cases.*
* [pydantic](https://github.com/pydantic/pydantic) - Data validation using Python type hints.


### Caching

*Libraries for caching data.*

* [python-diskcache](https://github.com/grantjenks/python-diskcache) - SQLite and file backed cache backend with faster lookups than memcached and redis.
* [redis](https://github.com/redis/redis) - Redis is often referred to as a data structures server.
* [memcached](https://github.com/memcached/memcached) - Memcached is a high performance multithreaded event-based key/value cache store intended to be used in a distributed system.

### ORM

*Libraries that implement Object-Relational Mapping or data mapping techniques.*

* Relational Databases
    * [SQLAlchemy](https://www.sqlalchemy.org/) - The Python SQL Toolkit and Object Relational Mapper.
        * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy)
* NoSQL Databases
    * [hot-redis](https://github.com/stephenmcd/hot-redis) - Rich Python data types for Redis.
    * [redisco](https://github.com/kiddouk/redisco) - A Python Library for Simple Models and Containers Persisted in Redis.

### WebSocket

*Libraries for working with WebSocket.*

* [websockets](https://github.com/aaugustin/websockets) - A library for building WebSocket servers and clients with a focus on correctness and simplicity.

### ASGI Servers

*[ASGI](https://asgi.readthedocs.io/en/latest/)-compatible web servers.*

* [daphne](https://github.com/django/daphne) - A HTTP, HTTP2 and WebSocket protocol server for ASGI and ASGI-HTTP.
* [uvicorn](https://github.com/encode/uvicorn) - A lightning-fast ASGI server implementation, using uvloop and httptools.
* [hypercorn](https://github.com/pgjones/hypercorn) - An ASGI and WSGI Server based on Hyper libraries and inspired by Gunicorn.

## Database Drivers

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
* S3 store
    * [minio-py](https://github.com/minio/minio-py) - Official synchronous the MinIO Python Client SDK.
    * [miniopy-async](https://github.com/hlf20010508/miniopy-async) - Unofficial Asynchronous MinIO Client SDK for Python

## Task Queues

*Libraries for working with task queues.*

* [celery](https://docs.celeryproject.org/en/stable/) - An asynchronous task queue/job queue based on distributed message passing.
* [dramatiq](https://github.com/Bogdanp/dramatiq) - A fast and reliable background task processing library for Python 3.
* [huey](https://github.com/coleifer/huey) - Little multi-threaded task queue.
* [mrq](https://github.com/pricingassistant/mrq) - A distributed worker task queue in Python using Redis & gevent.
* [rq](https://github.com/rq/rq) - Simple job queues for Python.

## Helpers
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

### Logging

*Libraries for generating and working with logs.*

* [sentry-python](https://github.com/getsentry/sentry-python) - Sentry SDK for Python.
### HTML Manipulation

*Libraries for working with HTML and XML.*

* [beautifulsoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Providing Pythonic idioms for iterating, searching, and modifying HTML or XML.

### HTTP Clients

*Libraries for working with HTTP.*

* [httpx](https://github.com/encode/httpx) - A next generation HTTP client for Python.


## File Manipulation

*Libraries for file manipulation.*

* [mimetypes](https://docs.python.org/3/library/mimetypes.html) - (Python standard library) Map filenames to MIME types.
* [pathlib](https://docs.python.org/3/library/pathlib.html) - (Python standard library) An cross-platform, object-oriented path library.
* [path.py](https://github.com/jaraco/path.py) - A module wrapper for [os.path](https://docs.python.org/3/library/os.path.html).
* [python-magic](https://github.com/ahupp/python-magic) - A Python interface to the libmagic file type identification library.
* [watchdog](https://github.com/gorakhargosh/watchdog) - API and shell utilities to monitor file system events.
* [aiofiles](https://github.com/Tinche/aiofiles) - aiofiles is an Apache2 licensed library, written in Python, for handling local disk files in asyncio applications..

# GUI Development

*Libraries for working with graphical user interface applications.*

* [curses](https://docs.python.org/3/library/curses.html) - Built-in wrapper for [ncurses](http://www.gnu.org/software/ncurses/) used to create terminal GUI applications.
* [Eel](https://github.com/ChrisKnott/Eel) - A library for making simple Electron-like offline HTML/JS GUI apps.
* [enaml](https://github.com/nucleic/enaml) - Creating beautiful user-interfaces with Declarative Syntax like QML.
* [Flexx](https://github.com/zoofIO/flexx) - Flexx is a pure Python toolkit for creating GUI's, that uses web technology for its rendering.
* [Gooey](https://github.com/chriskiehl/Gooey) - Turn command line programs into a full GUI application with one line.
* [kivy](https://kivy.org/) - A library for creating NUI applications, running on Windows, Linux, Mac OS X, Android and iOS.
* [pyglet](https://github.com/pyglet/pyglet) - A cross-platform windowing and multimedia library for Python.
* [PyGObject](https://pygobject.readthedocs.io/) - Python Bindings for GLib/GObject/GIO/GTK+ (GTK+3).
* [PyQt](https://doc.qt.io/qtforpython/) - Python bindings for the [Qt](https://www.qt.io/) cross-platform application and UI framework. Also see [Awesome Qt](https://github.com/JesseTG/awesome-qt#readme)
* [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI) - Wrapper for tkinter, Qt, WxPython and Remi.
* [pywebview](https://github.com/r0x0r/pywebview/) - A lightweight cross-platform native wrapper around a webview component.
* [Tkinter](https://wiki.python.org/moin/TkInter) - Tkinter is Python's de-facto standard GUI package.
* [Toga](https://github.com/pybee/toga) - A Python native, OS native GUI toolkit.
* [urwid](http://urwid.org/) - A library for creating terminal GUI applications with strong support for widgets, events, rich colors, etc.
* [wxPython](https://wxpython.org/) - A blending of the wxWidgets C++ class library with the Python.
* [DearPyGui](https://github.com/RaylockLLC/DearPyGui/) - A Simple GPU accelerated Python GUI framework

# Testing

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

# Resources

Where to discover learning resources or new Python libraries.

## Courses
* [Flying Car and Autonomous Flight Engineer](https://eu.udacity.com/course/flying-car-nanodegree--nd787) Udacity - Master autonomous flight software engineering skills as you build your career in flying cars and drone robotics.
* [Robotics: Dynamics and Control](https://www.edx.org/course/robotics-dynamics-control-pennx-robo3x) edX - Learn how to develop dynamic models of robot manipulators, mobile robots, and drones (quadrotors).

### Udemy

* [UAS/Drone Remote Pilot Test Prep for Part 107](https://www.udemy.com/remote-pilot-certificate-test-prep-for-part-107-exam/) - :dollar: - A comprehensive class that encompasses everything needed to know to become a proficient Remote Pilot and to pass the FAA written initial or recurrent exam.
* [Drone Photography | Shoot Professional Photos With Any Drone](https://www.udemy.com/course/dronephotography/) - :dollar: - Your Complete Online Guide to Shooting Incredible Drone Photography Like a Professional
* [Drone Programming with Python - Face Recognition & Tracking](https://www.udemy.com/course/drone-programming-with-python-face-recognition-tracking/) - :dollar: - Operating drone with network programming, face recognition using OpenCV, automatic tracking, implementing web camera

## Services

* [AirMap](https://www.airmap.com/) - Aeronautical data & services to unmanned aircraft.
* [DroneDeploy](https://www.dronedeploy.com/) - Drone & UAV Mapping Software.
* [RotorBuilds](https://rotorbuilds.com/) - FPV Part lists and Build Logs.
* [Zeitiew](https://www.zeitview.com/) - Online marketplace for Drone services. Formerly known as DroneBase.

## Newsletters

### Remote Control Transmitters

* [FlySky](http://www.flyskyrc.com/) - Entry level transmitters.
* [FrSky](https://www.frsky-rc.com/) - Taranis and Horus line of transmitters powered by OpenTX firmware.
* [Futaba](https://www.futabarc.com)
* [Spektrum](https://www.spektrumrc.com)
* [Team Blacksheep](https://team-blacksheep.com) - Tango 1 and 2 transmitters.

### Headsets

* [DJI Digital FPV System](https://www.dji.com/fpv/) - Low latency digital FPV goggles.
* [FatShark](https://www.fatshark.com) - Headsets praised by racers.
* [ORQA FPV.One](https://orqafpv.com) - Headsets and controllers

### Video Receivers

#### 1.3GHz

* [ClearView XLR 1.3](https://clearview-direct.com/product-category/ground-station-receivers/1-3-receivers/)

#### 2.4GHz

* [ClearView XLR 2.4](https://clearview-direct.com/product-category/ground-station-receivers/2-4-receivers/)
* [TBS Ground station](https://www.team-blacksheep.com/products/prod:tbs_gs_2g4)

#### 5.8GHz

* [ClearView Goggle Receiver](https://clearview-direct.com/shop/clearview-goggle-products/clearview-goggle-module/)
* [ClearView 5.8GHz Ground Station Receivers](https://clearview-direct.com/product-category/ground-station-receivers/5-8-receivers/)
* [rapidFIRE](https://www.immersionrc.com/fpv-products/rapidfire/)
* [TBS Fusion](https://www.team-blacksheep.com/products/prod:tbs_fusion) - Has CRSF integration (for changing channels).

### Electronics and Motors

Terminology:
See [glossary en-ru](GLOSSARY_EN-RU.md) for translate.  

* FC - Flight Controller
* ESC - Electronic Speed Controller
* PDB - Power Distribution Board
* RX - Receivers
* TX - Transmitters (external)
* VRX - Video Receiver
* VTX - Video Transmitter

List:

* [3BHobby](https://www.3bhobby.com) - Motors
* [Airbot](https://store.myairbot.com/flight-controller.html) - FC, ESC
* [BrotherHobby](https://www.brotherhobbystore.com) - Motors
* [ClearView](https://clearview-direct.com/) - VRX, VTX
* [DalProp](http://dalprop.com) - Props
* [Diatone](https://www.diatone.us/) - FC, ESC, VTX, Motors
* [Fl1ghtOne](https://flightone.com) - FC, ESC
* [Flyduino](https://www.flyduino.net/en_US/) - FC, ESC
* [GemFan](https://www.gfprops.com/) - Props
* [Hobbywing](http://www.hobbywing.com) - FC, ESC, Motors
* [Holybro](http://www.holybro.com) - FC, ESC, PDB
* [HQProp](http://www.hqprop.com) - Props
* [iFlight](https://www.iflight-rc.com) - Motors
* [Lumenier](https://www.lumenier.com) - FC, ESC, PDB, VTX, Motors
* [MatekSys](http://www.mateksys.com) - FC, PDB, VTX
* [RacerStar](https://www.racerstar.com) - FC, ESC, Motors
* [SP Racing](http://seriouslypro.com) - FC
* [T-Motor](http://www.tmotor.com) - FC, Motors
* [Team Blacksheep](https://www.team-blacksheep.com) - ESC, RX, TX, VRX, VTX

### Cameras

* [Caddx.us](https://caddxfpv.com/)
* [DJI O3 Air unit](https://www.dji.com/ee/o3-air-unit) - Camera with digital video transmission
* [Foxeer](http://www.foxeer.com)
* [RunCam](https://runcam.com)

### Vendors
#### Consumer

* [Autel](https://www.autelpilot.eu/) - :cn: - Compact EVO series drones, alternative to DJI Mavic series. Dragonfish series fixed-wing UAVs coming soon.
* [DJI](https://www.dji.com/) - :cn: - DJI is the world's leader in the consumer drone market - Mavic, Phantom, Inspire and Matrice series drones.
* [Eachine](https://www.eachine.com/) - :cn: - Mini and micro drones. FPV beginners sets.
* [Hubsan](https://www.hubsan.com/na/) - :cn: - Micro and Mini lower cost drones.
* [Parrot SA](https://www.parrot.com/global/) - :fr: - Famously Parrot Bebop and Parrot AR series drones.
* [Syma](http://www.symatoys.com/) - :cn: - RC toy quadcopters.
* [Yuneec International](https://www.yuneec.com/) - :cn: - Yuneec camera drones.

#### Military Vendors

* [AeroVironment](https://www.avinc.com/) - Small range fixed-wing UAVs.
* [Baykar](https://www.baykartech.com/en/) - Bayraktar series battle- proven long-range fixed-wing UAVs.
* [Eli](http://www.uav.ee/) - Pneumatic launchers for fixed wing UAVs.
* [INSITU](https://www.insitu.com/) - Long-range and extended endurance fixed-wing UAVs.
* [Threod Systems](http://threod.com/) - Fixed-wing and multi-rotor UAVs.

### Unmanned Ground Vehicles

#### Autonomous Ground Vehicles

* [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover) - Nasa JPL scaled down version of the curiosity rover, made of COTS.
* [Turtlebot](https://www.turtlebot.com) - Open sourced UGV, [ROS](http://www.ros.org/) standard platform.

### Unmanned Underwater Vehicles

* [Geneinno](https://www.geneinno.com/) - Underwater drones.

## Podcasts

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/26Remph/awesome-drone/blob/master/CONTRIBUTING.md) first.

- - -

If you have any question about this opinionated list, do not hesitate to contact me [@vvbars](https://t.me/vvbars) on Telegram or open an issue on GitHub.