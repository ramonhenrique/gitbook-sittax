# Integração/Configuração SIEG API

## SIEG

Dentro da configuração do escritório, é possível configurar a integração do Sittax com o serviço do SIEG, permitindo que as notas de saída e de entrada sejam importadas automaticamente para o sistema. Ao acessar este painel, siga os passos abaixo para realizar a configuração:

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

**1. Acesse a aba "Configurações"**\
Na tela **Dados do Escritório**, clique no botão **Configurações** localizado na parte superior da seção.

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Dados Necessários para Integração

Na janela **Serviços**, é obrigatório informar os seguintes dados:

* **API Key SIEG**
* **E-mail SIEG**
* **Senha SIEG**

Essas informações devem ser exatamente as mesmas utilizadas no cadastro e na geração da API dentro da SIEG.

***

### Transição das APIs SIEG

<figure><img src="../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

#### 1. API Antiga

* A **API antiga** continuará funcionando **somente até 31/07/2026**.
* Após essa data, a integração deixará de funcionar caso a migração não seja realizada.
* Recomendamos fortemente **não aguardar o prazo final** para realizar a troca.

***

#### 2. Nova API (Obrigatória)

A **Nova API SIEG** oferece melhorias de desempenho, estabilidade e segurança.

**Como gerar a Nova API na SIEG**

1. Acesse o painel da **SIEG**.
2.  Clique na opção **“Gerar nova chave API”**.<br>

    <figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>
3. Preencha os campos conforme abaixo:
   * **Nome de identificação:** escolha um nome que facilite a identificação (ex: _Integração Sittax_).
   * **Prazo de expiração:** selecione **5 anos (60 meses)**.
   * **Nível de permissões:** marque **Acesso total**.
4. Confirme a geração da chave.
5. **Copie o código da chave API gerada**.

***

### Configuração da Nova API no Sittax

Após gerar a nova chave na SIEG:

1. Acesse o **Sittax**.
2. Vá até a janela SIEG dentro da configuração do Escritório.
3. Preencha os campos com:
   * **API Key SIEG:** cole a nova chave gerada.
   * **E-mail SIEG:** e-mail utilizado na criação da API.
   * **Senha SIEG:** senha correspondente ao mesmo usuário.
4. Salve as alterações.



\
<br>
