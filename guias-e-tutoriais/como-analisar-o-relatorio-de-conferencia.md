# Como analisar o Relatório de Conferência?

### O que é? <a href="#o-que-e" id="o-que-e"></a>

O Relatório de Conferência é um recurso do Sittax que permite comparar os dados das notas fiscais emitidas com as sugestões de tributação feitas pelo sistema. Ele é utilizado para revisar possíveis ajustes fiscais antes da transmissão da apuração, garantindo mais segurança, conformidade e economia para o cliente.

### Como acessar? (Tela de apuração antiga - Gerar Apuração) <a href="#como-acessar" id="como-acessar"></a>

Para acessar o Relatório de Conferência, siga este passo a passo:

<figure><img src="../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

1. No menu lateral esquerdo, clique em **“Apuração”;**
2. Em seguida, selecione **“Gerar Apuração”;**
3. No topo da tela, clique no botão **“Outras ações”;**
4. Por fim, selecione a opção **“Relatório de conferência”**.

### Como acessar? (Nova tela de apuração - Apuração por XML)

Para acessar o Relatório de Conferência, siga este passo a passo:

<figure><img src="../.gitbook/assets/image (305).png" alt=""><figcaption></figcaption></figure>

1. Clique no botão **"Apuração"** localizado no canto superior direito da plataforma;
2. Clique no botão **"Conferência"** localizado no canto inferior da tela de apuração

**Importante:** o relatório deve ser gerado **após acatar as sugestões de tributação** do sistema, garantindo que os dados reflitam os ajustes feitos com base nas regras fiscais atualizadas.

Abaixo, um print com a indicação visual do caminho:

### Como utilizar o relatório para validar as apurações? <a href="#como-utilizar-o-relatorio-para-validar-as-apuracoes" id="como-utilizar-o-relatorio-para-validar-as-apuracoes"></a>

**Entendendo a estrutura do relatório:**

* **Colunas até a "N"**: mostram as informações originais da nota fiscal emitida pelo cliente, como CFOP, CST, NCM e valores.
* **Coluna "O" em diante**: apresentam os dados sugeridos ou alterados pelo Sittax, com base nas exceções tributárias acatadas (ICMS, PIS, COFINS).

**Aplicando filtros para análise crítica:**

* **Filtro por alíquota de ICMS ou por alíquota PIS/COFINS**:
  * Alíquota **zerada** → indica ST ou monofásico.
  * Alíquota **acima de 0%** → indica tributação normal.
* **Filtro por CFOP** (ex: 5405):
  * Verifique se o cliente emitiu como tributado e o Sittax sugeriu como ST.
  * Ajuda a identificar CFOPs incoerentes.
* **Base legal**:
  * Toda alteração sugerida deve trazer a legislação correspondente.
  * Isso reforça a confiabilidade da mudança proposta.

**Dicas práticas para enviar ao cliente:**

* **Copiar colunas úteis**:
  * **Coluna J** – Descrição do item
  * **Coluna K** – Código do produto
* **Criar nova aba**:
  * Cole as informações copiadas.
  * Use o recurso de **remover duplicados** no Google Planilhas.
* **Resultado**:
  * Uma lista objetiva com produtos que precisam de correção no ERP.

**Avaliação do CEST**

* Para clientes que **informam o CEST**, ative a opção:
  * `Configuração da empresa > Configuração do anexo > Avaliar CEST`
* Isso permite ao sistema reconhecer com mais precisão itens sujeitos à ST ou monofásico.

### Considerações finais <a href="#consideracoes-finais" id="consideracoes-finais"></a>

* O **Sittax não utiliza CFOP como base de tributação**.
* A lógica do sistema considera **NCM + base legal** para apurar corretamente.
* Quando não há CEST, o sistema entende como **tributação normal**, então:
  * Reforce a importância do **preenchimento correto pelo cliente**.
* O sistema **não obriga o contador a acatar** as sugestões, mas oferece recursos para auditoria e decisões fiscais mais seguras.
