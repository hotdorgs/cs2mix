🔫 CS2 Mix Balancer - Hotdorgs Edition

Um organizador de partidas (Mix/Scrim) para Counter-Strike 2 focado em equilíbrio matemático e inteligência artificial. Desenvolvido para garantir partidas justas baseadas no Rating do Leetify, com suporte a multiplayer em tempo real.

✨ Funcionalidades

⚡ Multiplayer em Tempo Real: Sincronização via Firebase. Todos os jogadores no lobby veem as alterações instantaneamente.

⚖️ Balanceamento Rigoroso: Algoritmo matemático que busca a menor diferença possível de rating médio entre os dois times (Time A vs Time B).

🤖 Modo IA (Experimental): Opção de usar a Inteligência Artificial do Google Gemini para sugerir times baseados em critérios mais complexos.

🧠 Coach IA: Após gerar os times, a IA analisa o confronto, prevê a probabilidade de vitória e dá dicas táticas (e provocações!).

🔗 Integração Leetify: Suporte para links de perfil e visualização rápida do ID do jogador.

📋 Copiar para Discord: Formatação pronta com emojis para colar no chat do Discord.

📱 Responsivo: Funciona bem em PC e Mobile.

🚀 Instalação e Uso

Este é um projeto Single File Application (Aplicação de Arquivo Único). Todo o código está contido no index.html.

Opção 1: Rodar Localmente

Baixe o arquivo index.html.

Abra-o em qualquer navegador moderno (Chrome, Edge, Firefox).

Opção 2: Hospedar no GitHub Pages (Recomendado)

Crie um repositório no GitHub.

Suba o arquivo index.html.

Vá em Settings > Pages e ative o site na branch main.

⚙️ Configuração Obrigatória

Para que o modo online e a IA funcionem, você precisa configurar as chaves de API. O site possui um painel de administração embutido para facilitar isso.

1. Acessando o Painel

No canto superior direito do site, clique em Configurações.

Usuário: hotdorgs

Senha: @apihotdorgs123

2. Configurando o Firebase (Banco de Dados)

O Firebase é necessário para que a lista de jogadores sincronize entre diferentes computadores.

Crie um projeto no Firebase Console.

Crie um Firestore Database (em modo de teste para começar).

Habilite o Authentication e ative o provedor Anônimo.

Vá nas configurações do projeto, adicione um App Web (</>) e copie as credenciais (apiKey, authDomain, etc.).

Cole essas credenciais no menu de Configurações do site e salve.

3. Configurando a IA (Google Gemini)

Necessário para o botão "Coach IA" e o modo de separação por IA.

Acesse o Google AI Studio.

Gere uma API Key gratuita.

Cole a chave no campo "Gemini API Key" no menu de Configurações do site.

🎮 Como Usar

Adicionar Jogadores: Clique em + ADD PLAYER. Insira o Nick, Link do Leetify e o Rating atual.

Preencher o Lobby: Aguarde até ter exatamente 10 jogadores na lista.

Equilibrar:

Use o botão EQUILIBRAR TIMES para o método matemático padrão.

Ou ative "Usar IA" para deixar o Gemini decidir.

Coach: Clique em ANÁLISE DO COACH IA para ver a previsão da partida.

Compartilhar: Clique em COPIAR TIMES e cole no seu grupo.

🛠️ Tecnologias Utilizadas

Frontend: HTML5, JavaScript (ES6+), Tailwind CSS (via CDN).

Backend (BaaS): Google Firebase (Firestore & Auth).

Inteligência Artificial: Google Gemini 2.5 Flash (via API REST).

Ícones: FontAwesome.

🤝 Créditos e Patrocínio

Este projeto é mantido e patrocinado por Hotdorgs.

📸 Instagram: @cesar.kali

🎮 Steam: hotdorgs

Desenvolvido com ❤️ para a comunidade de CS2.
