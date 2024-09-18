# Projeto com Docker e PostgreSQL

Este projeto utiliza Docker para configurar um ambiente com PostgreSQL.

### 💻 Pré-requisitos

- [x] Docker instalado
- [x] Docker Compose instalado

### Estrutura

- `docker-compose.yml`: Define a configuração do container PostgreSQL e a verificação para criação do banco de dados `prototipo`.

### 🚀 Instalação / Configuração

Execute o comando para a criação do container:

```
docker-compose up -d
```

Para verificar se o container está em execução:

```
docker ps
```

### 📝 Credenciais:

- Usuário: postgres
- Senha: qwepoi123
- Porta: 5432
- Banco de dados: prototipo (criado automaticamente)
