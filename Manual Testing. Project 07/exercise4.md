# 1. Activities: GET/api/v1/Activities
- URL "https://fakerestapi.azurewebsites.net/api/v1/Activities/{{activitybad_id}}"

- Ожидаемый результат Ошибка 400 Error: Not Found

- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: b7432761-94e2-40b6-97e0-33b1659da6b0
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
отсутствует
'''
- Заголовки ответа
'''
Content-Type: application/problem+json; charset=utf-8; v=1.0
Date: Thu, 15 Jun 2023 19:02:25 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
'''
Тело ответа 
'''
отсутствует


# 2. Activities: GET/api/v1/Activities
- URL "https://fakerestapi.azurewebsites.net/api/v1/Activities/{{activity_id}}"

- Ожидаемый результат 200 ОК

- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 7a3e951d-edef-43d1-a767-e46ab468ce1b
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
отсутствует
'''
- Заголовки ответа
'''
Content-Type: application/json; charset=utf-8; v=1.0
Date: Thu, 15 Jun 2023 18:58:46 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
'''
Тело ответа 
'''
отсутствует

# 3. Activities: PUT​/api​/v1​/Activities​/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Activities/{{activity_id}}"

- Ожидаемый результат 200 ОК

- Заголовки запроса
'''
Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: a28517bf-5c36-4b1b-951a-cee15a835a8f
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
{
  "id": 0,
  "title": "string",
  "dueDate": "2023-06-15T19:23:17.247Z",
  "completed": true
}

'''
- Заголовки ответа
'''
Content-Type: application/json; charset=utf-8; v=1.0
Date: Thu, 15 Jun 2023 19:24:49 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
'''
Тело ответа 
'''
{
    "id":0,
    "title":"string",
    "dueDate":"2023-06-15T19:23:17.247Z",
    "completed":true
    }

# 4. Activities: PUT​/api​/v1​/Activities​/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Activities/{{activitybad_id}}"

- Ожидаемый результат ошибка 405 Method Not Allowed - Метод не разрешен
'''
- Фактический результат код ответа 200 OK
'''
- Заголовки запроса
'''
Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: a28517bf-5c36-4b1b-951a-cee15a835a8f
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
{
  "id": 0,
  "title": "string",
  "dueDate": "2023-06-15T19:23:17.247Z",
  "completed": true
}

'''
- Заголовки ответа
'''
Content-Type: application/json; charset=utf-8; v=1.0
Date: Thu, 15 Jun 2023 19:24:49 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
'''
Тело ответа 


# 5. Activities: DELETE ​/api​/v1​/Activities​/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Activities/{{activity_id}}"

- Ожидаемый результат код ответа 200 OK
'''
- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: a46e2973-0101-42dc-85a8-e41ea0256d60
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
отсутствует
'''
- Заголовки ответа
'''
Content-Length: 0
Date: Thu, 15 Jun 2023 19:49:06 GMT
Server: Kestrel
api-supported-versions: 1.0
'''
Тело ответа
'''
отсутствует

# 6. Activities: DELETE ​/api​/v1​/Activities​/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Activities/{{activitybad_id}}"

- Ожидаемый результат код ответа 200 OK
'''
- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: a46e2973-0101-42dc-85a8-e41ea0256d60
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
отсутствует
'''
- Заголовки ответа
'''
Content-Length: 0
Date: Thu, 15 Jun 2023 19:49:06 GMT
Server: Kestrel
api-supported-versions: 1.0
'''
Тело ответа
'''
отсутствует

# 7. User: PUT​/api​/v1​/Users​/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Users/{{activity_id}}"

- Ожидаемый результат код ответа 200 OK
'''
- Заголовки запроса
'''
Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 5b3a924d-019c-460a-bee3-a2ef5bb7b0ec
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
{
  "id": 0,
  "userName": "string",
  "password": "null"
}
'''
- Заголовки ответа
'''
Content-Type: application/json; charset=utf-8; v=1.0
Date: Thu, 15 Jun 2023 19:59:12 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
'''
Тело ответа
'''
{
   "id":0,
   "userName":"string",
   "password":"null"
}

# 8. User: PUT​/api​/v1​/Users​/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Users/{{activitybad_id}}"

- Ожидаемый результат код ответа 405 метд зпрещен
'''
- Фактический результат : код ответа 200 ОК
'''
- Заголовки запроса
'''
Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 901fdcb5-92ab-4525-91c3-9d73f88a9915
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
{
  "id": 0,
  "userName": "string",
  "password": "null"
}
'''
- Заголовки ответа
'''
Content-Type: application/json; charset=utf-8; v=1.0
Date: Thu, 15 Jun 2023 20:02:52 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
'''
Тело ответа
'''
{
   "id":0,
   "userName":"string",
   "password":"null"
}

# 9. User: GET/api/v1/Users/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Users/{{activity_id}}"

- Ожидаемый результат код ответа 200 OK
'''
- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: b9320f97-f2db-494d-9cde-3a7d1a3363ea
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
отсутствует
'''
- Заголовки ответа
'''
Content-Type: application/json; charset=utf-8; v=1.0
Date: Thu, 15 Jun 2023 20:09:28 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
'''
Тело ответа
'''
отсутствует

# 10. User: GET/api/v1/Users/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Users/{{activitybad_id}}"

- Ожидаемый результат код ответа 404 Not Found
'''
- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 0683b296-5c45-4a14-bf2e-a8b88ab6d3f8
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
отсутствует
'''
- Заголовки ответа
'''
Content-Type: application/problem+json; charset=utf-8; v=1.0
Date: Thu, 15 Jun 2023 20:13:50 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
'''
Тело ответа
'''
отсутствует


# 11. User: DELETE/api/v1/Users/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Users/{{activity_id}}"

- Ожидаемый результат код ответа 200 OK
'''
- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 92abad4f-2440-4091-9cb0-cc89d78ffb97
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
отсутствует
'''
- Заголовки ответа
'''
Content-Length: 0
Date: Thu, 15 Jun 2023 20:20:37 GMT
Server: Kestrel
api-supported-versions: 1.0
'''
Тело ответа
'''
отсутствует

# 12. User: DELETE/api/v1/Users/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Users/{{activitybad_id}}"

- Ожидаемый результат код ответа 200 OK
'''
- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 032d3c4d-9c83-4fd0-9932-8f1d3282c4ab
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
отсутствует
'''
- Заголовки ответа
'''
Content-Length: 0
Date: Thu, 15 Jun 2023 20:23:53 GMT
Server: Kestrel
api-supported-versions: 1.0
'''
Тело ответа
'''
отсутствует


# 13. Authors: GET/api/v1/Authors/authors/books/{idBook}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Authors/authors/books/{{activity_id}}"

- Ожидаемый результат код ответа 200 OK
'''
- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 4328e114-89f9-4584-b3e2-5c2cd9e9921e
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
отсутствует
'''
- Заголовки ответа
'''
Content-Length: 0
Date: Thu, 15 Jun 2023 20:23:53 GMT
Server: Kestrel
api-supported-versions: 1.0Content-Type: application/json; charset=utf-8; v=1.0
Date: Thu, 15 Jun 2023 20:26:26 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
'''
Тело ответа
'''
отсутствует

# 14. Authors: GET/api/v1/Authors/authors/books/{idBook}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Authors/authors/books/{{activitybad_id}}"

- Ожидаемый результат код ответа 200 OK
'''
- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: a357ae1a-2698-4a4d-a9db-a60f9f76ab5d
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
отсутствует
'''
- Заголовки ответа
'''
Content-Type: application/json; charset=utf-8; v=1.0
Date: Thu, 15 Jun 2023 20:30:16 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
'''
Тело ответа
'''
отсутствует

# 15. Authors: GET​/api​/v1​/Authors​/{id}
- URL "hhttps://fakerestapi.azurewebsites.net/api/v1/Authors/{{activity_id}}"

- Ожидаемый результат код ответа 200 OK
'''
- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 1aadfb08-28d6-4f79-9a59-6bf37e97918e
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
отсутствует
'''
- Заголовки ответа
'''
Content-Type: application/json; charset=utf-8; v=1.0
Date: Thu, 15 Jun 2023 20:32:32 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
'''
Тело ответа
'''
отсутствует

# 16. Authors: GET​/api​/v1​/Authors​/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Authors/{{activitybad_id}}"

- Ожидаемый результат код ответа 404 Not Found
'''
- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 6e212524-2d50-49c1-9089-842dcdfa06d6
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
отсутствует
'''
- Заголовки ответа
'''
Content-Type: application/problem+json; charset=utf-8; v=1.0
Date: Thu, 15 Jun 2023 20:35:06 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
'''
Тело ответа
'''
отсутствует

# 17. Authors: PUT​/api​/v1​/Authors​/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Authors/{{activity_id}}"

- Ожидаемый результат код ответа 200 ok
'''
- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 0f8cb682-f088-4aba-bde2-4317de32d4bb
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}
'''
- Заголовки ответа
'''
Content-Type: application/problem+json; charset=utf-8
Date: Thu, 15 Jun 2023 20:38:55 GMT
Server: Kestrel
Transfer-Encoding: chunked
'''
Тело ответа
'''
{
    "id":0,
    "idBook":0,
    "firstName":"string",
    "lastName":"string"
}

# 18. Authors: PUT​/api​/v1​/Authors​/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Authors/{{activitybad_id}}"

- Ожидаемый результат код ответа 405 (Method Not Allowed - Метод не разрешен)
'''
- Фактический резульатат  код 200 ОК
'''
- Заголовки запроса
'''
Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 29a888d5-8cc4-4594-9ad0-f66341d2e1bd
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}
'''
- Заголовки ответа
'''
Content-Type: application/json; charset=utf-8; v=1.0
Date: Thu, 15 Jun 2023 20:45:04 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
'''
Тело ответа
'''
{
    "id":0,
    "idBook":0,
    "firstName":"string",
    "lastName":"string"
}

# 19. Authors: DELETE​/api​/v1​/Authors​/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Authors/1{{activity_id}}"

- Ожидаемый результат код ответа 200 ok
'''
- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 7c18cc9a-86fe-408d-bdae-da953e365faf
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
отсутствует
'''
- Заголовки ответа
'''
Content-Length: 0
Date: Thu, 15 Jun 2023 20:52:12 GMT
Server: Kestrel
api-supported-versions: 1.0
'''
Тело ответа
'''
отсутствует

# 20. Authors: DELETE​/api​/v1​/Authors​/{id}
- URL "https://fakerestapi.azurewebsites.net/api/v1/Authors/{{activitybad_id}}"

- Ожидаемый результат код ответа 200 ok
'''
- Заголовки запроса
'''
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 70354a77-aa06-4a0d-8d76-c4d74c4e220b
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
'''
- Тело запроса 
'''
отсутствует
'''
- Заголовки ответа
'''
Content-Length: 0
Date: Thu, 15 Jun 2023 20:54:55 GMT
Server: Kestrel
api-supported-versions: 1.0
'''
Тело ответа
'''
отсутствует
------------------------------
# 21. Books: GET. Запрос содержимого ресурса Books.

**URL:** https://fakerestapi.azurewebsites.net/api/v1/Books
**Ожидаемый результат:** 200
**Заголовки запроса:** 
> Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 20b13ae6-0bd2-489f-8adb-8d737727ab51
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
>
**Тело запроса:** Отсутствует
**Заголовки ответа:**
> Content-Type: application/json; charset=utf-8; v=1.0
Date: Fri, 16 Jun 2023 19:23:45 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
>
**Тело ответа:** 
> [
    {
        "id": 1,
        "title": "Book 1",
        "description": "Amet adipiscing sit consectetuer autem
>
# 22. Books: POST. Передача пользовательских данных. ​ID: {0}.

**URL:** https://fakerestapi.azurewebsites.net/api/v1/Books
**Ожидаемый результат:** 200
**Заголовки запроса:** 
> Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 4d1c3618-d033-451e-95b1-4892cabf8aaf
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
>
**Тело запроса:** 
> {
  "id": 0,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-16T16:44:52.668Z"
}
>
**Заголовки ответа:** 
> Content-Type: application/json; charset=utf-8; v=1.0
Date: Sat, 17 Jun 2023 04:27:28 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
>
**Тело ответа:** 
> {
    "id": 0,
    "title": "string",
    "description": "string",
    "pageCount": 0,
    "excerpt": "string",
    "publishDate": "2023-06-16T16:44:52.668Z"
}
>
# 23. Books: POST. Передача пользовательских данных. ​ID: {-1}.

**URL:** https://fakerestapi.azurewebsites.net/api/v1/Books/
**Ожидаемый результат:** 200
**Заголовки запроса:** 
> Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: ca63563b-e1b8-4e49-9626-ba57847f68dd
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
>
**Тело запроса:** 
> {
  "id": -1,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-16T16:44:52.668Z"
}
>
**Заголовки ответа:** 
> Content-Type: application/json; charset=utf-8; v=1.0
Date: Sat, 17 Jun 2023 04:33:08 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

**Тело ответа:** 
> {
    "id": -1,
    "title": "string",
    "description": "string",
    "pageCount": 0,
    "excerpt": "string",
    "publishDate": "2023-06-16T16:44:52.668Z"
}
>
# 24. Books: POST. Передача пользовательских данных. ​ID: {1}.

**URL:** https://fakerestapi.azurewebsites.net/api/v1/Books/
**Ожидаемый результат:** 200
**Заголовки запроса:** 
> Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: ec9417d7-2795-4923-9ec2-ac1483020ffa
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
>
**Тело запроса:** 
> {
  "id": 1,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-16T16:44:52.668Z"
}
>
**Заголовки ответа:** 
> Content-Type: application/json; charset=utf-8; v=1.0
Date: Sat, 17 Jun 2023 04:36:31 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
>
**Тело ответа:** 
> {
    "id": 1,
    "title": "string",
    "description": "string",
    "pageCount": 0,
    "excerpt": "string",
    "publishDate": "2023-06-16T16:44:52.668Z"
}
>
# 25. Books: POST. Передача пользовательских данных. ​ID: {#}.

**URL:** https://fakerestapi.azurewebsites.net/api/v1/Books/
**Ожидаемый результат:** 400
**Заголовки запроса:** 
> Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 01b7f5be-1b33-4535-af19-4b951e4775a1
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
>
**Тело запроса:** 
> {
  "id": #,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-16T16:44:52.668Z"
}
>
**Заголовки ответа:** 
> Content-Type: application/problem+json; charset=utf-8
Date: Sat, 17 Jun 2023 04:40:53 GMT
Server: Kestrel
Transfer-Encoding: chunked
>
**Тело ответа:** 
> {
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-ce7de621640c074e9650857aa8b8aa52-a7818ecf90105c40-00",
    "errors": {
        "$.id": [
            "'#' is an invalid start of a value. Path: $.id | LineNumber: 1 | BytePositionInLine: 8."
        ]
    }
}
>
# 26. Books: POST. Передача пользовательских данных. Отсутствует тело запроса.

**URL:** https://fakerestapi.azurewebsites.net/api/v1/Books
**Ожидаемый результат:** 415
**Заголовки запроса:** 
> User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: f1f3a034-3436-4faf-95e6-5ed837f33589
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
>
**Тело запроса:** отсутствует
**Заголовки ответа:** 
> Content-Type: application/problem+json; charset=utf-8
Date: Sat, 17 Jun 2023 04:48:05 GMT
Server: Kestrel
Transfer-Encoding: chunked
>
**Тело ответа:** 
> {
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.13",
    "title": "Unsupported Media Type",
    "status": 415,
    "traceId": "00-39039e17f38ecf4bafb37daa09529ee0-9a8bbdc2d41d1748-00"
}
>
# 27. Books: POST. Передача пользовательских данных. Неверное тело запроса.

**URL:** https://fakerestapi.azurewebsites.net/api/v1/Books
**Ожидаемый результат:** 400
**Заголовки запроса:** 
> Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: fa19e6c7-ac91-4257-9e77-6c4e15ccee83
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
>
**Тело запроса:** 
> {

 "id":

 "title":

 "description": 

 "pageCount": 

 "excerpt": 

 "publishDate":

}
>
**Заголовки ответа:** 
> Content-Type: application/problem+json; charset=utf-8
Date: Sat, 17 Jun 2023 04:51:58 GMT
Server: Kestrel
Transfer-Encoding: chunked
>
**Тело ответа:** 
> {
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-e1f84b662c82344d89b99a790a0d4187-60a6575f1f7e8e4f-00",
    "errors": {
        "$.id": [
            "The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 4 | BytePositionInLine: 8."
        ]
    }
}
>```
# 28. Books: GET. Запрос содержимого ресурса. ID: {0}.
**Ожидаемый результат:** 404

12:57:48.716 GET https://fakerestapi.azurewebsites.net/api/v1/Books/0

 
  "Request Headers":
  ```
   {
    "content-type": "application/json",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "cd96330b-0cc0-49ae-a431-aab8c648993c",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Request Body": 
  ```
  "[\r\n  {\r\n    \"id\": 0,\r\n    \"title\": \"string\",\r\n    \"description\": \"string\",\r\n    \"pageCount\": 0,\r\n    \"excerpt\": \"string\",\r\n    \"publishDate\": \"2023-06-16T16:51:12.463Z\"\r\n  }\r\n]",
  ```
  "Response Headers":
  ```
   {
    "content-type": "application/problem+json; charset=utf-8; v=1.0",
    "date": "Sat, 17 Jun 2023 04:57:39 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked",
    "api-supported-versions": "1.0"
  },
  ```
  "Response Body": 
  ```
  "{\"type\":\"https://tools.ietf.org/html/rfc7231#section-6.5.4\",\"title\":\"Not Found\",\"status\":404,\"traceId\":\"00-0a2124bda03f63498a069bd89eaed5ef-84a3d60961512f47-00\"}"
}
```
# 29. Books: GET. Запрос содержимого ресурса. ID: {-1}.
**Ожидаемый результат:** 404

12:58:10.865 GET https://fakerestapi.azurewebsites.net/api/v1/Books/-1
  
  "Request Headers":
  ```
   {
    "content-type": "application/json",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "f299ab10-510a-4b58-a27b-d1afd95ea9a5",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Request Body":
  ```
   "[\r\n  {\r\n    \"id\": 0,\r\n    \"title\": \"string\",\r\n    \"description\": \"string\",\r\n    \"pageCount\": 0,\r\n    \"excerpt\": \"string\",\r\n    \"publishDate\": \"2023-06-16T16:51:12.463Z\"\r\n  }\r\n]",
  ```
  "Response Headers": 
  ```
  {
    "content-type": "application/problem+json; charset=utf-8; v=1.0",
    "date": "Sat, 17 Jun 2023 04:58:03 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked",
    "api-supported-versions": "1.0"
  },
  ```
  "Response Body": 
  ```
  "{\"type\":\"https://tools.ietf.org/html/rfc7231#section-6.5.4\",\"title\":\"Not Found\",\"status\":404,\"traceId\":\"00-02af4968e6c89c40ac6c503295f526fd-094c9474b9b2d249-00\"}"
}
```
# 30. Books: GET. Запрос содержимого ресурса. ID: {1}.
**Ожидаемый результат:** 200

12:58:23.949 GET https://fakerestapi.azurewebsites.net/api/v1/Books/1

  "Request Headers":
  ```
   {
    "content-type": "application/json",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "fbb5710f-fcf4-43d9-b295-2b062a11c4a2",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Request Body": 
  ```
  "[\r\n  {\r\n    \"id\": 0,\r\n    \"title\": \"string\",\r\n    \"description\": \"string\",\r\n    \"pageCount\": 0,\r\n    \"excerpt\": \"string\",\r\n    \"publishDate\": \"2023-06-16T16:51:12.463Z\"\r\n  }\r\n]",
  "Response Headers": {
    "content-type": "application/json; charset=utf-8; v=1.0",
    "date": "Sat, 17 Jun 2023 04:58:16 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked",
    "api-supported-versions": "1.0"
  },
  ```
  "Response Body": 
  ```
  "{\"id\":1,\"title\":\"Book 1\",\"description\":\"Euismod et sadipscing dolor magna ut in takimata no takimata te at laoreet placerat no. Diam dolor sed lorem justo sea justo consectetuer et dolore tempor stet in imperdiet stet.\\n\",\"publishDate\":\"2023-06-16T04:58:16.3867397+00:00\"}"
}
```
# 31. Books: PUT. Загрузка содержимого ресурса. ID: {0}.
**Ожидаемый результат:** 404

13:11:38.286 PUT https://fakerestapi.azurewebsites.net/api/v1/Books/0
  
  "Request Headers": 
  ```
  {
    "content-type": "application/json",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "3178d177-5e4d-44e4-bed4-c2435abf9eff",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Request Body": 
  ```
  "{\r\n  \"id\": 0,\r\n  \"title\": \"string\",\r\n  \"description\": \"string\",\r\n  \"pageCount\": 0,\r\n  \"excerpt\": \"string\",\r\n  \"publishDate\": \"2023-06-16T16:38:23.643Z\"\r\n}",
  ```
  "Response Headers": 
  ```
  {
    "content-type": "application/json; charset=utf-8; v=1.0",
    "date": "Sat, 17 Jun 2023 05:11:30 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked",
    "api-supported-versions": "1.0"
  },
  ```
  "Response Body":
  ```
   "{\"id\":0,\"title\":\"string\",\"description\":\"string\",\"pageCount\":0,\"excerpt\":\"string\",\"publishDate\":\"2023-06-16T16:38:23.643Z\"}"
}
```
# 32. Books: PUT. Загрузка содержимого ресурса. ID: {1}.
**Ожидаемый результат:** 200

13:12:46.960 PUT https://fakerestapi.azurewebsites.net/api/v1/Books/1

  "Request Headers":
  ```
   {
    "content-type": "application/json",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "a6e774e4-6885-4a81-bf40-3837c3cde7a6",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Request Body": 
  ```
  "{\r\n  \"id\": 0,\r\n  \"title\": \"string\",\r\n  \"description\": \"string\",\r\n  \"pageCount\": 0,\r\n  \"excerpt\": \"string\",\r\n  \"publishDate\": \"2023-06-16T16:38:23.643Z\"\r\n}",
  ```
  "Response Headers":
  ``` {
    "content-type": "application/json; charset=utf-8; v=1.0",
    "date": "Sat, 17 Jun 2023 05:12:38 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked",
    "api-supported-versions": "1.0"
  },
  ```
  "Response Body":
  ```
   "{\"id\":0,\"title\":\"string\",\"description\":\"string\",\"pageCount\":0,\"excerpt\":\"string\",\"publishDate\":\"2023-06-16T16:38:23.643Z\"}"
}
```
# 33. Books: PUT. Загрузка содержимого ресурса. ID: {-1}.
**Ожидаемый результат:** 405

13:13:24.075 PUT https://fakerestapi.azurewebsites.net/api/v1/Books/-1
  
  "Request Headers": 
  ```
  {
    "content-type": "application/json",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "75e8eed7-d67d-4423-ba34-ef0a0c8c33f5",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Request Body": 
  ```
  "{\r\n  \"id\": 0,\r\n  \"title\": \"string\",\r\n  \"description\": \"string\",\r\n  \"pageCount\": 0,\r\n  \"excerpt\": \"string\",\r\n  \"publishDate\": \"2023-06-16T16:38:23.643Z\"\r\n}",
  ```
  "Response Headers": 
  ```
  {
    "content-type": "application/json; charset=utf-8; v=1.0",
    "date": "Sat, 17 Jun 2023 05:13:16 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked",
    "api-supported-versions": "1.0"
  },
```
  "Response Body": 
```
  "{\"id\":0,\"title\":\"string\",\"description\":\"string\",\"pageCount\":0,\"excerpt\":\"string\",\"publishDate\":\"2023-06-16T16:38:23.643Z\"}"
}
```
# 34. Books: PUT. Загрузка содержимого ресурса. ID: {10000000000}.
**Ожидаемый результат:** 400

13:14:18.193 PUT https://fakerestapi.azurewebsites.net/api/v1/Books/10000000000
  
  "Request Headers": 
  ```
  {
    "content-type": "application/json",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "3944d5d6-da02-458d-98e8-39eb062de81d",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Request Body": 
  ``` 
  "{\r\n  \"id\": 0,\r\n  \"title\": \"string\",\r\n  \"description\": \"string\",\r\n  \"pageCount\": 0,\r\n  \"excerpt\": \"string\",\r\n  \"publishDate\": \"2023-06-16T16:38:23.643Z\"\r\n}",
  ```
  "Response Headers": 
  ```
  {
    "content-type": "application/problem+json; charset=utf-8",
    "date": "Sat, 17 Jun 2023 05:14:10 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked"
  },
  ```
  "Response Body": 
  ```
  "{\"type\":\"https://tools.ietf.org/html/rfc7231#section-6.5.1\",\"title\":\"One or more validation errors occurred.\",\"status\":400,\"traceId\":\"00-889bf32fbc81e54784f62338c9d12b0b-12ae024c84732b40-00\",\"errors\":{\"id\":[\"The value '10000000000' is not valid.\"]}}"
}
```
# 35. Books: DELETE. Удаление ресурса. ID: {0}.
**Ожидаемый результат:** 200

13:22:55.559 DELETE https://fakerestapi.azurewebsites.net/api/v1/Books/0
  
  "Request Headers": 
```
{
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "ad8d95eb-beda-4906-9284-cc59b7923e16",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Response Headers":
```
 {
    "content-length": "0",
    "date": "Sat, 17 Jun 2023 05:22:47 GMT",
    "server": "Kestrel",
    "api-supported-versions": "1.0"
  }
}
```
# 36. Books: DELETE. Удаление ресурса. ID: {1}.
**Ожидаемый результат:** 200

13:23:14.095 DELETE https://fakerestapi.azurewebsites.net/api/v1/Books/1
 
  "Request Headers": 
```
{
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "e457c415-33b3-4432-95ad-cf2c322c4f52",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
```
  "Response Headers": 
```
  {
    "content-length": "0",
    "date": "Sat, 17 Jun 2023 05:23:05 GMT",
    "server": "Kestrel",
    "api-supported-versions": "1.0"
  }
}
```
# 37. Books: DELETE. Удаление ресурса. ID: {-1}.
**Ожидаемый результат:**200

13:23:24.892 DELETE https://fakerestapi.azurewebsites.net/api/v1/Books/-1
  
  "Request Headers": 
  ```
  {
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "acb6972c-7f39-4394-b1ea-b86167101ad3",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Response Headers": 
  ```
  {
    "content-length": "0",
    "date": "Sat, 17 Jun 2023 05:23:16 GMT",
    "server": "Kestrel",
    "api-supported-versions": "1.0"
  }
}
```
# 38. Books: DELETE. Удаление ресурса. ID: {10000000000}.
**Ожидаемый результат:** 400

13:23:35.581 DELETE https://fakerestapi.azurewebsites.net/api/v1/Books/10000000000
  
  "Request Headers": 
  ```
  {
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "fcf3ef3b-c29b-4791-8ee4-214f87facb0f",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Response Headers": 
  ```
  {
    "content-type": "application/problem+json; charset=utf-8",
    "date": "Sat, 17 Jun 2023 05:23:27 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked"
  },
  ```
  "Response Body": 
  ```
  "{\"type\":\"https://tools.ietf.org/html/rfc7231#section-6.5.1\",\"title\":\"One or more validation errors occurred.\",\"status\":400,\"traceId\":\"00-b64ed2f8e684474285b4c740b2ae6e4a-a744d5fefa704949-00\",\"errors\":{\"id\":[\"The value '10000000000' is not valid.\"]}}"
}
```
# 39. CoverPhotos: GET. Запрос содержимого ресурса CoverPhotos

**Ожидаемый результат:** 200

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/

**Заголовки запроса:** 
 
``` Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 20b13ae6-0bd2-489f-8adb-8d737727ab51
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
```
**Тело запроса:** Отсутствует

**Заголовки ответа:**
``` Content-Type: application/json; charset=utf-8; v=1.0
Date: Fri, 16 Jun 2023 19:23:45 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
```
**Тело ответа:** 
```        "id": 1,
        "title": "Book 1",
        "description": "Amet adipiscing sit consectetuer autem
```

# 40. CoverPhotos: POST. Запрос содержимого ресурса CoverPhotos 

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/0

**Ожидаемый результат:** 200

**Заголовки запроса:** 

``` Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 4d1c3618-d033-451e-95b1-4892cabf8aaf
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
```
**Тело запроса:** 
``` {
  "id": 0,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-16T16:44:52.668Z"
}
```
**Заголовки ответа:** 
``` Content-Type: application/json; charset=utf-8; v=1.0
Date: Sat, 17 Jun 2023 04:27:28 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
```
**Тело ответа:** 
``` {
    "id": 0,
    "title": "string",
    "description": "string",
    "pageCount": 0,
    "excerpt": "string",
    "publishDate": "2023-06-16T16:44:52.668Z"
}
```
# 41. CoverPhotos: POST. Запрос содержимого ресурса CoverPhotos 

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/-1

**Ожидаемый результат:** 200

**Заголовки запроса:** 

``` Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: ca63563b-e1b8-4e49-9626-ba57847f68dd
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
```
**Тело запроса:** 
``` {
  "id": -1,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-16T16:44:52.668Z"
}
```
**Заголовки ответа:** 
``` Content-Type: application/json; charset=utf-8; v=1.0
Date: Sat, 17 Jun 2023 04:33:08 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0

**Тело ответа:** 
``` {
    "id": -1,
    "title": "string",
    "description": "string",
    "pageCount": 0,
    "excerpt": "string",
    "publishDate": "2023-06-16T16:44:52.668Z"
}
```
# 42. CoverPhotos: POST. Запрос содержимого ресурса CoverPhotos

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/

**Ожидаемый результат:** 200

**Заголовки запроса:** 

``` Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: ec9417d7-2795-4923-9ec2-ac1483020ffa
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
```
**Тело запроса:** 
``` {
  "id": 1,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-16T16:44:52.668Z"
}
```
**Заголовки ответа:** 
``` Content-Type: application/json; charset=utf-8; v=1.0
Date: Sat, 17 Jun 2023 04:36:31 GMT
Server: Kestrel
Transfer-Encoding: chunked
api-supported-versions: 1.0
```
**Тело ответа:** 
``` 
    "id": 1,
    "title": "string",
    "description": "string",
    "pageCount": 0,
    "excerpt": "string",
    "publishDate": "2023-06-16T16:44:52.668Z"
```
# 43. CoverPhotos: POST. Запрос содержимого ресурса CoverPhotos

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/

**Ожидаемый результат:** 400

**Заголовки запроса:** 

``` Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: 01b7f5be-1b33-4535-af19-4b951e4775a1
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
```
**Тело запроса:** 
``` {
  "id": #,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-16T16:44:52.668Z"
}
```
**Заголовки ответа:** 
``` Content-Type: application/problem+json; charset=utf-8
Date: Sat, 17 Jun 2023 04:40:53 GMT
Server: Kestrel
Transfer-Encoding: chunked
```
**Тело ответа:** 
``` {
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-ce7de621640c074e9650857aa8b8aa52-a7818ecf90105c40-00",
    "errors": {
        "$.id": [
            "'#' is an invalid start of a value. Path: $.id | LineNumber: 1 | BytePositionInLine: 8."
        ]
    }
}
```
# 44. CoverPhotos: POST. Запрос содержимого ресурса CoverPhotos. Отсутствует тело запроса

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos

**Ожидаемый результат:** 415

**Заголовки запроса:** 

``` User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: f1f3a034-3436-4faf-95e6-5ed837f33589
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
```
**Тело запроса:** отсутствует

**Заголовки ответа:** 

``` Content-Type: application/problem+json; charset=utf-8
Date: Sat, 17 Jun 2023 04:48:05 GMT
Server: Kestrel
Transfer-Encoding: chunked
```
**Тело ответа:** 

``` {
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.13",
    "title": "Unsupported Media Type",
    "status": 415,
    "traceId": "00-39039e17f38ecf4bafb37daa09529ee0-9a8bbdc2d41d1748-00"
}
```
# 45. CoverPhotos: POST. Передача пользовательских данных. Неверное тело запроса

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos

**Ожидаемый результат:** 400

**Заголовки запроса:** 

``` Content-Type: application/json
User-Agent: PostmanRuntime/7.32.3
Accept: */*
Cache-Control: no-cache
Postman-Token: fa19e6c7-ac91-4257-9e77-6c4e15ccee83
Host: fakerestapi.azurewebsites.net
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
```
**Тело запроса:** 

``` {

 "id":

 "title":

 "description": 

 "pageCount": 

 "excerpt": 

 "publishDate":

}
```
**Заголовки ответа:** 

``` Content-Type: application/problem+json; charset=utf-8
Date: Sat, 17 Jun 2023 04:51:58 GMT
Server: Kestrel
Transfer-Encoding: chunked
```
**Тело ответа:** 

``` {
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-e1f84b662c82344d89b99a790a0d4187-60a6575f1f7e8e4f-00",
    "errors": {
        "$.id": [
            "The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 4 | BytePositionInLine: 8."
        ]
    }
}
```
# 46. CoverPhotos: GET. Передача пользовательских данных

**Ожидаемый результат:** 404

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/0

  "Request Headers":
  ```
   {
    "content-type": "application/json",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "cd96330b-0cc0-49ae-a431-aab8c648993c",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Request Body": 
  ```
  "[\r\n  {\r\n    \"id\": 0,\r\n    \"title\": \"string\",\r\n    \"description\": \"string\",\r\n    \"pageCount\": 0,\r\n    \"excerpt\": \"string\",\r\n    \"publishDate\": \"2023-06-16T16:51:12.463Z\"\r\n  }\r\n]",
  ```
  "Response Headers":
  ```
   {
    "content-type": "application/problem+json; charset=utf-8; v=1.0",
    "date": "Sat, 17 Jun 2023 04:57:39 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked",
    "api-supported-versions": "1.0"
  },
  ```
  "Response Body": 
  ```
  "{\"type\":\"https://tools.ietf.org/html/rfc7231#section-6.5.4\",\"title\":\"Not Found\",\"status\":404,\"traceId\":\"00-0a2124bda03f63498a069bd89eaed5ef-84a3d60961512f47-00\"}"
}
```
# 47. CoverPhotos: GET. Передача пользовательских данных

**Ожидаемый результат:** 404

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/-1
  
  "Request Headers":
  ```
   {
    "content-type": "application/json",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "f299ab10-510a-4b58-a27b-d1afd95ea9a5",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Request Body":
  ```
   "[\r\n  {\r\n    \"id\": 0,\r\n    \"title\": \"string\",\r\n    \"description\": \"string\",\r\n    \"pageCount\": 0,\r\n    \"excerpt\": \"string\",\r\n    \"publishDate\": \"2023-06-16T16:51:12.463Z\"\r\n  }\r\n]",
  ```
  "Response Headers": 
  ```
  {
    "content-type": "application/problem+json; charset=utf-8; v=1.0",
    "date": "Sat, 17 Jun 2023 04:58:03 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked",
    "api-supported-versions": "1.0"
  },
  ```
  "Response Body": 
  ```
  "{\"type\":\"https://tools.ietf.org/html/rfc7231#section-6.5.4\",\"title\":\"Not Found\",\"status\":404,\"traceId\":\"00-02af4968e6c89c40ac6c503295f526fd-094c9474b9b2d249-00\"}"
```
# 48. CoverPhotos: GET. Передача пользовательских данных

**Ожидаемый результат:** 200

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/1

  "Request Headers":
  ```
   {
    "content-type": "application/json",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "fbb5710f-fcf4-43d9-b295-2b062a11c4a2",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Request Body": 
  ```
  "[\r\n  {\r\n    \"id\": 0,\r\n    \"title\": \"string\",\r\n    \"description\": \"string\",\r\n    \"pageCount\": 0,\r\n    \"excerpt\": \"string\",\r\n    \"publishDate\": \"2023-06-16T16:51:12.463Z\"\r\n  }\r\n]",
  "Response Headers": {
    "content-type": "application/json; charset=utf-8; v=1.0",
    "date": "Sat, 17 Jun 2023 04:58:16 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked",
    "api-supported-versions": "1.0"
  },
  ```
  "Response Body": 
  ```
  "{\"id\":1,\"title\":\"Book 1\",\"description\":\"Euismod et sadipscing dolor magna ut in takimata no takimata te at laoreet placerat no. Diam dolor sed lorem justo sea justo consectetuer et dolore tempor stet in imperdiet stet.\\n\",\"publishDate\":\"2023-06-16T04:58:16.3867397+00:00\"}"
}
```
# 49. CoverPhotos: PUT. Загрузка содержимого ресурса

**Ожидаемый результат:** 404

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/0
  
  "Request Headers": 
  ```
  {
    "content-type": "application/json",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "3178d177-5e4d-44e4-bed4-c2435abf9eff",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Request Body": 
  ```
  "{\r\n  \"id\": 0,\r\n  \"title\": \"string\",\r\n  \"description\": \"string\",\r\n  \"pageCount\": 0,\r\n  \"excerpt\": \"string\",\r\n  \"publishDate\": \"2023-06-16T16:38:23.643Z\"\r\n}",
  ```
  "Response Headers": 
  ```
  {
    "content-type": "application/json; charset=utf-8; v=1.0",
    "date": "Sat, 17 Jun 2023 05:11:30 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked",
    "api-supported-versions": "1.0"
  },
  ```
  "Response Body":
  ```
   "{\"id\":0,\"title\":\"string\",\"description\":\"string\",\"pageCount\":0,\"excerpt\":\"string\",\"publishDate\":\"2023-06-16T16:38:23.643Z\"}"
}
```
# 50. CoverPhotos: PUT. Загрузка содержимого ресурса

**Ожидаемый результат:** 200

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/1

  "Request Headers":
  ```
   {
    "content-type": "application/json",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "a6e774e4-6885-4a81-bf40-3837c3cde7a6",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Request Body": 
  ```
  "{\r\n  \"id\": 0,\r\n  \"title\": \"string\",\r\n  \"description\": \"string\",\r\n  \"pageCount\": 0,\r\n  \"excerpt\": \"string\",\r\n  \"publishDate\": \"2023-06-16T16:38:23.643Z\"\r\n}",
  ```
  "Response Headers":
  ``` {
    "content-type": "application/json; charset=utf-8; v=1.0",
    "date": "Sat, 17 Jun 2023 05:12:38 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked",
    "api-supported-versions": "1.0"
  },
  ```
  "Response Body":
  ```
   "{\"id\":0,\"title\":\"string\",\"description\":\"string\",\"pageCount\":0,\"excerpt\":\"string\",\"publishDate\":\"2023-06-16T16:38:23.643Z\"}"
}
```
# 51. CoverPhotos: PUT. Загрузка содержимого ресурса

**Ожидаемый результат:** 405

 **URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/-1
  
  "Request Headers": 
  ```
  {
    "content-type": "application/json",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "75e8eed7-d67d-4423-ba34-ef0a0c8c33f5",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Request Body": 
  ```
  "{\r\n  \"id\": 0,\r\n  \"title\": \"string\",\r\n  \"description\": \"string\",\r\n  \"pageCount\": 0,\r\n  \"excerpt\": \"string\",\r\n  \"publishDate\": \"2023-06-16T16:38:23.643Z\"\r\n}",
  ```
  "Response Headers": 
  ```
  {
    "content-type": "application/json; charset=utf-8; v=1.0",
    "date": "Sat, 17 Jun 2023 05:13:16 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked",
    "api-supported-versions": "1.0"
  },
```
  "Response Body": 
```
  "{\"id\":0,\"title\":\"string\",\"description\":\"string\",\"pageCount\":0,\"excerpt\":\"string\",\"publishDate\":\"2023-06-16T16:38:23.643Z\"}"
}
```
# 52. CoverPhotos: PUT. Загрузка содержимого ресурса

**Ожидаемый результат:** 400

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/10000000000
  
  "Request Headers": 
  ```
  {
    "content-type": "application/json",
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "3944d5d6-da02-458d-98e8-39eb062de81d",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Request Body": 
  ``` 
  "{\r\n  \"id\": 0,\r\n  \"title\": \"string\",\r\n  \"description\": \"string\",\r\n  \"pageCount\": 0,\r\n  \"excerpt\": \"string\",\r\n  \"publishDate\": \"2023-06-16T16:38:23.643Z\"\r\n}",
  ```
  "Response Headers": 
  ```
  {
    "content-type": "application/problem+json; charset=utf-8",
    "date": "Sat, 17 Jun 2023 05:14:10 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked"
  },
  ```
  "Response Body": 
  ```
  "{\"type\":\"https://tools.ietf.org/html/rfc7231#section-6.5.1\",\"title\":\"One or more validation errors occurred.\",\"status\":400,\"traceId\":\"00-889bf32fbc81e54784f62338c9d12b0b-12ae024c84732b40-00\",\"errors\":{\"id\":[\"The value '10000000000' is not valid.\"]}}"
}
```
# 53. CoverPhotos: PUT. Загрузка содержимого ресурса
**Ожидаемый результат:** 200

**URL:**https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/0
  
  "Request Headers": 
```
{
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "ad8d95eb-beda-4906-9284-cc59b7923e16",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Response Headers":
```
 {
    "content-length": "0",
    "date": "Sat, 17 Jun 2023 05:22:47 GMT",
    "server": "Kestrel",
    "api-supported-versions": "1.0"
  }
}
```
# 54. CoverPhotos: DELETE. Удаление ресурса
**Ожидаемый результат:** 200

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/1
 
  "Request Headers": 
```
{
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "e457c415-33b3-4432-95ad-cf2c322c4f52",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
```
  "Response Headers": 
```
  {
    "content-length": "0",
    "date": "Sat, 17 Jun 2023 05:23:05 GMT",
    "server": "Kestrel",
    "api-supported-versions": "1.0"
  }
}
```
# 55. CoverPhotos: DELETE. Удаление ресурса

**Ожидаемый результат:**200

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/-1
  
  "Request Headers": 
  ```
  {
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "acb6972c-7f39-4394-b1ea-b86167101ad3",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Response Headers": 
  ```
  {
    "content-length": "0",
    "date": "Sat, 17 Jun 2023 05:23:16 GMT",
    "server": "Kestrel",
    "api-supported-versions": "1.0"
  }
}
```
# 51. CoverPhotos: DELETE. Удаление ресурса
**Ожидаемый результат:** 400

**URL:** https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/10000000000
  
  "Request Headers": 
  ```
  {
    "user-agent": "PostmanRuntime/7.32.3",
    "accept": "*/*",
    "cache-control": "no-cache",
    "postman-token": "fcf3ef3b-c29b-4791-8ee4-214f87facb0f",
    "host": "fakerestapi.azurewebsites.net",
    "accept-encoding": "gzip, deflate, br",
    "connection": "keep-alive"
  },
  ```
  "Response Headers": 
  ```
  {
    "content-type": "application/problem+json; charset=utf-8",
    "date": "Sat, 17 Jun 2023 05:23:27 GMT",
    "server": "Kestrel",
    "transfer-encoding": "chunked"
  },
  ```
  "Response Body": 
  ```
  "{\"type\":\"https://tools.ietf.org/html/rfc7231#section-6.5.1\",\"title\":\"One or more validation errors occurred.\",\"status\":400,\"traceId\":\"00-b64ed2f8e684474285b4c740b2ae6e4a-a744d5fefa704949-00\",\"errors\":{\"id\":[\"The value '10000000000' is not valid.\"]}}"
}

