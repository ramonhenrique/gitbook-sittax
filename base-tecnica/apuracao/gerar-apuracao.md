# Gerar Apuração

Esta é a tela principal de apuração do sistema, essencial para consolidar e analisar todas as notas fiscais importadas, aplicando automaticamente as regras de exceções de impostos como PIS, COFINS e ICMS. Este painel centraliza as operações fiscais, permitindo a transmissão de apurações, geração de relatórios e gestão de anexos. Ele fornece uma visão completa dos valores apurados, incluindo receitas, devoluções, RBT12 e RBA, além de calcular o DAS e distribuir impostos. O painel de auditoria alerta sobre possíveis inconsistências, garantindo a precisão e conformidade dos dados fiscais, tornando-se crucial para a gestão tributária eficiente da empresa.\
\
Ao abrir o menu de gerar apuração, um dashboard informativo será informado:\


<figure><img src="../../.gitbook/assets/image (155).png" alt=""><figcaption></figcaption></figure>

Deste modo, esse dashboard é separado em duas partes:

* **Informativa**, que se trata da visualização e dos avisos, demonstrando os valores e a distribuição dos impostos, ela é a responsável por processar as regras de ICMS, PIS/COFINS, exceções de itens, distribuir as notas entre seus respectivos anexos e demonstrar os valores finais que serão transmitidos.
* **Operacional**, onde é possível realizar a transmissão, fechamento da apuração, impressão da guia DAS e impressão de relatórios. Toda a operação nessa tela é feita nos botões de ações, que ficam no cabeçalho da tela.

***

## Visualizando as informações do Dashboard

Dentro das informações mostradas nos relatórios do Dashboard, algumas se destacam para a análise e para auditoria, trazendo mais assertividade ao processo de apuração e sua conferência:

<figure><img src="../../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>



**Item 1: Separação por Anexos**

A apuração é organizada por anexos, mostrando todos os anexos pertencentes ao CNPJ da empresa. As notas são anexadas aos seus respectivos anexos, permitindo tanto a visualização exclusiva de cada anexo quanto uma visão completa dos impostos na aba "Geral".\


<figure><img src="../../.gitbook/assets/image (49).png" alt=""><figcaption></figcaption></figure>

**Item 2: Receitas e Devoluções**

Este item apresenta as receitas e devoluções consideradas no cálculo da apuração. Ele exibe a receita de produtos, serviços, devoluções de vendas e a receita líquida, que é a soma das receitas de produtos e serviços subtraída das devoluções.

**Item 3: Faturamento**

Aqui são mostrados o RBT12, que é o faturamento dos últimos 12 meses, e o RBA, que representa o faturamento de janeiro até a data de vigência da apuração.

**Item 4: Percentual sobre a Receita e cálculo DAS**\
\


<figure><img src="../../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

1. **Valor do DAS**: Este painel mostra o valor total do DAS (Documento de Arrecadação do Simples Nacional) já com a alíquota efetiva calculada, nesse relatório é possível ver como a porcentagem sobre a receita. \
   Obs: A porcentagem mostrada nesse relatório se referencia ao valor da guia das sobre a receita total, não se trata da alíquota efetiva.
2. **Percentual da Receita**: Este painel exibe a base de cálculo dos impostos em termos percentuais, detalhando como a receita está sendo distribuída entre os diferentes impostos.
3. **Produtos**: Este painel mostra a divisão em valores absolutos dos diferentes impostos que compõem a apuração, facilitando a visualização dos valores destinados a cada tipo de imposto.\


### Painel de Auditoria

No painel de auditoria, é disponibilizado alguns avisos e advertências sobre a situação atual da apuração.

<figure><img src="../../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

Esses avisos, são os mesmo que aparecem no painel do contador ao clicar em uma empresa, porém, aplicados para o menu de apurações, para visualizar o aviso por completo basta passar o cursor em cima dos avisos. Os avisos consistem em:\


1. **Certificado**
   * Tem como objetivo mostrar a situação do certificado digital e sua data de vencimento
2. **Faturamento**
   * Avisa sobre a situação do faturamento sob uma visão de cálculo do RBT12, caso falte algum faturamento de um mês anterior ou atual, será mostrado aqui nessa advertência.
3. **CNAE**
   * Confirmar que todos os códigos de atividades econômicas (CNAE) cadastrados para a empresa estão corretos e atualizados. Este aviso se refere ao cadastro da empresa e evidencia se algum CNAE não é permitido pelo Simples Nacional.
4. **Inconsistências de Notas**
   * Identificar quebras de sequência ou outras inconsistências nas notas fiscais emitidas ou recebidas pela empresa. Ao importar notas fiscais para a apuração e houver quebra de sequência de numeração é necessário dar ciência ou corrigir as notas para prosseguir com a apuração.
5. **Inconsistências de CFOP**
   *   Identificar erros nos códigos fiscais de operações e prestações (CFOP). Este aviso mostra os CFOPs onde foram encontradas correções pelo Sittax. Ao identificar uma regra ou lei aplicável a um NCM, o aviso mostra quais produtos e notas terão seus CFOPs alterados para a realização da apuração. Ao clicar no aviso, é possível ver um relatório demonstrativo das correções que o Sefaz fez:\


       <figure><img src="../../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>
6. **Guia DAS Vencida**
   * Alertar que a guia de recolhimento do Documento de Arrecadação do Simples Nacional (DAS) não foi transmitida. Este aviso é baseado na competência (Mês/Ano) selecionada no cabeçalho do sistema e mostra se existe alguma Guia DAS que passou da data de vencimento ou não foi emitida de acordo com o E-CAC.
7. **Distorção de Alíquota**
   * Detectar possíveis distorções na alíquota efetiva do Simples Nacional. Este aviso alerta sobre a falta ou alterações bruscas de faturamento nos últimos meses, qualquer impacto direto no valor da alíquota da receita do Simples Nacional será referenciado.
8. **Exceção PIS/COFINS**
   *   Informar sobre qualquer erro ou exceção encontrada na apuração dos impostos PIS e COFINS. Este aviso refere-se à aplicação das regras de exceções PIS/COFINS sobre NCMs que não tiveram as sugestões acatadas ou cadastradas no sistema, o Sittax por meio desse aviso registra as alterações feitas e ao clicar no aviso disponibiliza a visualização das correções de PIS/COFINS.

       <figure><img src="../../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>
9. **Exceção ICMS**
   *   Informar sobre qualquer erro ou exceção encontrada na apuração do imposto ICMS. Este aviso refere-se à aplicação das regras de exceções ICMS sobre NCMs que não tiveram as sugestões acatadas ou cadastradas no sistema, o Sittax por meio desse aviso registra as alterações feitas e ao clicar no aviso disponibiliza a visualização das correções de ICMS.

       <figure><img src="../../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

Para aplicar as correções sugeridas, basta acessar Regras Tributárias -> Exceção PIS/COFINS ou Exceção ICMS e acatar as regras sugeridas. Após isso, é necessário que a apuração esteja aberta para as novas regras sejam aplicadas para corrigir a apuração.\


## Operando a tela de apuração

A operação da tela de apuração é bem simples, ela consiste abertura e fechamento da apuração, transmissão, emissão de relatórios de conferência, etc. Toda a operação pode ser realizada nos botões do cabeçalho, no topo da tela:\
\


<figure><img src="../../.gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

### Ações&#x20;

Ao clicar no botão "Ações" as opções mostradas dependem de como está a apuração, se ela estiver fechada, ao clicar no botão irá aparecer somente a opção de transmitir a apuração:\


<figure><img src="../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

Após realizar a transmissão, novas opções serão disponibilizadas como por exemplo:

<figure><img src="../../.gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

Dentre as opções, é possível:

* Retransmitir a apuração novamente, para gerar uma nova DAS;
* Gerar o arquivo e imprimir a DAS;
* Enviar a DAS ao e-mail cadastrado no cadastro da empresa.

### Outras Ações

No botão à direita, em "Outras Ações", é possível acessar outras operações dentro da tela de apuração. Dependendo do estado da apuração (caso já houver sido transmitida ou não) são disponibilizadas outras opções.\
\
Caso a apuração não tenha sido fechada e transmitida, será mostrado as seguintes opções:

<figure><img src="../../.gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

* Relatório de Conferência: Disponibiliza um relatório em excel que visualiza a tributação por produto das notas.
* Gerar Relatório: Permite a impressão do dashboard, imprimindo todas as informações de receitas e tributação, além do painel de auditoria.
*   Fechar Apuração: Fechar uma apuração determina com que ela não sofra mais alterações em seus valores, notas importadas e regras acatadas com a apuração fechada não terão efeito, apenas se for aberto novamente que as atualizações serão contabilidade. Tanto o fechamento quanto a transmissão ficam demarcados em um aviso no cabeçalho da tela de apuração:

    <figure><img src="../../.gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>

Em caso de uma apuração fechada ou já transmitida, as seguintes opções serão disponibilizadas:

<figure><img src="../../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>

* Relatório de Conferência: Disponibiliza um relatório em excel que visualiza a tributação por produto das notas.
* Gerar Relatório: Permite a impressão do dashboard, imprimindo todas as informações de receitas e tributação, além do painel de auditoria.
* Declaração: Faz o download do documento declaratório de arrecadação do Simples Nacional.
* Gerar Novo DAS: Retransmite a apuração gerando um novo DAS.
* Abrir a Apuração: Tem como função reabrir a apuração, descongelando o cálculo da apuração.
