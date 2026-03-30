# Olá, eu sou o Rafael Dourado! 👋

👨‍💻 **Desenvolvedor Backend .NET** focado em construir sistemas resilientes, escaláveis e seguros.

Sou apaixonado por arquitetura de software e boas práticas corporativas. Atualmente, meu foco principal é o desenvolvimento de APIs RESTful de alta performance, utilizando padrões de mensageria, segurança State-less e conteinerização para simular cenários reais de alta demanda.

---

### 🛠️ Minhas Habilidades e Tecnologias

* **Linguagens e Frameworks:** C#, ASP.NET Core (.NET 8)
* **Arquitetura & Design:** Arquitetura Orientada a Eventos (Event-Driven), Microsserviços, APIs RESTful
* **Segurança:** Autenticação State-less com JWT (JSON Web Tokens) e Controle de Acesso Baseado em Regras (RBAC)
* **Banco de Dados & Performance:** SQL Server, Entity Framework Core (Otimização com `.AsNoTracking()`, Paginação no BD)
* **DevOps & Mensageria:** Docker, Docker Compose, RabbitMQ (Message Broker)

---

### 🚀 Projetos em Destaque

#### 📦 [Sistema de Integração de Pedidos](https://github.com/Dourado86/sistema-integracao-pedidos)
*Ecossistema de microsserviços desenhado para Alta Disponibilidade e Performance.*

Este não é apenas um CRUD clássico. É uma simulação de um ambiente corporativo projetado para não cair sob alta carga de acessos.
* **Mensageria:** Implementação de comunicação assíncrona utilizando **RabbitMQ**. A API principal recebe o pedido e delega o processamento pesado para um *Worker Service* rodando em background.
* **Segurança:** Endpoints blindados com **JWT**. Implementação de RBAC para garantir que apenas usuários com a claim de `Admin` possam criar registros.
* **Performance de Banco de Dados:** Resolução de problemas de consumo de memória do servidor aplicando paginação diretamente no SQL Server e desativando o Change Tracker do EF Core (`.AsNoTracking()`) para consultas exclusivas de leitura.
* **Infraestrutura Ágil:** Ambiente totalmente conteinerizado. Com um único comando do **Docker Compose**, o SQL Server, o RabbitMQ e as duas APIs sobem simultaneamente.

#### 📝 [API RESTful de Tarefas](https://github.com/Dourado86/API-RESTful-de-Tarefas)
*Fundamentos sólidos de desenvolvimento backend.*

API para gerenciamento de tarefas focada em aplicar as melhores práticas de roteamento REST e persistência de dados.
* **Tecnologias:** ASP.NET Core, Entity Framework Core e SQL Server.

---

### 📫 Conecte-se comigo

* **LinkedIn:** [Acesse meu perfil profissional](https://www.linkedin.com/in/rafael-dourado-5565ab28b/)
