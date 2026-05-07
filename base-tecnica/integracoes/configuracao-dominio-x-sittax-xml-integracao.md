---
description: >-
  Esta seção tem como objetivo orientar sobre as configurações necessárias na
  ferramenta Domínio, garantindo uma interpretação adequada dos XMLs gerados
  pela Sittax no sistema contábil.
---

# Configuração Domínio x Sittax

## ACUMULADORES <a href="#id-1-acumuladores" id="id-1-acumuladores"></a>

> _**OBSERVAÇÕES: Esta configuração requer a criação de dois novos acumuladores específicos para Saídas. Para evitar sobreposição de códigos ao replicar as configurações para outras empresas, recomenda-se iniciar a numeração dos novos acumuladores a partir do Código 2000**_

_**Para acessar a tela "Acumuladores", siga o seguinte caminho: (Domínio): Arquivos > Acumuladores**_

### SAÍDAS <a href="#saidas" id="saidas"></a>

**IMPORTANTE:** Todos os acumuladores de **Saídas** devem estar com as opções **Faturamento** e **Receita Bruta** marcadas no quadro **Incide Sobre**, localizado na guia **Geral** do cadastro de acumuladores.

<figure><img src="../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

Nos acumuladores criados, na guia **Impostos**, deve ser adicionado o imposto **44 - Simples Nacional**. Em seguida, no botão "**\[...]"** da coluna **Definições**, deve-se parametrizar o respectivo **Anexo**, **Seção** e **Tabela**, conforme a operação correspondente.

**1°- Acumulador: "VENDAS MERC - ICMS-ST+PIS/COF MONOF (ICMS – ST + PIS/COFINS Monofásico)"**

<figure><img src="../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

**Tipo de receita:**

* **Anexo:** Anexo I - Comércio
* **Seção:** Seção II - Receita decorrentes da revenda de mercadoria sujeitas a substituição tributária
* **Tabela:** Tabela 4 - Substituição tributária do PIS/PASEP, COFINS e do ICMS



**2°- Acumulador: "VENDAS MERC - ICMS-NORMAL+PIS/COF MONOF (ICMS NORMAL + PIS/COFINS Monofásico)"**

<figure><img src="https://edu.sittax.com.br/~gitbook/image?url=https%3A%2F%2F3029319656-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fnpmd4zy4Id31URWUpPyI%252Fuploads%252FMVD7YAMU7yXcYEA7iBQP%252Fimage.png%3Falt%3Dmedia%26token%3D034fc6e8-db6f-413d-95cd-568a99f80c7b&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=b01edef&#x26;sv=2" alt=""><figcaption></figcaption></figure>

**Tipo de Receita:**

* **Anexo:** Anexo I - Comércio
* **Seção:** Seção II - Receita decorrentes da revenda de mercadoria sujeitas a substituição tributária
* **Tabela:** Tabela 7 - Substituição tributária somente do PIS/PASEP e da COFINS

### ENTRADAS <a href="#entradas" id="entradas"></a>

**IMPORTANTE:** Todos os acumuladores de **Entradas** relacionados à **Devolução de Vendas** devem estar com as opções **Faturamento**, **Receita Bruta** e **Devolução** marcadas no quadro **Incide Sobre**, localizado na guia **Geral** do cadastro de acumuladores.

<figure><img src="https://edu.sittax.com.br/~gitbook/image?url=https%3A%2F%2F3029319656-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fnpmd4zy4Id31URWUpPyI%252Fuploads%252FwBZfVDvK18fSl12dozR6%252Fimage.png%3Falt%3Dmedia%26token%3D1f60564d-f0eb-4e18-a0d3-7a472ae69859&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=ab542b61&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Nos acumuladores de **Entradas** (Devolução de Vendas), na guia **Impostos**, deve ser adicionado o imposto **44 - Simples Nacional**. Em seguida, no botão **"\[...]"** da coluna **Definições**, deve-se parametrizar o **Anexo**, **Seção** e **Tabela** correspondentes à operação. Ou seja, a parametrização deve ser quase idêntica à realizada nos acumuladores de **Saídas,** a tributação definida (Anexo, Seção e Tabela) no acumulador de **Saídas** deve ser replicada no acumulador de Devoluções **(Entradas)**.

**3°- Acumulador: "DEVOLUÇÃO VENDAS - ICMS+PIS/COF TRIB (ICMS tributado + PIS/COFINS tributado)"**

<figure><img src="https://edu.sittax.com.br/~gitbook/image?url=https%3A%2F%2F3029319656-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fnpmd4zy4Id31URWUpPyI%252Fuploads%252F1wZ0YUMf8gjZaT1hmxQh%252Fimage.png%3Falt%3Dmedia%26token%3Da1a945ee-96e8-4633-bdc6-b27dc4210d9f&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=c8f727b0&#x26;sv=2" alt=""><figcaption></figcaption></figure>

* **Anexo:** Anexo I - Comércio
* **Seção:** Seção I - Receitas decorrentes da revenda de mercadorias não sujeitas a substituição tributária
* **Tabela:** Tabela 1 - Sem substituição tributária

**4°- Acumulador: "DEVOLUÇÃO VENDAS - ICMS-ST+PIS/COF TRIB (ICMS - ST + PIS/COFINS tributado)"**

<figure><img src="https://edu.sittax.com.br/~gitbook/image?url=https%3A%2F%2F3029319656-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fnpmd4zy4Id31URWUpPyI%252Fuploads%252Frw6MrRvCakl4T73s0Te3%252Fimage.png%3Falt%3Dmedia%26token%3De0bc5bbe-d60f-4c56-8064-271b6b5660ad&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=2adb74bc&#x26;sv=2" alt=""><figcaption></figcaption></figure>

* **Anexo:** Anexo I - Comércio
* **Seção:** Seção II - Receita decorrentes da revenda de mercadoria sujeitas a substituição tributária
* **Tabela:** Substituição tributária somente do ICMS

**5°- Acumulador: "DEVOLUÇÃO VENDAS - ICMS-ST+PIS/COF MONOF (ICMS - ST + PIS/COFINS Monofásico)"**

<figure><img src="https://edu.sittax.com.br/~gitbook/image?url=https%3A%2F%2F3029319656-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fnpmd4zy4Id31URWUpPyI%252Fuploads%252FSud0xJkFglZsdtXaDY2l%252Fimage.png%3Falt%3Dmedia%26token%3D020f9469-2245-4343-ba49-d90d2bf44efb&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=deb4a414&#x26;sv=2" alt=""><figcaption></figcaption></figure>

* **Anexo:** Anexo I - Comércio
* **Seção:** Seção II - Receita decorrentes da revenda de mercadoria sujeitas a substituição tributária
* **Tabela:** Tabela 4 - Substituição tributária do PIS/PASEP, COFINS e do ICMS

**6°- Acumulador: "DEVOLUÇÃO VENDAS - ICMS TRI+PIS/COF MONO (ICMS Tributado + PIS/COFINS Monofásico)"**

<figure><img src="https://edu.sittax.com.br/~gitbook/image?url=https%3A%2F%2F3029319656-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fnpmd4zy4Id31URWUpPyI%252Fuploads%252FnLx6vD8O0gnkYGRTGlMc%252Fimage.png%3Falt%3Dmedia%26token%3D40c8db09-6e9f-4782-96a4-754d1376a757&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=99cea79e&#x26;sv=2" alt=""><figcaption></figcaption></figure>

* **Anexo:** Anexo I - Comércio
* **Seção:** Seção II - Receita decorrentes da revenda de mercadoria sujeitas a substituição tributária
* **Tabela:** Tabela 7 - Substituição tributária somente do PIS/PASEP e da COFINS

## CONFIGURAÇÃO DA IMPORTAÇÃO DOS XMLs: <a href="#id-2-configuracao-da-importacao-dos-xmls" id="id-2-configuracao-da-importacao-dos-xmls"></a>

_**Para acessar a tela "Acumuladores", siga o seguinte caminho: (Domínio): Arquivos > Configuração de Importação > NF-e Arquivo XML | NFC-e Arquivo XML**_

<figure><img src="https://edu.sittax.com.br/~gitbook/image?url=https%3A%2F%2F3029319656-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fnpmd4zy4Id31URWUpPyI%252Fuploads%252FPMemTfh0ihPLmpij1QMw%252Fimage.png%3Falt%3Dmedia%26token%3D63c21523-0888-474c-a45b-325bb5e426c5&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=df539ec5&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Esta configuração pode ser aplicada tanto na rotina de **NFC-e em arquivo XML**, como **NF-e arquivo XML**. Porém, como são modelos distintos, o Domínio Escrita possui configurações específicas para cada rotina.

Abaixo, apresentamos um exemplo de configuração para **NF-e (Modelo 55)**. Para **NFC-e (Modelo 65)**, a configuração é semelhante, seguindo os mesmos princípios.

#### GUIA SAÍDAS: <a href="#guia-saidas" id="guia-saidas"></a>

<figure><img src="https://edu.sittax.com.br/~gitbook/image?url=https%3A%2F%2F3029319656-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fnpmd4zy4Id31URWUpPyI%252Fuploads%252FziT3Lc8yVBWxXz1gnPbU%252Fimage.png%3Falt%3Dmedia%26token%3D6131d6e0-2592-467b-ae10-6d0012c8189c&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=93df2b61&#x26;sv=2" alt=""><figcaption></figcaption></figure>

No caso das **Saídas**, O relacionamento do ACUMULADOR será com base no CFOP + CST PIS/COFINS para defini-lo como Monofásico.

#### GUIA ENTRADAS: <a href="#guia-entradas" id="guia-entradas"></a>

Atualmente, na versão de mercado do Domínio (**10.4A-07**), não é possível segregar os lançamentos de **Entradas** ou distinguir acumuladores com base no **CST de PIS/COFINS**. Dessa forma, será necessário vincular os **NCMs** que devem ser considerados para fins de **tributação monofásica** de **PIS** e **COFINS**.

Na guia **Entradas**, subguia **Opções**, selecione a opção **"NCM"** no campo **Identificar o Produto para Relacionar ao Acumulador Por:**

<figure><img src="https://edu.sittax.com.br/~gitbook/image?url=https%3A%2F%2F3029319656-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fnpmd4zy4Id31URWUpPyI%252Fuploads%252FrztwDboBZs5kDI30j8B0%252Fimage.png%3Falt%3Dmedia%26token%3D9a2fa67e-72c5-4578-a028-2723493731d9&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=7cb31af8&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Para as ENTRADAS é necessário relacionar os CFOPs, ou seja, definir qual CFOP de ENTRADA será utilizado para cada CFOP de SAÍDA. Para isso, na guia ENTRADAS, subguia CFOPs você deverá efetuar tal relacionamento, desta forma:

Nas **Entradas**, é necessário relacionar os **CFOPs**, ou seja, definir qual **CFOP de Entrada** corresponderá a cada **CFOP de Saída**. Para isso, acesse a guia **Entradas**, subguia **CFOPs**, e realize o relacionamento conforme o exemplo abaixo:

<figure><img src="https://edu.sittax.com.br/~gitbook/image?url=https%3A%2F%2F3029319656-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fnpmd4zy4Id31URWUpPyI%252Fuploads%252FDxSQAaI53rggQAkVMw5D%252Fimage.png%3Falt%3Dmedia%26token%3Db85db107-68cf-4bff-a045-9b6ff65b19cb&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=6568b294&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Abaixo modelo da configuração dos **ACUMULADORES**:

<figure><img src="https://edu.sittax.com.br/~gitbook/image?url=https%3A%2F%2F3029319656-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252Fnpmd4zy4Id31URWUpPyI%252Fuploads%252FFMpO1FBrKVzT0Nnh0m8N%252Fimage.png%3Falt%3Dmedia%26token%3Dcf452e6a-73b6-4e27-8ebb-e0363b234638&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=e80323d1&#x26;sv=2" alt=""><figcaption></figcaption></figure>
