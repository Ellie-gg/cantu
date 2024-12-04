# Arquitetura  da Plataforma


## Funcionalidades
A plataforma vai ter:
- **Autenticaçao:** Gerenciamento de usuarios e login.
- **Carrinho:** Armazenamento e controle dos itens no carrinho.
- **Checkout:** Processamento de pagamento e finalizaçao de compras.
- **Catalogo:** Exibição dos produtos e detalhes.
- **Pedido (Order):** Criacao e acompanhamento dos pedidos.
- **Logs:** Envio de mensagens e atualizaçoes para clientes.

## Arquitetura

A arquitetura da aplicaçao é composta por:
- **Frontend:** Interface responsiva que acessa as APIs.
- **Microserviços:** Cada funcionalidade é um microserviço.
- **API Management:** Controle e exposiçao das APIs.
- **Banco de Dados:** Armazenamento de dados.
- **Cache e Load Balancer:** Melhorar desempenho e distribuir trafego.


## Gitflow e CI/CD

O Gitflow no projeto tem:
1. **Commit e integraçao de código** em branchs de funcionalidades.
2. **Execuçao de testes** automatizados.
3. **Deploy automatizado** em dev, homologacao e produçao.
4. **Gerenciamento de releases** e rollback quando der erro.


## Tecnologias

- Linguagens de desenvolvimento utilizadas
- Plataforma (Kubernetes, Openshift) a depender da definição.

