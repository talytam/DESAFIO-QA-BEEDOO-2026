# DESAFIO-QA-BEEDOO-2026

## Objetivo da aplicação

A aplicação disponibilizada possui como objetivo permitir o cadastro e a visualização de cursos.

A partir da análise da interface, é possível identificar que o sistema permite registrar cursos contendo informações como nome, descrição, instrutor, datas de início e fim, número de vagas e tipo de curso. Após o cadastro, os cursos são exibidos em formato de listagem através de cards.

Dessa forma, o fluxo principal da aplicação consiste em cadastrar cursos e visualizá-los posteriormente na listagem disponível no sistema.

## Principais fluxos disponíveis

Durante a exploração da aplicação, foi possível identificar os seguintes fluxos principais:

- Cadastro de cursos através do formulário disponível na opção "Cadastrar curso"
- Visualização dos cursos cadastrados através da opção "Listar cursos"
- Exclusão de cursos diretamente a partir da listagem
- Navegação entre as páginas de cadastro e listagem utilizando o menu superior
- Exibição dinâmica de campos no formulário de acordo com o tipo de curso selecionado (Online ou Presencial)


## Pontos críticos para teste

Durante a análise da aplicação, alguns pontos foram considerados mais críticos para validação:

- Validação dos campos obrigatórios no cadastro de cursos
- Consistência das informações exibidas na listagem após o cadastro
- Funcionamento correto da exclusão de cursos
- Comportamento dinâmico do campo "Tipo de curso", que altera os campos exibidos no formulário
- Validação de tipos de dados, como o campo "Número de vagas"
- Comportamento da interface quando dados muito longos são inseridos

## Decisões tomadas para criação dos testes

A criação dos cenários de teste buscou cobrir tanto o fluxo principal da aplicação quanto possíveis comportamentos inesperados.

Foram considerados cenários positivos, como o cadastro correto de cursos e a visualização na listagem, além de cenários negativos envolvendo validações de campos e possíveis falhas no sistema.

Também foram incluídos testes relacionados à navegação entre páginas e ao comportamento dinâmico do formulário, buscando identificar inconsistências que possam impactar a experiência do usuário.

## Estrutura do repositório

O repositório contém os seguintes materiais relacionados ao desafio:

- Planilha com os cenários e casos de teste
- Registro dos bugs identificados durante a execução dos testes
- Evidências da execução dos testes (prints e gravações)

## Links do desafio

Planilha com cenários e casos de teste:  
https://docs.google.com/spreadsheets/d/1H2AhGy3xN-7dRW9IzVCwguuY--hDI-sqTlKtQfBOjTQ

Evidências da execução dos testes:  
https://drive.google.com/drive/folders/1zCdVUFQ3sWzKP9Bpy2dWCkOLZGDVQ3VC