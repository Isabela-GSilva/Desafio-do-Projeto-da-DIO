# Desafio-do-Projeto-da-DIO
Descrição do Projeto:
Este projeto tem como objetivo aprimorar um modelo conceitual de banco de dados para um sistema de e-commerce ou plataforma de vendas, levando em consideração os requisitos específicos para o gerenciamento de clientes, pagamentos e entregas.

O modelo de dados foi refinado para contemplar os seguintes pontos essenciais:
Cliente PJ e PF:
Cada cliente pode ser uma pessoa física (PF) ou uma pessoa jurídica (PJ), mas não pode ser ambos ao mesmo tempo.
A modelagem garante a separação de dados específicos para cada tipo de cliente, como CPF para pessoa física e CNPJ para pessoa jurídica.

Pagamento:
Cada cliente pode registrar múltiplas formas de pagamento.
O modelo permite associar diversos métodos de pagamento a um cliente, como cartão de crédito, boleto bancário, PayPal, entre outros.

Entrega:
A entrega de produtos possui status (como "em andamento", "entregue", "cancelado", etc.) e um código de rastreio único.
O modelo permite o acompanhamento detalhado do status da entrega e o rastreamento do produto até o destino final.

Objetivo:
O projeto visa criar um modelo de banco de dados relacional, que seja escalável e eficiente, para gerenciar as informações de clientes, suas formas de pagamento e os status das entregas. Além disso, o modelo é flexível o suficiente para ser adaptado a diferentes tipos de sistema de vendas e e-commerce.

Ferramenta Utilizada:
MySQL Workbench
