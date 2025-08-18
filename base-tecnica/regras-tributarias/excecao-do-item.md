# Exceção do Item

a aba "Exceção de Item" permite definir regras de tributação para códigos de item específicos, garantindo que os impostos sejam calculados corretamente. É possível cadastrar exceções individualmente ou importar em lote por meio de uma planilha. Essa funcionalidade é útil quando um produto possui NCM incorreto e precisa ser corrigido para tributação adequada. Assim, o sistema garante a precisão no cálculo dos impostos.

\
Ao abrir a aba, o seguinte painel será mostrado:

<figure><img src="../../.gitbook/assets/image (65).png" alt=""><figcaption></figcaption></figure>

Na aba "Exceção de Item", é possível verificar e administrar as exceções existentes vinculadas à empresa selecionada. Você pode apagar, inativar ou ativar as regras conforme necessário, selecionando a operação desejada, marcando as regras a serem alteradas e clicando no botão laranja "Realizar Operação em Lote".

Para adicionar uma exceção, existem dois métodos: adição manual ou via Excel, sendo o último recomendado para inserção em massa de regras de exceção.

&#x20;

<div align="center"><figure><img src="../../.gitbook/assets/image (148).png" alt="" width="336"><figcaption><p>Cadastro exceção Item</p></figcaption></figure></div>

### Adição Manual

Clique no botão preto "Nova Exceção de Item".

1. Preencha os seguintes campos:
   * **Código do Item ou Nome do Item:** O item ao qual a exceção se aplicará.
   * **Data de Vigência:** Início e fim da vigência da exceção.
   * **Tributação PIS/COFINS:** Indique se é tributado ou não e qual a lei aplicada (substituição, isenção, redução).
   * **Tributação ICM**&#x53;**:** Indique se é tributado ou não e a respectiva lei.
2. Após preencher todas as informações, clique no botão laranja "Salvar" para concluir a operação.

***

### Importar por Excel

Este método é voltado para o cadastro em massa de regras de ICMS. Siga os passos abaixo para realizar o cadastro:

<figure><img src="../../.gitbook/assets/image (149).png" alt=""><figcaption></figcaption></figure>

1.  **Baixar Planilha Modelo**

    * No final da página do painel de cadastro, clique no botão amarelo "Planilha Modelo" (Item 1).
    * Uma planilha Excel será baixada contendo 5 colunas: Código do Item, Data de Início e Fim da Vigência, Tributação de PIS/COFINS (Sim ou Não), Tributação de ICMS (Sim ou Não) e suas Leis correspondentes.

    <figure><img src="../../.gitbook/assets/image (152).png" alt=""><figcaption></figcaption></figure>
2. **Preencher Planilha**
   * Preencha os dados das regras na planilha conforme as colunas especificadas.
   * Em **Tributado de ICMS** e **Tributado de PIS/COFINS**, é necessário informar "Sim" ou "Não"
3. **Importar Planilha**
   * Volte ao painel de cadastro e clique no botão central "Importe Seus Arquivos" para importar a planilha preenchida (Item 2).
   * A planilha será carregada e ficará pendente de envio para o Sittax.
4. **Enviar Planilha**
   * Para finalizar o processo, clique no botão laranja "Enviar para todos".
