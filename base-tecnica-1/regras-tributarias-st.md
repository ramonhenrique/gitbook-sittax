# Regras Tributárias ST

<figure><img src="../.gitbook/assets/image (350).png" alt=""><figcaption></figcaption></figure>

### MVA Original e MVA Ajustada

A **MVA (Margem de Valor Agregado)** é utilizada para compor a base de cálculo do ICMS ST.

O Sittax ST apresenta de forma transparente:

| MVA              | Origem                                     |
| ---------------- | ------------------------------------------ |
| **MVA Original** | Definida conforme legislação aplicável     |
| **MVA Ajustada** | Calculada automaticamente quando aplicável |

<figure><img src="../.gitbook/assets/image (352).png" alt=""><figcaption></figcaption></figure>

Ambos os valores são exibidos ao usuário para conferência e validação.

***

### Base de Cálculo do ICMS ST

A base de cálculo é formada a partir do valor da mercadoria, acrescido dos componentes previstos na legislação vigente:

```
Base ST = Valor da mercadoria
        + Frete
        + Seguro
        + Outros encargos (quando aplicáveis)
        × (1 + MVA)
```

O sistema demonstra de forma clara quais valores compõem cada base de cálculo utilizada — acessível no **Detalhamento do Item** (Etapa 7 do Tour Guiado).

***

### Tratamento de Exceções

O Sittax ST contempla tratamentos específicos conforme:

* **Unidade Federativa** — regras distintas por estado
* **NCM** — produto sujeito ou não à ST em cada UF
* **Tipo de imposto** — ST vs DIFAL vs DIFAL Revenda

As exceções são aplicadas automaticamente com base nas regras tributárias cadastradas e podem ser **personalizadas** pelo usuário em **Ajustes > Regras Tributárias** (Etapas 9 e 11 do Tour Guiado).

***

### Personalização de Fórmulas

As fórmulas de cálculo podem ser ajustadas:

* **Por escritório** — aplica a todos os clientes
* **Por empresa** — sobrescreve a fórmula do escritório para aquela empresa especificamente
