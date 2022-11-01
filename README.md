# Node Foundation

This is a common application created in order to apply the initial concepts of NodeJS.

This project is a task manager and has the following features.

## Routes

### POST /users
- **body** must have the following format:
  ``` json
  {
    "name": "Gabriel Beserra",
    "username": "gabrielbeserra"
  }
  ```

### GET /todos
- **username** must be provided via header

### POST /todos
- **username** must be provided via header
- **body** must have the following format:
  ``` json
  {
    "title": "Node Foundation",
    "deadline": "2022-11-04"
  }
  ```

### PUT /todos/:id
- **username** must be provided via header
- **body** must have the following format:
  ``` json
  {
    "title": "React Foundation",
    "deadline": "2022-11-12"
  }
  ```

### PATCH /todos/:id/done
- **username** must be provided via header

### DELETE /todos/:id
- **username** must be provided via header

## Installation

- `git clone https://github.com/gbeserra95/node-foundation`
- `bash yarn install`
- `bash yarn dev`
- Access `http://localhost:3333/` via any API platform and make the requests mentioned above.

## Author

Created by [Gabriel Beserra](https://github.com/gbeserra95).

Template by [Rocketseat](https://rocketseat.com.br).

Find me on [LinkedIn](https://www.linkedin.com/in/-gabrielbeserra/)!

Cheers! 🍻

<div align="right">
    <a href="#">back to top</a>
</div>