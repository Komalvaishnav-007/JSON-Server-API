# JSON Server API

This project sets up a simple API using [json-server](https://github.com/typicode/json-server). It serves a mock database and provides an easy way to create RESTful APIs.

## Project Setup

This project uses `json-server` to create a mock API that serves data from a `db.json` file. The data includes `ui-category` and `vscode-extension` resources.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/IshantSomani/dev-tool-json-server-api.git
   cd dev-tool-json-server-api
   ```


### Available Endpoints

- **GET /ui-category**: Returns all `ui-category` items.
- **GET /vscode-extension**: Returns all `vscode-extension` items.
- **GET /ui-category/:id**: Returns a specific `ui-category` item by ID.
- **GET /vscode-extension/:id**: Returns a specific `vscode-extension` item by ID.

## Data Structure

The `db.json` file has the following structure:

```json
{
  "ui-category": [
    {
      "title": "",
      "description": "",
      "url": "",
      "id": 1
    }
  ],
  "vscode-extension": [
    {
      "title": "",
      "description": "",
      "url": "",
      "id": 1
    }
  ]
}
```

## Modifying Data

The data is stored in the `db.json` file. You can edit this file to add, modify, or remove records as needed.

---

Feel free to update or expand the README based on your needs. This version provides an overview of setting up and running the project, details about the `db.json` structure, and how to access your endpoints.