![](https://github.com/2uj1m28ohz/workflow/blob/main/Screenshot.png)

## :mechanical_arm: Automação
Agilize processos e liberte-se de tarefas repetitivas com a automação de Workflow. CLI intuitivo, sem código e baseado em comandos simples para que você possa se concentrar em atividades de maior valor.

- **Backup e Restauração:** Automatize o backup de jogos selecionados, drivers de sistema, dados de usuário e da nuvem[^1] mantendo-os em local seguro, longe de ameaças digitais. Escolha o formato de compactação, o drive de destino, e observe a mágica acontecer.

- **Depuração do Sistema:** Otimize o desempenho do sistema operacional removendo arquivos temporários obsoletos a nível de sistema, usuário e softwares selecionados.

- **Diagnóstico do Sistema:** Consulte relatórios de bateria, eficiência energética, saúde dos drives e integridade do sistema de arquivos. Tome ações preventivas para manter seu dispositivo operacional por mais tempo.

- **Manutenção do Sistema:** Atualize aplicativos e restaure a integridade da instalação do sistema operacional com apenas um comando.

- **Informações:** Consulte informações detalhadas de hardware como BIOS, processador, memória, armazenamento, GPU, bateria e mais.

## :sparkles: Recursos
- **Atualização:** Como um software rolling release updates são baixados e instalados automaticamente. Instale uma vez, atualize para sempre[^2].

- **Segurança:** Dispositivos de segurança verificam a integridade dos updates antes da implantação, bem como detectam e corrigiem alterações ilegais de algoritmo.

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
& Workflow.ps1
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

## :clap: Atribuição
Imagem por [Jonny James](https://unsplash.com/photos/3no88nSvK88).

[^1]:Recurso disponível apenas para o OneDrive.
[^2]:Atualizações de software só podem ser garantidas em ambientes compatíveis e de acordo com a Política de Suporte.
