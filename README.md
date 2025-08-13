# ⭕ Jogo da Velha - Hackathon 1000 Devs

Um jogo da velha interativo e customizável desenvolvido em Java como desafio do Hackathon 1000 Devs, com tabuleiros dinâmicos e personalizações avançadas.

## 🏆 Hackathon 1000 Devs

Este projeto foi desenvolvido durante o **Hackathon 1000 Devs**, um evento focado em incentivar a criatividade, colaboração em equipe e desenvolvimento de soluções inovadoras.

**Desafio:** Criar um jogo da velha diferenciado com funcionalidades personalizáveis.

## 👥 Equipe - Grupo 3

| Membro | GitHub |
|--------|---------|
| **Ana Vitória** | [@ana-vitoria](https://github.com/ana-vitoria) |
| Audrey | [@audrey](https://github.com/audrey) |
| David | [@david](https://github.com/david) |
| Caio | [@caio](https://github.com/caio) |
| Angel | [@angel](https://github.com/angel) |
| Cauã | [@caua](https://github.com/caua) |
| Renan | [@renan](https://github.com/renan) |
| Letícia | [@leticia](https://github.com/leticia) |

## ✨ Funcionalidades

### 🎮 Jogabilidade
- **Tabuleiros Customizáveis**: Tamanho definido pelo jogador (3x3, 4x4, 5x5...)
- **Caracteres Personalizados**: Escolha entre `X`, `O`, `0`, `U`, `C` para jogador e CPU
- **Início Aleatório**: Sistema de sorteio para definir quem começa
- **Interface Terminal**: Visualização clara e atualizada do tabuleiro

### 🤖 Inteligência
- **CPU Inteligente**: Jogadas automáticas com validação
- **Detecção de Vitória**: Verificação automática de linhas, colunas e diagonais
- **Sistema de Empate**: Detecção quando todas posições estão ocupadas
- **Validação de Jogadas**: Impede movimentos inválidos

### 💫 Experiência do Usuário
- **Console Limpo**: Atualização automática da tela entre turnos
- **Feedback Visual**: Mensagens claras de status do jogo
- **Alternância Fluida**: Transição suave entre turnos de jogador e CPU

## 🛠️ Tecnologias

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

| Tecnologia | Versão | Finalidade |
|-----------|---------|------------|
| Java | 11+ | Linguagem principal |
| VS Code | Latest | Ambiente de desenvolvimento |

## 🏗️ Arquitetura

### Estrutura do Projeto
```
jogo-da-velha/
├── src/
│   └── Main.java
├── docs/
│   └── README.md
└── .gitignore
```

### Principais Componentes

#### 🎯 Classe Principal (`Main`)
- **Controle do fluxo principal** do jogo
- **Inicialização** de configurações
- **Loop principal** de execução

#### ⚙️ Funções Core
```java
// Principais métodos implementados
criarTabuleiro()          // Inicializa matriz do jogo
processarTurnoUsuario()   // Gerencia jogada do player
processarTurnoCPU()       // Controla movimento da CPU
validarJogada()           // Verifica se movimento é válido
verificarVitoria()        // Detecta condições de fim de jogo
exibirTabuleiro()         // Renderiza estado atual
```

## 🚀 Como Executar

### Pré-requisitos
- Java 11 ou superior
- VS Code (recomendado) ou qualquer IDE Java

### Instalação
```bash
# Clone o repositório
git clone [url-do-repositorio]

# Navegue até o diretório
cd jogo-da-velha

# Compile o projeto
javac src/Main.java

# Execute o jogo
java -cp src Main
```

## 🎮 Como Jogar

1. **Configuração Inicial**
   - Defina o tamanho do tabuleiro desejado
   - Escolha seu caractere (X, O, 0, U, C)
   - Sistema sorteia quem inicia

2. **Durante o Jogo**
   - Digite as coordenadas da sua jogada
   - Acompanhe as jogadas da CPU
   - Observe a verificação automática de vitória

3. **Fim de Partida**
   - Vitória por linha, coluna ou diagonal
   - Empate quando tabuleiro fica completo
   - Opção de jogar novamente

## 🏅 Destaques Técnicos

- **Algoritmo Dinâmico**: Suporte a tabuleiros NxN
- **Validação Robusta**: Prevenção de jogadas inválidas
- **Interface Limpa**: Sistema de limpeza de console
- **Código Modular**: Funções bem definidas e reutilizáveis

## 🚧 Futuras Melhorias

- [ ] Modo multiplayer local
- [ ] Diferentes níveis de dificuldade da CPU
- [ ] Sistema de pontuação
- [ ] Interface gráfica (Swing/JavaFX)
- [ ] Histórico de partidas

## 🤝 Contribuições

Este projeto foi desenvolvido colaborativamente durante o Hackathon. Contribuições futuras são bem-vindas!

## 📄 Licença

Projeto desenvolvido para fins educacionais durante o Hackathon 1000 Devs.

---

**⭐ Desenvolvido com dedicação pelo Grupo 3 durante o Hackathon 1000 Devs** ⭐
