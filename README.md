

# Rest API Documentation

### Route URL
menuapi.com/api/v1

## Get list of Item Groups

### Request

`GET /item-groups/`
      curl -i -H 'Accept: application/json' http://localhost:7000/thing/


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

`GET /item-groups/id`

### Response

    HTTP/1.1 201 Created
    Date: Thu, 24 Feb 2011 12:36:31 GMT
    Status: 201 Created
    Connection: close
    Content-Type: application/json
    Location: /thing/2
    Content-Length: 35

    {"id":2,"name":"Bar","status":null}
