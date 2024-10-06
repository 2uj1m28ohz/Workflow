# :atom_symbol: Evolução
Workflow foi criado a partir da necessidade de executar backup de dados e rotinas de manutenção do sistema de forma centralizada, ágil e eficiente para otimizar a segurança de dados e a resiliência do sistema. A automação intrínseca elimina a necessidade de intervenção humana, reduzindo drasticamente a margem de erros. Através do PowerShell, Workflow torna-se extremamente flexível, permitindo a criação de funcionalidades que se adaptem a diferentes arquiteturas, sistemas e necessidades.

## Tecnologias
Inicialmente escrito em PT-BR utilizando a linguagem Shell Script para o legado Prompt de Comando, foi posteriormente portado para PowerShell. Neste processo foi necessário substituir a [Codificação de Caracteres](https://github.com/2uj1m28ohz/Database/blob/main/SoftwareDevelopment/CharacterEncoding.md), alterações estas que aprimoraram significativamente a compatibilidade e a confiabilidade do software.

O suporte ao 7-Zip foi adicionado para implementar recursos eficientes de compressão de dados utilizando algoritmos e formato modernos, análise de arquivos, aplicação de filtros, compressão sólida, entre outros métodos avançados para reduzir o tamanho do backup de dados e do empacotamento de software.

## Métodos
O desenvolvimento de Workflow envolveu a tradução do código-fonte para EN-US somado à adoção de metodologias ágeis como [Extreme Programming](https://github.com/2uj1m28ohz/Database/blob/main/SoftwareDevelopment/AgileMethodologies.md) e atualmente [Scrum](https://github.com/2uj1m28ohz/Database/blob/main/SoftwareDevelopment/AgileMethodologies.md). Esses métodos permitiram um desenvolvimento mais iterativo e ágil, aplicando os princípios da filosofia [Clean Code](https://github.com/2uj1m28ohz/Database/blob/main/SoftwareDevelopment/SoftwareDesign.md) para aperfeiçoar a qualidade do código. O sistema de [Versionamento de Software](https://github.com/2uj1m28ohz/Database/blob/main/SoftwareDevelopment/SoftwareVersioning.md) evoluiu do SemVer (Versionamento Semântico) para o CalVer (Versionamento por Calendário), o que simplificou a identificação de versões.

```
─────────────── SemVer ─────────────────── › ─────────────── CalVer V1 ────────────── › ─────────────── CalVer V2 ─────────────

─────────────── 21.1.1-001 ─────────────── › ─────────────── 21.001.1 ─────────────── › ─────────────── 24.01.1 ───────────────
                 ┬ ┬ ┬  ┬                                     ┬  ┬  ┬                                    ┬  ┬ ┬
                 │ │ │  │                                     │  │  │                                    │  │ │
                 │ │ │  └─┤ Build                             │  │  └─┤ Revisão                          │  │ └─┤ Revisão
                 │ │ └────┤ Patch                             │  └────┤ Dia absoluto                     │  └───┤ Mês
                 │ └──────┤ Minor                             └───────┤ Ano                              └──────┤ Ano
                 └────────┤ Major
```

> O versionamento de software é o processo de controlar e gerenciar diferentes versões de um programa ou sistema ao longo do tempo. Ele é essencial por registrar e refletir as mudanças feitas no código-fonte de um software duarnte a evolução do projeto.

## Interface
A interface do Workflow foi fortemente influenciada pelo universo de Tron criado por Steven Lisberger, com diversos easter eggs espalhados pelo algoritmo e interface das versões iniciais, embora não tenham sido publicadas. O design atual respeita as Diretrizes de Interface que determinam intuitividade, unidade e minimalismo como alguns dos requisitos da experiência do usuário, guiando assim elementos, fluxos e conceitos.

O estudo da paleta de cores disponível na [CLI](https://github.com/2uj1m28ohz/Database/blob/main/SoftwareDevelopment/Interface.md) foi essencial para construir um layout consistente e agradável. Atualizações posteriores introduziram novos temas elevando a flexibilidade da interface.

> _Design não é apenas aparência, design é sobre como as coisas funcionam._ - Steve Jobs

## Segurança
Segurança é a característica central na lógica do algoritmo de Workflow. Para atender à este requisito, foram implementados diversos recursos críticos como o Registro de Eventos para monitorar as operações do software; instalação e atualização automáticas a partir do GitHub, projetadas para garantir controle, segurança, velocidade e confiabilidade na entrega de atualizações; e a Verificação de Integridade, incorporada para identificar e corrigir alterações ilegais no algoritmo, garantindo a constante integridade do software.

## Inteligência
A adoção de inteligência artificial proporcionou um salto notável no aprendizado e desenvolvimento de Workflow, automatizando tarefas complexas e facilitando a tomada de decisões. Ao mesmo tempo, a inteligência natural humana desempenhou um papel crucial nos aprimoramentos constantes do software, garantindo que cada atualização do algoritmo não apenas aumentasse sua qualidade e confiabilidade, mas também mantivesse a visão e os objetivos originais do projeto. A combinação dessas inteligências resultou em um software robusto e adaptável às necessidades em constante evolução.

## Lançamentos
Workflow é constantemente redesenhado para introduzir e aprimorar recursos e funcionalidades enquanto mantém sua [Arquitetura Monolítica](https://github.com/2uj1m28ohz/Database/blob/main/SoftwareDevelopment/SoftwareArchitecture.md). De forma geral, monólitos são convenientes por facilitar a sobrecarga cognitiva de gerenciamento de código e favorecer a velocidade em todas as etapas do software, do desenvolvimento à execução.

|Sprint|Versão    |Data      |Suporte|Arquiteturas       |Sistemas       |Crescimento|
|:----:|:--------:|:--------:|:-----:|:-----------------:|:-------------:|:---------:|
|73    |24.10.1   |06/10/2024|Sim    |x86/x64/ARM32/ARM64|Windows/Linux  |+09,93%    |
|72    |24.09.1   |01/09/2024|Sim    |x86/x64/ARM32/ARM64|Windows        |+00,36%    |
|71    |24.08.1   |04/08/2024|Sim    |x86/x64/ARM32/ARM64|Windows        |-03,80%    |
|70    |24.07.1   |07/07/2024|Não    |x86/x64/ARM32/ARM64|Windows        |+01,28%    |
|69    |24.06.1   |02/06/2024|Não    |x86/x64/ARM32/ARM64|Windows        |+00,11%    |
|68    |24.05.1   |05/05/2024|Não    |x86/x64/ARM32/ARM64|Windows        |-04,03%    |
|67    |24.04.1   |07/04/2024|Não    |x86/x64/ARM32/ARM64|Windows        |-08,97%    |
|66    |24.03.1   |03/03/2024|Não    |x86/x64/ARM32/ARM64|Windows        |+09,08%    |
|65    |24.02.1   |04/02/2024|Não    |x86/x64/ARM32/ARM64|Windows        |+04,57%    |
|64    |24.01.1   |02/01/2024|Não    |x86/x64/ARM32/ARM64|Windows        |+05,27%    |
|63    |23.340.1  |06/12/2023|Não    |x86/x64/ARM32/ARM64|Windows        |+04,34%    |
|62    |23.310.1  |06/11/2023|Não    |x86/x64/ARM32/ARM64|Windows        |-01,54%    |
|61    |23.280.1  |07/10/2023|Não    |x86/x64/ARM32/ARM64|Windows        |-03,82%    |
|60    |23.250.1  |07/09/2023|Não    |x86/x64/ARM32/ARM64|Windows        |+08,39%    |
|59    |23.220.1  |08/08/2023|Não    |x86/x64/ARM32/ARM64|Windows        |-01,93%    |
|58    |23.190.1  |09/07/2023|Não    |x86/x64/ARM32/ARM64|Windows        |-03,21%    |
|57    |23.160.1  |09/06/2023|Não    |x86/x64/ARM32/ARM64|Windows        |-02,89%    |
|56    |23.130.1  |10/05/2023|Não    |x86/x64/ARM32/ARM64|Windows        |+01,80%    |
|55    |23.100.1  |10/04/2023|Não    |x86/x64/ARM32/ARM64|Windows        |+05,64%    |
|54    |23.070.1  |11/03/2023|Não    |x86/x64/ARM32/ARM64|Windows        |+07,91%    |
|53    |23.040.1  |09/02/2023|Não    |x86/x64/ARM32/ARM64|Windows        |-11,74%    |
|52    |23.010.1  |10/01/2023|Não    |x86/x64/ARM32/ARM64|Windows        |+06,85%    |
|51    |22.340.1  |06/12/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+06,12%    |
|50    |22.310.1  |06/11/2022|Não    |x86/x64/ARM32/ARM64|Windows        |-00,93%    |
|49    |22.280.1  |07/10/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+01,95%    |
|48    |22.260.1  |17/09/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+03,74%    |
|47    |22.250.1  |07/09/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+13,72%    |
|46    |22.230.1  |18/08/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+02,94%    |
|45    |22.190.2  |09/07/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+01,62%    |
|44    |22.190.1  |09/07/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+02,33%    |
|43    |22.130.1  |10/05/2022|Não    |x86/x64/ARM32/ARM64|Windows        |-03,77%    |
|42    |22.120.1  |30/04/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+01,43%    |
|41    |22.110.1  |21/04/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+01,95%    |
|40    |22.100.1  |10/04/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+00,73%    |
|39    |22.090.1  |30/03/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+07,06%    |
|38    |22.080.1  |21/03/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+06,01%    |
|37    |22.070.1  |11/03/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+06,05%    |
|36    |22.60.1   |01/03/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+08,15%    |
|35    |22.50.1   |19/02/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+41,45%    |
|34    |22.40.1   |09/02/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+08,30%    |
|33    |22.30.1   |30/01/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+05,61%    |
|32    |22.20.1   |20/01/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+03,71%    |
|31    |22.10.1   |10/01/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+00,81%    |
|30    |22.1.1    |01/01/2022|Não    |x86/x64/ARM32/ARM64|Windows        |+14,72%    |
|29    |21.330.1  |23/11/2021|Não    |x86/x64            |Windows        |+16,68%    |
|28    |21.323.1  |19/11/2021|Não    |x86/x64            |Windows        |+19,74%    |
|27    |21.319.1  |15/11/2021|Não    |x86/x64            |Windows        |+16,26%    |
|26    |21.313.1  |09/11/2021|Não    |x86/x64            |Windows        |+05,02%    |
|25    |21.311.1  |07/11/2021|Não    |x86/x64            |Windows        |+03,26%    |
|24    |20.6.0-001|2021/2    |Não    |x86/x64            |Windows        |+04,17%    |
|23    |19.9.2-001|2021/2    |Não    |x86/x64            |Windows        |-20,98%    |
|22    |18.9.3-001|2021/2    |Não    |x86/x64            |Windows        |+27,93%    |
|21    |17.9.5-001|2021/2    |Não    |x86/x64            |Windows        |+21,17%    |
|20    |16.9.1-001|2021/2    |Não    |x86/x64            |Windows        |+02,12%    |
|19    |15.9.0-001|2021/2    |Não    |x86/x64            |Windows        |+09,51%    |
|18    |14.9.0-001|2021/2    |Não    |x86/x64            |Windows        |+02,16%    |
|17    |13.9.0-001|2021/2    |Não    |x86/x64            |Windows        |+24,80%    |
|16    |12.7.0-001|2021/2    |Não    |x86/x64            |Windows        |+03,92%    |
|15    |11.5.0-001|2021/2    |Não    |x86/x64            |Windows        |+03,78%    |
|14    |10.9.0-001|2021/2    |Não    |x86/x64            |Windows        |+08,86%    |
|13    |9.8.0-001 |2021/2    |Não    |x86/x64            |Windows        |+12,86%    |
|12    |8.8.0-001 |2021/2    |Não    |x86/x64            |Windows        |+06,06%    |
|11    |7.1.0-001 |2021/2    |Não    |x86/x64            |Windows        |+05,18%    |
|10    |6.5.0-001 |2021/2    |Não    |x86/x64            |Windows        |+08,19%    |
|9     |5.7.0-001 |2021/2    |Não    |x86/x64            |Windows        |+01,75%    |
|8     |5.3.0-001 |2021/2    |Não    |x86/x64            |Windows        |+07,55%    |
|7     |4.9.0-001 |2021/2    |Não    |x86/x64            |Windows        |+41,33%    |
|6     |3.7.0-001 |2021/2    |Não    |x86/x64            |Windows        |+18,11%    |
|5     |2.13.0-002|2021/2    |Não    |x86/x64            |Windows        |=00,00%    |
|4     |2.13.0-001|2021/2    |Não    |x86/x64            |Windows        |+35,11%    |
|3     |1.8.0-001 |2021/2    |Não    |x86/x64            |Windows        |+02,17%    |
|2     |1.7.0-001 |2021/2    |Não    |x86/x64            |Windows        |-12,38%    |
|1     |0.9.0-001 |2021/2    |Não    |x86/x64            |Windows        |+100%      |

> Verifique a [Política de Suporte](https://github.com/2uj1m28ohz/Workflow/blob/main/SUPPORT.md) para mais informações.
