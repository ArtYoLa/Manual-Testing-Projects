# Задание №5. Знакомство с функционалом Swagger

## Activities

### 1. GET ​/api​/v1​/Activities   
1. HTTP-метод:  GET  
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities  
3. Заголовки запроса: "accept: text/plain; v=1.0"  
4. Тело запроса: отсутствует  
5. Статус-код ответа: 200  
6. Тело ответа: 

    `{
    "id": 1,
    "title": "Activity 1",
    "dueDate": "2023-06-13T16:31:34.9534478+00:00",
    "completed": false
    }`

### 2. POST ​/api​/v1​/Activities  
1. HTTP-метод: POST    
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities  
3. Заголовки запроса: "accept: text/plain; v=1.0", "Content-Type: application/json; v=1.0"  
4. Тело запроса:  

    `{
    "id": 0,
    "title": "string",
    "dueDate": "2023-06-13T15:44:27.949Z",
    "completed": true
    }`

5. Статус-код ответа: 200  
6. Тело ответа: 

    `{
    "id": 0,
    "title": "string",
    "dueDate": "2023-06-13T15:44:27.949Z",
    "completed": true
    }`


### 3. GET ​/api​/v1​/Activities​/{1}  
1. HTTP-метод: GET  
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities/1  
3. Заголовки запроса: "accept: text/plain; v=1.0"  
4. Тело запроса: отсутствует  
5. Статус-код ответа: 200  
6. Тело ответа: 

    `{
    "id": 1,
    "title": "Activity 1",
    "dueDate": "2023-06-13T16:56:55.5583297+00:00",
    "completed": false
    }`

### 4. GET ​/api​/v1​/Activities​/{98332846864}  

1. HTTP-метод: GET  
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities/98332846864   
3. Заголовки запроса: "accept: text/plain; v=1.0"
4. Тело запроса: отсутствует  
5. Статус-код ответа: 400  
6. Тело ответа: 

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-da65f1352f3c9e46bcffc03b65780345-3c767a2d22ea974e-00",
    "errors": {
    "id": [
      "The value '98332846864' is not valid."
    ]
    }
    }`

### 5. PUT ​/api​/v1​/Activities​/{1}  
1. HTTP-метод: PUT  
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities/1  
3. Заголовки запроса: "accept: text/plain; v=1.0"  "Content-Type: application/json; v=1.0"   
4. Тело запроса:  

    `{
    "id": 0,
    "title": "string",
    "dueDate": "2023-06-13T16:02:36.748Z",
    "completed": true
    }`

5. Статус-код ответа:  200 
6. Тело ответа: 

    `{
    "id": 0,
    "title": "string",
    "dueDate": "2023-06-13T16:02:36.748Z",
    "completed": true
    }`

### 6. PUT ​/api​/v1​/Activities​/{4547564545646}  
1. HTTP-метод: PUT  
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities/4547564545646
3. Заголовки запроса: "accept: text/plain; v=1.0"  "Content-Type: application/json; v=1.0"   
4. Тело запроса:  

    `{
    "id": 0,
    "title": "string",
    "dueDate": "2023-06-13T16:02:36.748Z",
    "completed": true
    }`

5. Статус-код ответа: 400  
6. Тело ответа:

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-62f30d24dc57fc4c81384cbc9334fe4e-d10bfb14fa0fc443-00",
    "errors": {
    "id": [
      "The value '4547564545646' is not valid."
    ]
    }
    }`


### 7. DELETE ​/api​/v1​/Activities​/{1}  
1. HTTP-метод: DELETE   
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities/1    
3. Заголовки запроса: "accept: */*"   
4. Тело запроса: отсутствует  
5. Статус-код ответа: 200  
6. Тело ответа: отсутствует

### 8. DELETE ​/api​/v1​/Activities​/{435477878697}  
1. HTTP-метод: DELETE   
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities/435477878697    
3. Заголовки запроса: "accept: */*"   
4. Тело запроса: отсутствует  
5. Статус-код ответа: 400  
6. Тело ответа: 

    {
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-be31c4288c24d04eaa7d74433a5f059e-b2faabdc6fd6cc40-00",
    "errors": {
    "id": [
      "The value '435477878697' is not valid."
    ]
    }
    }


## Authors

### 9. GET ​/api​/v1​/Authors  
1. HTTP-метод: GET     
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors  
3. Заголовки запроса:  "accept: text/plain; v=1.0"
4. Тело запроса: отсутствует
5. Статус-код ответа: 200  
6. Тело ответа: 

    `{
    "id": 1,
    "idBook": 1,
    "firstName": "First Name 1",
    "lastName": "Last Name 1"
    }`



### 10. POST ​/api​/v1​/Authors   
1. HTTP-метод: POST     
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors  
3. Заголовки запроса: -H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0" 
4. Тело запроса:  

    `{
    "id": 0,
    "idBook": 0,
    "firstName": "string",
    "lastName": "string"
    }`

5. Статус-код ответа:  
6. Тело ответа: 200 

    `{
    "id": 0,
    "idBook": 0,
    "firstName": "string",
    "lastName": "string"
    }`


### 11. GET ​/api​/v1​/Authors​/authors​/books​/{1}
1. HTTP-метод:  GET 
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors/authors/books/1  
3. Заголовки запроса:  "accept: text/plain; v=1.0" 
4. Тело запроса:  отсутствует 
5. Статус-код ответа:  200 
6. Тело ответа: 

    `{
    "id": 1,
    "idBook": 1,
    "firstName": "First Name 1",
    "lastName": "Last Name 1"
    },
    {
    "id": 2,
    "idBook": 1,
    "firstName": "First Name 2",
    "lastName": "Last Name 2"
    }`

### 12. GET /api​/v1​/Authors​/authors​/books​/{345667578679}
1. HTTP-метод:  GET 
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors/authors/books/345667578679
3. Заголовки запроса:  "accept: text/plain; v=1.0" 
4. Тело запроса:  отсутствует 
5. Статус-код ответа:  400 
6. Тело ответа: 


    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-b2333e1416b77046ba4d249f7b9341b4-9b7217767574a341-00",
    "errors": {
    "idBook": [
      "The value '345667578679' is not valid."
    ]
    }
    }`


### 13. GET ​/api​/v1​/Authors​/{1}
1. HTTP-метод: GET     
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors/1  
3. Заголовки запроса:   "accept: text/plain; v=1.0"
4. Тело запроса:  отсутствует
5. Статус-код ответа: 200 
6. Тело ответа: 

    `{
    "id": 1,
    "idBook": 1,
    "firstName": "First Name 1",
    "lastName": "Last Name 1"
    }`


### 14. GET ​/api​/v1​/Authors​/{343455768}
1. HTTP-метод: GET     
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors/343455768
3. Заголовки запроса:   "accept: text/plain; v=1.0"
4. Тело запроса:  отсутствует
5. Статус-код ответа: 404 
6. Тело ответа: 

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.4",
    "title": "Not Found",
    "status": 404,
    "traceId": "00-35a6b40c02f0544c8e0c3691655b9c48-7574c4aaf1889c49-00"
    }`


### 15. PUT ​/api​/v1​/Authors​/{1}
1. HTTP-метод:  PUT    
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors/1  
3. Заголовки запроса:  -H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0" 
4. Тело запроса:  

    `{
    "id": 0,
    "idBook": 0,
    "firstName": "string",
    "lastName": "string"
    }`


5. Статус-код ответа: 200 
6. Тело ответа: 

    `{
    "id": 0,
    "idBook": 0,
    "firstName": "string",
    "lastName": "string"
    }`

### 16. PUT ​/api​/v1​/Authors​/{345366453454646}
1. HTTP-метод:  PUT    
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors/345366453454646 
3. Заголовки запроса:  -H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0" 
4. Тело запроса:  

    `{
    "id": 0,
    "idBook": 0,
    "firstName": "string",
    "lastName": "string"
    }`

5. Статус-код ответа: 400 
6. Тело ответа: 

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-4993c68aae603e4c89bd321c3f6d52ff-b70c780e6ffdb44a-00",
    "errors": {
    "id": [
      "The value '345366453454646' is not valid."
    ]
    }
    }`
    
### 17. DELETE ​/api​/v1​/Authors​/{1}
1. HTTP-метод: DELETE 
2. Полный URL запроса:   https://fakerestapi.azurewebsites.net/api/v1/Authors/1
3. Заголовки запроса:  -H  "accept: */*" 
4. Тело запроса:  отсутствует
5. Статус-код ответа:  200
6. Тело ответа: отсутствует


### 18. DELETE ​/api​/v1​/Authors​/{1}
1. HTTP-метод: DELETE 
2. Полный URL запроса:   https://fakerestapi.azurewebsites.net/api/v1/Authors/3435663453656 
3. Заголовки запроса:  -H  "accept: */*" 
4. Тело запроса:  отсутствует
5. Статус-код ответа:  400
6. Тело ответа: 

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-6495539828413a46bb9a4c65d791752c-6f0d3a7d8bf24a4f-00",
    "errors": {
    "id": [
      "The value '3435663453656' is not valid."
    ]
    }
    }`

## Books

### 19. GET ​/api​/v1​/Books
1. HTTP-метод: GET 
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Books  
3. Заголовки запроса:  "accept: text/plain; v=1.0" 
4. Тело запроса: отсутствует 
5. Статус-код ответа: 200  
6. Тело ответа: 

    `{
    "id": 1,
    "title": "Book 1",
    "description": "Lorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\n",
    "pageCount": 100,
    "excerpt": "Lorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\n",
    "publishDate": "2023-06-12T19:41:26.983218+00:00"
    }`


### 20. POST ​/api​/v1​/Books 
1. HTTP-метод: POST    
2. Полный URL запроса:  https://fakerestapi.azurewebsites.net/api/v1/Books  
3. Заголовки запроса:  -H  "accept: */*" -H  "Content-Type: application/json; v=1.0"
4. Тело запроса:  

    `{
    "id": 0,
    "title": "string",
    "description": "string",
    "pageCount": 0,
    "excerpt": "string",
    "publishDate": "2023-06-13T19:42:51.354Z"
    }`

5. Статус-код ответа:  200
6. Тело ответа: 

    `{
    "id": 0,
    "title": "string",
    "description": "string",
    "pageCount": 0,
    "excerpt": "string",
    "publishDate": "2023-06-13T19:42:51.354Z"
    }`

### 21. GET ​/api​/v1​/Books​/{1}
1. HTTP-метод: GET    
2. Полный URL запроса:  https://fakerestapi.azurewebsites.net/api/v1/Books/1 
3. Заголовки запроса: "accept: text/plain; v=1.0"
4. Тело запроса: отсутствсует 
5. Статус-код ответа:  200
6. Тело ответа: 

    `{
    "id": 1,
    "title": "Book 1",
    "description": "Lorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\n",
    "pageCount": 100,
    "excerpt": "Lorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\n",
    "publishDate": "2023-06-12T19:45:32.1812706+00:00"
    }`


### 22. GET ​/api​/v1​/Books​/{352325657678}
1. HTTP-метод: GET    
2. Полный URL запроса:  https://fakerestapi.azurewebsites.net/api/v1/Books/352325657678
3. Заголовки запроса: "accept: text/plain; v=1.0"
4. Тело запроса: отсутствсует 
5. Статус-код ответа:  400
6. Тело ответа: 

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-820996c8f7784046a11bb6e00000481b-3431ba19e0ee0d4c-00",
    "errors": {
    "id": [
      "The value '352325657678' is not valid."
    ]
    }
    }`

### 23. PUT ​/api​/v1​/Books​/{1}
1. HTTP-метод: PUT   
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Books/1 
3. Заголовки запроса:  -H  "accept: */*" -H  "Content-Type: application/json; v=1.0"
4. Тело запроса:  

    `{
    "id": 0,
    "title": "string",
    "description": "string",
    "pageCount": 0,
    "excerpt": "string",
    "publishDate": "2023-06-13T19:48:08.131Z"
    }`

5. Статус-код ответа:  200 
6. Тело ответа: 

    `{
    "id": 0,
    "title": "string",
    "description": "string",
    "pageCount": 0,
    "excerpt": "string",
    "publishDate": "2023-06-13T19:48:08.131Z"
    }`


### 24. PUT ​/api​/v1​/Books​/{354567768678}
1. HTTP-метод: PUT   
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Books/354567768678 
3. Заголовки запроса:  -H  "accept: */*" -H  "Content-Type: application/json; v=1.0"
4. Тело запроса:  

    `{
    "id": 0,
    "title": "string",
    "description": "string",
    "pageCount": 0,
    "excerpt": "string",
    "publishDate": "2023-06-13T19:48:08.131Z"
    }`



5. Статус-код ответа:  400 
6. Тело ответа: 

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-33e9345ab266cb4089d34b5639661ad5-14cf4943a50c674b-00",
    "errors": {
    "id": [
      "The value '354567768678' is not valid."
    ]
    }
    }`

    
### 25. DELETE ​/api​/v1​/Books​/{1}
1. HTTP-метод: DELETE    
2. Полный URL запроса:  https://fakerestapi.azurewebsites.net/api/v1/Books/1
3. Заголовки запроса:   "accept: */*"
4. Тело запроса:  отсутствует
5. Статус-код ответа:  200
6. Тело ответа: отсутствует

### 26. DELETE ​/api​/v1​/Books​/{3244565783456567}
1. HTTP-метод: DELETE    
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Books/3244565783456567 
3. Заголовки запроса:   "accept: */*"
4. Тело запроса:  отсутствует
5. Статус-код ответа:  400
6. Тело ответа: 

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-09487dea045bea48b6a43013a54e77ea-aa1b3439ea87d341-00",
    "errors": {
    "id": [
      "The value '3244565783456567' is not valid."
    ]
    }
    }`

## CoverPhotos

### 27. GET ​/api​/v1​/CoverPhotos
1. HTTP-метод: GET
2. Полный URL запроса:  https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos 
3. Заголовки запроса:  "accept: text/plain; v=1.0" 
4. Тело запроса:  отсутствует
5. Статус-код ответа:  200
6. Тело ответа: 

    `{
    "id": 1,
    "idBook": 1,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 1&w=250&h=350"
    }`

### 28. POST ​/api​/v1​/CoverPhotos 
1. HTTP-метод: POST     
2. Полный URL запроса:  https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos
3. Заголовки запроса:  -H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0"
4. Тело запроса:  

    `{
    "id": 0,
    "idBook": 0,
    "url": "string"
    }`


5. Статус-код ответа: 200 
6. Тело ответа: 

    `{
    "id": 0,
    "idBook": 0,
    "url": "string"
    }`


### 29. GET ​/api​/v1​/CoverPhotos​/books​/covers​/{1} 
1. HTTP-метод: GET     
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/books/covers/1 
3. Заголовки запроса:  "accept: text/plain; v=1.0"
4. Тело запроса:  отсутствует 
5. Статус-код ответа:  200
6. Тело ответа: 

    `{
    "id": 1,
    "idBook": 1,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 1&w=250&h=350"
    }`

### 30. GET /api​/v1​/CoverPhotos​/books​/covers​/{33456567588} 
1. HTTP-метод: GET     
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/books/covers/33456567588
3. Заголовки запроса:  "accept: text/plain; v=1.0"
4. Тело запроса:  отсутствует 
5. Статус-код ответа:  400
6. Тело ответа: 

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-7726cb53e9e31d4aa4e6835b82182580-7a37d5d79e0cb54d-00",
    "errors": {
    "idBook": [
      "The value '33456567588' is not valid."
    ]
    }
    }`

    
### 31. GET ​/api​/v1​/CoverPhotos​/{1}
1. HTTP-метод: GET     
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/1 
3. Заголовки запроса:  "accept: text/plain; v=1.0"
4. Тело запроса:  отсутствует
5. Статус-код ответа:  200
6. Тело ответа: 

    `{
    "id": 1,
    "idBook": 1,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 1&w=250&h=350"
    }`

### 32. GET ​/api​/v1​/CoverPhotos​/{235346769890}
1. HTTP-метод: GET     
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/235346769890
3. Заголовки запроса:  "accept: text/plain; v=1.0"
4. Тело запроса:  отсутствует
5. Статус-код ответа:  400
6. Тело ответа: 

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-eac3d0abdf26354c958dc3ff7825dd59-b9d49aa72572cf4e-00",
    "errors": {
    "id": [
      "The value '235346769890' is not valid."
    ]
    }
    }`


### 33. PUT ​/api​/v1​/CoverPhotos​/{1}
1. HTTP-метод: PUT    
2. Полный URL запроса:  https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/1
3. Заголовки запроса:  -H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0"
4. Тело запроса:  

    `{
    "id": 0,
    "idBook": 0,
    "url": "string"
    }`


5. Статус-код ответа: 200 
6. Тело ответа: 

    `{
    "id": 0,
    "idBook": 0,
    "url": "string"
    }`

### 34. PUT ​/api​/v1​/CoverPhotos​/{3435456768789}
1. HTTP-метод: PUT    
2. Полный URL запроса:  https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/3435456768789
3. Заголовки запроса:  -H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0"
4. Тело запроса:  

    `{
    "id": 0,
    "idBook": 0,
    "url": "string"
    }`


5. Статус-код ответа: 400 
6. Тело ответа: 

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-f89dea9b11040048972e627f9b7b5aeb-9ff10c2e36abf741-00",
    "errors": {
    "id": [
      "The value '3435456768789' is not valid."
    ]
    }
    }`
    
    
### 35. DELETE ​/api​/v1​/CoverPhotos​/{1}
1. HTTP-метод: DELETE    
2. Полный URL запроса:  https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/1
3. Заголовки запроса:   "accept: */*"
4. Тело запроса:  отсутствует
5. Статус-код ответа:  200
6. Тело ответа: отсутствует

### 36. DELETE ​/api​/v1​/CoverPhotos​/{1345354656769}
1. HTTP-метод: DELETE    
2. Полный URL запроса:  https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/1345354656769
3. Заголовки запроса:   "accept: */*"
4. Тело запроса:  отсутствует
5. Статус-код ответа:  400
6. Тело ответа: 

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-81d73dac279d8f4a9fb653770c4054cc-7e422eb5a2480443-00",
    "errors": {
    "id": [
      "The value '1345354656769' is not valid."
    ]
    }
    }`


## Users

### 37. GET ​/api​/v1​/Users
1. HTTP-метод: GET    
2. Полный URL запроса:  https://fakerestapi.azurewebsites.net/api/v1/Users
3. Заголовки запроса:  "accept: text/plain; v=1.0"
4. Тело запроса:  отсутствует
5. Статус-код ответа: 200  
6. Тело ответа: 

    `{
    "id": 1,
    "userName": "User 1",
    "password": "Password1"
    }`
 


### 38. POST ​/api​/v1​/Users 
1. HTTP-метод: POST     
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Users  
3. Заголовки запроса: -H  "accept: */*" -H  "Content-Type: application/json; v=1.0" 
4. Тело запроса:  

    `{
    "id": 0,
    "userName": "string",
    "password": "string"
    }`


5. Статус-код ответа:  200
6. Тело ответа: 

    `{
    "id": 0,
    "userName": "string",
    "password": "string"
    }`


### 39. GET ​/api​/v1​/Users​/{1} 
1. HTTP-метод: GET     
2. Полный URL запроса:  https://fakerestapi.azurewebsites.net/api/v1/Users/1
3. Заголовки запроса:  -H  "accept: */*"
4. Тело запроса:  отсутствует
5. Статус-код ответа:  200
6. Тело ответа: 

    `{
    "id": 1,
    "userName": "User 1",
    "password": "Password1"
    }`

### 40. GET ​/api​/v1​/Users​/{1334547678678} 
1. HTTP-метод: GET     
2. Полный URL запроса:  hhttps://fakerestapi.azurewebsites.net/api/v1/Users/1334547678678 
3. Заголовки запроса:  -H  "accept: */*"
4. Тело запроса:  отсутствует
5. Статус-код ответа:  400
6. Тело ответа: 

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-dda7d5d189f4f6458e01f3e43cdf24a0-84e863c2e44e934f-00",
    "errors": {
    "id": [
      "The value '1334547678678' is not valid."
    ]
    }
    }`


### 41. PUT ​/api​/v1​/Users​/{1} 
1. HTTP-метод: PUT    
2. Полный URL запроса:  https://fakerestapi.azurewebsites.net/api/v1/Users/1
3. Заголовки запроса:  -H  "accept: */*" -H  "Content-Type: application/json; v=1.0"
4. Тело запроса:  

    `{
    "id": 0,
    "userName": "string",
    "password": "string"
    }`


5. Статус-код ответа:  200
6. Тело ответа: 

    `{
    "id": 0,
    "userName": "string",
    "password": "string"
    }`


### 42. PUT ​/api​/v1​/Users​/{132446475653454} 
1. HTTP-метод: PUT    
2. Полный URL запроса:  https://fakerestapi.azurewebsites.net/api/v1/Users/132446475653454 
3. Заголовки запроса:  -H  "accept: */*" -H  "Content-Type: application/json; v=1.0"
4. Тело запроса:  

    `{
    "id": 0,
    "userName": "string",
    "password": "string"
    }`


5. Статус-код ответа:  400
6. Тело ответа: 

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-ab1c4fe2aae0684f839ee5d512733a50-10d394513c26844a-00",
    "errors": {
    "id": [
      "The value '132446475653454' is not valid."
    ]
    }
    }`


### 43. DELETE ​/api​/v1​/Users​/{1} 
1. HTTP-метод: DELETE     
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Users/1 
3. Заголовки запроса:   "accept: */*"
4. Тело запроса:  отсутствует
5. Статус-код ответа:  200
6. Тело ответа: отсутствует

### 44. DELETE ​/api​/v1​/Users​/{1323434546457678} 
1. HTTP-метод: DELETE     
2. Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Users/1323434546457678
3. Заголовки запроса:   "accept: */*"
4. Тело запроса:  отсутствует
5. Статус-код ответа:  400
6. Тело ответа: 

    `{
    "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
    "title": "One or more validation errors occurred.",
    "status": 400,
    "traceId": "00-0eddc2727665e542b4d2681caa7bc47b-405047b08db15c47-00",
    "errors": {
    "id": [
      "The value '1323434546457678' is not valid."
    ]
    }
    }`  
  