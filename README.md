<div align="center">

# 🧪 Desafio QA — Beedoo

### Análise exploratória, modelagem de testes e registro de defeitos em uma aplicação de cursos.

![Ano](https://img.shields.io/badge/desafio-2026-6B7280?style=for-the-badge)
![QA](https://img.shields.io/badge/foco-Quality_Assurance-7C3AED?style=for-the-badge)
![Testes](https://img.shields.io/badge/testes-manuais-2563EB?style=for-the-badge)

</div>

> **Desafio técnico concluído em 2026.**  
> O repositório é mantido como registro de uma atividade de processo seletivo e da abordagem utilizada na análise de qualidade da aplicação.

## Objetivo

A aplicação analisada permite o **cadastro e a visualização de cursos**.

A partir da exploração da interface, foram identificados fluxos para cadastrar cursos com informações como nome, descrição, instrutor, datas, número de vagas e tipo de curso, além da listagem e exclusão dos registros cadastrados.

## Escopo analisado

Foram considerados os seguintes fluxos principais:

- cadastro de cursos;
- visualização dos cursos cadastrados;
- exclusão de cursos;
- navegação entre cadastro e listagem;
- comportamento dinâmico do formulário conforme o tipo de curso selecionado, **Online** ou **Presencial**.

## Pontos críticos de teste

A análise priorizou:

- validação de campos obrigatórios;
- consistência dos dados após o cadastro;
- comportamento da exclusão de cursos;
- alteração dinâmica dos campos conforme o tipo de curso;
- validação de tipos de dados, como número de vagas;
- comportamento da interface diante de textos longos;
- navegação entre os principais fluxos da aplicação.

## Estratégia utilizada

Os testes foram elaborados a partir da exploração da aplicação, buscando cobrir o fluxo principal e situações com potencial de comportamento inesperado.

Foram contemplados:

- cenários positivos;
- cenários negativos;
- validações de campos;
- navegação;
- comportamento dinâmico do formulário;
- consistência das informações apresentadas ao usuário.

## Resultado da análise

Durante a execução foram registrados **4 defeitos**:

| ID | Resumo | Impacto |
| --- | --- | --- |
| BUG01 | Cadastro permitido com formulário vazio | Alto |
| BUG02 | Mensagem de exclusão é exibida, mas curso permanece na listagem | Alto |
| BUG03 | Descrição longa compromete a proporção do card | Baixo |
| BUG04 | Campo “Tipo de curso” permite selecionar novamente “Selecione...” | Baixo |

Os detalhes completos de reprodução, resultado atual e resultado esperado estão em [`bugs.md`](bugs.md).

## Artefatos

| Material | Conteúdo |
| --- | --- |
| [Cenários e casos de teste](https://docs.google.com/spreadsheets/d/1H2AhGy3xN-7dRW9IzVCwguuY--hDI-sqTlKtQfBOjTQ) | Planilha utilizada para modelagem e registro dos testes |
| [`bugs.md`](bugs.md) | Registro estruturado dos defeitos encontrados |
| [Evidências](https://drive.google.com/drive/folders/1zCdVUFQ3sWzKP9Bpy2dWCkOLZGDVQ3VC) | Prints e gravações produzidos durante a execução |

## Contexto

Este repositório representa uma atividade pontual realizada em **2026**. Ele permanece disponível como histórico do raciocínio de teste, da organização das evidências e da documentação de defeitos utilizada no desafio.
