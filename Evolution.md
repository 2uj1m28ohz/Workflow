## :atom_symbol: Evolução

### Ciclos
O desenvolvimento de Workflow está organizado em ciclos:

<details>
<summary>Ciclo Alpha</summary>

Inicialmente escrito para o legado Prompt de Comando, o desenvolvimento de Workflow tem início no segundo semestre de 2021 com o _Ciclo Alpha_, período de aprendizagem da linguagem shell script, construção do núcleo do software e execução dos primeiros testes. Posteriormente portado para PowerShell 5.1, o algoritmo ganhou em complexidade e compatibilidade.

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

```
                             23.001.1                                                   24.01.1
‹ ──────── CalVer V1 ─────────┬──┬──┬────────────────────────────── › CalVer V2 ─────────┬──┬─┬──────────────────♦
                              │  │  └─┤ Revisão                                          │  │ └─┤ Revisão
                              │  └────┤ Dia absoluto do ano                              │  └───┤ Mês
                              └───────┤ Ano                                              └──────┤ Ano
```
> O formato de versionamento CalVer V2 simplifica a identificação de versão.

Os ciclos anteriores foram fundamentais na construção de um software robusto e inteligente. Não será diferente em 2024.

</details>

### Lançamentos
|Ciclo|Sprint|Versão|Data|Suporte|Windows|PowerShell|7-Zip|Linhas|Sub-rotinas|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Delta|65|24.02.1|04/02/2024|:green_circle:|10 22H2|7.4.0|23.01|+04,57%|+02,46%|
|Delta|64|24.01.1|02/01/2024|:green_circle:|10 22H2|7.4.0|23.01|+05,27%|+02,53%|
|Gama|63|23.340.1|06/12/2023|:yellow_circle:|10 22H2|7.3.6|23.01|+04,34%|+03,66%|
|Gama|62|23.310.1|06/11/2023|:red_circle:|10 22H2|7.3.5|23.01|-01,54%|-01,04%|
|Gama|61|23.280.1|07/10/2023|:red_circle:|10 22H2|7.3.4|23.01|-03,82%|-03,98%|
|Gama|60|23.250.1|07/09/2023|:red_circle:|10 22H2|7.3.3|23.01|+08,39%|+06,35%|
|Gama|59|23.220.1|08/08/2023|:red_circle:|10 22H2|7.3.2|22.01|-01,93%|-04,06%|
|Gama|58|23.190.1|09/07/2023|:red_circle:|10 22H2|7.3.1|22.01|-03,21%|+04,23%|
|Gama|57|23.160.1|09/06/2023|:red_circle:|10 21H2|7.3.0|22.00|-02,89%|+13,17%|
|Gama|56|23.130.1|10/05/2023|:red_circle:|10 21H2|7.3.0|22.00|+01,80%|+15,17%|
|Gama|55|23.100.1|10/04/2023|:red_circle:|10 21H2|7.3.0|22.00|+05,64%|+02,84%|
|Gama|54|23.070.1|11/03/2023|:red_circle:|10 21H2|7.3.0|22.00|+07,91%|+28,18%|
|Gama|53|23.040.1|09/02/2023|:red_circle:|10 21H2|7.3.0|22.00|-11,74%|-09,09%|
|Gama|52|23.010.1|10/01/2023|:red_circle:|10 21H2|7.2.5|22.00|+06,85%|+01,68%|
|Beta|51|22.340.1|06/12/2022|:red_circle:|10 21H1|7.2.0|22.00|+06,12%|+08,18%|
|Beta|50|22.310.1|06/11/2022|:red_circle:|10 21H1|7.2.0|22.00|-00,93%|-00,90%|
|Beta|49|22.280.1|07/10/2022|:red_circle:|10 21H1|7.2.0|22.00|+01,95%|00,00%|
|Beta|48|22.260.1|17/09/2022|:red_circle:|10 21H1|7.2.0|22.00|+03,74%|+11,00%|
|Beta|47|22.250.1|07/09/2022|:red_circle:|10 20H2|7.2.0|22.00|+13,72%|+13,64%|
|Beta|46|22.230.1|18/08/2022|:red_circle:|10 2004|7.2.0|22.00|+02,94%|+02,33%|
|Beta|45|22.190.2|09/07/2022|:red_circle:|10 1909|7.2.0|21.07|+01,62%|-01,15%|
|Beta|44|22.190.1|09/07/2022|:red_circle:|10 1909|7.2.0|21.07|+02,33%|+01,16%|
|Beta|43|22.130.1|10/05/2022|:red_circle:|10 1903|7.2.0|21.07|-03,77%|+01,18%|
|Beta|42|22.120.1|30/04/2022|:red_circle:|10 1809|7.2.0|21.07|+01,43%|-01,16%|
|Beta|41|22.110.1|21/04/2022|:red_circle:|10 1803|7.2.0|21.07|+01,95%|+01,18%|
|Beta|40|22.100.1|10/04/2022|:red_circle:|10 1709|7.2.0|21.07|+00,73%|00,00%|
|Beta|39|22.090.1|30/03/2022|:red_circle:|10 1703|7.2.0|21.07|+07,06%|+06,25%|
|Beta|38|22.080.1|21/03/2022|:red_circle:|10 1607|7.2.0|21.07|+06,01%|+06,67%|
|Beta|37|22.070.1|11/03/2022|:red_circle:|10 1511|7.2.0|21.07|+06,05%|+04,17%|
|Beta|36|22.60.1|01/03/2022|:red_circle:|10 1507|7.2.0|21.07|+08,15%|+05,88%|
|Beta|35|22.50.1|19/02/2022|:red_circle:|10 1507|7.2.0|21.07|+41,45%|+30,77%|
|Beta|34|22.40.1|09/02/2022|:red_circle:|10 1507|7.2.0|21.07|+08,30%|+23,81%|
|Beta|33|22.30.1|30/01/2022|:red_circle:|10 1507|7.2.0|21.07|+05,61%|+07,69%|
|Beta|32|22.20.1|20/01/2022|:red_circle:|10 1507|7.2.0|21.06|+03,71%|+02,63%|
|Beta|31|22.10.1|10/01/2022|:red_circle:|10 1507|7.1.0|19.00|+00,81%|+58,33%|
|Beta|30|22.1.1|01/01/2022|:red_circle:|10 1507|7.0.0||+14,72%|+9,09%|
|Alpha|29|21.330.1|23/11/2021|:red_circle:|10 1507|5.1.0||+16,68%|+4,76%|
|Alpha|28|21.323.1|19/11/2021|:red_circle:|10 1507|5.1.0||+19,74%|-08,70%|
|Alpha|27|21.319.1|15/11/2021|:red_circle:|10 1507|5.1.0||+16,26%|+04,55%|
|Alpha|26|21.313.1|09/11/2021|:red_circle:|10 1507|5.1.0||+05,02%|00,00%|
|Alpha|25|21.311.1|07/11/2021|:red_circle:|10 1507|5.1.0||+03,26%|00,00%|
|Alpha|24|20.6.0-001|2021/2|:red_circle:|10 1507|5.1.0||+04,17%|+04,76%|
|Alpha|23|19.9.2-001|2021/2|:red_circle:|10 1507|5.1.0||-20,98%|+05,00%|
|Alpha|22|18.9.3-001|2021/2|:red_circle:|10 1507|5.1.0||+27,93%|+05,26%|
|Alpha|21|17.9.5-001|2021/2|:red_circle:|10 1507|5.1.0||+21,17%|+05,56%|
|Alpha|20|16.9.1-001|2021/2|:red_circle:|10 1507|5.1.0||+02,12%|+05,88%|
|Alpha|19|15.9.0-001|2021/2|:red_circle:|10 1507|5.1.0||+09,51%|+06,25%|
|Alpha|18|14.9.0-001|2021/2|:red_circle:|10 1507|5.1.0||+02,16%|+06,67%|
|Alpha|17|13.9.0-001|2021/2|:red_circle:|10 1507|5.1.0||+24,80%|+07,14%|
|Alpha|16|12.7.0-001|2021/2|:red_circle:|10 1507|5.1.0||+03,92%|+07,69%|
|Alpha|15|11.5.0-001|2021/2|:red_circle:|10 1507|5.1.0||+03,78%|+08,33%|
|Alpha|14|10.9.0-001|2021/2|:red_circle:|10 1507|5.1.0||+08,86%|+09,09%|
|Alpha|13|9.8.0-001|2021/2|:red_circle:|10 1507|5.1.0||+12,86%|+10,00%|
|Alpha|12|8.8.0-001|2021/2|:red_circle:|10 1507|5.1.0||+06,06%|+11,11%|
|Alpha|11|7.1.0-001|2021/2|:red_circle:|10 1507|5.1.0||+05,18%|+12,50%|
|Alpha|10|6.5.0-001|2021/2|:red_circle:|10 1507|5.1.0||+08,19%|+14,29%|
|Alpha|9|5.7.0-001|2021/2|:red_circle:|10 1507|5.1.0||+01,75%|00,00%|
|Alpha|8|5.3.0-001|2021/2|:red_circle:|10 1507|5.1.0||+07,55%|+16,67%|
|Alpha|7|4.9.0-001|2021/2|:red_circle:|10 1507|5.1.0||+41,33%|+20,00%|
|Alpha|6|3.7.0-001|2021/2|:red_circle:|10 1507|5.1.0||+18,11%|+25,00%|
|Alpha|5|2.13.0-002|2021/2|:red_circle:|10 1507|5.1.0||00,00%|00,00%|
|Alpha|4|2.13.0-001|2021/2|:red_circle:|10 1507|5.1.0||+35,11%|+33,33%|
|Alpha|3|1.8.0-001|2021/2|:red_circle:|10 1507|5.1.0||+02,17%|00,00%|
|Alpha|2|1.7.0-001|2021/2|:red_circle:|10 1507|5.1.0||-12,38%|-40,00%|
|Alpha|1|0.9.0-001|2021/2|:red_circle:|10 1507|5.1.0||00,00%|00,00%|

> - :green_circle: Suporte ativo
> - :yellow_circle: Suporte próximo do fim
> - :red_circle: Suporte inativo

> Verifique a [Política de Suporte](https://github.com/2uj1m28ohz/Workflow/blob/main/SUPPORT.md) para mais informações.
