🎲 Jogo do Número Secreto

📝 Descrição

O Jogo do Número Secreto é uma aplicação simples e divertida em JavaScript, onde o jogador tenta adivinhar um número aleatório gerado pelo sistema dentro de um intervalo definido. O jogo fornece dicas para ajudar o jogador, indicando se o número secreto é maior ou menor que o chute fornecido.

🚀 Funcionalidades

🔢 Gera um número aleatório entre 1 e 10 sem repetições consecutivas.

💬 Exibe mensagens dinâmicas para orientar o jogador durante o jogo.

📊 Conta o número de tentativas feitas pelo jogador para adivinhar o número secreto.

🔄 Permite reiniciar o jogo após o jogador acertar o número.

🎙️ Integração com o recurso de leitura de texto em voz para melhorar a experiência do usuário.

🎮 Como Jogar

O jogo inicia com uma mensagem informando o intervalo do número secreto (de 1 a 10).

O jogador digita um número no campo de entrada e clica no botão para verificar o chute.

O sistema informa se o jogador:

Acertou: Exibe o número de tentativas feitas e habilita o botão de reinício.

Errou: Indica se o número secreto é maior ou menor que o chute fornecido.

O jogador pode reiniciar o jogo clicando no botão de reinício.

💻 Tecnologias Utilizadas

HTML: Estrutura básica da interface.

CSS: Estilização visual (caso aplique no futuro).

JavaScript: Lógica do jogo e interação com o usuário.

ResponsiveVoice API: Leitura de texto em voz para mensagens exibidas no jogo.

🛠️ Estrutura do Código

Variáveis Globais: Gerenciam o estado do jogo, incluindo o número secreto, lista de números já sorteados e número de tentativas.

Funções Principais:

gerarNumeroAleatorio(): Gera o número secreto, garantindo que ele não seja repetido até que todos os números do intervalo sejam usados.

exibirTextoNaTela(tag, texto): Atualiza o conteúdo na interface e reproduz o texto em voz.

verificarChute(): Valida o chute do jogador e fornece feedback.

reiniciarJogo(): Reinicia o estado do jogo.

Interação com a Interface: Utiliza seletores do DOM para capturar entradas e atualizar elementos da interface.

▶️ Como Executar

Clone o repositório ou copie o código para um arquivo local.

Certifique-se de que possui uma conexão com a internet para acessar a API ResponsiveVoice.

Abra o arquivo HTML correspondente em um navegador.

📜 Licença

Este projeto é de uso livre e aberto para aprendizado e modificações. Utilize e adapte como preferir! 🌟

