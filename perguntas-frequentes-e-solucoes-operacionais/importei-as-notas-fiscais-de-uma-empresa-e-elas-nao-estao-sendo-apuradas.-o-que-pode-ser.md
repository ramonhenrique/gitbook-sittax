# Importei as notas fiscais de uma empresa e elas não estão sendo apuradas. O que pode ser?

#### Se as notas fiscais importadas não estão sendo apuradas corretamente no sistema, considere os seguintes pontos para identificar a causa do problema:

1. **Verificação da Data de Emissão:**
   * Certifique-se de que a **Data de Emissão** das notas fiscais confere com o período de apuração atual. Caso a data esteja fora do período de apuração, o sistema poderá importar as notas para o período informado na própria nota fiscal, e não para o período em que você está realizando a apuração.
2. **Emitente da Nota Fiscal:**
   * Verifique se o **Emitente** das notas fiscais é a mesma empresa configurada para executar a importação. O sistema somente irá processar as notas fiscais cujos emitentes correspondam à empresa selecionada para a importação. Se houver divergência no emitente, as notas não serão importadas.
3. **CFOP das Notas Fiscais:**
   * Confira se as **notas fiscais importadas** possuem CFOPs relacionados a operações de **Remessa**, **Bonificação**, **Outras Saídas** ou **Prestações**. O sistema considera esses CFOPs como **não calculáveis** para apuração fiscal e, portanto, não os incluirá no cálculo da apuração.
4. **Inscrição Municipal (Exclusivamente para empresas de Barueri):**
   * Para empresas localizadas no município de **Barueri**, é necessário que a **Inscrição Municipal** esteja registrada na tela de **Dados da Empresa**. Caso essa informação esteja ausente, o sistema não será capaz de processar e importar as notas fiscais emitidas para essa localidade.

Se, após revisar os itens acima, o problema persistir, sugerimos a realização de uma nova importação após ajustes necessários, ou o contato com nosso suporte técnico para análise detalhada do caso.
