# Crud_For_FrontEnd

# Product Management API

This project is a simple Express.js API that allows users to manage products, including adding, updating, and fetching products by category. It also limits users to adding only 5 products per day, based on their session ID.

## Table of Contents
- [Project Description](#project-description)
- [Setup Instructions](#setup-instructions)
- [API Endpoints](#api-endpoints)
  - [POST /product](#post-product)
  - [GET /product](#get-all-products)
  - [GET /product/:category](#get-products-by-category)
  - [PUT /product/:id](#update-product)
- [Dependencies](#dependencies)

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
git clone https://github.com/your-username/your-repository.git
cd your-repository
