# Apuração por XML

## Apuração XML

Esta é a tela de apuração por XML do sistema, criada para oferecer diferentes formas de cálculo e conferência do Simples Nacional. Nela, é possível escolher entre três métodos distintos de apuração, permitindo tanto a utilização da inteligência da Sittax quanto a leitura fiel das notas fiscais. Além disso, o painel também apresenta informações detalhadas de faturamento, percentuais de cálculo e comparativos gráficos entre impostos.

<figure><img src="../../.gitbook/assets/image (210).png" alt=""><figcaption></figcaption></figure>

Ao abrir o menu de apuração XML, o usuário terá acesso às seguintes opções:

*   **Apuração pela Sittax**: realizada a partir da importação das notas fiscais e do acatamento das exceções de PIS, COFINS e ICMS. Nesse modelo, todos os itens são considerados inicialmente como tributados e, em seguida, o sistema aplica as regras de ICMS ST, monofasia e exceções específicas, garantindo maior precisão no resultado.\


    <figure><img src="../../.gitbook/assets/image (211).png" alt=""><figcaption></figcaption></figure>
*   **Apuração via XML**: utiliza as informações exatas registradas nas notas fiscais, sem aplicar correções automáticas. É o modelo padrão utilizado pela maioria dos sistemas contábeis, refletindo integralmente o que foi informado no momento da emissão.\


    <figure><img src="../../.gitbook/assets/image (212).png" alt=""><figcaption></figcaption></figure>
*   **Apuração Personalizada**: possibilita combinar os dois métodos anteriores, permitindo definir quais tributos devem ser calculados pela Sittax e quais seguirão diretamente as notas fiscais. Dessa forma, o usuário pode, por exemplo, calcular ICMS pela Sittax e considerar PIS/COFINS conforme a nota, gerando uma apuração híbrida.\


    <figure><img src="../../.gitbook/assets/image (213).png" alt=""><figcaption></figcaption></figure>

***

### Dados de Faturamento

A tela também exibe informações detalhadas sobre o faturamento da empresa:\


<figure><img src="../../.gitbook/assets/image (214).png" alt=""><figcaption></figcaption></figure>

* Receita líquida, separada entre **produtos, serviços e devoluções**.
* **Alíquota efetiva aplicada** ao cálculo da apuração.
* Percentual de **redução de ICMS**, quando houver benefício ou ajuste por faixa de faturamento estadual.
* Exibição do **RBT12**, que representa o faturamento dos últimos 12 meses.
* Exibição do **RBA**, correspondente ao acumulado do ano.
* **Receita anual de serviços**, destacada separadamente.

***

### Percentual da Receita

Por fim, a tela disponibiliza **gráficos comparativos** que mostram a diferença entre:\


<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

* Os impostos calculados diretamente a partir das notas fiscais emitidas pelo cliente.
* Os impostos recalculados com base na análise da Sittax.

Esse comparativo destaca onde há maior concentração de base de cálculo e facilita a identificação de distorções ou inconsistências tributárias.\


***

### Painel de Auditoria

No painel de auditoria, é disponibilizado alguns avisos e advertências sobre a situação atual da apuração.

\
Esses avisos, são os mesmo que aparecem no painel do contador ao clicar em uma empresa, porém, aplicados para o menu de apurações, para visualizar o aviso por completo basta passar o cursor em cima dos avisos. Os avisos consistem em:\


<figure><img src="../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

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
6. **Distorção de Alíquota**
   * Detectar possíveis distorções na alíquota efetiva do Simples Nacional. Este aviso alerta sobre a falta ou alterações bruscas de faturamento nos últimos meses, qualquer impacto direto no valor da alíquota da receita do Simples Nacional será referenciado.
7. **Exceção PIS/COFINS**
   * Informar sobre qualquer erro ou exceção encontrada na apuração dos impostos PIS e COFINS. Este aviso refere-se à aplicação das regras de exceções PIS/COFINS sobre NCMs que não tiveram as sugestões acatadas ou cadastradas no sistema, o Sittax por meio desse aviso registra as alterações feitas e ao clicar no aviso disponibiliza a visualização das correções de PIS/COFINS.
8. **Exceção ICMS**
   * Informar sobre qualquer erro ou exceção encontrada na apuração do imposto ICMS. Este aviso refere-se à aplicação das regras de exceções ICMS sobre NCMs que não tiveram as sugestões acatadas ou cadastradas no sistema, o Sittax por meio desse aviso registra as alterações feitas e ao clicar no aviso disponibiliza a visualização das correções de ICMS.

Para aplicar as correções sugeridas, basta acessar Regras Tributárias -> Exceção PIS/COFINS ou Exceção ICMS e acatar as regras sugeridas. Após isso, é necessário que a apuração esteja aberta para as novas regras sejam aplicadas para corrigir a apuração.\


## Operando a Tela de Apuração por XML

Na parte inferior da tela, existe uma barra de operações que concentra todas as ações disponíveis para o usuário dentro da apuração XML. Essas operações são:\


<figure><img src="../../.gitbook/assets/image (3) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

*   **Seleção de Matriz/Filial**: permite visualizar as apurações da matriz e de eventuais filiais, apenas para consulta dos valores. Importante destacar que o PGDAS das filiais é sempre gerado diretamente pela matriz.\


    <figure><img src="../../.gitbook/assets/image (4) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>
*   **Seleção de Anexo**: possibilita filtrar os dados da apuração para visualizar apenas os valores referentes a um anexo específico.\


    <figure><img src="../../.gitbook/assets/image (5) (1) (1).png" alt=""><figcaption></figcaption></figure>
*   **Guia DAS e Novo DAS**: nesta opção é possível baixar uma guia já gerada (Guia DAS) ou emitir um novo arquivo da guia do PGDAS já transmitido (Novo DAS).\


    <figure><img src="../../.gitbook/assets/image (6) (1).png" alt=""><figcaption></figcaption></figure>
*   **Extrato Declaração e Recibo**: disponibiliza os documentos auxiliares da apuração. Após a transmissão, todos ficam disponíveis para download direto ao clicar.\


    <figure><img src="../../.gitbook/assets/image (7) (1).png" alt=""><figcaption></figcaption></figure>
*   **Relatório de Conferência:** Baixa o Relatório de Conferência com todos os dados da Apuração, para auditoria.\


    <figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>
*   **Acessórias**: caso exista integração com o sistema Acessórias, essa função dispara os dados da apuração diretamente para a API da plataforma.\


    <figure><img src="../../.gitbook/assets/image (8) (1).png" alt=""><figcaption></figcaption></figure>
*   **Recalcular**: reprocessa todos os dados da apuração, atualizando e regenerando os valores.\


    <figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>
*   **Enviar e-mail**: utiliza o próprio Sittax para enviar ao cliente, por e-mail, toda a documentação emitida.\


    <figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>
*   **Transmitir/Retransmitir**: é o botão principal da operação. Através dele é feita a transmissão oficial da apuração. Também é possível realizar retificação, o que gera sempre uma nova guia PGDAS.\


    <figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

