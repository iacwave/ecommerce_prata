# 🛒 E-commerce de Artigos em Prata

Projeto de **e-commerce desenvolvido em C#** com **MySQL**, focado na venda de **correntes, pulseiras e artigos em prata (Prata 925)**.
Este repositório contém a base inicial da aplicação, estruturada para crescimento, boas práticas e futura escalabilidade.

---

## 📌 Objetivo do Projeto

Criar uma plataforma de e-commerce moderna e segura, permitindo:

* Cadastro e autenticação de usuários
* Listagem e detalhamento de produtos
* Carrinho de compras
* Processamento de pedidos
* Área administrativa para gestão de produtos e pedidos

---

## 🧱 Tecnologias Utilizadas

* **Backend:** C# (.NET)
* **Framework:** ASP.NET Core
* **Banco de Dados:** MySQL
* **ORM:** Entity Framework Core (ou Dapper)
* **Frontend:** Razor Pages / MVC (ou API REST para frontend separado)
* **Versionamento:** Git
* **Banco Local:** MySQL Server / Docker (opcional)

---

## 📂 Estrutura Inicial do Projeto

```bash
📁 src
 ├── 📁 Controllers        # Controllers da aplicação
 ├── 📁 Models             # Entidades e modelos de domínio
 ├── 📁 Data               # Contexto do banco e migrations
 ├── 📁 Repositories       # Repositórios e acesso a dados
 ├── 📁 Services           # Regras de negócio
 ├── 📁 Views              # Views (MVC/Razor)
 └── Program.cs            # Configuração principal
```

---

## 🗄️ Banco de Dados

O banco de dados utilizado é o **MySQL**.

Exemplo de entidades principais:

* Usuários
* Produtos
* Categorias
* Carrinho
* Pedidos
* Itens do Pedido

As migrations serão gerenciadas via **Entity Framework Core**.

---

## ⚙️ Configuração do Ambiente

### Pré-requisitos

* .NET SDK instalado
* MySQL Server
* Git

### Configurar conexão com o banco

No arquivo `appsettings.json`:

```json
"ConnectionStrings": {
  "DefaultConnection": "Server=localhost;Database=ecommerce_prata;User=root;Password=senha;"
}
```

---

## ▶️ Executando o Projeto

```bash
dotnet restore
dotnet build
dotnet run
```

A aplicação ficará disponível em:

```
https://localhost:5001
```

---

## 🚀 Próximas Funcionalidades (Roadmap)

* [ ] Autenticação com JWT
* [ ] Painel administrativo
* [ ] Upload de imagens de produtos
* [ ] Integração com meios de pagamento
* [ ] Deploy em ambiente cloud
* [ ] Testes automatizados

---

## 🧪 Boas Práticas

* Separação de responsabilidades
* Código limpo e organizado
* Uso de DTOs
* Validações no backend
* Versionamento semântico

---

## 📄 Licença

Este projeto está sob a licença MIT.
Sinta-se livre para estudar, modificar e evoluir 🚀

---

## 👨‍💻 Autor

Desenvolvido por **[Seu Nome]**
📧 Contato: [seuemail@email.com](mailto:seuemail@email.com)
🔗 GitHub: [https://github.com/seuusuario](https://github.com/seuusuario)
