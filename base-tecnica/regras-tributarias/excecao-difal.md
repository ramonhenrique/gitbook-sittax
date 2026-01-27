# Exceção DIFAL

A tela **Exceção DIFAL** tem como objetivo configurar exceções específicas para o cálculo do **DIFAL** na escrituração fiscal, permitindo determinar regras personalizadas para o tratamento de determinados produtos, CFOPs ou itens.

## Não Calcula:

<figure><img src="../../.gitbook/assets/image (206).png" alt=""><figcaption></figcaption></figure>

Esta aba é utilizada para **informar quais itens, CFOPs ou NCMs devem ser desconsiderados no cálculo do DIFAL**, mesmo que a regra padrão da operação determine o contrário.

* **NCM's:**\
  Campo destinado à inserção do **código NCM** dos produtos que **não devem calcular DIFAL**.
* **CFOP's:**\
  Campo para incluir o **CFOPs** que **devem ser exceção ao cálculo do DIFAL**.
* **Código do Item ou Nome do Item:**\
  Insira aqui o **código interno do item** ou uma descrição do produto/mercadoria que não deve ser impactado pelo cálculo.

## Calcula FECOEP/PROTEGE:

<figure><img src="../../.gitbook/assets/image (200).png" alt=""><figcaption></figcaption></figure>

A aba **Calcula FECOEP/PROTEGE** permite configurar exceções fiscais em que o sistema **deverá aplicar acréscimo de alíquota** relacionado ao **FECOEP** ou **PROTEGE**, conforme legislações estaduais específicas.

* **NCM's:**\
  Informe o **NCM seguido da alíquota adicional** a ser aplicada.

> _**Siga a estrutura abaixo para se aplicar a alíquota:**_
>
> _**(NCM)%%(Alíquota)**_
>
> _**Ex: "12345678%%2"**_

* **CFOP's:**\
  Informe o **CFOP mais a alíquota** a ser aplicada para aquele tipo de operação.

> _**Siga a estrutura abaixo para se aplicar a alíquota:**_
>
> _**(CFOP)%%(Alíquota)**_
>
> _**Ex: "6101%%2"**_

* **Código do item ou Nome do item:**\
  Você também pode indicar o **código ou nome do produto**, seguido da alíquota.

> _**Siga a estrutura abaixo para se aplicar a alíquota:**_
>
> _**(Código/Nome)%%(Alíquota)**_
>
> _**Ex: "PRD123%%2"**_**&#x20;|&#x20;**_**"Notebook%%2,5"**_

## Calcula Benefício:

<figure><img src="../../.gitbook/assets/image (4) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

A aba **Calcula Benefício** permite cadastrar exceções de cálculo de DIFAL onde há **redução de alíquota** ou outro tipo de **benefício fiscal** concedido por legislação estadual.

* **NCM's:**\
  Informe o **NCM do produto** seguido da **alíquota a ser aplicada.**

> _**Siga a estrutura abaixo para se aplicar a alíquota:**_
>
> _**(NCM)%%(Alíquota)**_
>
> _**Ex: "12345678%%4"**_

* **CFOP's:**\
  Informe o **CFOP** mais a **alíquota beneficiada** que deve ser aplicada.

> _**Siga a estrutura abaixo para se aplicar a alíquota:**_
>
> _**(CFOP)%%(Alíquota)**_
>
> _**Ex: "6102%%5"**_

* **Código do item ou Nome do item:**\
  Caso o benefício se aplique a itens específicos, é possível indicar o código ou nome do item seguido da alíquota.

> _**Siga a estrutura abaixo para se aplicar a alíquota:**_
>
> _**(Código/Nome)%%(Alíquota)**_
>
> _**Ex: "REF456%%3"**_**&#x20;|&#x20;**_**"Bebida Energética%%2,5"**_

## Importar Exceção DIFAL:

<figure><img src="../../.gitbook/assets/image (5) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Na aba **Importar Exceção DIFAL**, você pode importar diversas exceções de cálculo de DIFAL em lote por meio de uma planilha modelo. O acesso a planilha modelo se encontra neste botão "Planilha Modelo", no qual se encontra no fim da página **Importar Exceção DIFAL.**

<figure><img src="../../.gitbook/assets/image (6) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Planilha Modelo:

<figure><img src="../../.gitbook/assets/image (199).png" alt=""><figcaption></figcaption></figure>

A ferramenta fornece um modelo de planilha com as seguintes colunas obrigatórias:

| NCM/CFOP/ITEM | ALÍQUOTA | TIPO DA EXCEÇÃO   | TIPO DO ITEM |
| ------------- | -------- | ----------------- | ------------ |
| 38151210      | 0,00%    | Não Calcula       | NCM          |
| 2102          | 0,00%    | Cálculo FECOEP    | CFOP         |
| Item123       | 10,00%   | Cálcula Benefício | Item         |

* **NCM/CFOP/ITEM**: \
  Código que será utilizado como base da exceção.
*   **ALÍQUOTA**:\
    Este campo **só deve ser preenchido** quando o **Tipo da Exceção** for:

    * **Calcula FECOEP/PROTEGE**
    * **Calcula Benefício**

    Para indicar a **alíquota diferenciada** a ser aplicada nesses casos (exemplo: 10%)
* **TIPO DA EXCEÇÃO**:
  * **Não Calcula**: o sistema ignora o cálculo de DIFAL para o item.
  * **Calcula FECOEP/PROTEGE**: aplica a alíquota de fundo específico.
  * **Calcula Benefício**: aplica uma alíquota reduzida conforme benefício fiscal.
* **TIPO DO ITEM**: \
  indica se o código informado é um:
  * **NCM**
  * **CFOP**
  * **Item** (nome ou código interno)

Após preencher ou ajustar a planilha com as exceções desejadas, **você pode importar a mesma planilha diretamente** na aba **“Importar Exceção DIFAL”**, utilizando o campo central identificado por **"Importe seus arquivos"**. O sistema reconhecerá as colunas e aplicará automaticamente as exceções conforme configurado na planilha.

<figure><img src="../../.gitbook/assets/image (198).png" alt=""><figcaption></figcaption></figure>
