# Ajuda
Um guia para instalação e execução de software. Encontre soluções para problemas comuns, instruções de atualização, configuração e dicas para o uso de funcionalildades.

## Instalação

<details>
<summary>Como instalar</summary>

- Windows
    - Baixe e descomprima o pacote
    - Abra o PowerShell
    - Habilite a execução de scripts `Set-ExecutionPolicy RemoteSigned -Scope CurrentUser -Force`
    - Desbloqueie o script `Get-Item Workflow.ps1 | Unblock-File`
    - Execute `.\Workflow.ps1`
- Linux
    - Baixe e descomprima o pacote
    - Abra o PowerShell `pwsh`
    - Execute `./Workflow.ps1`

</details>

<details>
<summary>Como executar</summary>

- Windows
    - Abra o PowerShell
    - Navegue até a pasta inicial `Set-Location $Home`
    - Execute `.\Workflow.ps1`
- Linux
    - Abra o PowerShell `pwsh`
    - Navegue até a pasta inicial `Set-Location $Home`
    - Execute `./Workflow.ps1`

</details>

<details>
<summary>Notificação de incompatibilidade após instalar</summary>

O software verifica diversas informações do ambiente para garantir que seja executado em um cenário mínimo de compatibilidade. Verifique os requisitos de sistema na página de download e tente novamente após resolver a incompatibilidade.

</details>

<details>
<summary>O software não é instalado automaticamente</summary>

Você está executando uma versão de software sem suporte. Utilize a versão mais recente para prosseguir. Verifique [Evolução][Evolução] e [Política de Suporte][Política de Suporte] para mais informações.

</details>

<details>
<summary>Atalho ausente no diretório do usuário</summary>

Se o atalho `Workflow.ps1` estiver ausente no diretório `$Home`, verifique o tópico **Acesso a Pastas Controladas** na seção **Software de Terceiros**. Em seguida execute Workflow manualmente a partir do diretório de instalação de software. O atalho será recriado automaticamente. Verifique a seção **Estrutura** para mais informações.

</details>

## Atualização

<details>
<summary>Como manter o software atualizado</summary>

Mantenha-se online e execute o software mensalmente para receber atualizações automáticas.

</details>

<details>
<summary>Erro de integridade comprometida</summary>

Esse erro pode ocorrer em diferentes situações e resulta nos seguintes efeitos:
- Instalação ou atualização de software: pacotes inválidos não serão aplicados.
- Alteração ilegal no algoritmo: a integridade de software é restaurada automaticamente.
- Alterações indevidas no arquivo de backup: você será notificado e poderá realizar o backup novamente.

</details>

<details>
<summary>Notificação de incompatibilidade após atualizar</summary>

Verifique os requisitos de sistema na página de download e tente novamente após resolver a incompatibilidade.

</details>

<details>
<summary>O software não recebe atualizações</summary>

Se o software não foi executado por um longo período, pode ter perdido suporte e está impossibilitado de receber atualizações automaticamente. Prossiga com a desinstalação manual e a instalação da versão de software mais recente.

</details> 

## Backup

<details>
<summary>Posso escolher o que incluir no backup?</summary>

Sim. Siga para `Configurações` `>` `Backup` `>` `Conteúdo`

</details>

<details>
<summary>Backup do armazenamento em nuvem corporativo não é possível</summary>

Contas corporativas podem ter estruturas diferentes das contas pessoais, o que pode impedir a inclusão no backup.

</details>

<details>
<summary>O que é suporte a multidispositivos e multiusuários?</summary>

Permite adicionar backups de vários dispositivos e usuários na mesma estrutura de backup.

</details>

<details>
<summary>Outro usuário pode fazer backup dos meus dados?</summary>

Não. Workflow opera em nível de usuário, impedindo que outros acessem seus dados locais. No entanto, observe que o backup de dados não é criptografado. É importante garantir que os drives de backup e réplica sejam armazenados de forma segura para proteger seus dados contra acesso não autorizado.

</details>

<details>
<summary>O que é Vault?</summary>

O Vault é uma pasta dentro do diretório do usuário para armazenar informações que podem ser incluídas no backup. Recomenda-se adicioná-la ao **Acesso a Pastas Controladas** nas configurações de segurança do Windows.

</details>

## Manutenção

<details>
<summary>Verificar Imagem do Sistema</summary>

- Verificar: Aciona o DISM (Deployment Imaging Service and Management Tool) para analisar a integridade da imagem do sistema, buscando possíveis corrupções.

- Reparar: Aciona o DISM para reparar automaticamente a integridade da imagem do sistema utilizando arquivos de reparo disponíveis localmente ou baixando-os dos servidores da Microsoft.

> A disponibilidade de recursos e funcionalidades pode variar conforme a plataforma.

</details>

<details>
<summary>Verificar Instalação do Sistema</summary>

- Verificar: Aciona o SFC (System File Checker) para analisar e reparar arquivos de sistema corrompidos ou ausentes a partir de uma cópia em cache disponível em uma área protegida do sistema.

- Consolidar: Aciona o DISM para limpar e otimizar a imagem do sistema, removendo componentes obsoletos e versões antigas, liberando espaço de armazenamento e melhorando a eficiência geral do sistema.

> A disponibilidade de recursos e funcionalidades pode variar conforme a plataforma.

</details>

## Configuração

<details>
<summary>Desabilitar notificações</summary>

Siga para `Configurações` `>` `Notificações`

</details>

<details>
<summary>Desabilitar o Registro de Eventos</summary>

Siga para `Configurações` `>` `Registro de Eventos` `>` `Status`

</details>

<details>
<summary>Alterar período de retenção do Registro de Eventos</summary>

Siga para `Configurações` `>` `Registro de Eventos` `>` `Período de Retenção`

</details>

<details>
<summary>Exportar hashes de empacotamento</summary>

Habilite o Registro de Eventos para exportar hashes de empacotamento.

</details>

<details>
<summary>Backup das configurações de software</summary>

- Windows
    - Siga para `Configurações` `>` `Gerenciar` `>` `Exportar`
    - Utilize `WIN+R` e acesse `%UserProfile%\Downloads`
    - Faça backup de `WorkflowSettingsBackup.json`
- Linux
    - Siga para `Configurações` `>` `Gerenciar` `>` `Exportar`
    - Utilize `ALT+F2` e acesse `~/Downloads`
    - Faça backup de `WorkflowSettingsBackup.json`

</details>

<details>
<summary>Transferir configurações para um novo dispositivo</summary>

- Windows
    - No dispositivo antigo:
        - Siga para `Configurações` `>` `Gerenciar` `>` `Exportar`
        - Utilize `WIN+R` e acesse `%UserProfile%\Downloads`
        - Copie o arquivo `WorkflowSettingsBackup.json`
    - No dispositivo novo:
        - Instale o software
        - Utilize `WIN+R` e acesse `%UserProfile%\Downloads`
        - Cole o arquivo `WorkflowSettingsBackup.json`
        - Siga para `Configurações` `>` `Gerenciar` `>` `Importar`
- Linux
    - No dispositivo antigo:
        - Siga para `Configurações` `>` `Gerenciar` `>` `Exportar`
        - Utilize `ALT+F2` e acesse `~/Downloads`
        - Copie o arquivo `WorkflowSettingsBackup.json`
    - No dispositivo novo:
        - Instale o software
        - Utilize `ALT+F2` e acesse `~/Downloads`
        - Cole o arquivo `WorkflowSettingsBackup.json`
        - Siga para `Configurações` `>` `Gerenciar` `>` `Importar`

> Informações de identificação e segurança não podem ser transferidas.

</details>

## Registro de Eventos

<details>
<summary>Coleta de dados</summary>

O Registro de Eventos coleta e armazena localmente informações sobre o ambiente, usuário e a execução do software. Esses dados são automaticamente excluídos conforme a Política de Retenção. O usuário pode desativar o Registro de Eventos ou ajustar o período de retenção nas configurações.

</details>

<details>
<summary>Uso de dados</summary>

Os dados do Registro de Eventos ajudam a monitorar o desempenho, diagnosticar problemas e otimizar o software. Eles permitem identificar padrões de uso, aprimorar a experiência do usuário e manter a cronologia das atividades de software, facilitando a análise retroativa e a recuperação de informações. Os dados do Registro de Eventos podem ser solicitados caso você entre em contato com o [Suporte][Política de Suporte].

</details>

<details>
<summary>Envio de dados</summary>

Nenhum dado é enviado para a internet.

</details>

## Modo de Reversão

<details>
<summary>O que é o Modo de Reversão?</summary>

Protege suas configurações ao executar versões anteriores de software. Todas as alterações são descartadas ao encerrar.

</details>

<details>
<summary>Como ativar o Modo de Reversão?</summary>

Ativado automaticamente ao executar uma versão anterior.

</details>

<details>
<summary>Como desativar o Modo de Reversão?</summary>

Não é possível desativá-lo manualmente.

</details>

## Navegação
Uma visão da árvore de menus da versão mais recente de software.

<details>
<summary>Windows</summary>

```
Home
├─ Backup
│   ├─ Iniciar Backup
│   ├─ Iniciar Réplica
│   └─ Testar Backup
├─ Depuração
├─ Diagnóstico
│   ├─ Relatório da Bateria
│   ├─ Verificar Saúde dos Drives
│   └─ Verificar Sistema de Arquivos
├─ Manutenção
│   ├─ Gerenciar Aplicativos
│   │   ├─ Listar
│   │   ├─ Atualizar
│   │   ├─ Importar
│   │   └─ Exportar
│   ├─ Desfragmentar
│   │   ├─ Analisar
│   │   ├─ Otimizar
│   │   └─ Trim
│   ├─ Gerenciar Administrador
│   │   ├─ Ativar
│   │   └─ Desativar
│   ├─ Verificar Imagem do Sistema
│   │   ├─ Verificar
│   │   └─ Reparar
│   └─ Verificar Instalação do Sistema
│       ├─ Verificar
│       └─ Consolidar
├─ Configurações
│   ├─ Backup
│   │   ├─ Parâmetros
│   │   │   ├─ Drive de Backup
│   │   │   ├─ Drive de Réplica
│   │   │   ├─ Período de Retenção
│   │   │   ├─ Nível de Compressão
│   │   │   ├─ Formatação Automática
│   │   │   └─ Replicação Automática
│   │   └─ Conteúdo
│   │       ├─ Usuário
│   │       │   ├─ Desktop
│   │       │   ├─ Documentos
│   │       │   ├─ Imagens
│   │       │   ├─ Vídeos
│   │       │   ├─ Músicas
│   │       │   ├─ Downloads
│   │       │   ├─ Vault
│   │       │   ├─ Projetos
│   │       │   └─ Softwares
│   │       ├─ Nuvem
│   │       │   ├─ OneDrive
│   │       │   ├─ Google Drive
│   │       │   ├─ iCloud Drive
│   │       │   └─ Dropbox
│   │       └─ Sistema
│   │           ├─ Fontes
│   │           └─ Drivers
│   ├─ Depuração
│   │   ├─ Parâmetros
│   │   │   └─ Período de Retenção
│   │   └─ Conteúdo
|   │       ├─ Arquivos de Sistema
│   │       │   ├─ Diretório Temporário
│   │       │   ├─ Diretório Prefetch
│   │       │   ├─ Windows Update
│   │       │   ├─ Reporte de Erros
│   │       │   └─ Cache DNS
│   │       ├─ Arquivos de Software
│   │       │   ├─ Microsoft Edge
│   │       │   ├─ OneDrive
│   │       │   └─ Epic Games
│   │       └─ Arquivos de Usuário
│   │           ├─ Diretório Temporário
│   │           ├─ Downloads
│   │           ├─ Screenshots
│   │           └─ Lixeira
│   ├─ Temas
│   │   ├─ Violeta
│   │   ├─ Azul
│   │   ├─ Verde
│   │   ├─ Amarelo
│   │   ├─ Vermelho
│   │   ├─ Cosmos
│   │   ├─ Sunrise
│   │   ├─ Sunset
│   │   └─ Aqua
│   ├─ Notificações
│   │   ├─ Software
│   │   ├─ Backup
│   │   ├─ Conversão
│   │   ├─ Depuração
│   │   ├─ Diagnóstico
│   │   └─ Manutenção
│   ├─ Registro de Eventos
│   │   ├─ Status
│   │   ├─ Período de Retenção
│   │   └─ Exibir
│   ├─ Gerenciar
│   │   ├─ Importar
│   │   ├─ Exportar
│   │   └─ Redefinir
│   ├─ Empacotar
│   └─ Desinstalar
├─ Sobre
└─ Encerrar
```

</details>

<details>
<summary>Linux</summary>

```
Home
├─ Backup
│   ├─ Iniciar Backup
│   ├─ Iniciar Réplica
│   └─ Testar Backup
├─ Conversão
│   ├─ 7Z
│   └─ WEBP
├─ Depuração
├─ Diagnóstico
│   └─ Relatório da Bateria
├─ Manutenção
│   ├─ Gerenciar Aplicativos
│   │   ├─ Listar
│   │   ├─ Atualizar
│   │   └─ Exportar
│   └─ Desfragmentar
│       ├─ Analisar
│       ├─ Otimizar
│       └─ Trim
├─ Configurações
│   ├─ Backup
│   │   ├─ Parâmetros
│   │   │   ├─ Drive de Backup
│   │   │   ├─ Drive de Réplica
│   │   │   ├─ Período de Retenção
│   │   │   ├─ Nível de Compressão
│   │   │   └─ Replicação Automática
│   │   └─ Conteúdo
│   │       ├─ Usuário
│   │       │   ├─ Desktop
│   │       │   ├─ Documentos
│   │       │   ├─ Imagens
│   │       │   ├─ Vídeos
│   │       │   ├─ Músicas
│   │       │   ├─ Downloads
│   │       │   ├─ Vault
│   │       │   ├─ Projetos
│   │       │   └─ Softwares
│   │       ├─ Nuvem
│   │       │   └─ Dropbox
│   │       └─ Sistema
│   │           └─ Fontes
│   ├─ Conversão
│   │   ├─ Reprocessar arquivos convertidos
│   │   └─ Preservar originais
│   ├─ Depuração
│   │   ├─ Parâmetros
│   │   │   └─ Período de Retenção
│   │   └─ Conteúdo
|   │       ├─ Arquivos de Sistema
│   │       │   ├─ Diretório Temporário
│   │       │   └─ Reporte de Erros
│   │       └─ Arquivos de Usuário
│   │           ├─ Downloads
│   │           ├─ Screenshots
│   │           └─ Lixeira
│   ├─ Temas
│   │   ├─ Violeta
│   │   ├─ Azul
│   │   ├─ Verde
│   │   ├─ Amarelo
│   │   ├─ Vermelho
│   │   ├─ Cosmos
│   │   ├─ Sunrise
│   │   ├─ Sunset
│   │   └─ Aqua
│   ├─ Notificações
│   │   ├─ Software
│   │   ├─ Backup
│   │   ├─ Conversão
│   │   ├─ Depuração
│   │   ├─ Diagnóstico
│   │   └─ Manutenção
│   ├─ Registro de Eventos
│   │   ├─ Status
│   │   ├─ Período de Retenção
│   │   └─ Exibir
│   ├─ Gerenciar
│   │   ├─ Importar
│   │   ├─ Exportar
│   │   └─ Redefinir
│   ├─ Empacotar
│   └─ Desinstalar
├─ Sobre
└─ Encerrar
```

</details>

## Estrutura
A estrutura de diretórios de software e backup é projetada para proporcionar a separação lógica dos dados, simplificando a manutenção e escalabilidade. Novos componentes, dispositivos e usuários podem ser facilmente integrados sem perturbar a estrutura existente.

<details>
<summary>Windows</summary>

### Software
```
[Usuário] ─┐
           └─ AppData ─┐
                       └─ Local ─┐
                                 └─ DC ─┐                                 | Diretório raiz
                                        └─ Workflow ─┐                    | Diretório de instalação
                                                     ├─ Software          | Diretório de software
                                                     ├─ Events            | Diretório de registro de eventos
                                                     └─ Cache             | Diretório de armazenamento temporário
```

### Backup
```
[Drive] ─┐
         └─ Workflow ─┐                                                   | Diretório raiz
                      └─ [Dispositivo] ─┐                                 | Diretório de controle
                                        └─ [Usuário] ─┐                   | Diretório de controle
                                                      └─ {+}              | Dados
```

</details>

<details>
<summary>Linux</summary>

### Software
```
[Usuário] ─┐
           └─ .DC ─┐                                                      | Diretório raiz
                   └─ Workflow ─┐                                         | Diretório de instalação
                                ├─ Software                               | Diretório de software
                                ├─ Events                                 | Diretório de registro de eventos
                                └─ Cache                                  | Diretório de armazenamento temporário
```

### Backup
```
[Drive] ─┐
         └─ Workflow ─┐                                                   | Diretório raiz
                      └─ [Dispositivo] ─┐                                 | Diretório de controle
                                        └─ [Usuário] ─┐                   | Diretório de controle
                                                      └─ {+}              | Dados
```

</details>

## Código-fonte
Prepare-se para uma jornada emocionante pelo universo do software livre.

<details>
<summary>Fundamentos da licença GPL</summary>

- `Liberdade 0`: Execute o software como quiser, para qualquer finalidade.
- `Liberdade 1`: Explore e ajuste o software conforme suas necessidades.
- `Liberdade 2`: Compartilhe o software para ajudar outras pessoas.
- `Liberdade 3`: Melhore o software e compartilhe suas inovações com a comunidade.

> Verifique [SPDX.org][SPDX.org] para mais informações.

</details>

<details>
<summary>Acesso ao código-fonte</summary>

- Baixe a versão mais recente do software.
- Extraia o pacote com um software compatível.
- Abra o arquivo **ps1** em seu editor de texto ou IDE preferido.
- Aproveite a experiência!

[SPDX.org]: https://spdx.org/licenses/GPL-3.0-or-later.html

</details>

## Softwares de terceiros

<details>
<summary>PowerShell: Como instalar</summary>

- Windows
    - Abra o terminal
    - Instale o pacote `winget install --id Microsoft.PowerShell --source winget`

- Linux
    - Abra o terminal
    - Instale o pacote `snap install powershell`

</details>

<details>
<summary>7-Zip: Como instalar</summary>

- Windows
    - Acesse o [repositório do projeto][7-Zip]
    - Baixe o pacote compatível com a arquitetura do seu dispositivo
    - Execute o instalador

- Linux
    - Método 1 (Desenvolvedor independente)
        - Abra o terminal
        - Instale o pacote `sudo apt install 7zip`
    - Método 2 (Desenvolvedor oficial)
        - Acesse o [repositório do projeto][7-Zip]
        - Baixe o pacote compatível com a arquitetura do seu dispositivo
        - Abra o terminal
        - Descomprima o pacote `tar --extract --file nome_do_pacote.tar.xz`
        - Navegue até o diretório do pacote `cd nome_do_pacote`
        - Copie os binários para o diretório do sistema `sudo cp 7zzs 7zz /usr/local/bin/`

</details>

<details>
<summary>WebP: Como instalar</summary>

- Linux
    - Método 1
        - Abra o terminal
        - Instale o pacote `sudo apt install webp`
    - Método 2
        - Acesse o [repositório do projeto][WebP]
        - Baixe o pacote compatível com a arquitetura do seu dispositivo
        - Abra o terminal
        - Descomprima o pacote `tar --extract --file nome_do_pacote.tar.gz`
        - Navegue até o diretório do pacote `cd nome_do_pacote`
        - Copie o conteúdo do diretório `bin` para o diretório do sistema `sudo cp --recursive bin/* /usr/local/bin/`
        - Copie o conteúdo do diretório `include` para o diretório do sistema `sudo cp --recursive include/* /usr/local/include/`
        - Copie o conteúdo do diretório `lib` para o diretório do sistema `sudo cp --recursive lib/* /usr/local/lib/`

</details>

<details>
<summary>Fontes: Como instalar</summary>

Para um design agradável, moderno e sofisticado no terminal, prefira a fonte [JetBrains Mono][JetBrains Mono]. Adicionalmente você pode utilizar a [Cascadia Code][Cascadia Code] ou a [Ubuntu Family][Ubuntu Family].

- Windows
    - Método 1
        - Clique com o botão direito do mouse no arquivo de fonte
        - Clique em Instalar
    - Método 2 (Windows 10 ou superior)
        - Copie a fonte para o diretório do sistema `C:\Windows\Fonts`
- Linux
    - Método 1
        - Clique com o botão direito do mouse no arquivo de fonte
        - Clique em Instalar
    - Método 2
        - Copie a fonte para o diretório do sistema `sudo cp * /usr/local/share/fonts`
        - Atualize o cache de fontes do sistema `sudo fc-cache --force --verbose`

</details>

<details>
<summary>Windows: Acesso a Pastas Controladas</summary>

Alguns recursos precisam de acesso a pastas de usuário ou aplicativos. Adicione o PowerShell e o 7-Zip ao Acesso a Pastas Controladas nas configurações de segurança do Windows.

</details>

[Evolução]: /Evolution.md
[Política de Suporte]: /SUPPORT.md
[7-Zip]: https://github.com/ip7z/7zip
[WebP]: https://developers.google.com/speed/webp/docs/precompiled
[JetBrains Mono]: https://github.com/JetBrains/JetBrainsMono
[Cascadia Code]: https://github.com/microsoft/cascadia-code
[Ubuntu Family]: https://design.ubuntu.com/font