# portfolio [![Build Status](https://travis-ci.org/abmamo/portfolio.svg?branch=master)](https://travis-ci.org/abmamo/portfolio)
<br />
A web application for serving single page portfolio websites. Uses javascript for various smooth scrolling animations, CSS for styling and flask to power the backend. for simplicity and discoverability purposes it uses google analytics tools to analyze site traffic. used in abmamo.com therefore has continuous integration enabled through Travis CI.

To install all dependencies

```sh
pip install -r requirements.txt
```

and to run the website

```sh
python wsgi.py
```

This code uses the pytest testing framework for simple testing (to test main page loading (200) or errors (4xx and 5xx).
