# Back-End Development Pictures

This project is the final submission for the **Back-End Development specialization**. It demonstrates the creation of a backend service using Flask, which manages picture resources from past events stored in cloud object storage. The project includes RESTful APIs for picture URL resources.

## Features
- **GET** and **POST** methods for managing pictures by ID.
- Integration with a MongoDB database to store and retrieve picture URLs.
- Error handling for non-existent pictures.
- Docker integration for easy deployment.

## Setup
1. Clone the repository.
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
4. Run the Flask app:

   ```bash
   flask run
   ```
## Testing
The repository includes Python unit tests. Run the tests using:
```bash
pytest
```
