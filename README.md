# Rest API Documentation

# ManuApi

[ManuApi](https://manuapi.herokuapp.com)
Manu-Api is a free online REST API for you to use whenever you need
pseudo-real data without running any server-side code. You can use for
teaching purposes, building something, sample codes, tests and etc.

You can visit in [ManuApi](https://manuapi.herokuapp.com) for more information.

## How to

you can fetch data with any kind of methods you know(fetch API, Axios, jquery ajax,...)

### Route URL

https://manuapi.herokuapp.com/api/fake-shop

## Get list of all Item Groups

### Request

`GET /item-groups/`

### Response

    HTTP/1.1 200 OK
    Date: Thu, 24 Feb 2011 12:36:30 GMT
    Status: 200 OK
    Connection: close
    Content-Type: application/json
    Content-Length: 2

    []

## Get a specific Item Group

### Request

`GET /item-groups/pkid/`

### Response

    HTTP/1.1 201 Created
    Date: Thu, 24 Feb 2011 12:36:31 GMT
    Status: 201 Created
    Connection: close
    Content-Type: application/json
    Location: /thing/2
    Content-Length: 35

    {"id":2,"name":"Bar","status":null}

## Get list of all Items

### Request

`GET /items/`

### Response

    HTTP/1.1 200 OK
    Date: Thu, 24 Feb 2011 12:36:30 GMT
    Status: 200 OK
    Connection: close
    Content-Type: application/json
    Content-Length: 2

    []

## Get a specific Item

### Request

`GET /items/pkid/`

### Response

    HTTP/1.1 201 Created
    Date: Thu, 24 Feb 2011 12:36:31 GMT
    Status: 201 Created
    Connection: close
    Content-Type: application/json
    Location: /thing/2
    Content-Length: 35

    {"id":2,"name":"Bar","status":null}
