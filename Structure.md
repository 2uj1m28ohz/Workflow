## :building_construction: Estrutura

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
> Esta é uma representação da estrutura da versão de software mais recente.
