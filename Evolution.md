# :atom_symbol: Evolução

## Ciclos
O desenvolvimento de Workflow está organizado em ciclos:

<details>
<summary>Ciclo Alfa</summary>

Inicialmente escrito para o legado Prompt de Comando, o desenvolvimento de Workflow tem início no segundo semestre de 2021 com o _Ciclo Alfa_, período de aprendizagem da linguagem shell script, construção do núcleo do software e execução dos primeiros testes. Posteriormente portado para PowerShell 5.1, o algoritmo ganhou em complexidade e compatibilidade.

O universo de Tron criado por Steven Lisberger foi uma clara inspiração na construção do projeto desde as primeiras linhas de código. Há diversos easter eggs espalhados pelo algoritmo e interface das versões iniciais, no entanto elas não foram publicadas.

Ao longo do ano, a cadência no lançamento de novas versões trouxe funcionalidades e avanços significativos ao software como o suporte ao PowerShell 7.0 e a codificação de caracteres [UTF8NoBom](https://github.com/2uj1m28ohz/Database/blob/main/Development/CharacterEncoding.md), atualização de elementos da interface, migração para o formato de versionamento [CalVer](https://github.com/2uj1m28ohz/Database/blob/main/Development/SoftwareVersioning.md), suporte à compressão de dados, e a escolha de uma licença de software livre.

```
                        21.1.1-001                                         21.001.1
♦─────── SemVer ─────────┬─┬─┬──┬───────────────────── › CalVer V1 ─────────┬──┬──┬────────────────────────────── ›
                         │ │ │  └─┤ Build                                   │  │  └─┤ Revisão
                         │ │ └────┤ Patch                                   │  └────┤ Dia absoluto do ano
                         │ └──────┤ Minor                                   └───────┤ Ano
                         └────────┤ Major
```

</details>

<details>
<summary>Ciclo Beta</summary>

Após seis meses de desenvolvimento, Workflow deixou de ser um software restrito e ganhou um repositório no GitHub, sendo publicado sob a GPL-3.0.

A partir de então iniciou-se um importante período de transição e implementação conhecido como _Ciclo Beta_, onde a refatoração constante do código possibilitado pelo lançamento de novas versões com o intervalo de apenas dez dias aplicou os conceitos da filosofia [Clean Code](https://github.com/2uj1m28ohz/Database/blob/main/Development/SoftwareDesign.md) e da metodologia ágil [Extreme Programming](https://github.com/2uj1m28ohz/Database/blob/main/Development/AgileMethodologies.md) para aprimorar a qualidade do algoritmo e introduzir novos recursos, entre eles o Registro de Eventos, instalação e atualização automáticas a partir do repositório, e a Verificação de Integridade que detecta e corrige alterações ilegais de algoritmo, recursos estes que permitem maior controle, segurança, velocidade e confiabilidade na entrega atualizações.

A interface recebeu refinamentos através de duas grandes versões que atualizaram os elementos existentes e adicionaram temas. Os fundamentos instituídos pelas Diretrizes de Interface determinam intuitividade, unidade e minimalismo como alguns dos requisitos da experiência do usuário. Tendo em mente que uma [CLI](https://github.com/2uj1m28ohz/Database/blob/main/Development/Interface.md) está limitada às possiblidades do terminal que a executa, é importante criar os próprios elementos, fluxos e estudar a palheta de cores legível pelo terminal a fim de criar um layout consistente e agradável. "_Design não é apenas aparência, design é sobre como as coisas funcionam._" - Steve Jobs.

Para elevar o nível do projeto, o arquivo Readme no formato TXT presente no pacote de software foi substituído pelo formato interativo HTML/CSS.

</details>

<details>
<summary>Ciclo Gama</summary>

Gama foi um importante ciclo de amadurecimento de software, quando dezenas de novos recursos conduziram Workflow à um nível de qualidade nunca antes visto, potencializado pela adocação da metodologia ágil [Scrum](https://github.com/2uj1m28ohz/Database/blob/main/Development/AgileMethodologies.md) que proporcionou um intervalo de planejamento maior e atualizações ainda mais sólidas. As principais alterações incluem:

- Geral
    - Porte do código-fonte para EN-US
    - Carregamento do software a partir da home do usuário
    - Bloqueio de software em caso de comprometimento de integridade

- Interface
    - Nova tela de carregamento
    - Nova tela de encerramento

- Backup
    - Unificação das rotinas de backup
    - Overview da rotina de backup
    - Estimativa do tamanho do backup
    - Suporte ao Google Drive
    - Suporte ao iCloud Drive
    - Suporte ao Dropbox
    - Suporte a multidispositivos
    - Suporte a multiusuários
    - Configuração do período de retenção
    - Verificação da saúde do drive de backup
    - Suporte à tabela de partições GPT no drive de backup
    - Suporte ao sistema de arquivos NTFS no drive de backup
    - Suporte à clusters de 64KB no drive de backup
    - Exibe o tempo total de execução

- Réplica
    - Replicação do backup de dados
    - Verificação da saúde do drive de réplica
    - Suporte à tabela de partições GPT no drive de réplica
    - Suporte ao sistema de arquivos NTFS no drive de réplica
    - Suporte à clusters de 64KB no drive de réplica
    - Exibe o tempo total de execução

- Compressão
    - Configuração da taxa de compressão de dados
    - Configuração do uso de memória
    - Suporte ao modo sólido
    - Suporte ao processamento multithread

- Configurações
    - Gerenciamento inteligente de configurações
    - Importação e exportação de configurações

</details>

<details>
<summary>Ciclo Delta</summary>

No _Ciclo Delta_ Workflow receberá aprimoramentos nos elementos, fluxos e conceitos já introduzidos, e expandirá a disponibilidade de recursos enquanto mantém sua [Arquitetura Monolítica](https://github.com/2uj1m28ohz/Database/blob/main/Development/SoftwareArchitecture.md). De forma geral, monólitos são convenientes por facilitar a sobrecarga cognitiva de gerenciamento de código e favorecer a velocidade de todas as etapas do software, do desenvolvimento à execução.

O versionamento de software é o processo de controlar e gerenciar diferentes versões de um programa ou sistema ao longo do tempo. Ele é essencial por registrar e refletir as mudanças feitas no código-fonte de um software duarnte a evolução do projeto. O formato de versionamento CalVer V2 foi planejado para simplificar a identificação de versão.

```
                             23.001.1                                                   24.01.1
‹ ──────── CalVer V1 ─────────┬──┬──┬────────────────────────────── › CalVer V2 ─────────┬──┬─┬──────────────────♦
                              │  │  └─┤ Revisão                                          │  │ └─┤ Revisão
                              │  └────┤ Dia absoluto do ano                              │  └───┤ Mês
                              └───────┤ Ano                                              └──────┤ Ano
```

Os ciclos anteriores foram fundamentais na construção de um software robusto e inteligente. Não será diferente em 2024.

</details>

## Lançamentos
|Ciclo|Sprint|Versão    |Data      |Suporte        |Windows|PowerShell|7-Zip|Linhas |Sub-rotinas|
|:---:|:----:|:--------:|:--------:|:-------------:|:-----:|:--------:|:---:|:-----:|:---------:|
|Delta|70    |24.07.1   |07/07/2024|:green_circle: |10 22H2|7.4.0     |23.01|4682   |165        |
|Delta|69    |24.06.1   |02/06/2024|:green_circle: |10 22H2|7.4.0     |23.01|4623   |167        |
|Delta|68    |24.05.1   |05/05/2024|:yellow_circle:|10 22H2|7.4.0     |23.01|4618   |167        |
|Delta|67    |24.04.1   |07/04/2024|:red_circle:   |10 22H2|7.4.0     |23.01|4812   |178        |
|Delta|66    |24.03.1   |03/03/2024|:red_circle:   |10 22H2|7.4.0     |23.01|5286   |206        |
|Delta|65    |24.02.1   |04/02/2024|:red_circle:   |10 22H2|7.4.0     |23.01|4846   |208        |
|Delta|64    |24.01.1   |02/01/2024|:red_circle:   |10 22H2|7.4.0     |23.01|4634   |203        |
|Gama |63    |23.340.1  |06/12/2023|:red_circle:   |10 22H2|7.3.6     |23.01|4402   |198        |
|Gama |62    |23.310.1  |06/11/2023|:red_circle:   |10 22H2|7.3.5     |23.01|4219   |191        |
|Gama |61    |23.280.1  |07/10/2023|:red_circle:   |10 22H2|7.3.4     |23.01|4285   |193        |
|Gama |60    |23.250.1  |07/09/2023|:red_circle:   |10 22H2|7.3.3     |23.01|4455   |201        |
|Gama |59    |23.220.1  |08/08/2023|:red_circle:   |10 22H2|7.3.2     |22.01|4110   |189        |
|Gama |58    |23.190.1  |09/07/2023|:red_circle:   |10 22H2|7.3.1     |22.01|4191   |197        |
|Gama |57    |23.160.1  |09/06/2023|:red_circle:   |10 21H2|7.3.0     |22.00|4330   |189        |
|Gama |56    |23.130.1  |10/05/2023|:red_circle:   |10 21H2|7.3.0     |22.00|4459   |167        |
|Gama |55    |23.100.1  |10/04/2023|:red_circle:   |10 21H2|7.3.0     |22.00|4380   |145        |
|Gama |54    |23.070.1  |11/03/2023|:red_circle:   |10 21H2|7.3.0     |22.00|4146   |141        |
|Gama |53    |23.040.1  |09/02/2023|:red_circle:   |10 21H2|7.3.0     |22.00|3842   |110        |
|Gama |52    |23.010.1  |10/01/2023|:red_circle:   |10 21H2|7.2.5     |22.00|4353   |121        |
|Beta |51    |22.340.1  |06/12/2022|:red_circle:   |10 21H1|7.2.0     |22.00|4074   |119        |
|Beta |50    |22.310.1  |06/11/2022|:red_circle:   |10 21H1|7.2.0     |22.00|3839   |110        |
|Beta |49    |22.280.1  |07/10/2022|:red_circle:   |10 21H1|7.2.0     |22.00|3875   |111        |
|Beta |48    |22.260.1  |17/09/2022|:red_circle:   |10 21H1|7.2.0     |22.00|3801   |111        |
|Beta |47    |22.250.1  |07/09/2022|:red_circle:   |10 20H2|7.2.0     |22.00|3664   |100        |
|Beta |46    |22.230.1  |18/08/2022|:red_circle:   |10 2004|7.2.0     |22.00|3222   |88         |
|Beta |45    |22.190.2  |09/07/2022|:red_circle:   |10 1909|7.2.0     |21.07|3130   |86         |
|Beta |44    |22.190.1  |09/07/2022|:red_circle:   |10 1909|7.2.0     |21.07|3080   |87         |
|Beta |43    |22.130.1  |10/05/2022|:red_circle:   |10 1903|7.2.0     |21.07|3010   |86         |
|Beta |42    |22.120.1  |30/04/2022|:red_circle:   |10 1809|7.2.0     |21.07|3128   |85         |
|Beta |41    |22.110.1  |21/04/2022|:red_circle:   |10 1803|7.2.0     |21.07|3084   |86         |
|Beta |40    |22.100.1  |10/04/2022|:red_circle:   |10 1709|7.2.0     |21.07|3025   |85         |
|Beta |39    |22.090.1  |30/03/2022|:red_circle:   |10 1703|7.2.0     |21.07|3003   |85         |
|Beta |38    |22.080.1  |21/03/2022|:red_circle:   |10 1607|7.2.0     |21.07|2805   |80         |
|Beta |37    |22.070.1  |11/03/2022|:red_circle:   |10 1511|7.2.0     |21.07|2646   |75         |
|Beta |36    |22.60.1   |01/03/2022|:red_circle:   |10 1507|7.2.0     |21.07|2495   |72         |
|Beta |35    |22.50.1   |19/02/2022|:red_circle:   |10 1507|7.2.0     |21.07|2307   |68         |
|Beta |34    |22.40.1   |09/02/2022|:red_circle:   |10 1507|7.2.0     |21.07|1631   |52         |
|Beta |33    |22.30.1   |30/01/2022|:red_circle:   |10 1507|7.2.0     |21.07|1506   |42         |
|Beta |32    |22.20.1   |20/01/2022|:red_circle:   |10 1507|7.2.0     |21.06|1426   |39         |
|Beta |31    |22.10.1   |10/01/2022|:red_circle:   |10 1507|7.1.0     |19.00|1375   |38         |
|Beta |30    |22.1.1    |01/01/2022|:red_circle:   |10 1507|7.0.0     |     |1364   |24         |
|Alfa |29    |21.330.1  |23/11/2021|:red_circle:   |10 1507|5.1.0     |     |1189   |22         |
|Alfa |28    |21.323.1  |19/11/2021|:red_circle:   |10 1507|5.1.0     |     |1019   |21         |
|Alfa |27    |21.319.1  |15/11/2021|:red_circle:   |10 1507|5.1.0     |     |851    |23         |
|Alfa |26    |21.313.1  |09/11/2021|:red_circle:   |10 1507|5.1.0     |     |732    |22         |
|Alfa |25    |21.311.1  |07/11/2021|:red_circle:   |10 1507|5.1.0     |     |697    |22         |
|Alfa |24    |20.6.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |675    |22         |
|Alfa |23    |19.9.2-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |648    |21         |
|Alfa |22    |18.9.3-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |820    |20         |
|Alfa |21    |17.9.5-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |641    |19         |
|Alfa |20    |16.9.1-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |529    |18         |
|Alfa |19    |15.9.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |518    |17         |
|Alfa |18    |14.9.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |473    |16         |
|Alfa |17    |13.9.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |463    |15         |
|Alfa |16    |12.7.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |371    |14         |
|Alfa |15    |11.5.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |357    |13         |
|Alfa |14    |10.9.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |344    |12         |
|Alfa |13    |9.8.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |316    |11         |
|Alfa |12    |8.8.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |280    |10         |
|Alfa |11    |7.1.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |264    |9          |
|Alfa |10    |6.5.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |251    |8          |
|Alfa |9     |5.7.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |232    |7          |
|Alfa |8     |5.3.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |228    |7          |
|Alfa |7     |4.9.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |212    |6          |
|Alfa |6     |3.7.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |150    |5          |
|Alfa |5     |2.13.0-002|2021/2    |:red_circle:   |10 1507|5.1.0     |     |127    |4          |
|Alfa |4     |2.13.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |127    |4          |
|Alfa |3     |1.8.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |94     |3          |
|Alfa |2     |1.7.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |92     |3          |
|Alfa |1     |0.9.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |105    |5          |

> - :green_circle: Suporte ativo
> - :yellow_circle: Suporte próximo do fim
> - :red_circle: Suporte inativo

> Verifique a [Política de Suporte](https://github.com/2uj1m28ohz/Workflow/blob/main/SUPPORT.md) para mais informações.
