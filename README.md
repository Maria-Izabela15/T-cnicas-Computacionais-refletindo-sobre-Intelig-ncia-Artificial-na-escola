# T-cnicas-Computacionais-refletindo-sobre-Intelig-ncia-Artificial-na-escola
# 🤖 Você decide o futuro da IA

Um jogo interativo de tomada de decisões baseado em perguntas e respostas sobre o impacto e o futuro da Inteligência Artificial na sociedade. À medida que o jogador escolhe suas respostas, uma narrativa personalizada é construída para mostrar o cenário da sua vida no ano de 2049.

## 🚀 Funcionalidades

- **Narrativa Ramificada:** Suas escolhas determinam o rumo das próximas perguntas e o desfecho da história.
- **Geração de Perfil Aleatório:** O jogo sorteia um nome próprio no início de cada partida para personalizar a conclusão.
- **Respostas Dinâmicas:** Sistema que sorteia reflexões e afirmações com base nas decisões tomadas.
- **Interface Responsiva:** Visual moderno e adaptável para diferentes tamanhos de tela, com suporte a transições e efeitos de *hover*.

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as tecnologias web fundamentais de forma modular (utilizando ES Modules):

- **HTML5:** Estruturação das caixas de perguntas, alternativas e telas do jogo.
- **CSS3:** Estilização baseada em variáveis de escopo global (`:root`) com uma paleta de cores voltada para o tema "Cyberpunk/Sci-Fi".
- **JavaScript (ES6+):** Manipulação dinâmica do DOM, controle de fluxo do jogo, modularização de arquivos (`import/export`) e lógica de aleatoriedade.

## 📁 Estrutura do Projeto

```text
├── index.html          # Página principal e estrutura do jogo
├── style.css           # Estilização e layout adaptável
├── script.js          # Lógica principal e controle de fluxo do jogo
├── perguntas.js       # Base de dados com o fluxo de perguntas e respostas
└── aleatorio.js       # Funções auxiliares de sorteio e personalização de nomes
```

## 🎮 Como Executar o Projeto

1. Clone este repositório para a sua máquina local.
2. Abra a pasta do projeto.
3. Como o projeto utiliza módulos nativos do JavaScript (`type="module"`), abra o arquivo `index.html` utilizando um servidor local (como a extensão **Live Server** no VS Code) para evitar erros de política de CORS.

---
Desenvolvido como um projeto prático para explorar manipulação do DOM e lógica de programação em JavaScript.
