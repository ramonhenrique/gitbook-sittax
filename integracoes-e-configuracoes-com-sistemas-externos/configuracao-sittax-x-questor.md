# Configuração Sittax x Questor

A integração entre a **Sittax** e o **ERP Questor** permite gerar um **arquivo de integração em TXT** (no padrão **SPED não fiscal**) com estrutura adaptada para que o Questor leia corretamente as informações fiscais.\
Esse modelo é **especialmente indicado** para cenários com **PIS/COFINS Monofásico**. Para empresas que **não** trabalham com monofásico, a integração via **XML tradicional** costuma atender normalmente.

**Quando utilizar este modelo de integração**

Utilize este modelo principalmente quando a empresa:

* Possui operações com **PIS/COFINS Monofásico**;
* Precisa que o Questor identifique corretamente as naturezas/tributações a partir de um arquivo consolidado.

> Importante: este fluxo **não altera XMLs**. Ele apenas gera um **TXT** para integração.

***

#### Como realizar a integração (passo a passo)

**1. Acesse a tela de geração de arquivos**

No menu lateral da Sittax, acesse:\
**Integrações › Gerar Arquivo**

<figure><img src="../.gitbook/assets/image (307).png" alt=""><figcaption></figcaption></figure>

Em seguida, dentro desse fluxo, clique em:\
**Arquivos XML (Questor) › Configuração Integração Contábil**

<figure><img src="../.gitbook/assets/image (308).png" alt=""><figcaption></figcaption></figure>

**2. Configure as “Naturezas Questor” na Sittax**

<figure><img src="../.gitbook/assets/image (309).png" alt=""><figcaption></figcaption></figure>

Na tela **Gerar Arquivos de Integração**, localize a seção **Naturezas Questor** e configure conforme as naturezas já utilizadas no ERP Questor do cliente.

Orientações importantes:

* As **naturezas devem refletir exatamente** as que o cliente já utiliza no Questor.
* A definição deve respeitar o **tipo de tributação** de cada operação.
* **Não é necessária configuração adicional no Questor**: todo o ajuste é realizado **diretamente na Sittax**.

Naturezas disponíveis por padrão:

* **ICMS Tributado + PIS/COFINS Tributado** → `5102001`
* **ICMS Tributado + PIS/COFINS Monofásico** → `5102005`
* **ICMS ST + PIS/COFINS Tributado** → `5405001`
* **ICMS ST + PIS/COFINS Monofásico** → `5405003`

Após definir, **salve** as alterações.

**3. Gere o arquivo de integração**

Com a configuração salva, ainda na tela **Integrações › Gerar Arquivo**, selecione os filtros necessários (empresa/período/tipo) e clique em **Gerar**.

O resultado será um **arquivo TXT** no padrão **SPED não fiscal**, pronto para ser importado no **ERP Questor**.

***

#### Observações importantes

* As alterações na configuração **impactam somente** o **TXT (SPED não fiscal)** gerado para o Questor.
* Essas alterações **não modificam** nenhum **XML** importado ou exportado pela Sittax.

#### Suporte sobre o Questor

Dúvidas sobre **parametrizações internas**, **cadastro de naturezas** e **funcionamento do ERP Questor** devem ser tratadas diretamente com o **suporte oficial da Questor**, pois a Sittax não realiza suporte sobre configurações internas do ERP.
