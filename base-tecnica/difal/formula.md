# Fórmula

O menu de Fórmulas do DIFAL consistem em métodos de cálculos separados por filtros específicos. Ao abrir o painel, podemos visualizar a seguinte tela:

<figure><img src="../../.gitbook/assets/image (173).png" alt=""><figcaption></figcaption></figure>

A tela de Fórmulas do DIFAL são separadas entre três filtros, eles são:

<figure><img src="../../.gitbook/assets/image (174).png" alt=""><figcaption></figcaption></figure>

Ambos operam da mesma maneira, permitindo criar fórmulas de cálculo gerais que, vinculadas ao escritório, se aplicam a todas as empresas cadastradas ou, mais especificamente, por empresas, sendo aplicada diretamente e unicamente na empresa vinculada à fórmula.

Para editar uma regra já existente, basta clicar no corpo do registro dentro da própria visualização das regras existentes, conforme o exemplo:\


<figure><img src="../../.gitbook/assets/image (175).png" alt=""><figcaption></figcaption></figure>

### Cadastrando uma nova fórmula

Para realizar o cadastro de uma nova fórmula basta clicar no ícone preto "Adicionar" no canto superior esquerdo da imagem e, logo em seguida, visualizar a seguinte aba:

<figure><img src="../../.gitbook/assets/image (177).png" alt=""><figcaption></figcaption></figure>

Observação: Caso seja selecionado para criar uma nova fórmula para uma empresa específica, um segundo campo chamado "Empresa" será disponibilizado abaixo do "Estado" para realizar a seleção.

Após a visualização do painel, é possível checar quais fórmulas já existem e cadastrar uma nova no botão laranja "Adicionar".\
Ao clicar em adicionar, o seguinte campo será disponibilizado:\


<figure><img src="../../.gitbook/assets/image (178).png" alt=""><figcaption></figcaption></figure>

Para realizar o preenchimento, basta preencher os seguintes campos:\


**1. Operação DIFAL**

* Esse campo permite definir o tipo de notas de entradapara a qual a fórmula será aplicada: "Mercadoria para Revenda" ou "Uso Consumo/Imobilizado".

**2. Composição Valor Item**

* Aqui você pode selecionar quais elementos devem compor o valor do item para o cálculo do DIFAL. As opções incluem:
  * Outras Despesas
  * Desconto
  * Seguro
  * Frete
  * IPI

**3. Percentual Fixo**

* Ativando esta opção, você pode utilizar um percentual fixo no cálculo do DIFAL. É uma escolha que pode ser ajustada conforme necessário. Em caso de ativação, as seguintes opções serão mostradas:

<figure><img src="../../.gitbook/assets/image (179).png" alt=""><figcaption></figcaption></figure>

Deste modo, é possível identificar quais produtos serão considerados dentre nacionais e importados, determinando um percentual fixo para o cálculo e os valores.

**4. Composição de Origem do Item**

* Esta seção define como será composta a origem do item para o cálculo do DIFAL e sua prioridade, com três opções principais:

<figure><img src="../../.gitbook/assets/image (180).png" alt=""><figcaption></figcaption></figure>

\
Observação: Existe um ícone "?" ao lado de cada item que especifica como funcionará a prioridade do cálculo.

* **Origem ICMS**: Baseia-se na origem do ICMS.
* **Alíquota do ICMS**: Considera apenas a alíquota do ICMS.
* **Origem + Alíquota do ICMS**: Combina a origem e a alíquota do ICMS.

**5. Diferenciar Cálculo Simples / Real e Presumido**

* Aqui, você pode ativar a opção de diferenciar o cálculo para os regimes tributários Simples Nacional, Real e Presumido. Isso garante que o cálculo seja adequado ao regime específico da empresa.

**6. Fórmula Simples**

*   Neste campo, você pode inserir uma fórmula personalizada para o cálculo do DIFAL. A fórmula pode usar variáveis como:

    * **ValorItem**
    * **AliquotaInterna**
    * **AliquotaExterna**
    * **AliquotaInterestadual**
    * **AliquotaFECOEP**
    * **AliquotaBeneficio**\


    **Exemplo:**&#x20;

    <figure><img src="../../.gitbook/assets/image (181).png" alt=""><figcaption><p>Fórmula Padrão de cálculo do Simples Nacional</p></figcaption></figure>



(({ValorItem} - ({ValorItem} \* {AliquotaInterestadual})) / (1 - {AliquotaInterna})) \* {AliquotaInterna} - ({ValorItem} \* {AliquotaInterestadual})\
\
\
Após o preenchimento, basta clicar em salvar e a nova fórmula estará ativa.
