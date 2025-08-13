# 🎲 Jogo do Número Secreto

Um jogo interativo desenvolvido em JavaScript onde o jogador precisa adivinhar um número secreto gerado aleatoriamente pelo sistema.

## 🚀 Demo

**[Jogar Agora](https://one-alura-cksx-git-main-ana-vitorias-projects-ec65fd0c.vercel.app/)**

## 📝 Sobre o Projeto

O Jogo do Número Secreto é uma aplicação interativa onde o jogador tenta adivinhar um número aleatório entre 1 e 10. Este projeto foca no desenvolvimento da **lógica JavaScript**, implementando funcionalidades como geração de números aleatórios, validação de chutes, feedback dinâmico e integração com síntese de voz.

> **Nota**: A interface visual (HTML/CSS) foi fornecida como base, e o desenvolvimento se concentrou na implementação completa da lógica do jogo em JavaScript.

## ✨ Funcionalidades

- 🔢 **Geração inteligente**: Números aleatórios entre 1 e 10 sem repetições consecutivas
- 💬 **Feedback dinâmico**: Mensagens que orientam o jogador durante toda a partida
- 📊 **Contador de tentativas**: Acompanhe quantas tentativas foram necessárias
- 🔄 **Reinício rápido**: Comece uma nova partida a qualquer momento
- 🎙️ **Narração por voz**: Experiência mais imersiva com leitura das mensagens
- 🎯 **Interface intuitiva**: Design simples e fácil de usar

## 🎮 Como Jogar

1. **Início**: O jogo apresenta o intervalo do número secreto (1 a 10)
2. **Chute**: Digite um número no campo e clique em "Verificar"
3. **Feedback**: O sistema informa se você:
   - ✅ **Acertou**: Mostra o número de tentativas e habilita o botão de reinício
   - ❌ **Errou**: Indica se o número é maior ou menor que seu chute
4. **Reiniciar**: Clique no botão de reinício para uma nova partida

## 💻 Tecnologias Utilizadas

| Tecnologia | Finalidade | Desenvolvimento |
|-----------|------------|----------------|
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Lógica do jogo e interatividade | ✅ **Desenvolvido** |
| ![ResponsiveVoice](https://img.shields.io/badge/ResponsiveVoice-4285F4?style=flat&logo=google&logoColor=white) | Síntese de voz para narração | ✅ **Integrado** |
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) | Estrutura da interface | 📋 Base fornecida |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) | Estilização visual | 📋 Base fornecida |

## 🛠️ Desenvolvimento JavaScript

### Funcionalidades Implementadas
- **Sistema de geração de números**: Algoritmo que evita repetições consecutivas
- **Validação de entrada**: Processamento e validação dos chutes do usuário
- **Lógica de feedback**: Comparação e retorno de dicas (maior/menor)
- **Contador de tentativas**: Controle do número de jogadas
- **Integração com API de voz**: Implementação do ResponsiveVoice para narração
- **Gerenciamento de estado**: Controle completo do fluxo do jogo

### Arquitetura do Código

```javascript
// Principais funções desenvolvidas
gerarNumeroAleatorio()     // Gera número secreto sem repetições
exibirTextoNaTela()        // Atualiza interface e reproduz áudio
verificarChute()           // Processa tentativa do jogador
reiniciarJogo()           // Reset completo do estado
```

### Variáveis de Estado
- `numeroSecreto`: Armazena o número atual da partida
- `listaDeNumerosSorteados`: Controla números já utilizados
- `tentativas`: Contador de jogadas do usuário

## 🚀 Como Executar Localmente

### Pré-requisitos
- Navegador web moderno
- Conexão com internet (para ResponsiveVoice API)

### Instalação
```bash
# Clone o repositório
git clone [git@github.com:Bella-my/JogoDoNumeroSecreto.git]

# Navegue até o diretório
cd jogo-numero-secreto

# Abra o index.html no seu navegador
# ou use um servidor local como Live Server (VS Code)
```

## 🌐 Deploy

Este projeto está hospedado na Vercel e pode ser acessado através do link:
**https://one-alura-cksx-git-main-ana-vitorias-projects-ec65fd0c.vercel.app/**

## 💡 Possíveis Expansões (JavaScript)

- [ ] Níveis de dificuldade com diferentes intervalos
- [ ] Sistema de pontuação baseado em tentativas
- [ ] Histórico de partidas com localStorage
- [ ] Timer para adicionar pressão temporal
- [ ] Modo desafio com múltiplas rodadas

## 🤝 Contribuições

Contribuições focadas na lógica JavaScript são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/LogicaAmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some JavaScript logic'`)
4. Push para a branch (`git push origin feature/LogicaAmazingFeature`)
5. Abra um Pull Request

## 👤 Autor

**Ana Vitória**
- GitHub: [@Bella_my](https://github.com/Bella-my)
- LinkedIn: [Ana Silva](https://www.linkedin.com/in/ana-silva-880931178/)

---
