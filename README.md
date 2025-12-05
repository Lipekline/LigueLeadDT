# LigueLeadDT

# 🚀 API de tarefas
Uma API REST moderna para gerenciar suas tarefas.  
Construída com Node.js + Express + Sequelize, temperada com boas práticas de arquitetura e integração externa.  

Sinta-se em casa. Puxe sua cadeira, abra seu VS Code e bora brincar com uns endpoints. 😎  

---

# ✨ O que essa API faz?

Gerencie suas tarefas de maneira simples e facil.

### 📁 Projetos
- Criar  
- Listar  
- Buscar por ID  
- Atualizar  
- Deletar  

### 📝 Tarefas
- Criar tarefas vinculadas a projetos  
- Atualizar título / descrição / status  
- Deletar  

Como bônus, a API também entrega **dicas externas** vindas de uma API pública ✨.

---

# 🧩 Arquitetura: limpa

O projeto segue uma arquitetura em camadas inspirada em padrões modernos:

src/

├── config/ # Configurações gerais (banco, env, etc)

├── controllers/ # Entrada e saída de requisições

├── services/ # Regras de negócio

├── repositories/ # Consultas ao banco via Sequelize

├── integrations/ # Consumo de APIs externas

├── models/ # Models Sequelize (Project, Task)

├── routes/ # Rotas organizadas

├── middlewares/ # Segurança, rate limit, error handler

├── app.js # Configuração do Express

└── server.js # Inicialização da API



### Por que isso é importante?
- Código fácil de ler  
- Alterações simples de implementar  
- Escalável sem bagunçar tudo  
- Seu futuro "eu" agradece 🙏

---

# 🛠️ Tecnologias Utilizadas

- **Node.js**  
- **Express**  
- **MySQL**  
- **Sequelize ORM**  
- **Axios**  
- **Arquitetura em camadas**  
- **Middlewares de segurança**  

---

# ⚙️ Como rodar esse belíssimo projeto

### 1️⃣ Clone o repositório
```bash
git clone https://github.com/lipekline/LigueLeadDT.git
cd projects-api
