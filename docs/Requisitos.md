# Requisitos do Projeto

## Visão Geral

Este documento descreve os requisitos funcionais e não funcionais do projeto **Gerador de Currículos ATS Friendly com Lovable**, desenvolvido como atividade prática utilizando Inteligência Artificial Generativa e a plataforma Lovable.

---

# Requisitos Funcionais

## RF01 – Cadastro Manual de Currículo

O sistema deve permitir que o usuário crie um currículo preenchendo manualmente todas as informações necessárias.

### Campos obrigatórios

* Dados pessoais
* Objetivo profissional
* Resumo profissional
* Experiência profissional
* Formação acadêmica
* Habilidades

### Campos opcionais

* Cursos
* Certificações
* Idiomas
* Projetos
* Informações complementares

---

## RF02 – Importação de Currículo

O sistema deve permitir a importação de um currículo existente.

Após a importação, as informações devem ser identificadas e distribuídas automaticamente nos respectivos campos do formulário.

---

## RF03 – Visualização em Tempo Real

Durante o preenchimento do formulário, o currículo deverá ser atualizado automaticamente na área de visualização.

Não será necessário gerar o documento manualmente para visualizar as alterações.

---

## RF04 – Histórico de Currículos

O sistema deverá manter um histórico dos currículos criados.

Cada registro deverá conter:

* Nome do candidato
* Nome do currículo
* Tipo (Manual ou Importado)
* Data de criação
* Data da última atualização

---

## RF05 – Edição

O usuário poderá editar qualquer currículo salvo anteriormente.

Todas as alterações deverão ser refletidas imediatamente no histórico.

---

## RF06 – Exclusão

O sistema deverá permitir a exclusão de currículos armazenados.

Antes da exclusão deverá existir uma confirmação da ação.

---

## RF07 – Exportação

O sistema deverá gerar um arquivo PDF contendo apenas o currículo final.

A exportação não deverá incluir menus, botões ou elementos da interface da aplicação.

---

## RF08 – Layout ATS Friendly

O currículo deverá ser organizado seguindo boas práticas para leitura por sistemas ATS.

Características esperadas:

* Estrutura simples
* Organização por seções
* Hierarquia de títulos
* Fonte legível
* Ausência de elementos gráficos complexos

---

## RF09 – Persistência

As informações dos currículos deverão permanecer disponíveis durante a utilização da aplicação, permitindo sua recuperação para edição.

---

# Requisitos Não Funcionais

## RNF01 – Usabilidade

A interface deverá ser intuitiva e de fácil navegação.

---

## RNF02 – Responsividade

A aplicação deverá adaptar sua visualização para diferentes tamanhos de tela.

---

## RNF03 – Desempenho

As atualizações do preview deverão ocorrer de forma rápida, proporcionando uma experiência fluida ao usuário.

---

## RNF04 – Organização

As informações deverão ser apresentadas de maneira clara e estruturada.

---

## RNF05 – Experiência do Usuário

A navegação deverá minimizar a quantidade de ações necessárias para criação do currículo.

---

## RNF06 – Manutenibilidade

A solução deverá permitir futuras evoluções, incluindo novas funcionalidades e melhorias.

---

# Premissas

* O usuário possui as informações profissionais necessárias para preencher o currículo.
* A aplicação tem como foco a geração de currículos compatíveis com sistemas ATS.
* O projeto foi desenvolvido utilizando a plataforma Lovable como ferramenta de apoio ao desenvolvimento.

---

# Restrições

* O projeto possui caráter demonstrativo e educacional.
* Algumas funcionalidades dependem das capacidades da plataforma Lovable.
* O layout foi projetado priorizando compatibilidade com sistemas ATS em vez de elementos visuais complexos.
