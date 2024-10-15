# Mapeando o domínio

## Entidades
- Produto
  - Identificador único
  - Nome
  - Tamanho
  - Cor

- Estoque
  -  Identificador do produto
  -  Quantidade Atual
  -  Quantidade Mínima

- Alerta
  - Identificador único
  - Identificador do produto

- Notificação
    - Identificador de alerta

- Venda
    - Identificador de Produto
    - Quantidade vendida
    - Valor unitário

- Compra
    - Identificador de Produto
    - Quantidade comprada
    - Valor unitário


## Casos de Uso

- Rastrear Produto por Id e filtros
- Gerar Alerta ao atingir quantidade mínima
- Enviar email de Alerta
- Obter métricas do histórico de vendas
- Gerar compra automática ao atingir quantidade mínima
- Gerar Alerta de fornecedor
- Criar Notificação de Alerta
