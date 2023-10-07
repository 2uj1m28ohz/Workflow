## :gem: Sobre

Workflow é uma poderosa ferramenta para automação de tarefas, criado para gerenciar backups e rotinas de manutenção do sistema. Altamente configurável para atender às necessidades do seu ambiente e com uma CLI intuitiva, é baseado em comandos simples e pode ser utilizado por usuários de todos os níveis de habilidade, tornando a automação acessível para todos. Workflow é constantemente desenvolvido para reduzir falhas humanas, aumentar sua produtividade e permitir que você se concentre em atividades de maior valor.

![](https://github.com/2uj1m28ohz/workflow/blob/main/Screenshot.png)

## :rocket: Funcionalidades
- **Backup de Dados:** Automatiza o backup de jogos[^1], dados de usuário[^2], armazenamento em nuvem[^3] e drivers de sistema mantendo-os em local seguro, longe de ameaças digitais. Workflow permite configurar, gerenciar e armazenar backups granulares com eficiência e flexibilidade. A partir do backup é possível criar nativamente uma réplica exata dos dados de forma segura. Selecione o formato e nível de compressão, drive de destino, período de retenção, e observe a mágica acontecer.

- **Depuração do Sistema:** Otimiza o desempenho do sistema operacional removendo arquivos temporários obsoletos a nível de sistema, software[^4] e usuário.

- **Diagnóstico do Sistema:** Gera relatórios de bateria e eficiência energética, exibe informações sobre a saúde dos drives e integridade do sistema de arquivos para ajudar você em ações preventivas que manterão seu dispositivo operacional por mais tempo.

- **Manutenção do Sistema:** Atualiza aplicativos e restaura a integridade do sistema operacional com facilidade.

## :zap: Recursos
- **Atualização:** Como um software rolling release, Workflow recebe atualizações contínuas e incrementais. Updates são baixados e instalados automaticamente. Instale uma vez, atualize para sempre[^5].

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
.\Workflow.ps1
```
> **NOTA:** Certifique-se de informar o local correto do script.

## :arrow_upper_right: Como Executar
1. Navegue até o diretório home do usuário:
```
Set-Location $Home
```
> **NOTA:** Home é o diretório padrão de execução do PowerShell.
2. Execute o script:
```
.\Workflow.ps1
```

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
Imagem por [Marcin Jozwiak](https://unsplash.com/pt-br/fotografias/H35_4lJCC48).

[^1]:EVE Online, Surviving Mars, Industries Of Titan, Aven Colony, Pharaoh: A New Era
[^2]:Desktop, Documentos, Imagens, Vídeos, Músicas, Downloads
[^3]:OneDrive, Google Drive, iCloud Drive
[^4]:EVE Online
[^5]:Atualizações de software só podem ser garantidas em ambientes compatíveis e de acordo com a [Política de Suporte](https://github.com/2uj1m28ohz/workflow/blob/main/SUPPORT.md)
