# Exceção PIS/COFINS

A tela de Exceção de PIS/COFINS é usada para gerenciar as regras de tributação específicas relacionadas aos impostos PIS e COFINS. Ela permite que os usuários visualizem, criem e administrem exceções e regras, assegurando que a tributação esteja em conformidade com as leis e regulamentos vigentes. Com esta tela, é possível definir e aplicar regras específicas para diferentes NCMs, ajustar a tributação conforme a necessidade, e garantir que todas as exceções sejam devidamente registradas e ativas durante o período de vigência. Além disso, a funcionalidade de operação em lote facilita a gestão eficiente de múltiplas regras ao mesmo tempo.\


Ao abrir o painel de Exceção PIS/COFINS, o seguinte menu será mostrado:

<figure><img src="../../.gitbook/assets/image (248).png" alt=""><figcaption></figcaption></figure>

Siga os itens demarcados na imagem

1. **Visualização de Exceções Atuais**
   * **NCM:** Lista o NCM (Nomenclatura Comum do Mercosul) ao qual a regra se aplica.
   * **Anexo:** Indica o anexo ao qual a regra pertence.
   * **Descrição da Regra:** Fornece uma descrição detalhada da exceção ou regra.
   * **Data de Vigência:** Mostra a data de início e fim em que a regra está em vigor.
   * **Lei Tributária e Base Legal:** Especifica a lei PIS/COFINS referente à regra e sua base legal.
   * **Tipo de Tributação:** Define se a tributação é por Substituição ou Monofásica.
   * **Origem:** Indica se a regra foi sugerida pelo Sittax ou inserida manualmente.
   * **Status:** Mostra se a regra está ativa ou inativa.
2. **Operação em Lote**
   * **Selecionar Operação:** Há um botão laranja "Operação em Lote" abaixo da visualização. Ao lado dele, selecione a operação desejada: Ativar, Desativar ou Excluir.
   * **Marcar Regras:** Marque as caixas na primeira coluna para selecionar as regras que deseja aplicar a operação.
   * **Executar Operação:** Clique em "Realizar Operação em Lote" para executar a função selecionada em todas as regras marcadas.
3. **Adicionar Nova Exceção**
   * **Iniciar Adição:** Clique no botão preto "Nova Exceção PIS/COFINS" para abrir o painel de preenchimento.
   * **Preencher Informações:**
     * **NCM:** Insira o NCM ao qual a regra se aplica.
     * **Descrição da Regra:** Forneça uma descrição detalhada da exceção.
     * **Data de Vigência:** Defina as datas de início e término da vigência da regra.
     * **Lei PIS/COFINS:** Especifique a lei tributária e sua base legal.
     * **Tipo de Tributação:** Selecione se é Substituição ou Monofásica.
     * **Anexo:** Indique o anexo ao qual a regra pertence.
   * **Salvar:** Após preencher todas as informações, clique em "Salvar" para adicionar a nova exceção ao sistema.

***

## Importar por Excel

Este método é voltado para o cadastro em massa de regras de PIS e COFINS. Siga os passos abaixo para realizar o cadastro:

<figure><img src="../../.gitbook/assets/image (249).png" alt=""><figcaption></figcaption></figure>

1.  **Baixar Planilha Modelo**

    * No final da página do painel de cadastro, clique no botão amarelo "Planilha Modelo" (Item 1).
    * Uma planilha Excel será baixada contendo 5 colunas: NCM, Data de Início e Fim da Vigência, Legislação PIS/COFINS e Tipo da Tributação.

    <figure><img src="../../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure>
2. **Preencher Planilha**
   * Preencha os dados das regras na planilha conforme as colunas especificadas.
3. **Importar Planilha**
   * Volte ao painel de cadastro e clique no botão central "Importe Seus Arquivos" para importar a planilha preenchida (Item 2).
   * A planilha será carregada e ficará pendente de envio para o Sittax.
4. **Enviar Planilha**
   * Para finalizar o processo, clique no botão laranja "Enviar para todos".

***

## Sugestão

Nessa tela, é possível ver as regras sugeridas pelo Sittax, essas regras são formuladas baseadas nas notas já importadas ao sistema e na configuração da empresa (UF, Cidade, CNAEs, etc..). Ao ser definida uma sugestão, ela irá aparecer no seguinte painel:

<figure><img src="../../.gitbook/assets/image (250).png" alt=""><figcaption></figcaption></figure>

Neste painel (Item 1), são exibidas as sugestões de regras de PIS/COFINS que ainda não foram importadas e estão pendentes. Ele mostra:

* O NCM ao qual a regra se aplica
* A descrição da regra
* O período de vigência de acordo com a lei
* A legislação tributária de PIS/COFINS relevante
* O tipo de tributação que a regra alterará

Para acatar uma sugestão e transformá-la em uma regra:

1. Marque as sugestões que deseja incorporar.
2. Clique no botão "Importar Exceções" (Item 2).

Após a importação, essas sugestões se tornam regras e podem ser validadas no primeiro menu "Exceção PIS/COFINS".

<figure><img src="../../.gitbook/assets/image (251).png" alt=""><figcaption></figcaption></figure>

***

## Não Acatadas

A aba **Não Acatadas** tem como finalidade permitir ao usuário **controlar e desconsiderar determinados NCMs** da apuração de **PIS/COFINS no regime monofásico**, para um cliente específico.

<figure><img src="../../.gitbook/assets/image (252).png" alt=""><figcaption></figcaption></figure>

#### **Como funciona:**

* Ao incluir um NCM na aba **“Não Acatadas”**, o sistema passa a **desconsiderar automaticamente a tratativa monofásica** durante a apuração de PIS/COFINS para aquele item.
* A nota fiscal será normalmente importada e registrada, mas os valores relacionados a PIS e COFINS **não serão tratados com a lógica de monofásico**, ou seja, poderão ser considerados como tributáveis, conforme parametrização.
* Isso permite um **controle individualizado** por NCM, com base na interpretação da legislação vigente ou em decisões administrativas.

#### **Quando utilizar:**

Essa funcionalidade pode ser aplicada, por exemplo, nos seguintes cenários:

* Produtos que, embora usualmente sujeitos ao **regime monofásico**, **não se enquadram** nessa sistemática por conta da **forma de comercialização, ou outros critérios legais**.
* Itens cujo **enquadramento fiscal foi realizado de forma incorreta** pelo fornecedor, mas o cliente deseja **ajustar o tratamento tributário** na apuração.
* Situações em que o cliente opta, com base em laudo ou parecer jurídico/fiscal, por **não considerar determinado NCM como monofásico**.
