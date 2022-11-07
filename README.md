# Express-Quests

### Initialisation

1. Clone the repo
2. `cd Express-Quests-04`
3. `npm i`
4. `cp .env.sample .env`
5. `npm run dev`

---

### To validate the quest

_In Postman_

1. Do a GET request `localhost:5005/api/users/`
2. Copy a user
3. Paste it in the body of your request
4. Delete the id line and modify the user
5. Do a POST request `localhost:5005/api/users/`
6. Do a GET request `localhost:5005/api/users/` and keep the ID in mind
7. Do a DELETE request `localhost:5005/api/users/*id of the new user*`
8. Do a GET request `localhost:5005/api/users/` to check if the user has been deleted !
