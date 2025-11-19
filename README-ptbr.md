# 🎯 Letrico

![Letrico Logo](https://img.shields.io/badge/LETRICO-Jogo_de_Palavras-success?style=for-the-badge&logo=gamepad)

**Um jogo de adivinhação de palavras em português inspirado no famoso Wordle - e principalmente sua versão brasileira, Letreco.**

[![Demo ao Vivo](https://img.shields.io/badge/Jogar-Demo_ao_Vivo-blue?style=for-the-badge)](https://portfolio-website-adrian-lobato.onrender.com/projects/letrico)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

[🎮 Jogar Agora](https://adrian1715.github.io/letrico/) • [📝 Reportar Bug](https://github.com/adrian1715/letrico/issues) • [✨ Sugerir Funcionalidade](https://github.com/adrian1715/letrico/issues)

---

## 📖 Sobre o Projeto

**Letrico** é um jogo interativo de adivinhação de palavras construído com **JavaScript puro**, inspirado no popular jogo Wordle - ou o mais conhecido Letreco no Brasil. Os jogadores têm 6 tentativas para adivinhar uma palavra portuguesa de 5 letras, com feedback visual fornecido após cada tentativa para ajudar a descobrir a palavra correta.

### 🎮 Como Funciona

- 🔤 **Adivinhe a Palavra:** Digite uma palavra portuguesa válida de 5 letras
- 🟩 **Verde:** Letra está correta e na posição certa
- 🟨 **Amarelo:** Letra está na palavra mas na posição errada
- ⬜ **Cinza:** Letra não está na palavra
- 🎯 **6 Tentativas:** Você tem seis chances para adivinhar a palavra correta

**OBS:** deixe o console do navegador aberto (F12) para algumas informações extras durante o jogo.

### 🌟 Características Principais

- ✅ **JavaScript Puro** - Sem frameworks ou bibliotecas (exceto Bootstrap para UI)
- 🎨 **Interface Bonita** - Design limpo e responsivo com animações suaves
- 🇧🇷 **Palavras em Português** - Dicionário extenso de palavras do português brasileiro
- 📊 **Feedback Visual** - Dicas intuitivas com código de cores
- 📱 **Totalmente Responsivo** - Funciona perfeitamente em mobile e desktop
- ⚡ **Performance Rápida** - Leve e otimizado para velocidade
- 🎯 **Jogabilidade Simples** - Fácil de aprender, desafiador de dominar

---

## 🚀 Demo ao Vivo

**[Jogue Letrico Agora →](https://adrian1715.github.io/letrico/)**

Tente adivinhar a palavra de hoje! Desafie seus amigos e veja quem consegue resolver em menos tentativas.

---

## 🛠️ Construído Com

- **HTML5** - Estrutura de marcação semântica
- **CSS3** - Estilos e animações personalizadas
- **JavaScript (ES6+)** - Lógica do jogo e interatividade
- **Bootstrap 5** - Framework UI responsivo

---

## 💻 Começando

### Pré-requisitos

- Um navegador web moderno (Chrome, Firefox, Safari, Edge)
- Nenhuma instalação adicional necessária!

### Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/adrian1715/letrico.git
   cd letrico
   ```

2. **Abra no navegador**
   
   Simplesmente abra `index.html` no seu navegador web:
   ```bash
   # No macOS
   open index.html
   
   # No Linux
   xdg-open index.html
   
   # No Windows
   start index.html
   ```

3. **Ou use um servidor local** (opcional)
   ```bash
   # Usando Python 3
   python -m http.server 8000
   
   # Usando Node.js http-server
   npx http-server
   ```
   
   Depois navegue para `http://localhost:8000`

---

## 📁 Estrutura do Projeto

```
letrico/
├── index.html          # Estrutura HTML principal
├── style.css          # Estilos customizados
├── app.js             # Lógica do jogo e funcionalidades
├── words.js           # Dicionário de palavras em português
├── README.md          # Documentação (Inglês)
└── README-ptbr.md     # Documentação (Português)
```

---

## 🎯 Como Jogar

1. **Inicie o Jogo**
   - Abra o jogo no seu navegador
   - O jogo seleciona automaticamente uma palavra aleatória de 5 letras

2. **Faça Seu Palpite**
   - Digite uma palavra portuguesa válida de 5 letras no campo de entrada
   - Clique em "Chutar" ou pressione Enter

3. **Verifique o Feedback**
   - 🟩 **Tiles verdes** - Letra correta na posição correta
   - 🟨 **Tiles amarelos** - Letra correta na posição errada
   - ⬜ **Tiles cinzas** - Letra não está na palavra

4. **Ganhe ou Perca**
   - Adivinhe a palavra corretamente em até 6 tentativas para ganhar!
   - Se acabarem as tentativas, a palavra correta será revelada

### Exemplo de Jogada

```
Tentativa 1: CARRO
Resultado: C🟨 A⬜ R🟩 R⬜ O⬜

Tentativa 2: VERDE
Resultado: V⬜ E🟨 R🟩 D⬜ E🟨

Tentativa 3: CERVO
Resultado: C🟩 E🟩 R🟩 V🟩 O🟩
✅ Você Ganhou!
```

---

## 🎨 Recursos Detalhados

### Mecânicas do Jogo
- **Validação de Palavras:** Verifica se a palavra digitada é válida em português
- **Feedback com Código de Cores:** Dicas visuais após cada tentativa
- **Contador de Tentativas:** Rastreia tentativas restantes
- **Gerenciamento de Estado:** Condições de vitória/derrota e reset do jogo

### Interface do Usuário
- **Grade Responsiva:** 6 linhas × 5 colunas para os palpites
- **Teclado Interativo:** Clique ou digite para jogar
- **Animações Suaves:** Viradas de tiles e transições de cores
- **Design Limpo:** Interface minimalista inspirada em jogos de palavras modernos

### Destaques Técnicos
- **Sem Dependências Externas** (exceto Bootstrap para UI)
- **Arquitetura de Código Limpa:** Modular e fácil de manter
- **Otimizado para Performance:** Tempos de carregamento rápidos e jogabilidade fluida
- **Compatível entre Navegadores:** Funciona em todos os navegadores modernos

---

## 🔧 Visão Geral do Código

### Arquivos Principais

**`app.js`** - Lógica central do jogo
```javascript
// Funções principais incluem:
- Seleção de palavra do dicionário
- Validação e processamento de entrada
- Lógica de código de cores para feedback das letras
- Verificação de condições de vitória/derrota
- Gerenciamento de estado do jogo
```

**`words.js`** - Banco de dados de palavras
```javascript
// Contém:
- Array de palavras portuguesas válidas de 5 letras
- Usado tanto para seleção de resposta quanto validação de entrada
```

**`index.html`** - Interface do jogo
```html
<!-- Estrutura inclui:
- Título e cabeçalho do jogo
- Grade 6×5 para palpites
- Campo de entrada e botão de envio
- Exibição de mensagens de vitória/derrota
-->
```

---

## 🌐 Compatibilidade de Navegadores

| Navegador | Versão Suportada |
|-----------|-----------------|
| Chrome    | ✅ 90+          |
| Firefox   | ✅ 88+          |
| Safari    | ✅ 14+          |
| Edge      | ✅ 90+          |
| Opera     | ✅ 76+          |

---

## 📱 Design Responsivo

Letrico é totalmente responsivo e funciona perfeitamente em:

- 📱 **Celulares** (320px+)
- 📱 **Tablets** (768px+)
- 💻 **Laptops** (1024px+)
- 🖥️ **Desktops** (1440px+)

---

## 🎓 O Que Aprendi

Construir o Letrico me ajudou a melhorar minhas habilidades em:

- ✅ **Manipulação do DOM:** Atualizações dinâmicas de conteúdo e tratamento de eventos
- ✅ **Lógica de Jogo:** Gerenciamento de estado e implementação de regras
- ✅ **Animações CSS:** Transições suaves e efeitos visuais
- ✅ **Design Responsivo:** Abordagem mobile-first
- ✅ **Experiência do Usuário:** Design de interface intuitiva
- ✅ **JavaScript Vanilla:** Construindo recursos complexos sem frameworks

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Se você tem sugestões ou melhorias:

1. Faça um Fork do projeto
2. Crie sua branch de feature (`git checkout -b feature/FuncionalidadeIncrivel`)
3. Commit suas mudanças (`git commit -m 'Adiciona alguma FuncionalidadeIncrivel'`)
4. Push para a branch (`git push origin feature/FuncionalidadeIncrivel`)
5. Abra um Pull Request

---

## 📝 Licença

Este projeto é open source e está disponível sob a [Licença MIT](LICENSE).

---

## 👨‍💻 Autor

**Adrian Lobato**

- GitHub: [@adrian1715](https://github.com/adrian1715)
- LinkedIn: [Adrian Lobato](https://linkedin.com/in/adrian-lobato)
- Portfólio: [portfolio-website-adrian-lobato.onrender.com](https://portfolio-website-adrian-lobato.onrender.com/)

---

## 🙏 Agradecimentos

- Inspirado no [Wordle](https://www.nytimes.com/games/wordle/index.html) e [Letreco](https://letreco.org/)
- Construído com ❤️ para falantes de português
- Agradecimentos especiais aos contribuidores da lista de palavras em português brasileiro

---

## 📊 Estatísticas do Projeto

![GitHub last commit](https://img.shields.io/github/last-commit/adrian1715/letrico?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/adrian1715/letrico?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/adrian1715/letrico?style=flat-square)

---

**Se você gostou deste projeto, considere dar uma ⭐ no repositório**

*Agradeço de coração seu suporte!*

[⬆ Voltar ao Topo](#-letrico)