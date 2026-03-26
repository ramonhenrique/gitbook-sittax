# Apuração identificou notas fiscais emitidas em contingência. O que fazer?

Notas emitidas em **contingência** são documentos fiscais gerados quando o emissor não consegue se comunicar com a SEFAZ.\
Isso pode ocorrer por diversos motivos, incluindo:

* sistemas ERP operando em modo offline,
* falhas de internet no momento da emissão,
* instabilidades ou indisponibilidades temporárias na SEFAZ.

Nessas situações, o sistema autoriza a nota localmente, permitindo sua emissão imediata. Porém, **a SEFAZ não recebe a transmissão da nota naquele momento** e, sem essa transmissão, a nota ainda **não é reconhecida oficialmente como receita**.

A Sittax identifica automaticamente quando um documento foi emitido em contingência analisando informações específicas do próprio XML, como o tipo de autorização e o modo de emissão. Ao detectar essas ocorrências, a plataforma informa o usuário por meio de um alerta antes da apuração e exige que tais notas sejam **autorizadas manualmente**, garantindo que somente documentos oficialmente válidos componham o cálculo do Simples Nacional.

<figure><img src="../.gitbook/assets/image (311).png" alt=""><figcaption></figcaption></figure>

Abaixo está o procedimento completo para localizar e autorizar manualmente as notas emitidas em contingência.

## Como autorizar notas emitidas em contingência para tributarem na apuração?

**1. Acesse a tela "Nota Fiscal de Saída"**\
No sistema, abra o menu lateral esquerdo e entre em Documentos Fiscais > Nota Fiscal de Saída.<br>

<figure><img src="../.gitbook/assets/image (312).png" alt=""><figcaption></figcaption></figure>

**2. Filtre as notas em "Contingência"**\
Dentro da tela "Nota Fiscal de Saída", utilize o filtro superior para visualizar apenas as notas em contingência: Selecione um filtro >> Status >> CONTINGÊNCIA.<br>

**3. Selecione todas as notas em Contingência**\
Após aplicar o filtro, a tela exibirá todas as notas marcadas como contingência. Marque todas as notas clicando nas caixas de seleção.

**4. Escolha a operação "Autorizar"**\
Com as notas selecionadas, clique em Selecione a operação e escolha Autorizar no menu suspenso.

**5. Clique em "Realizar operação em lote"**\
Finalize clicando em Realizar operação em lote para autorizar todas as notas selecionadas.

<figure><img src="../.gitbook/assets/image (313).png" alt=""><figcaption></figcaption></figure>
