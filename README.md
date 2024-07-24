# ContactsMangementApp

This project is a simple Contact List CRUD (Create, Read, Update, Delete) application built using Flask, a lightweight WSGI web application framework in Python. The application allows users to manage a contact list by adding, viewing, updating, and deleting contacts. Each contact entry consists of a first name, last name, and email address.


![demo](https://github.com/user-attachments/assets/a0f4adc7-351e-4768-8e05-6eb2da7cf558)


## Features

* **Create**: Add a new contact with a first name, last name, and email.
* **Read**: View a list of all contacts.
* **Update**: Edit the details of an existing contact.
* **Delete**: Remove a contact from the list.

## Technologies Used

* **Backend**: Flask
* **Database**: SQLite (can be easily replaced with any other database)
* **Frontend**: HTML, CSS, JavaScript

## Prerequisites

* Python 3.x
* Flask

## Installation


1. **Clone the repository:**

   ```javascript
   bashCopy codegit clone https://github.com/your-username/contact-list-crud-app.git
   cd contact-list-crud-app
   
   ```
2. **Create a virtual environment:**

   ```javascript
   bashCopy codepython -m venv venv
   
   ```
3. **Activate the virtual environment:**
   * On Windows:

     ```javascript
     bashCopy codevenv\Scripts\activate
     
     ```
   * On MacOS/Linux:

     ```javascript
     bashCopy codesource venv/bin/activate
     
     ```
4. **Install the required packages:**

   ```javascript
   bashCopy codepip install flask
   
   ```
5. **Run the application:**

   ```javascript
   python main.py
   
   ```

   The application will be accessible at `http://127.0.0.1:5000`.
6. **Frontend Setup:**

   
   1. Navigate to the frontend directory:

      ```javascript
      bashCopy codecd ../frontend
      
      ```
   2. Install the required packages:

      ```javascript
      bashCopy codenpm install
      
      ```
   3. Start the React application:

      ```javascript
      bashCopy codenpm start
      
      ```

   The frontend application will be accessible at `http://localhost:3000`.

## Project Structure

```javascript
javaCopy codecontact-list-crud-app/
│
├── backend/
│   ├── app.py
│   ├── models.py
│   ├── requirements.txt
│   ├── templates/
│   │   └── index.html
│   ├── static/
│   │   └── css/
│   └── README.md
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   ├── index.js
│   ├── package.json
│   └── README.md
│
└── README.md
```

* `backend/`: Contains the Flask application.
  * `app.py`: The main Flask application file where routes and logic are defined.
  * `models.py`: Contains the SQLAlchemy models for the Contact entity.
  * `templates/`: Contains HTML templates for rendering pages (if any).
  * `static/`: Contains static files like CSS (if any).
* `frontend/`: Contains the React application.
  * `public/`: Contains the public assets and the `index.html` file.
  * `src/`: Contains the React components and main application files.
    * `components/`: Contains React components for the application.
    * `App.js`: Main React component.
    * `index.js`: Entry point for the React application.
  * `package.json`: Contains the list of dependencies and scripts for the React application.

## Usage

### Adding a Contact


1. Navigate to the "Add Contact" page.
2. Fill in the first name, last name, and email fields.
3. Click the "Add" button to save the contact.

### Viewing Contacts


1. The home page displays a list of all contacts.
2. Each contact entry shows the first name, last name, and email.

### Editing a Contact


1. Click the "Edit" button next to a contact entry.
2. Modify the contact details in the form.
3. Click the "Save" button to update the contact.

### Deleting a Contact


1. Click the "Delete" button next to a contact entry.
2. Confirm the deletion to remove the contact from the list.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.


---


