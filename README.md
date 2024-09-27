# Meteora E-commerce - API Mock

Mock created using the json-server library for the Alura challenge, to simulate the operation of a fictional e-commerce called Meteora.

## Installation
Follow the steps below to install and run this Mock API.

1. Clone this repository to your computer;
2. Access the project directory:
  ```bash
   cd api-meteora
 ```
3. Install the project dependencies:
```bash
    npm install
 ```

## Running the Mock API
After installing the dependencies, you can start the server for this mock with the following command:
```bash
    npm start
 ```
## Available Endpoints
### 1. Categories

This endpoint provides information about the available product categories in the Meteora E-Commerce.

URL: `/categories`

Method: GET

Response: List of categories in JSON format

Example response:
```json
{
    "categories": [
        {
            "id": 1,
            "name": "Camisetas",
            "src": "https://raw.githubusercontent.com/giselleschwab/api-meteora/main/images/categories/camisetas.png"
        },
    ]
}
```

### 2. Products

This endpoint provides information about the available products in the Meteora E-Commerce.

URL: `/products`

Method: GET

Response: List of products in JSON format

Example response:
```json 
{
 "products": [
        {
            "id": 1,
            "name": "Camiseta Conforto",
            "description": "Multicores e tamanhos. Tecido de algodão 100%, fresquinho para o verão. Modelagem unissex.",
            "price": 70,
            "src": "https://raw.githubusercontent.com/giselleschwab/api-meteora/main/images/products/image.png",
            "colors": [
                "Mostarda",
                "Verde",
                "Preta"
            ],
            "sizes": [
                "PP",
                "P",
                "M",
                "G",
                "GG"
            ],
            "id_category": 1
        }
   ]
 }
```

## Developed by: 
Giselle Schwab
