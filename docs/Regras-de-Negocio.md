# Regras de Negócio

## Visão Geral

Este documento descreve as regras de negócio definidas para o funcionamento do **Gerador de Currículos ATS Friendly com Lovable**.

As regras estabelecem os comportamentos esperados da aplicação, garantindo padronização na criação, edição, armazenamento e exportação dos currículos.

---

# RN01 – Criação de Currículo

O sistema deve permitir a criação de um currículo por meio de duas formas:

* Cadastro manual.
* Importação de currículo existente.

Cada currículo criado deverá possuir uma identificação própria.

---

# RN02 – Cadastro Manual

Ao selecionar a opção de cadastro manual:

* O usuário deverá preencher as informações profissionais.
* O sistema deverá apresentar os campos organizados por categorias.
* As informações preenchidas deverão aparecer automaticamente no preview.
* O currículo deverá utilizar o nome informado pelo usuário.
* O currículo deverá ser salvo no histórico após a criação.

---

# RN03 – Identificação do Candidato

O nome do candidato deverá ser utilizado como identificação principal do currículo.

O sistema não deverá apresentar nomes genéricos ou fixos quando existir um nome cadastrado.

Exemplo:

**Correto:**

```
Carlos Shitsu
Gerente de Projetos
Atualizado em 17/07/2026
```

**Incorreto:**

```
Meu Currículo
Atualizado em 17/07/2026
```

---

# RN04 – Histórico de Currículos

O histórico deverá apresentar:

* Nome do candidato.
* Título do currículo.
* Tipo de criação.
* Data de criação.
* Data da última atualização.

Cada currículo deverá aparecer como um registro independente.

---

# RN05 – Atualização do Histórico

Quando um currículo for alterado:

* A data de atualização deverá ser modificada.
* As informações exibidas no histórico deverão permanecer sincronizadas.
* O sistema não deverá criar registros duplicados automaticamente.

---

# RN06 – Edição de Currículo

Ao selecionar um currículo salvo:

* O usuário deverá conseguir editar as informações existentes.
* As alterações deverão atualizar o preview.
* As alterações deverão ser salvas no histórico.

---

# RN07 – Exclusão de Currículo

Ao excluir um currículo:

* O sistema deverá solicitar confirmação.
* O registro deverá ser removido do histórico.
* O usuário deverá receber uma confirmação da ação realizada.

---

# RN08 – Importação de Currículo

Ao importar um currículo existente:

O sistema deverá:

* Identificar as informações relevantes.
* Separar os dados por categorias.
* Preencher os campos correspondentes.
* Permitir ajustes antes da geração final.

---

# RN09 – Visualização do Currículo

O preview deverá:

* Apresentar o currículo atualizado em tempo real.
* Mostrar somente informações preenchidas.
* Manter a estrutura ATS Friendly.
* Não exibir elementos da aplicação.

---

# RN10 – Exportação em PDF

Ao exportar o currículo:

O sistema deverá:

* Gerar somente o documento final.
* Remover menus e componentes da interface.
* Preservar títulos e seções.
* Manter a organização adequada para impressão.

---

# RN11 – Estrutura ATS Friendly

O currículo gerado deverá priorizar:

* Texto pesquisável.
* Organização por seções.
* Palavras-chave profissionais.
* Estrutura simples.
* Compatibilidade com sistemas automatizados.

Evitar:

* Tabelas complexas.
* Muitas imagens.
* Elementos gráficos que dificultem leitura automática.

---

# RN12 – Currículos de Teste

Para validação da aplicação podem ser utilizados perfis fictícios.

Exemplos:

* Fabricia Goldenshai.
* Carlos Shitsu.

Os dados fictícios devem ser utilizados apenas para testes e demonstração da aplicação.

---

# RN13 – Evolução Contínua

Novas funcionalidades poderão ser adicionadas mantendo:

* Compatibilidade com as regras existentes.
* Preservação dos dados cadastrados.
* Melhoria da experiência do usuário.
* Documentação das alterações realizadas.

---

# Resultado Esperado

A aplicação deve permitir que qualquer usuário consiga criar, gerenciar e exportar um currículo profissional de forma organizada, rápida e compatível com processos seletivos que utilizam sistemas ATS.
