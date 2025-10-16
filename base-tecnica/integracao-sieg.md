---
description: >-
  Este guia tem o objetivo de instruir passo a passo o processo completo de
  integração entre o sistema SIEG e o Sittax Simples, garantindo que todas as
  notas fiscais sejam corretamente baixadas.
---

# Integração SIEG

### 🧩 Etapa 1 — Download e Instalação do Aplicativo da SIEG

1. Acesse o **HUB SIEG** com o login do cliente.
2.  Vá até o menu lateral e clique em **“Todos os Serviços” → “Utilidades” → “Baixar o APP”**.\


    <figure><img src="../.gitbook/assets/image (266).png" alt=""><figcaption></figcaption></figure>
3. Após o download, instale o aplicativo normalmente.
4.  Um ícone chamado **SIEG** será criado na área de trabalho.\
    &#x20;

    <figure><img src="../.gitbook/assets/image (267).png" alt=""><figcaption></figcaption></figure>

> ⚠️ **Importante:** sempre execute o aplicativo **como Administrador** para evitar falhas de permissão durante o download dos arquivos.

***

### ⚙️ Etapa 2 — Configuração Base do Aplicativo

1. Abra o aplicativo da SIEG.
2. Faça o Login com os dados do Cliente em questão.
3. Clique em **Configurações (ícone de engrenagem)**.
4. Valide se todos os campos obrigatórios estão preenchidos corretamente, conforme o modelo de configuração padrão da SIEG

<figure><img src="../.gitbook/assets/image (272).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (270).png" alt=""><figcaption></figcaption></figure>



> Essa etapa é essencial antes de qualquer parametrização de diretórios ou filtros.

***

### 📥 Etapa 3 — Estrutura de Coleta de Notas

O objetivo principal é utilizar o **app do HUB SIEG** para **baixar automaticamente** as notas fiscais do cliente para um **diretório local**, que posteriormente será utilizado pelo **NF Monitor** para enviar os dados ao **Sittax Simples**.

#### Passos:

1. Com o aplicativo aberto, clique em **Utilitários**.
2.  Em seguida, acesse a opção **Hub / Cofre**.\


    <figure><img src="../.gitbook/assets/image (274).png" alt=""><figcaption></figcaption></figure>
3.  Você verá a tela principal de configuração do Cofre, ela será exatamente assim:\


    <figure><img src="../.gitbook/assets/image (275).png" alt=""><figcaption></figcaption></figure>

***

### 🧮 Etapa 4 — Configuração dos Arquivos e Filtros

Nesta etapa, definiremos **quais tipos de notas** serão baixadas e **de qual período**.

1. Dentro de **Configurações**, marque as opções de documentos que o cliente utiliza:
   * NF-e (Notas Fiscais de Saída)
   * NFS-e (Serviços)
   * NFC-e (Consumidor)
   * CTe (Transporte)
   * Outros (caso aplicável)

<figure><img src="../.gitbook/assets/image (276).png" alt=""><figcaption></figcaption></figure>

> 💡 Caso o cliente **não emita** determinado tipo de nota, **não há necessidade de marcar** a opção correspondente.

2. Escolha o **período retroativo** (por exemplo, o último mês completo).

**Exemplo:**\
Se hoje é **15/10/2025** e você deseja puxar notas de **setembro**, configure o filtro de **01/09/2025 até 30/09/2025 e depois que a importação der certo, faça novamente do dia 01/10/2025 a 15/10/2025**.

<figure><img src="../.gitbook/assets/image (277).png" alt=""><figcaption></figcaption></figure>

> Isso garante que o sistema traga **todas as notas até o momento da configuração**, e siga baixando automaticamente as novas notas a partir do dia seguinte.

4. Clique em **Definir Filtros** e depois em **Salvar**.

<figure><img src="../.gitbook/assets/image (278).png" alt=""><figcaption></figcaption></figure>

***

### 📁 Etapa 5 — Definição do Diretório de Armazenamento

O diretório é o local onde as notas serão salvas antes de serem lidas pelo NF Monitor.

<figure><img src="../.gitbook/assets/image (279).png" alt=""><figcaption></figcaption></figure>

* Por padrão, o aplicativo cria uma estrutura automática que separa as notas por **CNPJ**, **Ano de Emissão** e **Mês de Emissão**.
* **Não é necessário alterar a estrutura** — apenas valide o caminho.
*   O diretório é vinculado ao **usuário do Windows**, normalmente localizado em algo como:

    ```
    C:\Users\NOME_DO_USUARIO\HUB SIEG
    ```

>
>
> 🔍 Esse caminho será posteriormente informado dentro do **NF Monitor**, para que o Sittax possa ler as notas baixadas.

<figure><img src="../.gitbook/assets/image (280).png" alt=""><figcaption></figcaption></figure>

***

### ⏬ Etapa 6 — Download Inicial e Sincronização Diária

1. Retorne ao menu **Empresas** dentro do **Hub / Cofre**.
2. Clique na opção **“Baixar Notas”**.

<figure><img src="../.gitbook/assets/image (281).png" alt=""><figcaption></figcaption></figure>

1. O aplicativo iniciará o download de todas as notas dentro do período definido.
2. Após o download inicial, o sistema passará a **sincronizar automaticamente** as novas notas diariamente, caso a seguinte opção nas configurações tenha sido preenchida:

<figure><img src="../.gitbook/assets/image (282).png" alt=""><figcaption></figcaption></figure>

> ⏱️ Mantenha o aplicativo SIEG em execução em segundo plano. Ele é responsável por atualizar o diretório continuamente.

***

### 🔗 Etapa 7 — Integração com o NF Monitor (Sittax)

Após o diretório estar populado com as notas, siga os passos abaixo para finalizar a integração:

1. Abra o **NF Monitor** (dentro do Sittax Simples).
2.  Configure o caminho de leitura para o **diretório onde as notas da SIEG estão sendo salvas**.\


    <figure><img src="../.gitbook/assets/image (283).png" alt=""><figcaption></figcaption></figure>
3. O NF Monitor fará a varredura das subpastas (CNPJ / Ano / Mês) e importará as notas automaticamente para o **Sittax Simples**.

> ✅ Após configurado, o processo será **totalmente automático**: o aplicativo SIEG baixa as notas, o NF Monitor lê, e o Sittax processa.

***

