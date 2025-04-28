# ReVest

Trabalho prático da disciplina de **Programação Web 2025/1** – UFMS  
Realizado por **Giulia Delarissa** e **Maria Eduarda Justino**

---

## Proposta

Desenvolver um site de **banco de trocas de roupas**, onde não há transações financeiras, apenas a possibilidade de trocar peças de roupa entre usuários.  
A plataforma incentiva o consumo consciente e a moda circular.

- [Protótipo no Figma](https://www.figma.com/design/SzuSETj2EnJg5eQpBUnnap/Untitled?node-id=0-1&t=3wFFJJm4wea3lvJO-1)
- [Link do github](https://github.com/delarissag/progweb_ReVest.git)


---

## Funcionalidades implementadas

- **Frontend**:
    - Página inicial com listagem de produtos/peças disponíveis para troca
    - Página de detalhes do produto
    - Sistema de login e perfil de usuário (interface pronta; integração backend será implementada)
    - Carrinho de trocas (adicionar/remover peças)
    - Histórico de trocas realizadas (minhas trocas)
    - Página "Como Funciona" explicando a lógica de trocas e créditos
    - Design responsivo, seguindo o protótipo do Figma
    - Navegação intuitiva com navbar e ícones

- **Fluxo de Trocas**:
    - Usuário envia suas peças para avaliação
    - Peças aprovadas geram créditos para o usuário
    - Usuário utiliza créditos para resgatar novas peças
    - Histórico de trocas e status (“concluída”, “em andamento”)

- **Backend** (em desenvolvimento):
    - Estrutura inicial com Node.js + Express
    - API RESTful para produtos, usuários, trocas e carrinho
    - Integração planejada com banco de dados MySQL (estrutura pronta para migrations e scripts SQL)
    - Organização modular para futuras implementações de autenticação, upload de fotos, avaliações, etc.

---

## Requisitos do professor atendidos até o momento

- [x] Catálogo de produtos (peças de roupa)
- [x] Página de detalhes do produto
- [ ] Cadastro/login do usuário (frontend implementado, falta fazer o backend)
- [x] Carrinho (reserva de peças para troca)
- [x] Histórico de pedidos/trocas
- [x] Sistema de navegação (navbar, páginas, links)
- [x] Front-end estático pronto para integração com o back-end
- [x] Explicação das regras do sistema (créditos/trocas) na página "Como Funciona"
- [x] Prototipação visual (Figma)
- [ ] Back-end em Node.js/Express com MySQL 
- [ ] API RESTful com autenticação e persistência 
- [ ] Documentação de API e scripts de banco 

---

## Como rodar o projeto

1. **Front-end:**  
    - Basta abrir `public/index.html` em um navegador
    - As páginas estão todas em `/public`

2. **Back-end:**  
    - Ainda não foi implementado. Iremos fazer utilizando Node JS e o banco de dados será o MySql.

---

## Próximos passos

- Finalizar rotas da API e conexão com o banco
- Implementar autenticação de usuários
- Implementar upload de fotos de produtos
- Ajustar controle de créditos e avaliações
- Testes de integração (client ↔ server)

---

> **Este README será atualizado conforme o projeto evolui.**
