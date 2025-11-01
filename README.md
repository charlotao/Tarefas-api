# Tarefas API

Esse projeto é uma API REST feita em Java com Spring Boot, voltada para o gerenciamento de tarefas. A ideia é permitir que o usuário cadastre, edite, consulte e exclua tarefas de forma simples, com os dados armazenados em um banco MySQL.

---

## Tecnologias utilizadas

- Java 17  
- Spring Boot  
- Spring Data JPA  
- MySQL  
- Postman (para testes)  
- Git e GitHub  

---

## Endpoints disponíveis

- `GET /tarefas` → Lista todas as tarefas  
- `GET /tarefas/{id}` → Busca uma tarefa específica  
- `POST /tarefas` → Cria uma nova tarefa  
- `PUT /tarefas/{id}` → Atualiza uma tarefa existente  
- `DELETE /tarefas/{id}` → Exclui uma tarefa  

---

## Testes realizados

### Teste 1 – Listar tarefas  
Foi feito um `GET /tarefas` para verificar se as tarefas estavam sendo listadas corretamente.

### Teste 2 – Criar tarefa com meu nome  
Foi criada uma tarefa com os seguintes dados:

```json
{
  "id": 4,
  "nome": "Desenvolvimento da API",
  "dataEntrega": "2025-12-12",
  "responsavel": "Charles RU-38884700"
}
## Prints dos testes

Os testes foram feitos no Postman e no terminal. Os prints estão disponíveis na aba de arquivos do repositório.
