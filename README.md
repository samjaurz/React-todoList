TODO LIST CREATED IN REACT 

API FLASK / DJANGO FLASK

| Method | Endpoint             | Description                                          |
| :----- | :------------------- | :--------------------------------------------------- |
| `GET`  | `/task/`             | Retrieve all tasks.                                  |
| `GET`  | `/task/<id>`         | Get a specific task by ID.                           |
| `GET`  | `/task/search/`      | Retrieve all tasks matching with the name (use `?name=<query>` for search). |
| `POST` | `/task/`             | Create a new task (requires JSON body: `{ "name": "...", "status": "..." }`). |
| `PUT`  | `/task/<id>`         | Update a specific task by ID (requires JSON body with fields to update). |
| `DELETE`| `/task/<id>`         | Delete a specific task by ID.  
