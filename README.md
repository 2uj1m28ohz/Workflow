![](https://github.com/2uj1m28ohz/workflow/blob/main/Screenshot.png)

## :mechanical_arm: Automação
Agilize processos e libere-se de tarefas repetitivas com a automação de Workflow[^1]. CLI intuitivo, sem código e baseado em comandos simples para que você possa se concentrar em atividades de maior valor.

- **Backup e Restauração:** Automatize backups e restaurações de dados dos seus games favoritos mantendo-os em local seguro, longe de ameaças digitais.

- **Depuração do Sistema:** Otimize o desempenho do sistema operacional removendo arquivos temporários antigos e sem uso a nível de sistema, usuário e outros aplicativos.

- **Diagnóstico do Sistema:** Verifique relatórios da bateria, eficiência energética, saúde dos drives e da integridade do sistema de arquivos para tomar ações preventivas e manter seu dispositivo operacional por mais tempo.

- **Manutenção do Sistema:** Atualize aplicativos, verifique e restaure a integridade da instalação do sistema operacional com apenas um comando.

- **Informações:** Consulte informações detalhadas do seu dispositivo como BIOS, processador, memória, armazenamento, GPU, bateria e mais.

## :sparkles: Recursos
- **Segurança:** Workflow verifica a integridade dos pacotes de software, baixa e instala atualizações automaticamente para entregar correções, otimizações e novos recursos na velocidade da luz, além de detectar alterações ilegais de algoritmo e corrigi-lo.

- **Notificações:** Receba notificações importantes sobre a execução do software no seu desktop.

- **Personalização:** Escolha entre cinco temas diferentes pra deixar o seu setup com aquele brilho cintilante.

- **Modo Rollback:** Execute versões anteriores de software temporariamente sem comprometer as configurações da versão atual.

## :arrow_down: Como Instalar
1. Baixe a versão de software mais recente disponível no [repositório](https://github.com/2uj1m28ohz/workflow/releases);
2. Descomprima o pacote;
3. Execute o PowerShell;
4. [Habilite](https://docs.microsoft.com/powershell/module/microsoft.powershell.security/set-executionpolicy) a execução de scripts para o usuário atual:
```
Set-ExecutionPolicy Unrestricted -Scope CurrentUser -Force
```
5. [Desbloqueie](https://docs.microsoft.com/powershell/module/microsoft.powershell.utility/unblock-file) o script:
```
Get-Item Workflow.ps1 | Unblock-File
```
6. Execute o script:
```
.\Workflow.ps1
```
> **NOTA:** Certifique-se de informar o local correto do script.

## :notebook_with_decorative_cover: Documentação
- [Navegação](https://github.com/2uj1m28ohz/workflow/blob/main/Navigation.md)
- [Evolução](https://github.com/2uj1m28ohz/workflow/blob/main/Evolution.md)
- [Código-fonte](https://github.com/2uj1m28ohz/workflow/blob/main/SourceCode.md)
- [Contribuindo](https://github.com/2uj1m28ohz/Workflow/blob/main/CONTRIBUTING.md)
- [Política de Suporte](https://github.com/2uj1m28ohz/workflow/blob/main/SUPPORT.md)
- [Licença de Software](https://github.com/2uj1m28ohz/workflow/blob/main/LICENSE)
- [Código de Conduta](https://github.com/2uj1m28ohz/workflow/blob/main/CODE_OF_CONDUCT.md)
> **NOTA:** Todas as outras marcas mencionadas são de propriedade de seus respectivos proprietários.

## :clap: Atribuição
Wallpaper por [Neil Mark Thomas](https://unsplash.com/photos/1euFcqLsPWA)

[^1]:Este é um projeto pessoal
