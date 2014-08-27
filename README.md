happiest-state-python
=====================

Determining the happiest USA state using Twitter streams and Sentiment Analysis in Python.

**To test**

```$ python happiest_state.py AFINN-111.txt output.txt```

- Coded for the Data Science Coursera class (University of Washington)
- Uses geolocation information (and falls back to user-written location information) to determine Tweet location
- Uses basic sentiment analysis to determine tweet sentiment
- The provided output.txt is an example Twitter Stream, but an arbitrary length stream can be used (processing time will increase linearly)
