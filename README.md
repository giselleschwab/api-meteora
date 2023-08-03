# Meteora E-commerce - API Mock

Mock criado utilizando a biblioteca [json-server](https://github.com/typicode/json-server) para o desafio da Alura, para simular o funcionamento de um e-commerce fictício chamado Meteora. 

## Instalação
Siga os passos abaixo para instalar e executar essa API Mock.

1. Clone este repositório para o seu computador;
2. Acesse o diretório do projeto:
  ```bash
   cd api-meteora
 ```
3. Instale as dependências do projeto:
```bash
    npm install
 ```

## Executando o API Mock
Após a instalação das dependências, você pode iniciar o servidor desse mock com o seguinte comando:
```bash
    npm start
 ```
## Endpoints disponíveis
### 1. Categories

Este endpoint fornece informações sobre as categorias de produtos disponíveis no Meteora E-Commerce.

URL: `/categories`

Método: GET

Retorno: Lista de categorias em formato JSON

Exemplo de resposta:
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

Este endpoint fornece informações sobre os produtos disponíveis no Meteora E-Commerce.

URL: `/products`

Método: GET

Retorno: Lista de produtos em formato JSON

Exemplo de resposta:
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

