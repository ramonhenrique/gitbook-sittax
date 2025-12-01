# Notas de Serviço do Anexo III foram interpretadas como Anexo III Exterior. Como corrigir?

A identificação como **Anexo III Exterior** é realizada pela ferramenta quando o XML da nota fiscal de serviço apresenta uma das seguintes condições:

* **Ausência de dados do Tomador** no XML;
* **Ausência da localização (município/UF) do Tomador** no XML.

Sem essas informações, o sistema não consegue identificar corretamente o Anexo do serviço, e por padrão, a enquadra como prestação de serviço ao exterior.

***

#### Para realizar a correção da interpretação do Anexo correto para as prestações de serviço, siga os passos descritos abaixo:

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

1. **Acesse a tela de Nota Fiscal de Saída**\
   Vá até a tela **Nota Fiscal de Saída** da empresa em que as notas foram importadas.
2. **Localize e selecione as notas afetadas**\
   Marque as notas de serviço que foram classificadas como **Anexo III Exterior**.
3. **Selecione a operação "Alterar CFOP"**\
   Clique em **"Selecione a operação"** e escolha a opção **"Alterar CFOP"**.
4. **Clique em "Realizar operação em lote"**\
   Após selecionar a operação, clique no botão **"Realizar operação em lote"** para iniciar a alteração.
5.  **Altere o CFOP na nova tela**

    <figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

    * No campo **CFOP de Origem**, insira o CFOP que foi atribuído incorretamente (ex: **7933**, utilizado para serviços ao exterior)
    * No campo **CFOP de Destino**, insira o CFOP correto da prestação de serviço (ex: **5933**, referente à operação interna).
6. **Confirme a alteração**\
   Finalize o processo clicando em **"Confirmar"**.
