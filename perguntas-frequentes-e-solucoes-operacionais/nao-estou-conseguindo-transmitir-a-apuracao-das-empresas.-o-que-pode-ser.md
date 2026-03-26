# Não estou conseguindo transmitir a apuração das empresas. O que pode ser?

## Para a validação das requisições feitas na ferramenta, siga a etapa abaixo:

### Etapa única: Verificar o status da transmissão

* Após solicitar a **transmissão da apuração da empresa**, é necessário validar se o processo foi concluído com sucesso ou se houve algum impedimento.
* Para isso, acesse a funcionalidade **"Tarefas"**, localizada no **canto superior direito da página**.

<figure><img src="../.gitbook/assets/image (231).png" alt=""><figcaption></figcaption></figure>

Essa área é responsável por exibir o **status das requisições** realizadas dentro da ferramenta Sittax, como por exemplo:

* Geração de arquivos de integração;
* Geração dos livros de **Entradas/Saídas**;
* Relatórios de conferência;
* E a **transmissão da apuração**.

Através da funcionalidade **"Tarefas"**, você poderá verificar se houve falhas ou se a transmissão foi concluída corretamente.

## Impedimentos de transmissão que podem ocorrer:

### Valores dos impostos apurados pelo sistema e o valor apurado pelo PGDAS não coincidiram:

<figure><img src="../.gitbook/assets/image (232).png" alt=""><figcaption></figcaption></figure>

* Esse impedimento pode ocorrer quando a ferramenta encontra **dificuldades para validar a Declaração anterior** no momento da transmissão e geração da Declaração do **período atual de apuração**.
* No entanto, há uma **solução alternativa** que pode ser aplicada para resolver esse cenário.

#### Para a solução do impedimento, siga as etapas abaixo:

> _**OBSERVAÇÃO:** Antes de seguir as etapas abaixo, **certifique-se de que a apuração da empresa esteja aberta**. Manter a apuração aberta garante que **os dados sejam atualizados em tempo real** conforme as ações forem executadas, evitando inconsistências durante o processo._

1. Acesse o PGDAS e baixe o **PDF da Declaração PGDAS** referente ao **último período de apuração** da empresa.
2. Com o PDF salvo em sua máquina, **importe o arquivo** no mesmo local onde são importados os **XMLs para a apuração das notas** dentro do sistema.
3. Após a importação, **tente realizar a transmissão da empresa novamente**.

### Falta de Procuração no e-CAC pelo Autor da Transmissão:

<figure><img src="../.gitbook/assets/image (314).png" alt=""><figcaption></figcaption></figure>

Essa situação ocorre quando a empresa está configurada para utilizar transmissão via certificado por procuração, onde o escritório (autor da transmissão) atua como responsável pelo envio das obrigações. Quando esse escritório não possui uma procuração ativa no e-CAC para a empresa transmitida, o envio é bloqueado automaticamente. Esse impedimento é detectado pela Sittax e apresentado nas mensagens internas da empresa com aviso de acesso negado, informando que o autor do pedido não possui autorização de procuração no e-CAC.

Esse cenário também pode ocorrer quando a empresa utiliza um certificado próprio do tipo A1 importado diretamente na aba de **Certificados**. Caso o certificado importado não corresponda à empresa correta, como nos casos em que é importado o certificado da filial para uma empresa matriz, haverá divergência de dados e o sistema não permitirá a transmissão. Isso acontece porque o certificado precisa estar alinhado com o CNPJ base da empresa transmitida, garantindo que a autenticação seja compatível com os dados fiscais esperados pela SEFAZ e pelo e-CAC.

Quando esse tipo de impedimento ocorre, recomenda-se que o usuário verifique se o escritório possui uma procuração válida e ativa no e-CAC para a empresa desejada. Caso não possua, essa será a causa da falha de transmissão e será necessário incluir ou renovar a procuração para prosseguir. Nos casos em que a transmissão utiliza certificado próprio da empresa, é importante conferir se o certificado corresponde à matriz ou filial correta e, se estiver incorreto, substituir o certificado pelo arquivo digital correspondente à empresa certa para normalizar o envio.
