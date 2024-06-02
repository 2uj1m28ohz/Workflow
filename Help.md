# :parachute: Ajuda
Este é um guia de instalação e execução de software. Encontre soluções para problemas comuns, além de instruções de atualização, configurações de software, e dicas para o uso de funcionalildades.

## Instalação
1. Como Instalar
- Baixe e descomprima o pacote
- Execute o PowerShell
- Habilite a execução de scripts
```
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser -Force
```
- Desbloqueie o script
```
Get-Item Workflow.ps1 | Unblock-File
```
- Execute o script
```
.\Workflow.ps1
```

2. Como Executar
- Navegue até o diretório home
```
Set-Location $Home
```
- Execute o script
```
.\Workflow.ps1
```

3. Ao executar o software pela primeira vez recebo uma notificação de incompatibilidade.

    Durante o carregamento o software verifica diversas informações do ambiente para garantir que seja executado em um cenário mínimo de compatibilidade, os requisitos de sistema. Você pode verificar os requisitos de sistema na página de download da versão. Após solucionar a incompatibilidade, execute o software novamente.

4. A versão de software que estou executando não é instalada automaticamente.

    Você está executando uma versão de software sem suporte. Versões sem suporte não podem ser instaladas. Baixe a versão de software mais recente para prosseguir com a instalação. Consulte [Evolução](https://github.com/2uj1m28ohz/Workflow/blob/main/Evolution.md) e [Política de Suporte](https://github.com/2uj1m28ohz/Workflow/blob/main/SUPPORT.md) para mais informações.

5. Não consigo localizar o atalho Workflow.ps1 na home do usuário.

    Navegue até o diretório home do usuário utilizando o comando `Set-Location $Home`. Caso o arquivo `Workflow.ps1` não esteja presente, verifique a seção **Acesso a Pastas Controladas** logo abaixo. Em seguida execute Workflow manualmente utilizando a [Estrutura](https://github.com/2uj1m28ohz/Workflow/blob/main/Structure.md) para localizar o diretório de instalação do software. Workflow recriará o atalho automaticamente.

## Atualização
1. Como manter o software atualizado?

    Para receber atualizações de software basta estar conectado à Internet e executá-lo ao menos uma vez ao mês. Atualizações são baixadas e instaladas automaticamente durante a inicialização quando disponíveis.

2. Como corrigir o erro "*Hash incompatível*"?

    Este erro pode ser exibido durante a instalação ou atualização de software, quando Workflow verifica a integridade dos pacotes de software baixados da Internet, ou caso uma alteração ilegal seja detectada no algoritmo do software. Em todos os cenários você não precisa tomar qualquer ação, os pacotes inválidos de software não são aplicados e a integridade de Workflow é restaurada automaticamente.

3. Após uma atualização de software uma notificação de incompatibilidade é exibida.

    Verifique os requisitos de sistema na página de download da versão. Após solucionar a incompatibilidade, execute o software novamente.

4. O software está instalado, no entanto não recebe novas atualizações.

    Possivelmente o software não tenha sido executado há algum tempo, perdendo a compatibilidade e, portanto, impossibilitado de receber atualizações automaticamente. Prossiga com a desinstalação manual e a instalação da versão de software mais recente.

## Backup de Dados
1. Posso selecionar o que incluir no backup?

    Sim, você pode escolher o que incluir no backup habilitando e desabilitando as opções disponíveis no menu Configurações > Backup > Conteúdo.

2. Porque não é possível fazer backup do armazenamento em núvem vinculado à minha conta corporativa?

    Contas corporativas podem utilizar nomes de usuario e diretórios, além de caminhos diferentes dos padrões encontrados em contas pessoais naturalmente esperadas pelo software.

3. O que significa suporte a multidispositivos e multiusuários?

    O suporte à multidispositivos e multiusuários do Backup de Dados permite que sejam adicionados backups de diversos dispositivos e usuários à mesma estrutura de backup presente no drive de backup.

4. Outro usuário pode fazer backup dos meus dados?

    Não. Workflow é executado a nível de usuário, portanto os dados dos demais usuários não são tocados.

5. O que é Vault?

    Vault é o nome padrão de um diretório, localizado dentro do diretório do usuário, onde você pode armazenar informações relevantes para serem adicionadas ao backup de dados. Vault não existe naturalmente, portanto, precisa ser criado pelo usuário. Por conter informações importantes, é altamente recomendado adicioná-lo à configuração de Acesso a Pastas Controladas no aplicativo Segurança do Windows.

## Configuração
1. É possível desabilitar notificações na Central de Notificações?

    Siga para o menu Configurações > Notificações

2. É possível desabilitar o Registro de Eventos?

    Siga para o menu Configurações > Registro de Eventos > Status

3. É possível alterar o período de retenção do Registro de Eventos?

    Siga para o menu Configurações > Registro de Eventos > Período de Retenção

4. Porque a opção Empacotar não exporta os hashes dos pacotes?

    Para exportar os hashes dos pacotes, habilite o Registro de Eventos.

5. Como faço o backup das configurações de software?

    - Siga para o menu Configurações > Gerenciar > Exportar
    - Abra o Executar com Win+R
    - Digite `%UserProfile%\Downloads` e clique em Ok
    - Faça backup do arquivo `WorkflowSettingsBackup.json`

6. Como faço para transferir as configurações de software para um novo dispositivo?

    No dispositivo antigo:
    - Siga para o menu Configurações > Gerenciar > Exportar
    - Abra o Executar com Win+R
    - Digite `%UserProfile%\Downloads` e clique em Ok
    - Copie o arquivo `WorkflowSettingsBackup.json`

    No dispositivo novo:
    - Efetue a instalação de software
    - Abra o Executar com Win+R
    - Digite `%UserProfile%\Downloads` e clique em Ok
    - Cole o arquivo `WorkflowSettingsBackup.json`
    - Siga para o menu Configurações > Gerenciar > Importar

> [!NOTE]
> Informações de identificação e segurança não são transferidas.

## Modo Rollback
1. O que é o Modo Rollback?

    O Modo Rollback é um recurso desenhado para impedir que a execução de uma versão de software inferior comprometa as configurações de software da versão atual. Quando ativado, qualquer alteração nas configurações são perdidadas ao encerrar o software.

2. Como ativar o Modo Rollback?

    O Modo Rollback é ativado automaticamente caso você execute manualmente uma versão de software inferior a versão disponível.

3. Como desativar o Modo Rollback?

    Não é possível desativar o Modo Rollback manualmente.

## Acesso a Pastas Controladas
Alguns recursos de software requerem acesso à leitura e gravação de dados em pastas controladas, como pastas de usuário e aplicativos de terceiros. Adicione o PowerShell e o 7-Zip à configuração de Acesso a Pastas Controladas no aplicativo Segurança do Windows.
