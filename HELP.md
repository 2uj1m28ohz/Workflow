## :parachute: Ajuda
### Interface
Elementos são uma forma simples de compreender a execução e a interface do software:

|Elemento|Nome|Descrição|
|:---:|:---|:---|
|`¬`|Título|Destaca o nome da tela ou funcionalidade e exibe o local atual|
|`*`|Descrição|Destaca a descrição da tela ou funcionalidade|
|`!`|Notificação|Sinaliza lembretes e informações relevantes|
|`→`|Execução|Sinaliza progresso na execução do software|
|`+`|Expansor|Sinaliza que há um submenu disponível|
|`›`|Separador|Sinaliza níveis da árvore de menus|
|`‹`|Recomendado|Sinaliza configurações recomendadas|
|`•`|NavBit|Sinaliza funcionalidades executadas e telas visualizadas|
|`│`|Status|Sinaliza configurações habilitadas|
|`■`|Pixel|Exibe a palheta de cores da Interface|

### Instalação
1. Ao executar o software pela primeira vez recebo uma notificação de incompatibilidade.

    Durante o carregamento o software verifica diversas informações do ambiente para garantir que seja executado em um cenário mínimo de compatibilidade, os requisitos de sistema. Você pode verificar os requisitos de sistema na página de download da versão. Após solucionar a incompatibilidade, execute o software novamente.

2. A versão de software que estou executando não é instalada automaticamente.

    Você está executando uma versão de software sem suporte. Versões sem suporte não podem ser instaladas. Baixe a versão mais recente para prosseguir com a instalação do software. Consulte [Evolução](https://github.com/2uj1m28ohz/workflow/blob/main/Evolution.md) e [Política de Suporte](https://github.com/2uj1m28ohz/workflow/blob/main/SUPPORT.md) para mais informações.

3. Porque o arquivo de atalho Workflow.ps1 não está presente na home do usuário?

    Navegue até o diretório home do usuário utilizando o comando `Set-Location $Home`. Caso o arquivo `Workflow.ps1` não esteja presente, verifique a seção **Acesso a Pastas Controladas** logo abaixo. Em seguida execute Workflow manualmente utilizando a [Estrutura](https://github.com/2uj1m28ohz/Workflow/blob/main/Structure.md) para localizar o diretório de instalação do software. Workflow recriará o atalho automaticamente.

### Atualização
1. Como manter o software atualizado?

    Workflow verifica, baixa e instala atualizações automaticamente, trazendo correções, otimizações e novos recursos na velocidade da luz. Basta executá-lo regularmente para manter o software atualizado.

2. Como corrigir o erro "*Hash incompatível*"?

    Este erro pode ser exibido durante a instalação ou atualização de software, quando Workflow verifica a integridade dos pacotes de software baixados da Internet, ou ainda caso uma alteração ilegal seja detectada no algoritmo do software. Em todos os cenários você não precisa tomar qualquer ação, os pacotes de software não são aplicados e a integridade de Workflow é restaurada automaticamente.

3. Após uma atualização de software uma notificação de incompatibilidade é exibida.

    Verifique os requisitos de sistema na página de download da versão. Após solucionar a incompatibilidade, execute o software novamente.

4. O software está instalado, no entanto não recebe novas atualizações.

    A [Política de Suporte](https://github.com/2uj1m28ohz/workflow/blob/main/SUPPORT.md) determina quantas versões estão sujeitas à garantia de atualização de software. Possivelmente o software não tenha sido executado há muito tempo, perdendo a compatibilidade e portanto, impossibilitado de receber atualizações automaticamente. Para solucionar, prossiga com a desinstalação manual da versão instalada, baixe e instale a versão de software mais recente.

### Backup de Dados
1. Eu posso selecionar o que incluir no backup?

    Sim, você pode escolher o que incluir no backup habilitando e desabilitando as opções disponíveis no menu Configurações > Backup > Conteúdo.

2. O que significa suporte a multidispositivos e multiusuários?

    O suporte à multidispositivos e multiusuários do Backup de Dados permite que sejam adicionados backups de diversos dispositivos e usuários à mesma estrutura de backup presente no drive de backup.

3. Outro usuário pode fazer backup dos meus dados?

    Não. Workflow é executado a nível de usuário, portanto os dados dos demais usuários não são tocados.

4. Quais as vantagens da tabela de partições GPT para o backup de dados?

    - Recuperação de dados simplificada: A GPT utiliza redundância de tabela de partições em várias áreas do disco, o que torna a recuperação de dados mais fácil em caso de corrupção ou falha no disco. Se uma cópia da tabela de partições for danificada, o sistema pode usar as cópias de backup para restaurar as informações de partição corretas.

    - Identificação única global: Cada partição em um disco GPT possui um identificador único global (GUID). Isso facilita a identificação e seleção correta das partições durante o processo de backup, garantindo que os dados corretos sejam copiados.

    - Suporte a discos grandes: A GPT é capaz de lidar com unidades de armazenamento de grande capacidade, o que é benéfico para backups de dados volumosos. Se você precisa fazer o backup de grandes quantidades de dados, a GPT permitirá aproveitar ao máximo a capacidade do disco de backup.

    - Compatibilidade com sistemas operacionais modernos: A GPT é reconhecida nativamente por sistemas operacionais modernos e firmware, como o UEFI. Isso garante uma melhor compatibilidade e interoperabilidade ao fazer backup e restaurar dados em diferentes sistemas.

5. Quais as vantagens do sistema de arquivos NTFS para o backup de dados?

    - Suporte a arquivos grandes: O NTFS tem suporte nativo para arquivos grandes, permitindo que você faça backup de arquivos de tamanho significativo. Isso é particularmente útil para backups de vídeos, imagens de disco ou qualquer outro tipo de arquivo que exceda os limites de tamanho de outros sistemas de arquivos.

    - Recuperação de dados: O NTFS possui recursos de recuperação de dados integrados. Ele mantém cópias de backup das informações críticas do sistema de arquivos, como a tabela de alocação de arquivos (MFT - Master File Table). Em caso de corrupção de dados ou falhas no disco, o sistema de arquivos NTFS pode recuperar automaticamente as informações corretas, reduzindo a probabilidade de perda de dados durante o backup.

    - Integridade do sistema de arquivos: O NTFS possui mecanismos de verificação e reparação de integridade do sistema de arquivos. Durante o backup, esses mecanismos podem identificar e corrigir erros ou setores defeituosos no disco, garantindo a integridade dos dados armazenados e evitando a propagação de erros durante o processo de backup.

6. Quais as vantagens de clusters de 64 KB para o backup de dados?

    - Eficiência de armazenamento: O tamanho do cluster determina a quantidade mínima de espaço em disco alocada para cada arquivo. Com clusters maiores, como 64 KB, há menos sobrecarga em termos de espaço em disco desperdiçado devido ao tamanho mínimo alocado para cada arquivo. Isso pode ser particularmente benéfico ao fazer backup de muitos arquivos pequenos, pois reduz o espaço desperdiçado em relação a clusters menores.

    - Desempenho do backup: Ao fazer o backup de arquivos grandes, um tamanho de cluster maior pode melhorar o desempenho geral do processo de backup. Isso ocorre porque o tamanho do cluster determina o número de operações de leitura/gravação necessárias para copiar um arquivo. Com um cluster maior, menos operações são necessárias para copiar um arquivo grande, resultando em um tempo de backup menor.

    - Fragmentação reduzida: O tamanho do cluster também está relacionado à fragmentação do disco. Com clusters maiores, há menos chances de fragmentação de arquivos ocorrer, o que pode melhorar o desempenho do acesso aos dados durante a restauração de backups.

    - Desempenho do sistemas de arquivos: O tamanho do cluster pode ser especialmente benéfico em sistemas de arquivos que são otimizados para tamanhos de cluster maiores, como o sistema de arquivos NTFS. O NTFS tende a ter um desempenho melhor com clusters maiores, e um tamanho de cluster de 64 KB pode oferecer uma boa combinação de eficiência de armazenamento e desempenho.

### Configuração
1. É possível desabilitar notificações na Central de Notificações?

    Siga para o menu Configurações > Notificações > Status

2. É possível desabilitar o Registro de Eventos[^1]?

    Siga para o menu Configurações > Registro de Eventos > Status

3. É possível alterar o período de retenção do Registro de Eventos?

    Siga para o menu Configurações > Registro de Eventos > Retenção

4. Porque a opção Empacotar não exporta os hashes dos pacotes?

    Para exportar os hashes dos pacotes, habilite o Registro de Eventos.

5. Como faço o backup das configurações de software?

    - Siga para o menu Configurações > Exportar
    - Abra o Executar com Win+R
    - Digite `%UserProfile%\Downloads` e clique em Ok
    - Faça backup do arquivo `WorkflowSettingsBackup.json`

6. Como faço para transferir[^2] as configurações de software para um novo dispositivo?

    No dispositivo antigo:
    - Siga para o menu Configurações > Exportar
    - Abra o Executar com Win+R
    - Digite `%UserProfile%\Downloads` e clique em Ok
    - Copie o arquivo `WorkflowSettingsBackup.json`

    No dispositivo novo:
    - Efetue a instalação de software
    - Abra o Executar com Win+R
    - Digite `%UserProfile%\Downloads` e clique em Ok
    - Cole o arquivo `WorkflowSettingsBackup.json`
    - Siga para o menu Configurações > Importar

### Modo Rollback
1. O que é o Modo Rollback?

    O Modo Rollback é um recurso desenhado para impedir que a execução de uma versão de software inferior comprometa as configurações de software da versão atual. Quando ativado, qualquer alteração nas configurações são perdidadas ao encerrar o software.

2. Como ativar o Modo Rollback?

    O Modo Rollback é ativado automaticamente caso você execute manualmente uma versão de software inferior a versão disponível.

3. Como desativar o Modo Rollback?

    Não é possível desativar o Modo Rollback manualmente. Para retornar ao modo de execução normal, basta seguir as instruções disponíveis no [repositório](https://github.com/2uj1m28ohz/workflow).

### Acesso a Pastas Controladas
Alguns recursos de software requerem acesso à leitura e gravação de dados em pastas controladas, como pastas de usuário e aplicativos de terceiros. Para autorizar o acesso abra o aplicativo **Segurança do Windows** e adicione os executáveis do PowerShell e do 7-Zip à lista de aplicativos permitidos.

[^1]:Verifique a [Política de Suporte](https://github.com/2uj1m28ohz/workflow/blob/main/SUPPORT.md) para mais informações.
[^2]:Configurações de identificação e segurança do software não são transferidas.
