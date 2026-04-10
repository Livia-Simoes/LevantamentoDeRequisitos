# Curso Sistemas Operacionais - 90H (120Aulas)

## Módulo 1 - Introdução a Sistemas Operacionais

### Aula 1 -  Apresentação do Curso

### Aula 2 - Sistemas Operacionais e Sistemas de Arquivos

- O que é Sistema Operacional
    - Kernel
    - Shell
    - Programas
    - Interfaces:
        - GUI
        - CLI
- Sistema de Arquivos
    - Tipos de Armazenamentos
    - Sistemas de Armazenamento
        - FAT32
        - NTFS
        - EXT4
        - APFS
- Tipos de Sistemas Operacionais
  - Código Fechado (Licença de Uso)
     - Win e MacOS(IOS - Celular)
  - Código Aberto (copyleft)
     - Linux (diversas distros)
     - Android (Sistema google é fechado)
## Módulo 2 - Sistema Operacional de Código fechado (windows)

### Introdução ao Ecossistema windows
- Histórico 
    - MS-DOS (sistema CLI)
    - Wind 95 e 98 (cascata sobre o MS-DOS)
    - Win xp (baseado no NT)
        - interface GUI mais robusta
    - Win Vista, 7, 8, 8.1 (base do NT)
    - Win 10, Win 11 (mais recente)
- Download do Win
    - baixar a ISO (formato para fazer boot) diretamente do site da Microsoft
    - Instalar do Media Create Tool
      - Baixar a ISO ou criar um pendrive Bootável
    - usar o assistente 
      - Atualiza o sistema da Máquina Atual 
-Virtualização
  - virtualização de hardware (profissional)
    - usada em servidores para criar vários sistemas operacionais em uma única máquina 
      - sistema em desuso (sistemas em nuvem vem ganhando mercado)
  - Virtualização de SO (host/guest)
      - criação de Guest (VM)
  - Quando usar virtualização 
      - utilização de sistemas antigos, precisa rodar um SO mais antigo 
      - teste em sistemas operacionais (linux, IOS e android)
- instalação de SO em MUndo Real 
    - Baixar ISO
    - Utilizar Rufus para criar um pendrive Bootável (inicializável)
    - permite a instalação do SO em diversas Máquinas de forma rápida
    - utilização de softwares de clonagem
      - Wimpe, Ghost, clonezilla 
       - permite a cópia de máquinas já configuradas (com SO e softwares instalados) 

### Operação em Modo Gráfico (GUI)      
- dualidade da interface
    - menu de configurações (UWP): voltado para a experiencia do usuário 
    - painel de controle (Win32): motor do sistema, configurações mais avançadas 

- métricas de desempenho: 
   - Gargalo do sistema:
      - CPU:
      - disco:
      - memória:
         - quando a memória atinge 100% - SWAP (usar memória de armazenamento para processamento) - melhor com SSD 
- ferramentas de administração e gerenciamento 
   - diskngmt.msc (gerenciamento de disco)
      - FAT32 e NTFS (controle de acesso)
   - controle de acesso:
      - herança de permissões: pasta herda as características da pasta superior 
      - desabilitar herança é negar acesso a todos os outros usuários
      - adicionar manualmente o acesso 
      - controle total: "cuidado" 
