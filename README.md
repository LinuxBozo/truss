# Truss Software Engineering Interview

## Requirements
This code has been tested with python 3.8.x in your path. It does look for python3 in general. If you do get an error about `pytz` you should be able to fix by installing `pytz` with pip:
```shell
pip install pytz
```


## How to run
It reads a CSV formatted file on stdin and emits a normalized CSV formatted file on stdout. You can test this code on the command line like this:

```shell
./normalizer < sample.csv > output.csv
```


