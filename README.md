![](https://github.com/2uj1m28ohz/workflow/blob/main/Screenshot.png)

## :mechanical_arm: Automação
Agilize processos e libere-se de tarefas repetitivas com a automação de Workflow[^1]. CLI intuitivo, sem código e baseado em comandos simples para que você possa se concentrar em atividades de maior valor.

- **Backup e Restauração:** Automatize o backup de dados do usuário local, da nuvem[^2], jogos selecionados e drivers de sistema mantendo-os em local seguro, longe de ameaças digitais.

- **Depuração do Sistema:** Otimize o desempenho do sistema operacional removendo arquivos temporários obsoletos a nível de sistema, usuário e softwares selecionados.

- **Diagnóstico do Sistema:** Consulte relatórios de bateria, eficiência energética, saúde dos drives e integridade do sistema de arquivos. Tome ações preventivas para manter seu dispositivo operacional por mais tempo.

- **Manutenção do Sistema:** Atualize aplicativos e restaure a integridade da instalação do sistema operacional com apenas um comando.

- **Informações:** Consulte informações detalhadas de hardware como BIOS, processador, memória, armazenamento, GPU, bateria e mais.

## :sparkles: Recursos
- **Segurança:** Workflow verifica a integridade dos pacotes de software, baixa e instala atualizações automaticamente, além de detectar e corrigir alterações ilegais de algoritmo.

- **Personalização:** Escolha entre cinco temas diferentes pra deixar o seu setup com aquele brilho cintilante.

- **Notificações:** Receba notificações importantes sobre a execução do software na área de trabalho.

## :arrow_down: Como Instalar
1. Baixe a versão de software mais recente disponível no [repositório](https://github.com/2uj1m28ohz/workflow/releases);
2. Descomprima o pacote;
3. Execute o PowerShell;
4. Habilite a execução de scripts para o usuário atual:
```
Set-ExecutionPolicy Unrestricted -Scope CurrentUser -Force
```
5. Desbloqueie o script:
```
Get-Item Workflow.ps1 | Unblock-File
```
6. Execute o script:
```
.\Workflow.ps1
```
> **NOTA:** Certifique-se de informar o local correto do script.

## :notebook_with_decorative_cover: Documentação
- [Ajuda](https://github.com/2uj1m28ohz/workflow/blob/main/HELP.md)
- [Navegação](https://github.com/2uj1m28ohz/workflow/blob/main/Navigation.md)
- [Evolução](https://github.com/2uj1m28ohz/workflow/blob/main/Evolution.md)
- [Estrutura](https://github.com/2uj1m28ohz/workflow/blob/main/Structure.md)
- [Código-fonte](https://github.com/2uj1m28ohz/workflow/blob/main/SourceCode.md)
- [Contribuindo](https://github.com/2uj1m28ohz/workflow/blob/main/CONTRIBUTING.md)
- [Política de Suporte](https://github.com/2uj1m28ohz/workflow/blob/main/SUPPORT.md)
- [Licença de Software](https://github.com/2uj1m28ohz/workflow/blob/main/LICENSE)
- [Código de Conduta](https://github.com/2uj1m28ohz/workflow/blob/main/CODE_OF_CONDUCT.md)
> **NOTA:** Todas as outras marcas mencionadas são de propriedade de seus respectivos proprietários.

## :clap: Atribuição
Imagem por [Alexis Antoine](https://unsplash.com/photos/lbIgR6AwLfw).

[^1]:Este é um projeto pessoal que tem como objetivo atender exclusivamente as demandas do desenvolvedor, podendo eventualmente ser útil a outros contextos. Verifique a Licença de Software para mais informações.
[^2]:Recurso disponível apenas para o OneDrive.
