#Pizzaria 404 – Sistema de Delivery

Sistema de delivery online para a Pizzaria 404, desenvolvido como projeto da disciplina de Estrutura de Dados no curso de Ciência da Computação.

 Descrição do Projeto

O objetivo do projeto foi criar um sistema funcional de pedidos online para uma pizzaria, com foco em organização, agilidade e experiência do usuário. A solução simula o processo completo: exibição do cardápio, adição de itens ao carrinho, finalização de pedido e gerenciamento no backend.

Sua importância está na aplicação prática de conceitos de estruturas de dados, programação orientada a objetos (POO) e desenvolvimento web full stack.

 Instruções de Execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/pizzaria-404.git
   cd pizzaria-404
   ```

2. Instale as dependências do backend:
   ```bash
   pip install django
   ```

3. Execute as migrações e inicie o servidor:
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

4. Acesse no navegador:
   ```
   http://127.0.0.1:8000/
   ```

  Tecnologias Utilizadas

- Front-end:
  - HTML5, CSS3, JavaScript
  - Bootstrap 5
- Back-end:
  - Python com Django (MTV)
  - SQLite como banco de dados
- Extras:
  - Font Awesome para ícones
  - LocalStorage para persistência do carrinho

 Estrutura dos Arquivos

```
pizzaria-404/
├── manage.py
├── pizzaria404/             # Configurações do projeto Django
│   ├── settings.py
│   └── urls.py
├── pedidos/                 # Aplicativo responsável pelos pedidos
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   └── templates/
│       └── *.html
├── static/                  # Arquivos estáticos (CSS, JS, imagens)
│   └── ...
└── README.md
```

Aplicação de Conceitos

- POO:
  - Classes `Pedido` e `PedidoForm` com herança (`models.Model`, `forms.ModelForm`)
  - Encapsulamento, abstração e polimorfismo (ex: sobrescrita do `__str__()`)
- Estruturas de Dados:
  - Listas para manipulação do carrinho
  - Recursão: cálculo da média e contagem de notas máximas
- Algoritmos:
  - `bubble_sort` e `quick_sort` aplicados à ordenação de avaliações
- CRUD completo:
  - Criar, listar, editar e excluir pedidos
- Lógica de ordenação dinâmica:**
  - Filtros por data ou nota

 👥 Integrantes do Grupo

-  Paulo Vitor
-  Rafael Leonardo

---

Projeto desenvolvido em 26/05/2025 – Disciplina: Estrutura de Dados 
Curso: Ciência da Computação
