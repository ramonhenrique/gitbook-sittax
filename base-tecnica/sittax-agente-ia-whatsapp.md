---
description: >-
  A inteligência artificial propria da Sittax que conecta o WhatsApp à
  plataforma. Com ele, clientes conseguem consultar informações e executar
  rotinas fiscais diretamente pelo aplicativo de mensagens!
icon: square-whatsapp
---

# SITTAX AGENTE IA (WhatsApp)

O Agente IA da Sittax é a inteligência artificial própria da Sittax que conecta o **WhatsApp** à plataforma.\
Ele foi desenvolvido para simplificar a experiência dos escritórios de contabilidade, permitindo que ações que antes exigiam navegação no sistema sejam feitas de forma conversacional.\
Com o Sittax GPT, clientes conseguem consultar informações, gerar documentos e executar rotinas fiscais diretamente pelo aplicativo de mensagens, de forma rápida e prática. \
Basta enviar comandos no **WhatsApp** oficial da Sittax e o resultado será retornado em segundos.

<h2 align="center">Cadastro do WhatsApp na plataforma.</h2>

Para que o Agente de IA Sittax  funcione, é obrigatório que o **WhatsApp do usuário esteja cadastrado** dentro da plataforma Sittax Simples.\
O agente de IA só responderá se o número que enviar mensagens estiver vinculado a um usuário válido dentro de um escritório.

Para cadastrar o WhatsApp de um usuário:

1.  Acesse o menu de **Cadastro de Usuários** no escritório.\


    <figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>


2. Edite ou crie o usuário que fará as solicitações.\

3.  Preencha corretamente o campo de **WhatsApp**.\


    <figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>


4. Salve as alterações.

Após o cadastro realizado, basta entrar em contato com o nosso whatsapp para acessar as funcionalidades:

<h3 align="center"><em><mark style="background-color:$primary;"><strong>+55 62 99813-7718</strong></mark></em></h3>

<h2 align="center"><strong>Funcionalidades</strong></h2>

<h3 align="center">Declarações e DAS</h3>

Conjunto de funções voltadas à consulta e geração de **declarações** e **DAS**:

* **Novo DAS** → Gera um DAS atualizado.
  * Exemplos: “Gerar novo DAS da empresa X”, “Emitir DAS da empresa Y”.
* **Último DAS / DAS por Período (MM/AAAA)** → Retorna o DAS atual ou de um mês específico.
  * Exemplos: “Último DAS da empresa X”, “DAS 08/2025 da empresa Y”.
* **Todos os DAS** → Lista todos os DAS do cliente.
  * Exemplos: “Histórico de DAS da empresa X”, “Listar todos os DAS da empresa Y”.
* **Última Declaração / Declaração por Período (MM/AAAA)** → Retorna a declaração atual ou de um período informado.
  * Exemplos: “Última declaração da empresa X”, “Declaração 08/2025 da empresa Y”.
* **Todas as Declarações** → Lista todas as declarações do cliente.
  * Exemplos: “Todas as declarações da empresa X”, “Listar histórico de declarações da empresa Y”.

***

<h3 align="center">Inconsistências</h3>

Agrupa as consultas de empresas com problemas identificados:

* **Resumo de Inconsistências (MM/AAAA)** → Mostra todas as inconsistências de determinado mês.
  * Exemplos: “Resumo inconsistências 08/2025”, “Inconsistências da empresa X em julho”.
* **CFOP / CNAE / Faturamento** → Empresas com erros nessas categorias.
  * Exemplos: “Empresas com erro de CFOP”, “Clientes com erro de CNAE”.
* **Certificados Vencidos / Quebra de Notas** → Empresas com certificados expirados ou notas quebradas.
  * Exemplos: “Clientes com certificado vencido”, “Empresas com quebra de notas”.
* **Distorção de Alíquota / Exceção PIS-COFINS / Exceção ICMS** → Empresas com distorções ou exceções fiscais.
  * Exemplos: “Empresas com distorção de alíquota”, “Quais têm exceção ICMS?”.
* **Itens com NCM Divergente** → Lista itens com divergência de NCM.
  * Exemplos: “Itens com NCM divergente”, “Listar divergência de NCM”.

***

<h3 align="center">Empresas e Transmissões</h3>

Funções que acompanham a situação de transmissão das empresas:

* **Empresas Não Transmitidas** → Lista de empresas que ainda não transmitiram.
  * Exemplos: “Quais empresas não transmitiram?”, “Listar clientes não transmitidos”.
* **Empresas Transmitidas** → Lista de empresas já transmitidas.
  * Exemplos: “Quais empresas já transmitiram?”, “Me mostra empresas transmitidas”.

***

<h3 align="center">Notas Fiscais (DANFE)</h3>

Consultas de documentos fiscais (DANFE):

* **DANFE pela Chave de Acesso** → Retorna DANFE pela chave.
  * Exemplos: “DANFE da chave 123…”, “Nota fiscal da chave 456…”.
* **Nota Fiscal de Saída pelo Nome** → Retorna DANFE de saída pelo número e nome do cliente.
  * Exemplos: “Nota de saída 123 da empresa X”, “NF saída do cliente Y”.
* **Nota Fiscal de Entrada pelo Nome** → Retorna DANFE de entrada pelo número e nome do fornecedor.
  * Exemplos: “Nota de entrada 456 do fornecedor X”, “NF entrada do cliente Y”.

***

<h2 align="center">Observações Técnicas</h2>

* Sempre informar períodos no formato **MM/AAAA**.
* Certificados devem estar válidos.
* Respostas podem vir em **texto, link ou arquivo**.

***

