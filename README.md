# Orçamento Pessoal

Este é um projeto de um sistema de controle financeiro pessoal, onde o usuário pode registrar e consultar despesas.

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 4
- Font Awesome
- Local Storage (para persistência de dados no navegador)

## Estrutura do Projeto

### 1. Páginas

- **index.html**: Formulário para cadastro de novas despesas.
- **consulta.html**: Interface para consulta de despesas registradas.

### 2. Scripts

- **app.js**: Contém a lógica principal do sistema.

## Funcionalidades

### Cadastro de Despesas

O usuário pode cadastrar uma despesa informando:
- Ano
- Mês
- Dia
- Tipo (Alimentação, Educação, Lazer, Saúde, Transporte)
- Descrição
- Valor

Os dados são armazenados no Local Storage do navegador.

### Consulta de Despesas

O usuário pode filtrar despesas por:
- Ano
- Mês
- Dia
- Tipo
- Descrição
- Valor

Os dados cadastrados são carregados dinamicamente e exibidos em uma tabela.

## Como Executar o Projeto

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` no navegador para cadastrar despesas.
3. Acesse `consulta.html` para consultar despesas registradas.

## Melhorias Futuras

- Implementação de backend para persistência permanente.
- Melhorias na interface do usuário.
- Exportação de relatórios em PDF/Excel.
- Implementação de autenticação para acesso seguro aos dados.

