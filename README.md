# Eclipse sobre Corvalto

Tower defense roguelike de magia em pixel art. É um único arquivo HTML, sem dependências: abre em qualquer navegador e funciona offline.

## Como jogar

- **No navegador:** abra `index.html`.
- **No Android:** salve o arquivo e abra com o Chrome.
- **No iPhone:** salve o arquivo no app Arquivos e abra pelo app Sitecase (Compartilhar → Sitecase).
- **GitHub Pages:** em Settings → Pages, publique a branch `main`. O jogo fica disponível no link do Pages.

## O jogo

- **4 casas**, cada uma com traço, feitiço inicial e Supremo próprios: Brasa (fogo), Névoa (sombra), Astro (raio) e Raiz (natureza).
- **5 fases com 10 ondas**, campeão na onda 5 e chefe na onda 10. Cada fase tem um desafio próprio, e cada jornada tem um presságio aleatório.
- **Pedestais livres:** construa em qualquer espaço de terreno fora do caminho.
- **Feitiços por páginas:** os inimigos soltam páginas, e 3 páginas de um elemento ensinam o feitiço ou aumentam o domínio dele.
- **Caldeirão de fusão:** combina 2 ou 3 elementos com chance de sucesso. Uma falha pode deixar um resíduo negativo.
- **Relíquias:** comuns, raras e amaldiçoadas (bônus forte com um custo).
- **Ondas com tempo limite:** vencer rápido rende bônus, e estourar o tempo enfurece os inimigos.
- **Hordas em dobro:** depois de mais de 3 derrotas seguidas, o tamanho diminui. Uma vitória restaura.
- **Talentos permanentes** comprados com estrelas, além de 3 dificuldades: Aprendiz, Lua Cheia e Eclipse Total.
- **Modo celular ou computador** detectado pelo navegador. No computador há atalhos: Espaço, Q, C, 1/2/3 e Esc.

## Perfis de jogador

Na tela inicial, cada pessoa cria o seu jogador com nome e brasão. Estrelas, talentos, dificuldades liberadas, Grimório e jornada em andamento ficam separados por jogador e não se misturam. Tudo fica salvo no navegador do aparelho (localStorage).
