## API
Api url: https://my-json-server.typicode.com/tadite/demo
### resources:
#### Items:  
Запрос: GET /items  
```json
[
    {
        "id": 1,
        "author": 1,
        "name": "Test 1",
        "desc": "desc 1",
        "tags": [
            1
        ],
        "downloads": 33,
        "previews": [
            3,
            9
        ],
        "type": 1
    },
]
```  
##### Возможные пути (работают для всех ресурсов):  
Получить item по id=5: GET /items/5  
Пагинация: GET /items?_page=1  
Фильтрация: GET /items?type=1  
Пагинация+Фильтрация по типу: GET /items?type=1&_page=1

#### Authors:  
Запрос: GET /authors  
```json
[
  {
    "id": 1,
    "username": "admin"
  },
]
```    

#### Types:  
Запрос: GET /types  
```json
[
  {
    "id": 1,
    "name": "type1"
  },
]
```  

#### Tags:  
Запрос: GET /tags  
```json
[
  {
    "id": 1,
    "name": "tag1"
  },
]
```  

#### Previews:  
Запрос: GET /previews  
```json
[
  {
    "id": 1,
    "url": "https://picsum.photos/500/200?image=61"
  },
]
```  
