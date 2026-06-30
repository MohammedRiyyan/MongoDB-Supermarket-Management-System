# Supermarket Management System Using MongoDB

## Overview

This project demonstrates the implementation of a **Supermarket Management System** using **MongoDB**. It showcases basic MongoDB operations such as creating a database, creating collections, inserting documents, and retrieving data using the MongoDB Shell (`mongosh`).

## Database Name

`supermarket`

## Collections

The project contains the following collections:

### 1. employees

Stores employee information.

**Fields:**

* `emp_name`
* `emp_age`
* `job_role`
* `salary`

### 2. inventory

Stores details of products available in the supermarket.

**Fields:**

* `name`
* `price`
* `quantity`
* `category`

### 3. payments

Stores payment transaction details.

**Fields:**

* `gross_amount`
* `discounts`
* `net_amount`

### 4. promo

Stores promotional campaign information.

**Fields:**

* `name`
* `period`
* `daily_sales`

## Operations Performed

* Created a MongoDB database named **supermarket**
* Created collections:

  * employees
  * inventory
  * payments
  * promo
* Inserted multiple documents using `insertMany()`
* Retrieved documents using `find().pretty()`

## Technologies Used

* MongoDB
* MongoDB Shell (mongosh)
* JavaScript

## Project Structure

```
supermarket/
│
├── supermarket.js      # MongoDB Shell program
├── README.md           # Project documentation
```

## Sample Commands

Create the database:

```javascript
use supermarket
```

Create a collection:

```javascript
db.createCollection("employees");
```

Insert documents:

```javascript
db.employees.insertMany(data1);
```

Display all documents:

```javascript
db.employees.find().pretty();
```

## Learning Outcomes

After completing this project, you will be able to:

* Create and use MongoDB databases
* Create collections
* Insert multiple documents
* Store arrays inside documents
* Retrieve documents in a readable format
* Understand basic NoSQL database operations

## Author

**Mohammed Riyyan**

## License

This project is intended for educational and academic purposes.
