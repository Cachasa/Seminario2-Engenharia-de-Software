# **Plano de Testes**

#### **1. Objetivo dos testes**

Verificar o funcionamento geral do sistema de compartilhamento da Biblioteca Steam, garantindo que as funcionalidades de criação e gerenciamento de famílias, compartilhamento de jogos, controle de contas limitadas e registro de atividades funcionem conforme o esperado.

#### **2. Funcionalidades que serão testadas**

- Criação de famílias;
    
- Compartilhamento da biblioteca de jogos entre os membros;
    
- Verificação das restrições de contas limitadas;
    
- Aceitação de convites para participar de uma família;
    
- Saída e reentrada de membros em uma mesma família;
    
- Acesso e execução de jogos pertencentes à biblioteca de outro familiar;
    
- Registro de ações no histórico de atividades (logs).
    

#### **3. Funcionalidades que não serão testadas**

- Tentativa de remoção de outro membro por um usuário sem autorização;
    
- Bloqueio ou restrição do acesso a jogos específicos;
    
- Funcionalidades de controle parental;
    
- Funcionalidades que não estejam diretamente relacionadas ao compartilhamento da Biblioteca Steam.
    

#### **4. Ambiente utilizado**

Os testes serão realizados utilizando a plataforma Steam, em dois computadores desktop:

- **Computador 1:** Processador Intel Core i5 de 12ª geração, 32 GB de memória RAM, placa de vídeo Radeon RX 9060 XT e Windows 11.
    
- **Computador 2:** Processador AMD Ryzen 7 2700, 16 GB de memória RAM, placa de vídeo NVIDIA RTX 2060 de 6 GB e Windows 11.
    

#### **5. Tipos de testes que serão executados**

- **Testes funcionais:** verificar se as funcionalidades de criação de famílias, compartilhamento de jogos e gerenciamento de membros funcionam corretamente.
    
- **Testes de permissões:** verificar as restrições impostas às contas limitadas e as condições necessárias para participar de uma família.
    
- **Testes de integração:** verificar a comunicação entre diferentes contas Steam e o compartilhamento de jogos entre os dispositivos.
    
- **Testes de registro:** verificar se as ações realizadas pelos membros são registradas corretamente no histórico de atividades.
    

**Cenários específicos:**

1. **Criação de família com conta limitada:** verificar se uma conta que não realizou o gasto mínimo exigido (5 dólares) pela Steam consegue criar uma família e se o sistema apresenta a mensagem de restrição esperada.
    
2. **Saída e reentrada na mesma família:** verificar se um membro consegue sair voluntariamente de uma família e posteriormente retornar por meio de um novo convite sem a restrição de 1 ano.
    
3. **Mensagens no histórico de logs:** verificar se a criação de uma família é registrada corretamente no histórico, apresentando o nome do responsável e o nome da família.
    
4. **Abertura de jogos de outro familiar:** verificar se um membro consegue visualizar, baixar e executar um jogo pertencente à biblioteca de outro integrante, desde que não haja outro membro utilizando aquela cópia do jogo.
    

