## Projeto de Avaliação PHP - Gestão de Funcionários e Empresas

Este projeto é uma aplicação web desenvolvida em PHP para gerenciar funcionários e empresas, incluindo cadastro, listagem, edição, exclusão e exportação de dados em PDF.

### Funcionalidades principais

- Autenticação de usuários
- Cadastro, edição e exclusão de funcionários
- Cadastro de empresas
- Listagem paginada de funcionários
- Cálculo automático de bonificação de funcionários
- Exportação de lista de funcionários para PDF

### Estrutura do Projeto

- **index.php**: Redireciona para a tela de login
- **controllers/**: Lógica dos controladores (Company, Employee, User)
- **models/**: Modelos de dados e acesso ao banco
- **services/**: Regras de negócio e validações
- **views/**: Telas do sistema (login, cadastro, listagem, etc.)
- **config/**: Configuração de conexão com banco de dados
- **database/**: Scripts SQL para criação das tabelas
- **libs/fpdf186/**: Biblioteca para geração de PDFs
- **utils/**: Utilitários e validadores

### Como rodar o projeto

1. Clone este repositório
2. Configure o banco de dados em `config/database.php`
3. Importe o script SQL em `database/create_table.sql`
4. Execute o projeto em um servidor local (ex: XAMPP, WAMP, PHP built-in server)
5. Acesse `index.php` pelo navegador

### Observações

- O projeto utiliza a biblioteca FPDF para exportação de relatórios em PDF.
- Certifique-se de que as extensões PDO estejam habilitadas no PHP.

---

Desenvolvido por Pedro Marcusso
