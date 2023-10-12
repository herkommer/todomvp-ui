# Next level MVP TODO
---------------------

## Testa CRUD via Postman
-------------------------------------
- GET /todos = alla todos
- GET /todos/1 = todo med id 1
- POST /todos/{todo} = skicka med todo data i forms, returnerar ngt?
- PUT /todos/1 + {todo} = skicka med id + todo data i forms att uppdatera
- DELETE /todos/1 = ta bort todo med id 1

## Nytt projekt, ny mapp och ny git repo och github repo
----------------------------------------------------------
- express
- view
- controller
- route
- skapa en "index.html" med ett element att "hooka" fast skapad html kod via js
- skapa en app.js
- OBS: inte en index.htlm utan en controller, route och view
- Skapa en layout och använd PUG (view/template engine)

### app.js
------
- onclick kod för knappen add, delete
- event window.onload = autostarta kod efter att hela webbfönstret är laddat
- använd FETCH (sätt en variabel för url till API servern)


## OBS
------------------------
- hantera CORS via npm install cors på API servern
- för att testa start API server OCH UI servern
lägg gärna till serverkod för att visa status för varje anrop
