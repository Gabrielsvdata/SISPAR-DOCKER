# 💼 SISPAR - Sistema de Reembolso

SISPAR é um sistema Full Stack para gerenciamento de solicitações de reembolso.  
A aplicação permite:

- Cadastro e login de colaboradores
- Envio de pedidos de reembolso com comprovantes
- Acompanhamento e aprovação/rejeição por parte dos responsáveis
- Análise por meio de gráficos e tabelas

---

## 🚀 Tecnologias Utilizadas

| Camada     | Tecnologia                                   |
|------------|----------------------------------------------|
| Front-end  | ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=white&style=flat) |
| Back-end   | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat) + ![Flask](https://img.shields.io/badge/-Flask-000000?logo=flask&logoColor=white&style=flat) |
| Banco      | ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?logo=mysql&logoColor=white&style=flat) |
| Docker     | ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white&style=flat) |
| Docs API   | ![Swagger](https://img.shields.io/badge/-Swagger-85EA2D?logo=swagger&logoColor=black&style=flat) via Flasgger |

---

## 🛠️ Como Rodar o Projeto com Docker

### 1. Clone os repositórios do frontend e backend:
```bash
git clone https://github.com/Gabrielsvdata/Sispar-Frontend sispar-frontend
git clone https://github.com/Gabrielsvdata/Sispar-Backend sispar-backend
```

> Obs: os nomes das pastas devem ser `Sispar-Frontend` e `Sispar-Backend`, como o `docker-compose.yml` espera.

---

### 2. Estrutura de pastas esperada

Organize os arquivos assim dentro da pasta principal (`SISPAR-DOCKER/`):

```
SISPAR-DOCKER/
├── docker-compose.yml
├── README.md
├── Sispar-Frontend/
└── Sispar-Backend/
```

---

### 3. Configure suas variáveis de ambiente

Crie um arquivo `.env` dentro da pasta `Sispar-Backend/` com o seguinte conteúdo:

```env
DB_HOST=sispar-db
DB_PORT=3306
DB_NAME=sispar
DB_USER=user
DB_PASSWORD=userpass
SECRET_KEY=sua_chave_secreta
```

---

### 4. Suba os containers com Docker

```bash
docker-compose up --build
```

Após a inicialização, acesse:

- 🌐 **Frontend**: http://localhost:3000  
- ⚙️ **Documentação da API (Swagger)**: http://localhost:5000/apidocs

---

## ✅ Funcionalidades

- 👤 Cadastro e login de colaboradores
- 📎 Envio de solicitações de reembolso com comprovantes
- ✅ Aprovação e rejeição de reembolsos
- 📊 Visualização por gráficos e tabelas
- 📄 Documentação da API com Swagger

---

## 👨‍💻 Autor

Gabriel Silvano Vieira  
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=flat)](https://www.linkedin.com/in/gabriel-silvano-vieira-2615a618b/)  
[![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white&style=flat)](https://github.com/Gabrielsvdata)

---

## 📝 Licença

Este projeto está licenciado sob a MIT License.
