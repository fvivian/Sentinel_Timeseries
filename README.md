# Sentinel Timeseries

### These notebooks are used in the following environment:
Windwos 10 (64-bit)
Python 3.6.3 (Anaconda)

### Modules:
requests
json
PIL
pyproj

First, the timeseries data is downloaded and stored locally in order to provide easier data manipulation and video fiddling.

Second, the data is loaded into another jupyter notebook script. With a little bit of processing the video is created with openCV and saved locally.

In order to get your own Web Map Service (WMS) instance running (i.e. your own ID), you need to register on https://apps.sentinel-hub.com/configurator/#/ (click on login and then choose "don't have an account yet").

When starting the notebook via command line, add the following option:
```cmd
jupyter notebook --NotebookApp.iopub_data_rate_limit=1e9
```
