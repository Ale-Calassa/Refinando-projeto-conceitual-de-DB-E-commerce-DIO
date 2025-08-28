# PT-BR
💼 Projeto E-commerce – Modelagem de Banco de Dados
Este repositório apresenta o desafio proposto pela DIO no curso de modelagem de banco de dados, com foco em um sistema de E-commerce. O objetivo foi desenvolver um modelo conceitual e refiná-lo com base em requisitos reais de negócio.

📌 Descrição do Desafio
Durante o curso, foi proposto o desenvolvimento de um modelo de banco de dados para um sistema de E-commerce. A primeira versão foi construída em conjunto com a instrutora, seguida por uma etapa de refinamento individual, considerando regras de negócio mais específicas.

🧠 Requisitos do Sistema
🛒 Produto
Os produtos são vendidos por uma única plataforma online.
Cada produto pode ter vendedores distintos (terceiros).
Cada produto possui um fornecedor.
Um ou mais produtos podem compor um pedido.

👤 Cliente
O cliente pode se cadastrar com CPF (Pessoa Física) ou CNPJ (Pessoa Jurídica).
Uma conta não pode conter ambos os tipos de cadastro.
O endereço do cliente influencia no valor do frete.
Um cliente pode realizar múltiplos pedidos.
Existe um período de carência para devolução dos produtos.

📦 Pedido
Criado por um cliente, contendo informações de compra, endereço e status da entrega.
Pode conter um ou mais produtos.
Pode ser cancelado.

💳 Pagamento
O cliente pode cadastrar múltiplas formas de pagamento.

🚚 Entrega
Cada entrega possui um status (em trânsito, entregue, etc.).
Inclui código de rastreio para acompanhamento.

🛠️ Tecnologias Utilizadas
Modelagem Conceitual e Lógica: MySQL Workbench

📈 Evolução do Projeto
O refinamento do modelo buscou representar com maior fidelidade os requisitos do negócio, como:
Separação clara entre clientes PF e PJ.
Flexibilidade na forma de pagamento.
Inclusão de rastreio e status de entrega.

========================================================================================================================

# EN-US
💼 E-commerce Project – Database Modeling Challenge
This repository presents the challenge proposed by DIO during the database modeling course, focused on designing a conceptual model for an E-commerce system. The goal was to build the initial model with the instructor and then refine it based on real business rules.

📌 Project Description
The challenge involved creating a conceptual database model for an online sales platform. After building the initial version with the instructor, the project was refined to better reflect business logic and user scenarios.

🧠 System Requirements
🛒 Product
Products are sold through a single online platform.
Each product may have different third-party sellers.
Every product has a supplier.
One or more products can be part of an order.

👤 Customer
Customers can register using either CPF (individual) or CNPJ (company).
An account cannot contain both CPF and CNPJ.
The customer's address determines the shipping cost.
Customers can place multiple orders.
There is a grace period for product returns.

📦 Order
Orders are created by customers and include purchase details, address, and delivery status.
Orders may contain one or more products.
Orders can be canceled.

💳 Payment
Customers can register multiple payment methods.

🚚 Delivery
Each delivery has a status (e.g., in transit, delivered).
Includes a tracking code.

🛠️ Technologies Used
Modeling Tool: MySQL Workbench

📈 Project Refinement
The refined version includes:
Clear separation between individual and company customers.
Support for multiple payment methods.
Delivery tracking and status updates.

========================================================================================================================

# ES 
💼 Proyecto E-commerce – Desafío de Modelado de Base de Datos
Este repositorio presenta el desafío propuesto por DIO durante el curso de modelado de bases de datos, enfocado en diseñar un modelo conceptual para un sistema de comercio electrónico. El objetivo fue construir el modelo inicial junto con la instructora y luego refinarlo según reglas reales de negocio.

📌 Descripción del Proyecto
El desafío consistió en crear un modelo conceptual de base de datos para una plataforma de ventas en línea. Después de construir la versión inicial con la instructora, el proyecto fue refinado para representar mejor la lógica de negocio y los escenarios de usuario.

🧠 Requisitos del Sistema
🛒 Producto
Los productos se venden a través de una única plataforma en línea.
Cada producto puede tener diferentes vendedores externos.
Cada producto tiene un proveedor.
Uno o más productos pueden formar parte de un pedido.

👤 Cliente
El cliente puede registrarse con CPF (persona física) o CNPJ (persona jurídica).
Una cuenta no puede contener ambos tipos de registro.
La dirección del cliente determina el costo del envío.
El cliente puede realizar múltiples pedidos.
Existe un período de gracia para devoluciones.

📦 Pedido
Los pedidos son creados por clientes e incluyen detalles de compra, dirección y estado de entrega.
Pueden contener uno o más productos.
Los pedidos pueden ser cancelados.

💳 Pago
El cliente puede registrar múltiples métodos de pago.

🚚 Entrega
Cada entrega tiene un estado (en tránsito, entregado, etc.).
Incluye código de seguimiento.

🛠️ Tecnologías Utilizadas
Herramienta de Modelado: MySQL Workbench

📈 Refinamiento del Proyecto
La versión refinada incluye:
Separación clara entre clientes físicos y jurídicos.
Soporte para múltiples métodos de pago.
Seguimiento y actualización del estado de entrega.
