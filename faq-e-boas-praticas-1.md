# FAQ e Boas Práticas

### Para melhor referência, acesse:

{% content-ref url="base-tecnica-1/tour-guiado-de-utilizacao.md" %}
[tour-guiado-de-utilizacao.md](base-tecnica-1/tour-guiado-de-utilizacao.md)
{% endcontent-ref %}

### Validações e Alertas do Sistema

O sistema apresenta mensagens e alertas para identificar inconsistências:

* **Notas não classificadas** — notas que não receberam tipo de operação
* **Divergências** entre imposto devido e imposto destacado na nota

> Esses alertas **não impedem a apuração**, mas indicam pontos que merecem atenção do contador.

***

### Integrações

O Sittax ST pode operar de forma integrada:

* Aos módulos da Sittax (importação via Sittax Simples)
* Ao NF Monitor para importação automática de notas

> No momento, **não há geração de arquivos SPED** no Sittax ST. O foco é apuração e conferência dos tributos — a geração de guias está prevista em evolução futura.

***

### Boas Práticas de Uso

* Garantir a importação de **todas** as notas interestaduais antes de calcular
* Classificar corretamente a finalidade das notas (revenda vs uso e consumo)
* Conferir periodicamente as regras tributárias aplicadas
* Utilizar o **relatório de conferência** antes da geração de guias
* Não ignorar os alertas do sistema

***

### Erros Comuns e Como Evitar

| Erro                                          | Como Evitar                                                      |
| --------------------------------------------- | ---------------------------------------------------------------- |
| Não classificar notas de entrada              | Classificar todas as notas antes de executar o cálculo (Etapa 4) |
| Desconsiderar alertas do sistema              | Tratar todos os alertas antes de finalizar a apuração            |
| Não revisar regras tributárias personalizadas | Conferir regras em _Ajustes > Regras Tributárias_ periodicamente |
| Calcular sem importar todas as notas          | Verificar importação completa antes do cálculo (Etapa 3)         |

***

### Perguntas Frequentes

**O Sittax ST substitui o julgamento do contador?**\
Não. O sistema é uma ferramenta de apoio à apuração — a responsabilidade pela validação das informações, regras e resultados é sempre do contador.

**O sistema gera guias automaticamente?**\
Essa funcionalidade está prevista para evolução futura. Na versão atual, a geração de guias é manual.

**É possível personalizar regras?**\
Sim. Regras e fórmulas podem ser ajustadas conforme o entendimento tributário do contador — por escritório ou por empresa específica. Ver Etapas 11 e 12 do 03&#x20;

{% content-ref url="base-tecnica-1/tour-guiado-de-utilizacao.md" %}
[tour-guiado-de-utilizacao.md](base-tecnica-1/tour-guiado-de-utilizacao.md)
{% endcontent-ref %}

**O sistema apura Antecipação Tributária?**\
Não na versão atual. A arquitetura está preparada para incorporar essa funcionalidade em evolução futura.

**Quais regimes tributários são suportados?**\
Todos — diferente do Sittax Simples, o Sittax ST atende empresas de qualquer regime (Simples Nacional, Lucro Presumido, Lucro Real).
