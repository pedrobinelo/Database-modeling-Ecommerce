# Refining a conceptual database design 

First project challenge of [DIO](https://www.dio.me/) "SQL Database Specialist" course.

## 💵 E-commerce 

- **Entities:** Product, Stock, Supplier, Order, Client. 

## 📖 Story

- **CPF:** CPF (Cadastro de Pessoas Físicas) is a Brazilian taxpayer identification number issued by the Federal Revenue Service of Brazil. It is an 11-digit number used to identify individuals for tax, financial, and legal purposes.
- **CNPJ:** CNPJ (Cadastro Nacional da Pessoa Jurídica) is a Brazilian business identification number issued by the Federal Revenue Service of Brazil. It is used to identify legal entities (companies, organizations, and other business entities) for tax, financial, and regulatory purposes.

**1. Product**

- Products are sold through a single online platform. However, they may have different sellers (third parties).
- Each product has a supplier.
- A order can have one or more products.

**2. Client**

- The customer can register on the website with their CPF or CNPJ. 
- The customer's address will determine the shipping cost.
- A customer can purchase more than one order. This has a grace period for returning the product.

**3. Order**

- Orders are created by customers and have purchase information, address and delivery status.
- The order can be cancelled.
- A order can have one or more products. 

## 💻 Challenge description 
 
Refine the presented model by adding the following points:

- Customers can create an individual or business account, but this account cannot have both information.
- The customer can register more than one payment method.
- Delivery has status and tracking code.

## ✅ Solution

<img align="center" src="https://github.com/pedrobinelo/Database-modeling-Ecommerce/blob/main/ecommerce.png" width=""/> 

## 💻 Technologies 

![MySQL Workbench](https://img.shields.io/badge/MySQL%20Workbench-ffffff?style=for-the-badge&logo=mysql&logoColor=black)

