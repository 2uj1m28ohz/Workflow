## :asterisk: Sobre

Workflow é uma poderosa ferramenta para automação de tarefas, criado para gerenciar backups e rotinas de manutenção do sistema. Altamente configurável para atender às necessidades do seu ambiente e com uma CLI intuitiva, é baseado em comandos simples e pode ser utilizado por usuários de todos os níveis de habilidade, tornando a automação acessível para todos. Workflow é constantemente desenvolvido para que você possa se concentrar em atividades de maior valor, reduzindo falhas humanas, aumentando sua eficiência e produtividade.

![](https://github.com/2uj1m28ohz/workflow/blob/main/Screenshot.png)

## :mechanical_arm: Automação
- **Backup de Dados:** Automatize o backup de jogos selecionados[^1], drivers de sistema, dados de usuário[^2] e da nuvem[^3] mantendo-os em local seguro, longe de ameaças digitais. Escolha o formato e nível de compressão, drive de destino, período de retenção, e observe a mágica acontecer.

- **Depuração do Sistema:** Otimize o desempenho do sistema operacional removendo arquivos temporários obsoletos a nível de sistema, usuário e softwares selecionados[^4].

- **Diagnóstico do Sistema:** Consulte relatórios de bateria, eficiência energética, saúde dos drives e integridade do sistema de arquivos. Tome ações preventivas para manter seu dispositivo operacional por mais tempo.

- **Manutenção do Sistema:** Atualize aplicativos e restaure a integridade do sistema operacional com apenas um comando.

- **Informações:** Consulte informações detalhadas de hardware como BIOS, processador, memória, armazenamento, GPU, bateria e mais.

## :gem: Recursos
- **Atualização:** Como um software rolling release, updates são baixados e instalados automaticamente. Instale uma vez, atualize para sempre[^5].

- **Segurança:** Algoritmos de segurança verificam a integridade dos updates antes da instalação, bem como detectam e corrigem alterações ilegais de software.

- **Configurações:** Exporte suas configurações para um novo dispositivo e continue exatamente do ponto onde parou.

- **Personalização:** Escolha entre cinco temas diferentes pra deixar o seu setup com aquele brilho cintilante.

- **Notificações:** Receba notificações importantes sobre a execução do software na Central de Notificações do sistema.

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

## :blue_book: Documentação
- [Ajuda](https://github.com/2uj1m28ohz/workflow/blob/main/HELP.md)
- [Navegação](https://github.com/2uj1m28ohz/workflow/blob/main/Navigation.md)
- [Evolução](https://github.com/2uj1m28ohz/workflow/blob/main/Evolution.md)
- [Estrutura](https://github.com/2uj1m28ohz/workflow/blob/main/Structure.md)
- [Código-fonte](https://github.com/2uj1m28ohz/workflow/blob/main/SourceCode.md)
- [Contribuindo](https://github.com/2uj1m28ohz/workflow/blob/main/CONTRIBUTING.md)
- [Política de Suporte](https://github.com/2uj1m28ohz/workflow/blob/main/SUPPORT.md)
- [Licença de Software](https://github.com/2uj1m28ohz/workflow/blob/main/LICENSE)
- [Código de Conduta](https://github.com/2uj1m28ohz/workflow/blob/main/CODE_OF_CONDUCT.md)

## :bust_in_silhouette: Atribuição
Imagem por [Dave Herring](https://unsplash.com/pt-br/fotografias/B7cjB9bIGAQ).

[^1]:EVE Online, Surviving Mars, Industries Of Titan, Aven Colony
[^2]:Desktop, Documentos, Imagens, Vídeos, Músicas, Downloads
[^3]:Recurso disponível apenas para o OneDrive
[^4]:EVE Online
[^5]:Atualizações de software só podem ser garantidas em ambientes compatíveis e de acordo com a [Política de Suporte](https://github.com/2uj1m28ohz/workflow/blob/main/SUPPORT.md)
