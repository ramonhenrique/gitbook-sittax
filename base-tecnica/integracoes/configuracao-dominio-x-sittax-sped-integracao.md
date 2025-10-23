---
hidden: true
---

# Configuração Domínio x Sittax (SPED Integração)

Esta página descreve o novo modelo de integração entre o **Sittax** e o **Domínio**, realizado por meio do arquivo **SPED**. Desenvolvido para otimizar o processo de importação das notas fiscais, esse método substitui a leitura individual via **XML**, proporcionando maior **agilidade**, **consistência dos dados** e **segurança na escrituração contábil**.

### 1. Criação dos Acumuladores

1.  No sistema Domínio, acesse o menu **Arquivos > Acumuladores**.

    <figure><img src="../../.gitbook/assets/image (284).png" alt=""><figcaption></figcaption></figure>
2. Clique em **Novo** para adicionar um novo acumulador.
3. Preencha os seguintes campos:
   * **Nome do Acumulador:** conforme a tabela **Padrão de Acumuladores.**
   * **Descrição:** use a descrição recomendada “Sittax”.
   *   Marque as opções **Faturamento** e **Receita Bruta**.

       <figure><img src="../../.gitbook/assets/image (285).png" alt=""><figcaption></figcaption></figure>
4.  Inclua o **Imposto 44** e altere as **Definições** conforme o tipo de operação.

    <figure><img src="../../.gitbook/assets/image (286).png" alt=""><figcaption></figcaption></figure>
5.  Informe o **Anexo**, **Seção** e **Tabela** conforme a tabela **Padrão de Acumuladores**.

    <figure><img src="../../.gitbook/assets/image (287).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../.gitbook/assets/image (288).png" alt=""><figcaption></figcaption></figure>
6.  Na aba **Estadual**, marque a opção `[✓] Não efetuar controle de CFOP por UF do cliente`.

    <figure><img src="../../.gitbook/assets/image (289).png" alt=""><figcaption></figcaption></figure>
7. Para agilidade, clique com o botão direito e selecione **Copiar Registro** antes de gravar.
8.  Após gravar, clique com o botão direito em um novo registro, selecione **Colar Registro** e altere as informações conforme o segundo acumulador.

    <figure><img src="../../.gitbook/assets/image (290).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../.gitbook/assets/image (291).png" alt=""><figcaption></figcaption></figure>

#### Padrão de Acumuladores: (Tabela para seguir na criação de acumuladores)

| Código | Descrição                         | Imposto | Anexo | Tabela | Seção |
| ------ | --------------------------------- | ------- | ----- | ------ | ----- |
| 2000   | VENDAS – ICMS + PIS/COF TRIB      | 44      | 1     | I      | 1     |
| 2001   | VENDAS – ICMS ST + PIS/COF TRIB   | 44      | 1     | II     | 1     |
| 2002   | VENDAS – ICMS ST + PIS/COF MONO   | 44      | 1     | II     | 4     |
| 2003   | VENDAS – ICMS TRIB + PIS/COF MONO | 44      | 1     | II     | 7     |
| 2004   | DEV – ICMS + PIS/COF TRIB         | 44      | 1     | I      | 1     |
| 2005   | DEV – ICMS ST + PIS/COF TRIB      | 44      | 1     | II     | 1     |
| 2006   | DEV – ICMS ST + PIS/COF MONO      | 44      | 1     | II     | 4     |
| 2007   | DEV – ICMS TRIB + PIS/COF MONO    | 44      | 1     | II     | 7     |

***

### 2. Configuração da Importação

> _**Recomenda-se iniciar pelos acumuladores de saídas, e somente depois configurar as entradas.**_

1.  No sistema Domínio, acesse o menu **Arquivos > Configuração de Importação > SPED Fiscal**.

    <figure><img src="../../.gitbook/assets/image (292).png" alt=""><figcaption></figcaption></figure>
2.  Acesse a aba **Saídas > Acumuladores > Incluir.**

    <figure><img src="../../.gitbook/assets/image (293).png" alt=""><figcaption></figcaption></figure>
3.  Selecione o **modelo de documento** utilizado pelo cliente.

    <figure><img src="../../.gitbook/assets/image (294).png" alt=""><figcaption></figcaption></figure>
4.  Em **Operação**, selecione **Todas**.

    <figure><img src="../../.gitbook/assets/image (295).png" alt=""><figcaption></figcaption></figure>
5.  Inclua os **CFOPs** correspondentes ao acumulador.

    <figure><img src="../../.gitbook/assets/image (296).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../.gitbook/assets/image (297).png" alt=""><figcaption></figcaption></figure>
6.  Inclua os **CSTs** do acumulador:

    <figure><img src="../../.gitbook/assets/image (298).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../.gitbook/assets/image (299).png" alt=""><figcaption></figcaption></figure>

    * **000, 100** → **PIS/COFINS normal.**
    * **050, 150** → **PIS/COFINS monofásico.**
7. Ao final, marque `[✓] Considerar como exceção a opção “Todos” das colunas para relacionamento do acumulador.`

<figure><img src="../../.gitbook/assets/image (300).png" alt=""><figcaption></figcaption></figure>

#### Padrão de Configuração – Saídas (Configuração Importação - SPED FISCAL)

| **Espécie do Documento** | **Operação** | **CFOPs**                    | **CSTs** | **Acumulador**             |
| ------------------------ | ------------ | ---------------------------- | -------- | -------------------------- |
| (Modelo do cliente)      | Todas        | 5102, 5106, 6102, 6106, 6108 | 000, 100 | 2000                       |
| (Modelo do cliente)      | Todas        | 5405, 6404                   | 000, 100 | 2001                       |
| (Modelo do cliente)      | Todas        | 5405, 6404                   | 050, 150 | 2002                       |
| (Modelo do cliente)      | Todas        | 5102, 5106, 6102, 6106, 6108 | 050, 150 | 2003                       |
| (Modelo do cliente)      | Todas        | 5949, 6949                   | —        | (Acumulador Outras Saídas) |

#### Padrão de Configuração – Entradas (Configuração Importação - SPED FISCAL)

| **Espécie do Documento** | **Operação** | **CFOPs**  | **CSTs** | **Acumulador**               |
| ------------------------ | ------------ | ---------- | -------- | ---------------------------- |
| (Modelo do cliente)      | Todas        | 1202, 2202 | 000, 100 | 2004                         |
| (Modelo do cliente)      | Todas        | 1411, 2411 | 000, 100 | 2005                         |
| (Modelo do cliente)      | Todas        | 1411, 2411 | 050, 150 | 2006                         |
| (Modelo do cliente)      | Todas        | 1202, 2202 | 050, 150 | 2007                         |
| (Modelo do cliente)      | Todas        | 1949, 2949 | —        | (Acumulador Outras Entradas) |

***

### 3. Importação de Notas

Para a importação do arquivo SPED dentro da ferramenta Domínio, acesse os campos: **Utilitários > Importação > Importação Padrão > SPED Fiscal**

<figure><img src="../../.gitbook/assets/image (301).png" alt=""><figcaption></figcaption></figure>

*   Caso o cliente **já tenha importado notas anteriormente**, é **necessário sobrescrever** os dados para que a nova configuração seja aplicada corretamente.

    * Para fazer com que o sistema sobrescreva os dados já importados, acesse:

    **Configurações > Geral > Opções > Movimentos > (Marque "Sobrescrever registros existentes")**

    <figure><img src="../../.gitbook/assets/image (302).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../.gitbook/assets/image (303).png" alt=""><figcaption></figcaption></figure>
* Após ajustar todas as configurações, clique em **Importar** para iniciar o processo.
* Valide os resultados e verifique os acumuladores criados.

***

### 4. Validação Final e Checklist

**Antes da importação, valide:**

* Se todos os acumuladores foram criados corretamente.
* Se os CFOPs e CSTs estão associados aos acumuladores correspondentes.
* Se os documentos foram importados sem erros.
