# 🎮 Jogo do Número Secreto 2.0

Um jogo interativo de adivinhação desenvolvido em JavaScript, HTML e CSS com recursos de síntese de voz. Feito com o curso Logica e Programação da Alura! 

## 📋 Sobre o Projeto

O Jogo do Número Secreto é uma aplicação web onde o jogador deve adivinhar um número aleatório entre 1 e 10. O jogo oferece feedback visual e auditivo, tornando a experiência mais imersiva e acessível.

## ✨ Funcionalidades

- 🎯 Geração aleatória de números entre 1 e 10
- 🔊 Síntese de voz (Text-to-Speech) em português brasileiro
- 📊 Contador de tentativas
- 🔄 Sistema de reinício de jogo
- 📱 Design responsivo
- ♿ Acessibilidade com feedback auditivo
- 🎲 Sistema inteligente que evita repetição de números recentes

## 🚀 Como Jogar

1. Digite um número entre 1 e 10 no campo de entrada
2. Clique no botão "Chutar"
3. Receba dicas se o número é maior ou menor que o número secreto
4. Continue tentando até acertar
5. Use o botão "Novo jogo" para reiniciar

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da página
- **CSS3** - Estilização e design responsivo
- **JavaScript** - Lógica do jogo e interatividade
- **Web Speech API** - Síntese de voz
- **Google Fonts** - Tipografia (Chakra Petch e Inter)

## 📁 Estrutura do Projeto

```
js-curso-2-aula1/
├── index.html          # Página principal
├── app.js             # Lógica do jogo
├── style.css          # Estilos da aplicação
├── img/               # Recursos visuais
│   ├── ia.png         # Imagem do personagem
│   ├── bg.png         # Imagem de fundo
│   ├── code.png       # Imagem decorativa
│   └── Ruido.png      # Textura de fundo
└── README.md          # Documentação
```

## 🎯 Funcionalidades Técnicas

### Geração de Números Aleatórios
- Sistema que evita repetir os últimos 3 números sorteados
- Reinicialização automática da lista quando necessário

### Síntese de Voz
- Compatibilidade com navegadores que suportam Web Speech API
- Configuração em português brasileiro
- Velocidade de fala otimizada (1.2x)

### Interface Responsiva
- Adaptação para diferentes tamanhos de tela
- Design mobile-friendly
- Elementos visuais que se ajustam automaticamente

## 🌐 Como Executar

1. Clone ou baixe o projeto
2. Abra o arquivo `index.html` em um navegador web moderno
3. Certifique-se de que o navegador suporta Web Speech API para o recurso de voz

## 📱 Compatibilidade

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ Síntese de voz pode variar entre navegadores

## 🎨 Design

O jogo apresenta um design moderno com:
- Gradiente azul elegante
- Tipografia personalizada
- Elementos visuais imersivos
- Interface intuitiva e acessível

## 🔧 Personalização

Para modificar o intervalo de números, altere a variável `numeroLimite` no arquivo `app.js`:

```javascript
let numeroLimite = 10; // Altere para o valor desejado
```

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais.

---

Desenvolvido com ❤️ durante o curso de JavaScript da Alura
