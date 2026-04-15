# 🛒 VendaPro — Gestão de Vendas

## 📌 Descrição
O **VendaPro** é uma aplicação web simples para gerenciamento de vendas por cliente.  
Com ele, é possível cadastrar clientes, adicionar produtos aos pedidos e visualizar automaticamente o total da compra, além de gerar um recibo pronto para impressão.

---

## 🚀 Tecnologias
- JavaScript (lógica da aplicação)
- HTML5 + CSS3 (interface moderna e responsiva)
- LocalStorage (persistência de dados no navegador)

---

## 🧠 Regras de negócio

### Clientes
- Cada cliente pode ter múltiplos produtos vinculados

### Produtos
- Nome  
- Preço  
- Quantidade  
- Categoria (opcional)  
- Status (ativo/inativo)

### Cálculos
- Apenas produtos **ativos** entram no cálculo do total
- O sistema calcula automaticamente:
  - Total do pedido
  - Quantidade total de itens

### Validações
- Não é permitido:
  - Criar produto sem nome
  - Criar produto com preço inválido
  - Criar cliente sem nome

### Ações disponíveis
- Aumentar/diminuir quantidade de produtos
- Ativar/desativar produtos do pedido
- Remover produtos ou clientes
- Limpar pedido completo

### Recibo
- Geração de recibo contendo:
  - Nome do cliente
  - Data/hora
  - Lista de produtos
  - Total final
