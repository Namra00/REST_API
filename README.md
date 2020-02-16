
# API to search the details of the books 

This demo api project helps to search the books based the different filters and will fetch you the details based on that

## Getting Started

There are two .py files. api.py includes the basic featuring of data without using any database and just fetching the data from the dictionary. While second api_using_SQLite3.py file makes use of databse and collects data from there to give the search result.

### Prerequisites

you need to install python and flask in order to run this api in your local system

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

## Running the tests

run the project in below given order

RUNNING THE .py FILE

```
python api.py
```

RUNNING THE SEARCHES ON DATA(examples)
```
http://127.0.0.1:5000/api/v1/resources/books/all
```
```
127.0.0.1:5000/api/v1/resources/books?id=0
```

RUNNING THE api_using_SQLite.py 

```
python api_using_SQLite.py 
```

RUNNING THE SEARCHES ON DATA (examples)
```
http://127.0.0.1:5000/api/v1/resources/books/all
```
```
http://127.0.0.1:5000/api/v1/resources/books?author=Connie+Willis
```
```
http://127.0.0.1:5000/api/v1/resources/books?author=Connie+Willis&published=1999
```
```
http://127.0.0.1:5000/api/v1/resources/books?published=2010
```
