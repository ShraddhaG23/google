google
======

A python library for easily downloading data from Google's services that sit behind a login. Currently, this module supports:
* Google Trends
* Google Correlate
* Google Ngram
* Google search

Quick start
-----------
Fire up a requests session with:

    import google
    session = google.Session("username", "password")

You can use session like any other requests session and access anything protected by a Google login.

The session object is passed to the classes which automatically handle the different Google services.
