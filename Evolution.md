# :atom_symbol: Evolução
Workflow foi criado a partir da necessidade de executar backup de dados e rotinas de manutenção do sistema de forma centralizada, ágil e eficiente para otimizar a segurança de dados e a resiliência do sistema. A automação intrínseca elimina a necessidade de intervenção humana, reduzindo drasticamente a margem de erros. Através do PowerShell, Workflow torna-se extremamente flexível, permitindo a criação de funcionalidades que se adaptem a diferentes plataformas, arquiteturas e necessidades.

## Tecnologias
Inicialmente escrito em PT-BR utilizando a linguagem Shell Script para o legado Prompt de Comando, foi posteriormente portado para PowerShell. Neste processo foi necessário substituir a [Codificação de Caracteres](https://github.com/2uj1m28ohz/Database/blob/main/Development/CharacterEncoding.md), alterações estas que aprimoraram significativamente a compatibilidade e a confiabilidade do software.

O suporte ao 7-Zip foi adicionado para implementar recursos eficientes de compressão de dados utilizando algoritmos e formato modernos, análise de arquivos, aplicação de filtros, compressão sólida, entre outros métodos avançados para reduzir o tamanho do backup de dados e do empacotamento de software.

## Métodos
O desenvolvimento de Workflow envolveu a tradução do código-fonte para EN-US somado à adoção de metodologias ágeis como [Extreme Programming](https://github.com/2uj1m28ohz/Database/blob/main/Development/AgileMethodologies.md) e atualmente [Scrum](https://github.com/2uj1m28ohz/Database/blob/main/Development/AgileMethodologies.md). Esses métodos permitiram um desenvolvimento mais iterativo e ágil, aplicando os princípios da filosofia [Clean Code](https://github.com/2uj1m28ohz/Database/blob/main/Development/SoftwareDesign.md) para aperfeiçoar a qualidade do código. O sistema de [Versionamento de Software](https://github.com/2uj1m28ohz/Database/blob/main/Development/SoftwareVersioning.md) evoluiu do SemVer (Versionamento Semântico) para o CalVer (Versionamento por Calendário), o que simplificou a identificação de versões.

```
                        21.1.1-001                                      24.01.1
♦─────── SemVer ─────────┬─┬─┬──┬───────────────────── › CalVer ─────────┬──┬─┬──────────────────♦
                         │ │ │  └─┤ Build                                │  │ └─┤ Revisão
                         │ │ └────┤ Patch                                │  └───┤ Mês
                         │ └──────┤ Minor                                └──────┤ Ano
                         └────────┤ Major
```

> O versionamento de software é o processo de controlar e gerenciar diferentes versões de um programa ou sistema ao longo do tempo. Ele é essencial por registrar e refletir as mudanças feitas no código-fonte de um software duarnte a evolução do projeto.

## Interface
A interface do Workflow foi fortemente influenciada pelo universo de Tron criado por Steven Lisberger, com diversos easter eggs espalhados pelo algoritmo e interface das versões iniciais, embora não tenham sido publicadas. O design atual respeita as Diretrizes de Interface que determinam intuitividade, unidade e minimalismo como alguns dos requisitos da experiência do usuário, guiando assim elementos, fluxos e conceitos.

O estudo da paleta de cores disponível na [CLI](https://github.com/2uj1m28ohz/Database/blob/main/Development/Interface.md) foi essencial para construir um layout consistente e agradável. Atualizações posteriores introduziram novos temas elevando a flexibilidade da interface.

> _Design não é apenas aparência, design é sobre como as coisas funcionam._ - Steve Jobs

## Segurança
Segurança é a característica central na lógica do algoritmo de Workflow. Para atender à este requisito, foram implementados diversos recursos críticos como o Registro de Eventos para monitorar as operações do software; instalação e atualização automáticas a partir do GitHub, projetadas para garantir controle, segurança, velocidade e confiabilidade na entrega de atualizações; e a Verificação de Integridade, incorporada para identificar e corrigir alterações ilegais no algoritmo, garantindo a constante integridade do software.

## Inteligência
A adoção de inteligência artificial proporcionou um salto notável no aprendizado e desenvolvimento de Workflow, automatizando tarefas complexas e facilitando a tomada de decisões. Ao mesmo tempo, a inteligência natural humana desempenhou um papel crucial nos aprimoramentos constantes do software, garantindo que cada atualização do algoritmo não apenas aumentasse sua qualidade e confiabilidade, mas também mantivesse a visão e os objetivos originais do projeto. A combinação dessas inteligências resultou em um software robusto e adaptável às necessidades em constante evolução.

## Lançamentos
Workflow é constantemente redesenhado para introduzir e aprimorar funcionalidades e recursos enquanto mantém sua [Arquitetura Monolítica](https://github.com/2uj1m28ohz/Database/blob/main/Development/SoftwareArchitecture.md). De forma geral, monólitos são convenientes por facilitar a sobrecarga cognitiva de gerenciamento de código e favorecer a velocidade em todas as etapas do software, do desenvolvimento à execução.

|Sprint|Versão    |Data      |Suporte        |Windows|PowerShell|7-Zip|Linhas |Sub-rotinas|
|:----:|:--------:|:--------:|:-------------:|:-----:|:--------:|:---:|:-----:|:---------:|
|72    |24.09.1   |01/09/2024|:green_circle: |10 22H2|7.4.0     |24.07|4520   |163        |
|71    |24.08.1   |04/08/2024|:green_circle: |10 22H2|7.4.0     |24.07|4504   |160        |
|70    |24.07.1   |07/07/2024|:yellow_circle:|10 22H2|7.4.0     |23.01|4682   |165        |
|69    |24.06.1   |02/06/2024|:red_circle:   |10 22H2|7.4.0     |23.01|4623   |167        |
|68    |24.05.1   |05/05/2024|:red_circle:   |10 22H2|7.4.0     |23.01|4618   |167        |
|67    |24.04.1   |07/04/2024|:red_circle:   |10 22H2|7.4.0     |23.01|4812   |178        |
|66    |24.03.1   |03/03/2024|:red_circle:   |10 22H2|7.4.0     |23.01|5286   |206        |
|65    |24.02.1   |04/02/2024|:red_circle:   |10 22H2|7.4.0     |23.01|4846   |208        |
|64    |24.01.1   |02/01/2024|:red_circle:   |10 22H2|7.4.0     |23.01|4634   |203        |
|63    |23.340.1  |06/12/2023|:red_circle:   |10 22H2|7.3.6     |23.01|4402   |198        |
|62    |23.310.1  |06/11/2023|:red_circle:   |10 22H2|7.3.5     |23.01|4219   |191        |
|61    |23.280.1  |07/10/2023|:red_circle:   |10 22H2|7.3.4     |23.01|4285   |193        |
|60    |23.250.1  |07/09/2023|:red_circle:   |10 22H2|7.3.3     |23.01|4455   |201        |
|59    |23.220.1  |08/08/2023|:red_circle:   |10 22H2|7.3.2     |22.01|4110   |189        |
|58    |23.190.1  |09/07/2023|:red_circle:   |10 22H2|7.3.1     |22.01|4191   |197        |
|57    |23.160.1  |09/06/2023|:red_circle:   |10 21H2|7.3.0     |22.00|4330   |189        |
|56    |23.130.1  |10/05/2023|:red_circle:   |10 21H2|7.3.0     |22.00|4459   |167        |
|55    |23.100.1  |10/04/2023|:red_circle:   |10 21H2|7.3.0     |22.00|4380   |145        |
|54    |23.070.1  |11/03/2023|:red_circle:   |10 21H2|7.3.0     |22.00|4146   |141        |
|53    |23.040.1  |09/02/2023|:red_circle:   |10 21H2|7.3.0     |22.00|3842   |110        |
|52    |23.010.1  |10/01/2023|:red_circle:   |10 21H2|7.2.5     |22.00|4353   |121        |
|51    |22.340.1  |06/12/2022|:red_circle:   |10 21H1|7.2.0     |22.00|4074   |119        |
|50    |22.310.1  |06/11/2022|:red_circle:   |10 21H1|7.2.0     |22.00|3839   |110        |
|49    |22.280.1  |07/10/2022|:red_circle:   |10 21H1|7.2.0     |22.00|3875   |111        |
|48    |22.260.1  |17/09/2022|:red_circle:   |10 21H1|7.2.0     |22.00|3801   |111        |
|47    |22.250.1  |07/09/2022|:red_circle:   |10 20H2|7.2.0     |22.00|3664   |100        |
|46    |22.230.1  |18/08/2022|:red_circle:   |10 2004|7.2.0     |22.00|3222   |88         |
|45    |22.190.2  |09/07/2022|:red_circle:   |10 1909|7.2.0     |21.07|3130   |86         |
|44    |22.190.1  |09/07/2022|:red_circle:   |10 1909|7.2.0     |21.07|3080   |87         |
|43    |22.130.1  |10/05/2022|:red_circle:   |10 1903|7.2.0     |21.07|3010   |86         |
|42    |22.120.1  |30/04/2022|:red_circle:   |10 1809|7.2.0     |21.07|3128   |85         |
|41    |22.110.1  |21/04/2022|:red_circle:   |10 1803|7.2.0     |21.07|3084   |86         |
|40    |22.100.1  |10/04/2022|:red_circle:   |10 1709|7.2.0     |21.07|3025   |85         |
|39    |22.090.1  |30/03/2022|:red_circle:   |10 1703|7.2.0     |21.07|3003   |85         |
|38    |22.080.1  |21/03/2022|:red_circle:   |10 1607|7.2.0     |21.07|2805   |80         |
|37    |22.070.1  |11/03/2022|:red_circle:   |10 1511|7.2.0     |21.07|2646   |75         |
|36    |22.60.1   |01/03/2022|:red_circle:   |10 1507|7.2.0     |21.07|2495   |72         |
|35    |22.50.1   |19/02/2022|:red_circle:   |10 1507|7.2.0     |21.07|2307   |68         |
|34    |22.40.1   |09/02/2022|:red_circle:   |10 1507|7.2.0     |21.07|1631   |52         |
|33    |22.30.1   |30/01/2022|:red_circle:   |10 1507|7.2.0     |21.07|1506   |42         |
|32    |22.20.1   |20/01/2022|:red_circle:   |10 1507|7.2.0     |21.06|1426   |39         |
|31    |22.10.1   |10/01/2022|:red_circle:   |10 1507|7.1.0     |19.00|1375   |38         |
|30    |22.1.1    |01/01/2022|:red_circle:   |10 1507|7.0.0     |     |1364   |24         |
|29    |21.330.1  |23/11/2021|:red_circle:   |10 1507|5.1.0     |     |1189   |22         |
|28    |21.323.1  |19/11/2021|:red_circle:   |10 1507|5.1.0     |     |1019   |21         |
|27    |21.319.1  |15/11/2021|:red_circle:   |10 1507|5.1.0     |     |851    |23         |
|26    |21.313.1  |09/11/2021|:red_circle:   |10 1507|5.1.0     |     |732    |22         |
|25    |21.311.1  |07/11/2021|:red_circle:   |10 1507|5.1.0     |     |697    |22         |
|24    |20.6.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |675    |22         |
|23    |19.9.2-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |648    |21         |
|22    |18.9.3-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |820    |20         |
|21    |17.9.5-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |641    |19         |
|20    |16.9.1-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |529    |18         |
|19    |15.9.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |518    |17         |
|18    |14.9.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |473    |16         |
|17    |13.9.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |463    |15         |
|16    |12.7.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |371    |14         |
|15    |11.5.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |357    |13         |
|14    |10.9.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |344    |12         |
|13    |9.8.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |316    |11         |
|12    |8.8.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |280    |10         |
|11    |7.1.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |264    |9          |
|10    |6.5.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |251    |8          |
|9     |5.7.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |232    |7          |
|8     |5.3.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |228    |7          |
|7     |4.9.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |212    |6          |
|6     |3.7.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |150    |5          |
|5     |2.13.0-002|2021/2    |:red_circle:   |10 1507|5.1.0     |     |127    |4          |
|4     |2.13.0-001|2021/2    |:red_circle:   |10 1507|5.1.0     |     |127    |4          |
|3     |1.8.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |94     |3          |
|2     |1.7.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |92     |3          |
|1     |0.9.0-001 |2021/2    |:red_circle:   |10 1507|5.1.0     |     |105    |5          |

> - :green_circle: Suporte ativo
> - :yellow_circle: Suporte próximo do fim
> - :red_circle: Suporte inativo

> Verifique a [Política de Suporte](https://github.com/2uj1m28ohz/Workflow/blob/main/SUPPORT.md) para mais informações.
