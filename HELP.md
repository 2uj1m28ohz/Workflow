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
|`•`|NavBit|Sinaliza funcionalidades executadas e telas visualizadas|
|`│`|Status|Sinaliza configurações habilitadas|
|`■`|Pixel|Exibe a palheta de cores da Interface|

### Instalação
1. Ao executar o software pela primeira vez recebo uma notificação de incompatibilidade.

    Durante o carregamento o software verifica diversas informações do ambiente para garantir que seja executado em um cenário mínimo de compatibilidade, os requisitos de sistema. Você pode verificar os requisitos de sistema na página de download da versão. Após solucionar a incompatibilidade, execute o software novamente.

2. A versão de software que estou executando não é instalada automaticamente.

    Você está executando uma versão de software sem suporte. Versões sem suporte não podem ser instaladas. Baixe a versão mais recente para prosseguir com a instalação do software. Consulte [Evolução](https://github.com/2uj1m28ohz/workflow/blob/main/Evolution.md) e [Política de Suporte](https://github.com/2uj1m28ohz/workflow/blob/main/SUPPORT.md) para mais informações.

### Atualização
1. Como manter o software atualizado?

    Workflow verifica, baixa e instala atualizações automaticamente, trazendo correções, otimizações e novos recursos na velocidade da luz. Basta executá-lo regularmente para manter o software atualizado.

2. Como corrigir o erro "*Hash incompatível*"?

    Este erro pode ser exibido durante a instalação ou atualização de software, quando Workflow verifica a integridade dos pacotes de software baixados da Internet, ou ainda caso uma alteração ilegal seja detectada no algoritmo do software. Em todos os cenários você não precisa tomar qualquer ação, os pacotes de software não são aplicados e a integridade de Workflow é restaurada automaticamente.

3. Após uma atualização de software uma notificação de incompatibilidade é exibida.

    Verifique os requisitos de sistema na página de download da versão. Após solucionar a incompatibilidade, execute o software novamente.

4. O software está instalado, no entanto não recebe novas atualizações.

    A [Política de Suporte](https://github.com/2uj1m28ohz/workflow/blob/main/SUPPORT.md) determina quantas versões estão sujeitas à garantia de atualização de software. Possivelmente o software não tenha sido executado há muito tempo, perdendo a compatibilidade e portanto, impossibilitado de receber atualizações automaticamente. Para solucionar, prossiga com a desinstalação manual da versão instalada, baixe e instale a versão de software mais recente.

### Backup e Restauração
1. Ao restaurar um backup o software apresenta o erro "*Diretório não encontrado*".

    Games selecionados como EVE Online, Survivings Mars, Aven Colony e Insdustries Of Titan tem opções de restauração de backup. Ao utilizá-las, Workflow busca pelo formato de arquivo
    compactado configurado no software. Este erro pode significar que um backup não foi previamente criado, portanto não pode ser restaurado, ou que o backup foi criado usando um formato de compactação diferente do que está atualmente configurado no software.
    
    Verifique se há um backup disponível para ser restaurado, e se ele está no mesmo formato da configuração de software. Caso esteja em um formato diferente, basta alterar a configuração de software temporariamente para o mesmo formato de compactação do arquivo de backup.

2. Porque não há opções de restauração de backup para os dados do usuário, OneDrive e drivers de sistema?

    Como você pode imaginar, a manipulação de dados pessoais e de sistema pode ser bastante delicada. Há grandes riscos ao disponibilizar opções automatizadas de restauração dessa classe de dados, o que pode implicar em perda de informações ou incompatibilidade ao subscrever dados atualizados por suas versões antigas quando em uma ação não intencional desastrosa. Desta forma, optou-se por não permitir a automatização da restauração de dados do usuário e de sistema, que deve ser feita intencional, consciente e manualmente pelo usuário a partir do arquivo de backup.

### Configurações
1. É possível desabilitar notificações no desktop?

    Para desabilitar notificações[^1] no desktop siga para o menu Configurações > Notificações > Sistema > Desabilitar.

2. É possível desabilitar o Registro de Eventos?

    Para desabilitar o Registro de Eventos[^2] siga para o menu Configurações > Registro de Eventos > Status > Desabilitar.

3. É possível alterar o período de retenção do Registro de Eventos?

    Para alterar o período de retenção siga para o menu Configurações > Registro de Eventos > Período e escolha uma entre as opções disponíveis.

### Modo Rollback
1. O que é o Modo Rollback?

    O Modo Rollback é um recurso desenhado para impedir que a execução de uma versão de software inferior comprometa as configurações de software da versão atual. Quando ativado, qualquer alteração nas configurações são perdidadas ao encerrar o software.

2. Como ativar o Modo Rollback?

    O Modo Rollback é ativado automaticamente caso você execute manualmente uma versão de software inferior a versão disponível.

3. Como desativar o Modo Rollback?

    Não é possível desativar o Modo Rollback manualmente. Para retornar ao modo de execução normal basta executar o software a partir do local de instalação, sinalizado no atalho criado no desktop do usuário.

[^1]:Notificações de compatibilidade não podem ser desabilitadas.
[^2]:Verifique a [Política de Suporte](https://github.com/2uj1m28ohz/workflow/blob/main/SUPPORT.md) para mais informações.
