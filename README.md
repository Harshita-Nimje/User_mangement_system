# Customer Management System

This is a customer management system built using Node.js, Express, and MongoDB. It allows users to create, read, update, and delete customer records.

## Demo
![Screenshot 2024-01-19 224135](https://github.com/Harshita-Nimje/User_mangement_system.github.io/assets/140044690/0323a9c7-61e3-4e93-8d60-62e2966fce2f)

## Prerequisites

To run this application, you will need the following:

* Node.js (version 16 or higher)
* npm (version 7 or higher)
* MongoDB (version 4 or higher)


```
git clone https://github.com/Harshita-Nimje/User_mangement_system.github.io.git
```

2. Change the directory to the project folder.

```
cd customer-management-system
```

3. Install the dependencies.

```
npm install
```

4. Create a `.env` file in the project root directory and add the following environment variables:

```
MONGODB_URI=mongodb://localhost:27017/customer-management
```

Replace `mongodb://localhost:27017/customer-management` with the connection string to your MongoDB database.

5. Start the application.

```
npm start
```

## Usage

The application is accessible at `http://localhost:5000`.

### Create a Customer

To create a new customer, click on the "Create Customer" button on the homepage. Enter the customer's name, email, and phone number in the form fields and click on the "Create" button.
![Screenshot 2024-01-19 225703](https://github.com/Harshita-Nimje/User_mangement_system.github.io/assets/140044690/e8bab1c7-2026-4a60-adbc-9f93f09f45e0)

### Read Customers

To view all customers, click on the "Customers" link on the homepage. This will display a list of all customers in the database.

### Update a Customer

To update a customer, click on the "Edit" button next to the customer's name. This will open the customer's profile page. Make the necessary changes to the customer's information and click on the "Update" button.
![Screenshot 2024-01-19 225822](https://github.com/Harshita-Nimje/User_mangement_system.github.io/assets/140044690/c5741698-8bb7-466e-b49d-4b6eb0730a5e)

### Delete a Customer

To delete a customer, click on the "Delete" button next to the customer's name. This will display a confirmation dialog. Click on the "Delete" button again to confirm the deletion.

### Server Configuration

The `server/config/db.js` file contains the code for connecting to the MongoDB database.


