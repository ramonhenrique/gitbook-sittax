# Dados do Escritório

## Dados

\
Na aba "Dados", dentro de "Dados do Escritório", são exibidos todos os dados principais do escritório, como CNPJ, nome, UF, nome fantasia, município, e-mail, data de criação no SITTAX e telefone do escritório.

<figure><img src="../../../.gitbook/assets/image (115).png" alt=""><figcaption></figcaption></figure>

Aqui é possível alterar o nome fantasia, E-mail e telefone do escritório.

## E-mails

Nesse painel, é possível acessar a configuração e parametrização dos e-mails automáticos.

### O que enviar:

<figure><img src="../../../.gitbook/assets/image (116).png" alt=""><figcaption></figcaption></figure>

**Seção "O que enviar"**

Nesta seção, você pode configurar quais relatórios serão enviados por e-mail automaticamente. Você pode selecionar quais relatórios deseja que sejam enviados, ativando ou desativando cada opção com os interruptores disponíveis. Esta funcionalidade é útil para manter a equipe informada e garantir que os documentos necessários sejam sempre enviados e recebidos de maneira automatizada.

**Tipos de Relatórios e Descrições**

* **DAS**: Guia gerada no PGDAS para o pagamento do imposto.
* **EXTRATO**: Extrato da declaração enviada ao PGDAS para conferência da declaração.
* **FATURAMENTO**: Declaração do faturamento dos últimos 12 meses.
* **CERTIDÕES**: Certidões negativas estaduais e federais.
* **CONFERÊNCIA**: Relatório analítico com as notas declaradas na apuração.
* **CONFERÊNCIA DIFAL**: Relatório analítico com as notas interestaduais.
* **QUEBRA DE SEQUÊNCIA**: Relatório analítico dos problemas que houveram na apuração.
* **GUIA DIFAL**: Guia gerada para o pagamento do DIFAL.

### Apuração:

Nesta seção, você configura o e-mail para envio automático dos dados da apuração. Esta funcionalidade é essencial para garantir que os dados apurados sejam enviados corretamente aos destinatários, mantendo-os informados e facilitando a conferência das informações.

<figure><img src="../../../.gitbook/assets/image (117).png" alt=""><figcaption></figcaption></figure>

Inicialmente, um campo para a digitalização do corpo do e-mail será apresentado, nele usando as ferramentas do cabeçalho, é possível digitalizar conforme desejado, além de anexar imagens com a logo ou mensagens que irão compor o corpo do e-mail.

A digitação do e-mail se dá por meio de tags que irão processar o que será enviado para o cliente final, elas são:

Campos de Personalização:

* **{NOME\_CLIENTE}**: Inserir o nome do cliente.
* **{MES}**: Inserir o mês da apuração.
* **{numeroDareGuiaRevenda}**: Inserir o número da guia de revenda.
* **{numeroDareGuiaUsoConsumoImobilizado}**: Inserir o número da guia de uso/consumo imobilizado.
* **{arquivoZip}**: Inserir o link para o arquivo zip com os dados da apuração.

Exemplo de Texto do E-mail:

"Olá, {NOME\_CLIENTE}. A apuração do mês {MES} foi transmitida. Acesse o arquivo abaixo: {arquivoZip}"\
\
&#xNAN;_&#x4C;embrando que a digitalização das tags tem que ser exatamente como mostrado no exemplo_.

Após finalizar as configurações e digitações, recomendamos que utilize os testes de e-mail para verificar como será exibido para o seu cliente.

#### Testes

* **Teste de e-mail**: Permite enviar um e-mail de teste para verificar se a configuração está correta, será enviado para o e-mail que está informado no cadastro do escritório.
* **Teste de e-mail download**: Envia um e-mail de teste com opção de download para verificar a funcionalidade de anexos para o e-mail no cadastro do escritório

### Faturamento:

Nesta seção, você configura o e-mail para envio automático dos dados do faturamento do cliente. Esta funcionalidade é essencial para garantir que a apuração do faturamento seja enviado corretamente aos destinatários, mantendo-os informados e facilitando a conferência das informações.

<figure><img src="../../../.gitbook/assets/image (118).png" alt=""><figcaption></figcaption></figure>

Inicialmente, um campo para a digitalização do corpo do e-mail será apresentado, nele usando as ferramentas do cabeçalho, é possível digitalizar conforme desejado, além de anexar imagens com a logo ou mensagens que irão compor o corpo do e-mail. A digitação do e-mail se dá por meio de tags que irão processar o que será enviado para o cliente final, elas são:

* **{nomeEmpresa}**: Inserir o nome da empresa do cliente.
* **{MES}**: Inserir o mês do faturamento.
* **{cnpj}**: Insesir o CNPJ da empresa do cliente.<br>

Logo abaixo, é possível anexar uma imagem de cabeçalho para o E-mail, uma imagem de assinatura e uma de rodapé, basta clicar em selecionar e enviar após a seleção.

Após finalizar as configurações e digitações, recomendamos que utilize os testes de e-mail para verificar como será exibido para o seu cliente.

#### Testes

* **Teste de e-mail**: Permite enviar um e-mail de teste para verificar se a configuração está correta, será enviado para o e-mail que está informado no cadastro do escritório.
* **Teste de e-mail download**: Envia um e-mail de teste com opção de download para verificar a funcionalidade de anexos para o e-mail no cadastro do escritório.

## Certificado

Neste painel, é possível adicionar o certificado digital do escritório. No início do painel, você encontrará uma visualização dos certificados ativos na base (Item 1), que descreve a data de importação e a data de validade do certificado (A1).

<figure><img src="../../../.gitbook/assets/image (120).png" alt=""><figcaption></figcaption></figure>

**Passos para Adicionar um Novo Certificado**

1. **Importar Certificado**:
   * Clique no botão central "Importe seus arquivos" (Item 2).
   * Um menu de busca será aberto para que você possa procurar o arquivo desejado dentro do seu computador.
   * **Lembrando:** A estrutura do nome do certificado deve incluir a senha, da seguinte maneira: `nome senha123.pfx`.
2. **Listagem e Envio do Certificado**:
   * Após adicionar o certificado, ele ficará listado como pendente para aprovação (Item 3).
   * Para enviar o certificado para o sistema, clique nos botões laranjas "Enviar" ou "Enviar todos".

## Sócios

Nessa tela é possível cadastrar os sócios desse escritório, essa função é extremamente importante para escritórios que utilizam certificados por procuração em cliente onde o certificado digital usado será o de pessoa física do Sócio. Nesse caso, após cadastrar o sócio é possível importar o certificado dele no menu "Certificados" dentro do cadastro do escritório.\
\
Ao abrir o menu "Sócios" a seguinte tela poderá ser visualizada:

<figure><img src="../../../.gitbook/assets/image (123).png" alt=""><figcaption></figcaption></figure>

Para cadastrar um sócio, basta clicar em "Adicionar Sócio", preencher o nome, o CPF e clicar no botão laranja "Salvar".

## Configurações

No menu de configurações, é possível ativar e desativar avisos, notificações, tipo de pesquisa e o fuso horário. Ao clicar nessa função, o seguinte painel será mostrado:<br>

<figure><img src="../../../.gitbook/assets/image (126).png" alt=""><figcaption></figcaption></figure>

* **Notificação de Quebra de Sequência**:  Ao marcar esta opção, você será notificado quando empresas vinculadas a este escritório apresentarem quebra de sequência.
* **Data de Entrada Automática**: Ao ativar, sempre será considerada a data de emissão da nota ao importar.
* **Aviso de Erros no Certificado**: Ao marcar esta opção, você receberá avisos sobre o vencimento do certificado.
* **Pesquisa por Razão Social**: Ao ativar esta funcionalidade, será possível buscar empresas pelo nome da razão social.

## SIEG

Dentro da configuração do escritório, é possível configurar a integração do Sittax com o serviço do SIEG, permitindo que as notas de saída e de entrada sejam importadas automaticamente para o sistema. Ao acessar este painel, siga os passos abaixo para realizar a configuração:

<figure><img src="https://edu.sittax.com.br/sittax-base-conhecimento/~gitbook/image?url=https%3A%2F%2F2688983956-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FOLejyHkoluGzXQSWUsNa%252Fuploads%252FT9l3AGa7dJfHXeaWimLs%252Fimage.png%3Falt%3Dmedia%26token%3Df4da30de-274d-4154-9fad-8b8da00092ff&#x26;width=768&#x26;dpr=3&#x26;quality=100&#x26;sign=5bc44217&#x26;sv=2" alt=""><figcaption></figcaption></figure>

**1. Acesse a aba "Configurações"** Na tela **Dados do Escritório**, clique no botão **Configurações** localizado na parte superior da seção.

<figure><img src="https://edu.sittax.com.br/sittax-base-conhecimento/~gitbook/image?url=https%3A%2F%2F2688983956-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FOLejyHkoluGzXQSWUsNa%252Fuploads%252FkekceTv1bRgRblNYedfU%252Fimage.png%3Falt%3Dmedia%26token%3Dc2a51a57-4d54-4c83-a955-4e714c108576&#x26;width=768&#x26;dpr=3&#x26;quality=100&#x26;sign=a1b8cf7c&#x26;sv=2" alt=""><figcaption></figcaption></figure>

#### Dados Necessários para Integraçã<sub>o</sub> <a href="#dados-necessarios-para-integracao" id="dados-necessarios-para-integracao"></a>

Na janela **Serviços**, é obrigatório informar os seguintes dados:

* **API Key SIEG**
* **E-mail SIEG**
* **Senha SIEG**

Essas informações devem ser exatamente as mesmas utilizadas no cadastro e na geração da API dentro da SIEG.

***

#### Transição das APIs SIEG <a href="#transicao-das-apis-sieg" id="transicao-das-apis-sieg"></a>

<figure><img src="https://edu.sittax.com.br/sittax-base-conhecimento/~gitbook/image?url=https%3A%2F%2F2688983956-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FOLejyHkoluGzXQSWUsNa%252Fuploads%252FcmxMxgsDED5ynrTtgF39%252Fimage.png%3Falt%3Dmedia%26token%3D4fdc1a89-c693-4942-9c2d-31d883c79077&#x26;width=768&#x26;dpr=3&#x26;quality=100&#x26;sign=a5fbffe0&#x26;sv=2" alt=""><figcaption></figcaption></figure>

**1. API Antiga**

* A **API antiga** continuará funcionando **somente até 31/07/2026**.
* Após essa data, a integração deixará de funcionar caso a migração não seja realizada.
* Recomendamos fortemente **não aguardar o prazo final** para realizar a troca.

***

**2. Nova API (Obrigatória)**

A **Nova API SIEG** oferece melhorias de desempenho, estabilidade e segurança.

**Como gerar a Nova API na SIEG**

1. Acesse o painel da **SIEG**.
2.  Clique na opção **“Gerar nova chave API”**.



    <figure><img src="https://edu.sittax.com.br/sittax-base-conhecimento/~gitbook/image?url=https%3A%2F%2F2688983956-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FOLejyHkoluGzXQSWUsNa%252Fuploads%252FrFzF8W3tmY1UgZmYDPAc%252Fimage.png%3Falt%3Dmedia%26token%3D2c7d2893-c35e-4f22-9778-9d2b8643ffb3&#x26;width=768&#x26;dpr=3&#x26;quality=100&#x26;sign=bdc563c0&#x26;sv=2" alt=""><figcaption></figcaption></figure>
3. Preencha os campos conforme abaixo:
   * **Nome de identificação:** escolha um nome que facilite a identificação (ex: _Integração Sittax_).
   * **Prazo de expiração:** selecione **5 anos (60 meses)**.
   * **Nível de permissões:** marque **Acesso total**.
4. Confirme a geração da chave.
5. **Copie o código da chave API gerada**.

***

#### Configuração da Nova API no Sittax <a href="#configuracao-da-nova-api-no-sittax" id="configuracao-da-nova-api-no-sittax"></a>

Após gerar a nova chave na SIEG:

1. Acesse o **Sittax**.
2. Vá até a janela SIEG dentro da configuração do Escritório.
3. Preencha os campos com:
   * **API Key SIEG:** cole a nova chave gerada.
   * **E-mail SIEG:** e-mail utilizado na criação da API.
   * **Senha SIEG:** senha correspondente ao mesmo usuário.
4. Salve as alterações.

## Acessórias

Nesta aba, você pode configurar a integração do **Sittax** com a plataforma **Acessórias**, possibilitando o envio automático de documentações, como: **Declaração, Extrato, DAS e Recibo**.

Para realizar a configuração, siga os passos abaixo:

<figure><img src="../../../.gitbook/assets/image (259).png" alt=""><figcaption></figcaption></figure>

**1. Acesse a aba "Acessórias"**\
Na tela **Dados do Escritório**, clique na aba **Acessórias** localizada no menu superior.

**2. Informe a API Key Acessórias**\
Digite a **API Key Acessórias** no campo indicado.

**3. Clique em "Salvar"**\
Após preencher a API Key, finalize clicando no botão **Salvar** para concluir a configuração.

## Financeiro

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

A aba **Financeiro** é destinada exclusivamente ao **administrador do escritório** e tem como objetivo centralizar todas as informações relacionadas aos pagamentos da assinatura da ferramenta.

Por meio desta aba, o usuário pode:

* **Acessar os boletos** das mensalidades vigentes e anteriores;
* **Realizar o pagamento** de faturas em aberto, clicando em **“Pagar Agora”**;
* **Consultar o histórico de pagamentos**, visualizando status (Aberto/Quitado), datas de vencimento e pagamento, valores e descontos aplicados;
* **Emitir a segunda via** ou **visualizar faturas já quitadas**, por meio da opção **“Ver”** disponível em cada linha.

Essa área garante **transparência e autonomia financeira** ao escritório, permitindo o acompanhamento completo das cobranças, sem necessidade de contato direto com o suporte para obtenção dos boletos.
