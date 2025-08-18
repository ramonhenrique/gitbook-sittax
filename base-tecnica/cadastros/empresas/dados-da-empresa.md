---
description: >-
  Ao clicar duas vezes sobre alguma empresa cadastrada, será aberta uma nova
  tela com todos os dados e configurações da empresa.
---

# Dados da Empresa

Ao clicar duas vezes sobre alguma empresa cadastrada, será aberta uma nova tela com todos os dados e configurações da empresa.

<figure><img src="../../../.gitbook/assets/image (189).png" alt=""><figcaption></figcaption></figure>

## Configurações

Na aba Dados da Empresa > Configurações, pode ser habilitado e desabilitado algumas configurações da empresa, há nessa aba as seguintes opções:

### **Acesso da empresa**

&#x20;Ativando essa opção o seu cliente conseguirá fazer login na ferramenta utilizando o CNPJ tanto no login quanto na senha. O acesso do mesmo será reduzido, sendo possível apenas importar notas, verificar notas importas, visualizar o DIFAL e visualizar a apuração. Ele não poderá fazer mais nada além disso.

### **Fator R**

Essa opção deve ser marcada para todas as empresas prestadoras de serviço que possuem Fator R pois, somente mediante a ativação dessa opção que será considerado o Fator R.\
\
Após a ativação, um novo painél será disponibilizado acima:\


<figure><img src="../../../.gitbook/assets/image (190).png" alt=""><figcaption></figcaption></figure>

**Para aprender a operacionalizar esse menu, verifique:**

{% content-ref url="fator-r.md" %}
[fator-r.md](fator-r.md)
{% endcontent-ref %}

### **Certificado por procuração**

Ativando essa opção o sistema irá parar de olhar para o certificado digital próprio da empresa e começará a utilizar a procuração presente no certificado digital do escritório.

### **Data de Entrada Automática**

Ativando essa opção o sistema irá adicionar de forma automática a Data de Entrada das notas de entrada.

### **Dados Contabilistas**

Essa opção é onde é selecionado o contador que será informado no SPED fiscal. Esse contador é cadastrado nos dados do escritório, na aba “Contador”.

### **Usa Crédito do DIFAL**

Ativando essa opção o sistema irá começar a fazer o controle do crédito no DIFAL gerado pelas nota de devolução.

### **Usa Inscrição Estadual Para Gerar DIFAL**

Ativando essa opção, como o próprio nome já diz, é utilizado a inscrição estadual para gerar o DIFA&#x4C;**.**

### **Considera ICMS ST no valor dos produtos**

Ativando essa opção o ICMS ST destacado no xml da nota, será considerado como receita na apuração da empresa.

### **Considera valor do frete na Nota**

Ativando essa opção o sistema irá considerar o valor de frete da nota como receita na apuração da empresa.

### Acréscimo CF-E

Caso alguma nota modelo 59 (SAT / CF-E) tenha sido emitida com acréscimo, se essa opção estiver ativa, o acréscimo irá compor o valor do item e no faturamento, caso desativado, o acréscimo é desconsiderado do cálculo do faturamento.\
\
Exemplo Real: Um restaurante que lança gorjeta como acréscimo na CF-e e não vai considerar esse acréscimo como faturamento, nesse caso, deve desativar essa opção.

### Usa Desconto Condicional

Se ativado, o sistema irá considerar **descontos condicionais** informados nas notas fiscais durante os cálculo.

### Usa Desconto Incondicional

Se ativado, o sistema irá considerar **descontos incondicionais** como redutores do valor da base de cálculo.

### Usa Valor Deduções

Permite considerar valores específicos de **dedução** informados nas notas fiscais para reduzir a base tributável.

### Importa notas pelo sistema SIEG

Quando ativado, permite que o sistema importe automaticamente notas fiscais que estejam cadastradas no **SIEG** (integrador fiscal).

### Regime Caixa

Ao ativar a configuração **Regime de Caixa** no cadastro da empresa, o sistema passará a reconhecer as receitas com base na **data de pagamento** e não mais na data de emissão das notas fiscais. Dessa forma, a apuração tributária considerará o momento em que o valor foi efetivamente recebido, em conformidade com o regime de caixa.

Com a ativação dessa opção, será disponibilizado um novo painel dentro do cadastro da empresa, denominado **Caixa/Recebimentos**. Esse painel permitirá o controle detalhado dos recebimentos vinculados a cada nota fiscal, possibilitando lançamentos manuais e a gestão precisa dos valores recebidos.

Para maiores informações sobre a utilização, configuração e boas práticas relacionadas ao Regime de Caixa, acesse o material completo disponível no link abaixo:

{% content-ref url="recebimento-faturamento-regime-caixa.md" %}
[recebimento-faturamento-regime-caixa.md](recebimento-faturamento-regime-caixa.md)
{% endcontent-ref %}

### Usa Regime de Caixa Apuração

Ao ativar a opção **Usa Regime de Caixa Apuração** nas configurações da empresa, o Sittax passará a considerar, para fins de apuração e geração de guias, o faturamento realizado e os respectivos recebimentos efetivos no caixa.

Dessa forma, a geração das guias de pagamento será realizada com base nos valores que foram efetivamente recebidos pela empresa, desconsiderando a mera emissão das notas fiscais. Essa configuração garante que a apuração esteja de acordo com o regime de caixa, respeitando o fluxo financeiro real da operação.

### Homologada

A opção **Homologada** serve como um marcador para identificar empresas que já passaram pelo processo de auditoria e estão aptas para realizar a transmissão de obrigações fiscais no sistema.

Apenas empresas marcadas como homologadas poderão efetuar transmissões. No momento da transmissão, o sistema exigirá a autenticação do usuário responsável, mediante a inserção do login e senha utilizados para acesso à plataforma. Essa exigência funciona como uma camada adicional de segurança, impedindo que empresas não auditadas ou em fase de ajustes sejam transmitidas de forma inadequada.

Essa configuração é fundamental para garantir a conformidade dos dados enviados e reduzir riscos operacionais.
