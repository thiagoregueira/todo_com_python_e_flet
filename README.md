# Todo List com Flet

Este é um projeto de lista de tarefas (Todo List) desenvolvido utilizando python e o framework [Flet](https://flet.dev/). O objetivo deste projeto é demonstrar como criar uma aplicação web simples para gerenciar tarefas.

## Funcionalidades

- Adicionar novas tarefas
- Marcar tarefas como completas
- Filtrar tarefas por status (Todas, Ativas, Completas)
- Limpar tarefas completas

## Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [Flet](https://flet.dev/)
- [Flask](https://flask.palletsprojects.com/)
- [Glitch](https://glitch.com/) para hospedagem

## Estrutura do Projeto

```plaintext
.
├── tarefas.py
├── requirements.txt
└── README.md
```

- `tarefas.py`: Contém o código principal da aplicação.
- `requirements.txt`: Lista de dependências do projeto.
- `README.md`: Documentação do projeto.

## Instalação

1. Clone o repositório:

   ```sh
   git clone https://github.com/thiagoregueira/todo_com_python_e_flet.git
   cd todo_com_python_e_flet
   ```

2. Crie um ambiente virtual e ative-o:

   ```sh
   python3 -m venv venv
   source venv/bin/activate  # No Windows use `venv\Scripts\activate`
   ```

3. Instale as dependências:

   ```sh
   pip install -r requirements.txt
   ```

## Execução

Para executar a aplicação localmente, utilize o comando:

```sh
python3 tarefas.py
```

A aplicação estará disponível em `http://0.0.0.0:8000`.

## Deploy

O projeto está em produção e pode ser acessado através do endereço: [https://todo-list-flet.glitch.me/](https://todo-list-flet.glitch.me/)

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
