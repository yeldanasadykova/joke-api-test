# 🧪 Joke API Testing with Postman

This repository contains a Postman test collection and environment setup for testing the **Akademie - Students** joke API.

## 📂 Contents

- `Joke.postman_collection.json`: A Postman collection with 21 API request examples
- `Joke.postman_environment.json`: A Postman environment with variables like host, access codes, and more

## 🚀 Getting Started

To use the collection and environment in Postman:

1. **Download or clone** this repository.
2. **Open Postman**.
3. Go to **File → Import**, then select:
   - `Joke.postman_collection.json`
   - `Joke.postman_environment.json`
4. Select the environment named `Jokes` before making requests.

## 🌐 Environment Variables

The environment file includes:

| Variable Name              | Value                  | Description                          |
|---------------------------|------------------------|--------------------------------------|
| `protocol`                | `https`                | Request protocol                     |
| `host`                    | `uuapp.plus4u.net`     | Base host                            |
| `appName`                 | `uu-jokes-maing01`     | App name in the URL                  |
| `awid`                    | `4ef6a7b01b5942ecbfb925b249af987f` | Application workspace ID     |
| `accessCode1`             | `User01`               | Test login (username)                |
| `accessCode2`             | `password`             | Test login (password)                |
| `token`                   | *(blank)*              | Can be used to set auth tokens       |
| `categoryId`, `jokeID`, etc. | *(blank)*          | Used in dynamic requests             |

## 📌 Notes

- This project is intended for educational and testing purposes.
- Make sure to update any blank variables (`token`, `categoryId`, etc.) as needed when testing specific endpoints.

## 🛠 Requirements

- [Postman](https://www.postman.com/downloads/)
