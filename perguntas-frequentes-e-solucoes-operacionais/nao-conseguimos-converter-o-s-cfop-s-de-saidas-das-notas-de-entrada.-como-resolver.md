# Não conseguimos converter o(s) CFOP(s) de saídas das notas de entrada. Como resolver?

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Esse aviso ocorre quando a ferramenta identifica que um **CFOP utilizado não possui o devido parâmetro de conversão** entre **CFOP de Entrada** e **CFOP de Saída** no cadastro de _**Tipo de Item por CFOP**_. Essa ausência de correspondência impede a continuidade da geração do arquivo de integração ou do SPED Fiscal.

Para corrigir a situação, siga o procedimento abaixo com base na imagem de exemplo acima:

1.  Na mensagem apresentada, clique no link destacado em **“clique aqui”** para acessar diretamente a tela de **Tipo de Item por CFOP**.

    <figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>
2.  Na tela de cadastro, clique em **“Novo Tipo do Item por CFOP”**.

    <figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>
3.  No formulário que será exibido:

    <figure><img src="../.gitbook/assets/image (3) (1) (1).png" alt=""><figcaption></figcaption></figure>

    * Selecione o **Tipo de Item** correspondente.
    * Informe o **CFOP de Origem** e o **CFOP de Destino** que devem estar relacionados.
    * Caso necessário, adicione a **Extensão de CFOP** ou uma **Descrição** para auxiliar na identificação.
4. Clique em **Salvar** para confirmar os dados.

Após esse ajuste, a correspondência será estabelecida e o sistema permitirá prosseguir com a geração do arquivo normalmente.

#### Observação:

Considere regerar o arquivo de integração para que a ferramenta possa gerá-lo com os dados atualizados, e com a conversão de CFOP sobre o **Tipo do Item** parametrizado na tela **Tipo de Item por CFOP.**
