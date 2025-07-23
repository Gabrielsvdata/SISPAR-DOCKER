# 💼 SISPAR - Sistema de Reembolso

SISPAR é um sistema Full Stack para gerenciamento de solicitações de reembolso. A aplicação permite cadastro e login de colaboradores, envio de pedidos de reembolso com comprovantes, acompanhamento e aprovação/rejeição por parte dos responsáveis.

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

1. **Clone o repositório**
```bash

```

2. **Configure suas variáveis de ambiente**

Antes de subir os containers, certifique-se de que o arquivo `.env` esteja presente na **raiz do projeto** com as credenciais corretas para conexão com o banco de dados.

> ⚠️ Por motivos de segurança, o conteúdo do `.env` **não está incluído no repositório**. Consulte o desenvolvedor ou a equipe responsável para obtê-lo.

3. **Suba os containers**
```bash
docker-compose up --build
```

Aguarde a inicialização de todos os serviços. A aplicação estará disponível em:

- 🌐 Frontend: http://localhost:3000  
- ⚙️ Backend Swagger: http://localhost:5000/apidocs

---

## 📦 Estrutura do Projeto

```
sispar-fullstack-docker/
├── api-t3/               # Backend Flask
│   ├── src/
│   ├── Dockerfile
│   └── requirements.txt
├── Projeto-Sispar/       # Frontend React
│   ├── src/
│   ├── Dockerfile
│   └── package.json
├── docker-compose.yml    # Orquestrador
└── READEME.md            # Informações
```

---

## ✅ Funcionalidades

- Cadastro e login de colaboradores
- Envio de solicitações de reembolso
- Aprovação e rejeição de reembolsos
- Análise com graficos e tabelas





---

## 👨‍💻 Autor

Gabriel Silvano Vieira  
[LinkedIn](https://www.linkedin.com/in/gabriel-silvano-vieira-2615a618b/) • [GitHub](https://github.com/Gabrielsvdata)

---

## 📝 Licença

Este projeto está licenciado sob a MIT License.
