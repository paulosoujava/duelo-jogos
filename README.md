# Duelo!

Site de jogos para dois jogadores, cada um no seu celular: Jogo da Velha, Forca, Damas (regras brasileiras), Dominó e Xadrez com Professor para iniciantes.

Um jogador cria a sala, manda o link e o outro entra. A conexão entre os celulares passa por um retransmissor MQTT público (EMQX e HiveMQ, via WSS), sem servidor próprio. Funciona em 4G e Wi-Fi.

Site estático: basta publicar o `index.html` (Vercel, Netlify, GitHub Pages).
