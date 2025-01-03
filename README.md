# Crud_For_FrontEnd

# Product Management API

This project is a simple Express.js API that allows users to manage products, including adding, updating, and fetching products by category. It also limits users to adding only 5 products per day, based on their session ID.

# Table of Contents

- [**Project Description**](#project-description)  
  A brief overview of the project, its goals, and its purpose.

- [**API Domain**](#api-domain)  
  The base URL for accessing the API:  
  `https://product-service-f92omfl9b-mearn-projects.vercel.app/`

- [**API Endpoints**](#api-endpoints)  
  A list of available API endpoints and their functionality:  
  - **[POST /api/product](#post-api/product)**:  
    Adds a new api/product to the database.  
  - **[GET /api/product](#get-all-products)**:  
    Retrieves a list of all products available in the database.  
  - **[GET /api/product/:category](#get-products-by-category)**:  
    Fetches products belonging to a specific category.  
  - **[PUT /api/product/:id](#update-product)**:  
    Updates the details of a specific product using its ID.

- [**Dependencies**](#dependencies)  
  A list of libraries and frameworks used in the project along with their purpose.

## Project Description

This API handles product-related operations for an e-commerce platform. The operations include:
- Adding new products.
- Fetching products by category.
- Fetching all products.
- Updating existing products.

It also includes a restriction that allows users to add only **5 products per day**, based on a session ID or any unique identifier.

## Setup Instructions

1. Clone this repository to your local machine.

```bash
https://github.com/mahmoudsabry12/Crud_For_FrontEnd.git
cd your-repository
