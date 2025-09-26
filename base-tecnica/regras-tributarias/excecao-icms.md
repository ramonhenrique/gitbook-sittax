---
description: >-
  A tela de Exceção de ICMS é usada para gerenciar as regras de tributação
  específicas relacionada ao imposto de ICMS.
---

# Exceção ICMS

\
A tela de Exceção de ICMS é usada para gerenciar as regras de tributação específicas relacionadas ao imposto de ICMS. Ela permite que os usuários visualizem, criem e administrem exceções e regras, garantindo que a tributação esteja em conformidade com as leis e regulamentos vigentes.

Alimentada tanto pela tela de sugestões do próprio Sittax quanto pela adição manual de regras, essa ferramenta possibilita definir e aplicar regras específicas para diferentes NCMs e CESTs, ajustando a tributação conforme necessário. Os usuários podem garantir que todas as exceções estejam devidamente registradas e ativas durante o período de vigência. Além disso, a funcionalidade de operação em lote facilita a gestão eficiente de múltiplas regras simultaneamente, tornando a administração das regras de ICMS mais ágil e eficaz.

Ao abrir o painel de Exceção ICMS, o seguinte menu será mostrado:\


<figure><img src="../../.gitbook/assets/image (244).png" alt=""><figcaption></figcaption></figure>

1.  **Visualização de Exceções Atuais**

    * **CNPJ:** Registra o CNPJ da empresa a qual a regra está vinculada.
    * **NCM:** Lista o NCM (Nomenclatura Comum do Mercosul) ao qual a regra se aplica.
    * **CEST:** Lista o CEST (Código Especificador da Substituição Tributária) ao qual a regra se aplica.
    * **Anexo:** Indica o anexo ao qual a regra pertence.
    * **Descrição da Regra:** Fornece uma descrição detalhada da exceção ou regra.
    * **Data de Vigência:** Mostra a data de início e fim em que a regra está em vigor.
    * **Lei Tributária e Base Legal:** Especifica a lei ICMS referente à regra e sua base legal.
    * **Tipo de Tributação:** Define se a tributação é por Substituição ou Isenta/Redução.
    * **Origem:** Indica se a regra foi sugerida pelo Sittax ou inserida manualmente.
    * **Status:** Mostra se a regra está ativa ou inativa.


2.  **Operação em Lote**

    * **Selecionar Operação:** Há um botão laranja "Operação em Lote" abaixo da visualização. Ao lado dele, selecione a operação desejada: Ativar, Desativar ou Excluir.
    * **Marcar Regras:** Marque as caixas na primeira coluna para selecionar as regras que deseja aplicar a operação.
    * **Executar Operação:** Clique em "Realizar Operação em Lote" para executar a função selecionada em todas as regras marcadas.


3.  **Adicionar Nova Exceção**

    *   **Iniciar Adição:** Clique no botão preto "Nova Exceção ICMS" para abrir o painel de preenchimento:

        <figure><img src="../../.gitbook/assets/image (143).png" alt=""><figcaption></figcaption></figure>
    *   **Preencher Informações:**

        * **NCM:** Insira o NCM ao qual a regra se aplica.
        * **CEST:** Insira a qual CEST a regra se aplicará.
        * **Descrição da Regra:** Forneça uma descrição detalhada da exceção.
        * **Data de Vigência:** Defina as datas de início e término da vigência da regra.
        * **Lei ICMS:** Especifique a lei tributária e sua base legal.
        * **Tipo de Tributação:** Selecione se é Substituição ou Isenção/Redução.
        * **Anexo:** Indique o anexo ao qual a regra pertence.



    Lembrando: A regra criada manual será registrada para a empresa selecionada na "seleção de empresas" no cabeçalho do sistema.

* **Salvar:** Após preencher todas as informações, clique em "Salvar" para adicionar a nova exceção ao sistema.

***

## Importar por Excel

Este método é voltado para o cadastro em massa de regras de ICMS. Siga os passos abaixo para realizar o cadastro:\


<figure><img src="../../.gitbook/assets/image (245).png" alt=""><figcaption></figcaption></figure>

1. **Baixar Planilha Modelo**
   * No final da página do painel de cadastro, clique no botão amarelo "Planilha Modelo" (Item 1).
   *   Uma planilha Excel será baixada contendo 5 colunas: NCM, Data de Início e Fim da Vigência, Legislação ICMS e Tipo da Tributação ICMS.\


       <figure><img src="../../.gitbook/assets/image (146).png" alt=""><figcaption></figcaption></figure>
2. **Preencher Planilha**
   * Preencha os dados das regras na planilha conforme as colunas especificadas.
3. **Importar Planilha**
   * Volte ao painel de cadastro e clique no botão central "Importe Seus Arquivos" para importar a planilha preenchida (Item 2).
   * A planilha será carregada e ficará pendente de envio para o Sittax.
4. **Enviar Planilha**
   * Para finalizar o processo, clique no botão laranja "Enviar para todos".

***

## Sugestão

Nessa tela, é possível ver as regras sugeridas pelo Sittax, essas regras são formuladas baseadas nas notas já importadas ao sistema e na configuração da empresa (UF, Cidade, CNAEs, etc..). Ao ser definida uma sugestão do sistema, ela irá aparecer no seguinte painel:\


<figure><img src="../../.gitbook/assets/image (246).png" alt=""><figcaption></figcaption></figure>

Neste painel (Item 1), são exibidas as sugestões de regras de ICMS que ainda não foram importadas e estão pendentes. Ele mostra:

* **NCM**: O NCM ao qual a regra se aplica.
* **CEST**: O CEST para o qual a regra se aplica.
* **UF**: A UF de aplicação da regra.
* **Descrição**: A descrição da sugestão.
* **Legislação Tributária**: A legislação tributária de ICMS relevante.
* **Tipo de Tributação**: O tipo de tributação que a regra alterará para.

Para acatar uma sugestão e transformá-la em uma regra:

1. Marque as sugestões que deseja incorporar.
2. Clique no botão "Importar Exceções do ICMS" (Item 2).

Após a importação, essas sugestões se tornam regras e podem ser validadas no primeiro menu "Exceção ICMS".

***

## Não Acatadas

A aba **“Não Acatadas”** tem como objetivo permitir ao usuário **controlar e desconsiderar determinados NCMs** da apuração de Substituição Tributária de um cliente específico.

<figure><img src="../../.gitbook/assets/image (247).png" alt=""><figcaption></figcaption></figure>

Essa funcionalidade é especialmente útil em situações em que determinados produtos, embora estejam configurados com S.T. na origem, **não devem ser considerados na apuração** do contribuinte, seja por entendimento fiscal, particularidade da operação, regime tributário ou orientação do cliente.

#### **Como funciona:**

* Ao incluir um NCM na aba **“Não Acatadas”**, o sistema **desconsidera automaticamente** esse código de mercadoria durante o processo de apuração da Substituição Tributária para o cliente em questão.
* Essa ação **não afeta o lançamento contábil ou escritural da nota**, apenas impacta o cálculo tributário da S.T. no módulo de apuração.

#### **Quando utilizar:**

Essa funcionalidade pode ser utilizada, por exemplo, nos seguintes casos:

* Produtos que, por interpretação da legislação vigente ou orientação do cliente, **não são considerados sujeitos à substituição tributária**, mesmo que o fornecedor os tenha destacado.
* Situações em que a apuração correta demanda uma **exclusão pontual e controlada** de NCMs para fins de S.T.

A aba **“Não Acatadas”** deve ser utilizada com **cautela e validação técnica**, preferencialmente sob orientação da contabilidade ou do departamento fiscal responsável.
