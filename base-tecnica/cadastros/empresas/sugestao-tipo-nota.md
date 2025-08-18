# Sugestão Tipo Nota

No Sittax, a operação principal e inicial relacionada às notas de entrada é a Classificação das Notas. Para facilitar esse processo, o campo "Sugestão Tipo Nota" permite a parametrização de regras de classificação automática. Com ele, é possível vincular fornecedores e itens a um tipo específico de classificação, automatizando a categorização das notas. Essa funcionalidade otimiza o processo, reduzindo erros e aumentando a eficiência no gerenciamento das notas fiscais.

<figure><img src="../../../.gitbook/assets/image (78).png" alt=""><figcaption></figcaption></figure>

Ao abrir o menu de "Sugestão Tipo Nota" será possível visualizar as regras já criadas, constando as informações dessas regras dentro das colunas. Para adicionar uma nova regra, basta clicar no botão preto "Adicionar", onde será aberto o seguinte painel:

<figure><img src="../../../.gitbook/assets/image (79).png" alt=""><figcaption></figcaption></figure>

#### Flexibilidade dos Filtros

Como existem filtros que não são obrigatórios, é possível criar uma variedade de regras. Você pode configurar filtros mais abrangentes, que fazem&#x20;

com que todas as notas de entrada sejam classificadas com o mesmo tipo de nota. Alternativamente, é possível configurar filtros mais detalhados preenchendo e configurando todos os campos, permitindo que a regra aplique filtros específicos para CFOP, NCM ou códigos de itens, alterando esses itens para o tipo selecionado.\
\
Para realizar uma parametrização **global**, que se aplicará para todas as notas de um fornecedor, utilize:

1. **CNPJ do Fornecedor**: Preencha o CNPJ desejado para aplicar a regra. Se deixar em branco, o sistema interpretará como uma regra geral.
2. **Nome do Fornecedor**: Insira a razão social do fornecedor. Se o CNPJ não for preenchido, o sistema usará o nome para filtrar as notas de entrada importadas.
3. **Tipo da Nota**: Indique o tipo de nota para o qual a regra irá converter. Quando a regra filtrar com base no CNPJ ou nome do fornecedor, todas as notas importadas serão alteradas para este tip

***

Para criar uma parametrização específica para **Itens**, **CFOPs** e **NCMs** de sua escolha, basta deixar os itens acima desmarcados e preencher os seguintes campos:

1. **Tipo**: Utilize este campo para um filtro mais específico, como CFOP, NCM ou código de item. Este campo é opcional.
2. **Informe o Código**: Se você preencheu o campo "Tipo", insira aqui o código específico (CFOP, NCM ou código do item) que será utilizado para a regra.
3. **Tipo do Item**: Defina o tipo de item para o qual a natureza será alterada, considerando os campos anteriores.

#### Considerações Importantes

* Os campos "Tipo", "Informe o Código" e "Tipo do Item" sobrepõem a configuração geral de notas por fornecedor, aplicando a regra somente aos itens específicos que forem adicionados às regras.
* Não há limite para a quantidade de regras que podem ser criadas, permitindo flexibilidade para atender a diferentes objetivos e necessidades.

Ao seguir esses passos e configurar corretamente, você assegura que as notas de entrada sejam automaticamente classificadas conforme as regras estabelecidas, otimizando o processo de importação e classificação.\
\
Em caso de dúvidas, assista:
