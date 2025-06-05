 📘 Book Management API Testing Project – Postman

This project showcases API testing using Postman for a simple Book Management system. It covers CRUD operations (Create, Read, Update, Delete), test automation scripts, and data-driven testing with CSV.

🔧 Tools Used
- Postman
- JavaScript (Test Scripts)
- CSV File (for bulk data testing)

✅ Features Covered

- Add Book (POST)
  Adds a new book using dynamic data from CSV.
  
- Get All Books (GET) 
  Fetches a list of all books.

- Get Book by ID (GET)  
  Retrieves specific book details using ID.

- Update Book (PUT)  
  Updates book details (e.g., title, author).

- Delete Book (DELETE) 
  Deletes a book based on its ID.

 📌 Test Automation

Postman test scripts were used to validate:
- HTTP status codes (200, 201, 404)
- Presence of fields like `id`, `title`, `author`
- JSON response structure
- Response content using assertions

 📂 Files Included

| File | Description |
|------|-------------|
| `BookManagementAPI.postman_collection.json` | Main Postman collection with all 5 CRUD requests |
| `books.csv` | Sample test data (title and author for data-driven POST) |
| `README.md` | Project overview and instructions |

 ▶️ How to Run the Collection

1. Open Postman → Import the JSON collection file.
2. Open Collection Runner → Choose `Add Book` request.
3. Upload `books.csv` for dynamic input.
4. Click Run to see the results and test execution.

 💼 Project Highlights

- Demonstrates real-world API testing approach used by QA Engineers.
- Adds value to resume under "Projects" section.

 📧 Contact

Created by:Prinshia Silas  
Location:Mumbai, India  
LinkedIn:prinshia-silas