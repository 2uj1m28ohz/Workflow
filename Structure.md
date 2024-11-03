# :building_construction: Estrutura
A estrutura de diretórios de software e backup é projetada para proporcionar a separação lógica dos dados, simplificando a manutenção e escalabilidade. Novos componentes, dispositivos e usuários podem ser facilmente integrados sem perturbar a estrutura existente.

## :window: Windows
### Software
```
[Usuário] ─┐
           └─ AppData ─┐
                       └─ Local ─┐
                                 └─ DC ─┐                                      | Diretório raiz
                                        └─ Workflow ─┐                         | Diretório de instalação
                                                     ├─ Software               | Diretório de software
                                                     ├─ Events                 | Diretório de registro de eventos
                                                     └─ Cache                  | Diretório de armazenamento temporário
```

### Backup
```
[Drive] ─┐
         └─ Workflow ─┐                                                        | Diretório raiz
                      └─ [Dispositivo] ─┐                                      | Diretório de controle
                                        └─ [Usuário] ─┐                        | Diretório de controle
                                                      └─ {+}                   | Dados
```

## :penguin: Linux
### Software
```
[Usuário] ─┐
           └─ .DC ─┐                                                           | Diretório raiz
                   └─ Workflow ─┐                                              | Diretório de instalação
                                ├─ Software                                    | Diretório de software
                                ├─ Events                                      | Diretório de registro de eventos
                                └─ Cache                                       | Diretório de armazenamento temporário
```

### Backup
```
[Drive] ─┐
         └─ Workflow ─┐                                                        | Diretório raiz
                      └─ [Dispositivo] ─┐                                      | Diretório de controle
                                        └─ [Usuário] ─┐                        | Diretório de controle
                                                      └─ {+}                   | Dados
```
