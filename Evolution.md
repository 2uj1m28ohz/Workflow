# Evolução
Workflow é desenvolvido para simplificar a conversão de arquivos, execução de backups e rotinas de manutenção do sistema. Com uma abordagem ágil e centralizada, otimiza a segurança dos dados e a resiliência do sistema. A automação intrínseca ao software maximiza a eficiência, promovendo operações fluidas e confiáveis.

## Tecnologias
Inicialmente escrito em Shell Script para o legado Prompt de Comando, Workflow foi reescrito e portado para o PowerShell, uma linguagem orientada a objetos que amplia significativamente as possibilidades de desenvolvimento. Ao adotar um paradigma orientado a objetos, o projeto se beneficia de conceitos como modelagem do mundo real, encapsulamento e polimorfismo, permitindo a criação de componentes modulares, reutilizáveis e de fácil manutenção. Essa abordagem melhora a organização e abstração do código, proporcionando uma flexibilidade extraordinária para a implementação de novas funcionalidades e adaptações para diversas arquiteturas, sistemas e necessidades.

Essa transição envolveu ainda a substituição da [Codificação de Caracteres][Codificação de Caracteres], resultando em uma melhoria significativa na compatibilidade e confiabilidade do software.

## Métodos
O desenvolvimento contínuo de Workflow incluiu a tradução do código-fonte do idioma PT-BR para EN-US e a implementação de [Metodologias Ágeis][Metodologias Ágeis] como o Extreme Programming e Scrum, alinhando-se aos princípios da filosofia [Clean Code][Clean Code]. Esses métodos proporcionaram um processo dinâmico e iterativo, elevando a qualidade do código.

Para simplificar a identificação de versões e refletir a evolução do projeto, o sistema de [Versionamento de Software][Versionamento de Software] semântico foi substituído pelo de calendário.

```
───────── 20.6.0-001 ─────────────── ─ ───────── 21.311.1 ─────────────── ─ ───────── 24.01.1 ───────────────
SEMVER      ┬ ┬ ┬  ┬                   CALVER V1  ┬  ┬  ┬                   CALVER V2  ┬  ┬ ┬
            │ │ │  │                              │  │  │                              │  │ │
            │ │ │  └─┤ Build                      │  │  └─┤ Revisão                    │  │ └─┤ Revisão
            │ │ └────┤ Patch                      │  └────┤ Dia absoluto               │  └───┤ Mês
            │ └──────┤ Minor                      └───────┤ Ano                        └──────┤ Ano
            └────────┤ Major
```

## Design
A [Interface][Interface] de Workflow foi inspirada no universo de Tron, criado por Steven Lisberger, incorporando easter eggs no algoritmo e interface das versões iniciais. O design atual segue as Diretrizes de Interface, priorizando intuitividade, unidade e minimalismo para uma experiência fluida, guiando elementos, fluxos e conceitos.

A análise da paleta de cores do terminal foi essencial para construir um layout consistente e agradável. Atualizações posteriores introduziram novos temas, elevando a flexibilidade da interface.

> _Design não é apenas aparência, design é sobre como as coisas funcionam._ - Steve Jobs

## Extensões
Workflow possibilita a integração com extensões de alto nível que operam em perfeita harmonia com o controle e automação do software. Cada ferramenta foi escolhida para transformar a manipulação de arquivos em uma experiência poderosa e intuitiva.

- **7‑Zip:** Com tecnologia avançada de compressão e descompressão, o 7‑Zip eleva a eficiência do backup de dados e empacotamento de software, otimizando tamanho e performance.
- **WebP:** Ideal para converter e otimizar imagens, o WebP gera arquivos de alta qualidade em tamanhos compactos – perfeito para web e armazenamento inteligente.
- **FFmpeg:** Essencial para processamento multimídia, o FFmpeg facilita a conversão, transcodificação e manipulação de áudio e vídeo, integrando essas funções de forma fluida.

Ao possibilitar o acoplamento de extensões, Workflow expande suas funcionalidades para oferecer uma solução completa, versátil e poderosa. Essa abordagem permite que Workflow atenda a uma ampla variedade de necessidades e contextos, proporcionando uma experiência superior para todos os usuários.

> A disponibilidade de recursos e funcionalidades pode variar conforme a plataforma.

## Segurança
A segurança está no núcleo do algoritmo de Workflow. Para atender a este requisito, foram implementados recursos críticos:

- **Registro de eventos:** Monitora as operações do software, proporcionando transparência e controle.
- **Atualizações automáticas:** Asseguram agilidade e confiabilidade na entrega de correções e melhorias.
- **Verificação de integridade:** Identifica e corrige alterações ilegais no algoritmo, mantendo a integridade constante do software.

## Resiliência
Workflow foi projetado para garantir uma operação contínua, implementando uma arquitetura resiliente que utiliza múltiplos métodos de execução em diversos recursos e funcionalidades. Caso o método primário falhe, métodos de fallback são acionados automaticamente para manter a continuidade da execução sem interrupções significativas. Esse design inteligente previne cenários de falhas críticas, criando um software que não apenas responde a imprevistos, mas também se adapta e recupera rapidamente, preservando a confiabilidade das operações.

## Multiplataforma
Portar Workflow para Linux permite ao usuários migrar facilmente entre plataformas mantendo o mesmo fluxo e utilizando a mesma ferramenta de forma consistente. A adaptação para Linux exigiu uma reestruturação significativa do código para garantir uma transição suave e a preservação dos recursos e funcionalidades disponíveis. Ajustes para que Workflow opere de maneira eficiente e confiável em ambos os ambientes, sem comprometer a experiência do usuário.

Esse desenvolvimento marca um importante passo na evolução do Workflow, tornando-o uma solução verdadeiramente multiplataforma, com potencial de uso para administradores e usuários que transitam entre em ambientes distintos, permitindo uma integração fluida e flexível entre Windows e Linux.

## Inteligência
A integração da inteligência artificial impulsionou o desenvolvimento do projeto, simplificando tarefas complexas e acelerando decisões. Simultaneamente a inteligência natural é essencial para refinar o software, garantindo que cada atualização do algoritmo preserve a visão e os objetivos originais. A combinação dessas inteligências resulta em um software poderoso e adaptável às necessidades em constante evolução.

## Lançamentos
Workflow é aprimorado continuamente para ampliar a compatibilidade, introduzir novos recursos e melhorar funcionalidades, utilizando tecnologias flexíveis, eficientes e robustas, com preferência por soluções de código aberto. Tudo isso mantendo a simplicidade de uma [Arquitetura Monolítica][Arquitetura Monolítica].

De forma geral, monólitos são convenientes por reduzir a sobrecarga cognitiva, acelerar o desenvolvimento e a execução do software.

| Sprint | Versão     | Data       | Suporte | Arquiteturas        | Sistemas        | Crescimento |
| :----: | :--------: | :--------: | :-----: | :-----------------: | :-------------: | :---------: |
| 80     | 25.05.0    | 04/05/2025 | Sim     | x86/x64/ARM32/ARM64 | Windows/Linux   | +00,15%     |
| 79     | 25.04.0    | 06/04/2025 | Sim     | x86/x64/ARM32/ARM64 | Windows/Linux   | +09,73%     |
| 78     | 25.03.0    | 02/03/2025 | Sim     | x86/x64/ARM32/ARM64 | Windows/Linux   | +03,49%     |
| 77     | 25.02.0    | 02/02/2025 | Não     | x86/x64/ARM32/ARM64 | Windows/Linux   | +00,40%     |
| 76     | 25.01.0    | 05/01/2025 | Não     | x86/x64/ARM32/ARM64 | Windows/Linux   | +04,51%     |
| 75     | 24.12.1    | 01/12/2024 | Não     | x86/x64/ARM32/ARM64 | Windows/Linux   | +04,27%     |
| 74     | 24.11.1    | 03/11/2024 | Não     | x86/x64/ARM32/ARM64 | Windows/Linux   | +11,21%     |
| 73     | 24.10.1    | 06/10/2024 | Não     | x86/x64/ARM32/ARM64 | Windows/Linux   | +09,93%     |

<details>
<summary>Mais</summary>

| Sprint | Versão     | Data       | Suporte | Arquiteturas        | Sistemas        | Crescimento |
| :----: | :--------: | :--------: | :-----: | :-----------------: | :-------------: | :---------: |
| 72     | 24.09.1    | 01/09/2024 | Não     | x86/x64/ARM32/ARM64 | Windows         | +00,36%     |
| 71     | 24.08.1    | 04/08/2024 | Não     | x86/x64/ARM32/ARM64 | Windows         | -03,80%     |
| 70     | 24.07.1    | 07/07/2024 | Não     | x86/x64/ARM32/ARM64 | Windows         | +01,28%     |
| 69     | 24.06.1    | 02/06/2024 | Não     | x86/x64/ARM32/ARM64 | Windows         | +00,11%     |
| 68     | 24.05.1    | 05/05/2024 | Não     | x86/x64/ARM32/ARM64 | Windows         | -04,03%     |
| 67     | 24.04.1    | 07/04/2024 | Não     | x86/x64/ARM32/ARM64 | Windows         | -08,97%     |
| 66     | 24.03.1    | 03/03/2024 | Não     | x86/x64/ARM32/ARM64 | Windows         | +09,08%     |
| 65     | 24.02.1    | 04/02/2024 | Não     | x86/x64/ARM32/ARM64 | Windows         | +04,57%     |
| 64     | 24.01.1    | 02/01/2024 | Não     | x86/x64/ARM32/ARM64 | Windows         | +05,27%     |
| 63     | 23.340.1   | 06/12/2023 | Não     | x86/x64/ARM32/ARM64 | Windows         | +04,34%     |
| 62     | 23.310.1   | 06/11/2023 | Não     | x86/x64/ARM32/ARM64 | Windows         | -01,54%     |
| 61     | 23.280.1   | 07/10/2023 | Não     | x86/x64/ARM32/ARM64 | Windows         | -03,82%     |
| 60     | 23.250.1   | 07/09/2023 | Não     | x86/x64/ARM32/ARM64 | Windows         | +08,39%     |
| 59     | 23.220.1   | 08/08/2023 | Não     | x86/x64/ARM32/ARM64 | Windows         | -01,93%     |
| 58     | 23.190.1   | 09/07/2023 | Não     | x86/x64/ARM32/ARM64 | Windows         | -03,21%     |
| 57     | 23.160.1   | 09/06/2023 | Não     | x86/x64/ARM32/ARM64 | Windows         | -02,89%     |
| 56     | 23.130.1   | 10/05/2023 | Não     | x86/x64/ARM32/ARM64 | Windows         | +01,80%     |
| 55     | 23.100.1   | 10/04/2023 | Não     | x86/x64/ARM32/ARM64 | Windows         | +05,64%     |
| 54     | 23.070.1   | 11/03/2023 | Não     | x86/x64/ARM32/ARM64 | Windows         | +07,91%     |
| 53     | 23.040.1   | 09/02/2023 | Não     | x86/x64/ARM32/ARM64 | Windows         | -11,74%     |
| 52     | 23.010.1   | 10/01/2023 | Não     | x86/x64/ARM32/ARM64 | Windows         | +06,85%     |
| 51     | 22.340.1   | 06/12/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +06,12%     |
| 50     | 22.310.1   | 06/11/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | -00,93%     |
| 49     | 22.280.1   | 07/10/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +01,95%     |
| 48     | 22.260.1   | 17/09/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +03,74%     |
| 47     | 22.250.1   | 07/09/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +13,72%     |
| 46     | 22.230.1   | 18/08/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +02,94%     |
| 45     | 22.190.2   | 09/07/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +01,62%     |
| 44     | 22.190.1   | 09/07/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +02,33%     |
| 43     | 22.130.1   | 10/05/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | -03,77%     |
| 42     | 22.120.1   | 30/04/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +01,43%     |
| 41     | 22.110.1   | 21/04/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +01,95%     |
| 40     | 22.100.1   | 10/04/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +00,73%     |
| 39     | 22.090.1   | 30/03/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +07,06%     |
| 38     | 22.080.1   | 21/03/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +06,01%     |
| 37     | 22.070.1   | 11/03/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +06,05%     |
| 36     | 22.60.1    | 01/03/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +08,15%     |
| 35     | 22.50.1    | 19/02/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +41,45%     |
| 34     | 22.40.1    | 09/02/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +08,30%     |
| 33     | 22.30.1    | 30/01/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +05,61%     |
| 32     | 22.20.1    | 20/01/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +03,71%     |
| 31     | 22.10.1    | 10/01/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +00,81%     |
| 30     | 22.1.1     | 01/01/2022 | Não     | x86/x64/ARM32/ARM64 | Windows         | +14,72%     |
| 29     | 21.330.1   | 23/11/2021 | Não     | x86/x64             | Windows         | +16,68%     |
| 28     | 21.323.1   | 19/11/2021 | Não     | x86/x64             | Windows         | +19,74%     |
| 27     | 21.319.1   | 15/11/2021 | Não     | x86/x64             | Windows         | +16,26%     |
| 26     | 21.313.1   | 09/11/2021 | Não     | x86/x64             | Windows         | +05,02%     |
| 25     | 21.311.1   | 07/11/2021 | Não     | x86/x64             | Windows         | +03,26%     |
| 24     | 20.6.0-001 | 2021/2     | Não     | x86/x64             | Windows         | +04,17%     |
| 23     | 19.9.2-001 | 2021/2     | Não     | x86/x64             | Windows         | -20,98%     |
| 22     | 18.9.3-001 | 2021/2     | Não     | x86/x64             | Windows         | +27,93%     |
| 21     | 17.9.5-001 | 2021/2     | Não     | x86/x64             | Windows         | +21,17%     |
| 20     | 16.9.1-001 | 2021/2     | Não     | x86/x64             | Windows         | +02,12%     |
| 19     | 15.9.0-001 | 2021/2     | Não     | x86/x64             | Windows         | +09,51%     |
| 18     | 14.9.0-001 | 2021/2     | Não     | x86/x64             | Windows         | +02,16%     |
| 17     | 13.9.0-001 | 2021/2     | Não     | x86/x64             | Windows         | +24,80%     |
| 16     | 12.7.0-001 | 2021/2     | Não     | x86/x64             | Windows         | +03,92%     |
| 15     | 11.5.0-001 | 2021/2     | Não     | x86/x64             | Windows         | +03,78%     |
| 14     | 10.9.0-001 | 2021/2     | Não     | x86/x64             | Windows         | +08,86%     |
| 13     | 9.8.0-001  | 2021/2     | Não     | x86/x64             | Windows         | +12,86%     |
| 12     | 8.8.0-001  | 2021/2     | Não     | x86/x64             | Windows         | +06,06%     |
| 11     | 7.1.0-001  | 2021/2     | Não     | x86/x64             | Windows         | +05,18%     |
| 10     | 6.5.0-001  | 2021/2     | Não     | x86/x64             | Windows         | +08,19%     |
| 9      | 5.7.0-001  | 2021/2     | Não     | x86/x64             | Windows         | +01,75%     |
| 8      | 5.3.0-001  | 2021/2     | Não     | x86/x64             | Windows         | +07,55%     |
| 7      | 4.9.0-001  | 2021/2     | Não     | x86/x64             | Windows         | +41,33%     |
| 6      | 3.7.0-001  | 2021/2     | Não     | x86/x64             | Windows         | +18,11%     |
| 5      | 2.13.0-002 | 2021/2     | Não     | x86/x64             | Windows         | =00,00%     |
| 4      | 2.13.0-001 | 2021/2     | Não     | x86/x64             | Windows         | +35,11%     |
| 3      | 1.8.0-001  | 2021/2     | Não     | x86/x64             | Windows         | +02,17%     |
| 2      | 1.7.0-001  | 2021/2     | Não     | x86/x64             | Windows         | -12,38%     |
| 1      | 0.9.0-001  | 2021/2     | Não     | x86/x64             | Windows         | +100%       |

</details>

> Verifique a [Política de Suporte][Política de Suporte] para mais informações.

[Codificação de Caracteres]: https://github.com/2uj1m28ohz/Database/blob/main/SoftwareDevelopment/CharacterEncoding.md
[Metodologias Ágeis]: https://github.com/2uj1m28ohz/Database/blob/main/SoftwareDevelopment/AgileMethodologies.md
[Clean Code]: https://github.com/2uj1m28ohz/Database/blob/main/SoftwareDevelopment/SoftwareDesign.md
[Versionamento de Software]: https://github.com/2uj1m28ohz/Database/blob/main/SoftwareDevelopment/SoftwareVersioning.md
[Interface]: https://github.com/2uj1m28ohz/Database/blob/main/SoftwareDevelopment/Interface.md
[Arquitetura Monolítica]: https://github.com/2uj1m28ohz/Database/blob/main/SoftwareDevelopment/SoftwareArchitecture.md
[Política de Suporte]: /Policies.md