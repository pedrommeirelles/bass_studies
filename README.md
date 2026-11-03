# bass_studies

Ferramentas de estudo de contrabaixo elétrico.

## Mapeamento Horizontal

**Site:** https://pedrommeirelles.github.io/bass_studies/

Treino da escala maior corda por corda, pelos graus, seguindo as orientações das aulas com o Maca:

- regra 3 + 4: do 1 saem três notas em distância de tom, do 4 saem quatro; semitom só do 3 para o 4 e do 7 para o 1;
- âncoras no 1 e no 4 de cada corda (e o 5 logo em seguida);
- dedo 1 no 1 e dedo 1 no 4 ao começar cada desenho;
- com backing track, até virar música.

### Seções

| Aba | Para que serve |
|---|---|
| Hoje | Sessão guiada por tom e corda. Cada etapa é marcada com um toque (Travei / Com esforço / Fluente). Base do dia, variação e desafio sorteados, cronômetro e registro da sessão. |
| Teoria | Trilhas de harmonia ligadas às aulas, feitas para o celular e sem precisar do baixo. A primeira: dominantes secundários e menor harmônica em "Isn't She Lovely" (aula de 03/11), em 7 sessões de 15 minutos (03/11 a 09/11). Cada sessão tem revisão das anteriores, a ideia com tabelas e braço, exemplos de áudio e teste de ouvido, perguntas geradas na hora com explicação, registro com um toque e um bloco opcional no baixo. Bases sem baixo da música (partes A, B, forma completa e o trecho Sol#7 → Dó#m7) em Mi ou Sol, a 70, 90 ou 119 BPM. |
| Mapa | Matriz de cobertura tom × corda × pares de cordas, braço inteiro por tom (graus, só 1-4-5 ou notas), histórico, sincronização e ajustes. |
| Teste | Rodadas de 10 perguntas: nota → grau, grau → casa na corda, corda solta → grau, tom ou semitom. Cada resposta traz a explicação pelo caminho de volta até a tônica. No computador, responde pelo teclado. |
| Bases | Backing tracks por tom: jazz ii V I e bossa nova nos 12 tons; pop/rock e grooves sem baixo em Dó, Sol, Ré, Lá e Mi; em Mi, a base de "Isn't She Lovely" que o Maca mandou. |
| Regras | Resumo das orientações das aulas. |

### Onde fica o progresso

- Por padrão, no navegador de cada aparelho.
- Para ter o mesmo progresso no Mac, no Windows e no celular, abra **Mapa › Sincronizar entre aparelhos**, crie um token do GitHub só com a permissão `gist` (o link no site já abre a página com essa permissão marcada) e cole no campo. O progresso passa a ficar num Gist secreto da sua conta, no arquivo `bass_studies_progresso.json`. O token fica guardado apenas no navegador onde foi colado.
- Também há backup manual (copiar e colar o progresso) em **Mapa › Ajustes**.
- O progresso da aba Teoria (sessões, avaliações e respostas) vai junto, no mesmo arquivo, e as sessões aparecem no histórico do Mapa.

### Usar como aplicativo no celular

Abra o site no navegador do celular e escolha "Adicionar à tela de início". O ícone abre a ferramenta em tela cheia.

### Arquivos

- `index.html`: a ferramenta inteira (HTML, CSS e JavaScript num arquivo só). Não há etapa de compilação. O áudio da aba Teoria é sintetizado no navegador (Web Audio), sem arquivos de som.
- Para testes automatizados, abrir com `?teste=1` expõe `window.__teoria` (geradores de perguntas, peças de áudio e funções de dados).
- `manifest.webmanifest`, `icon.svg`, `icon-*.png`: ícone e instalação na tela de início.

### Publicação

O GitHub Pages publica o site a partir do branch `gh-pages`, que tem o mesmo conteúdo do `main`. Ao atualizar a ferramenta, envie a mesma versão para os dois branches (`git push origin main main:gh-pages`). Se preferir um branch só, troque a origem em Settings › Pages para `main` e apague o `gh-pages`.

### Créditos das bases

Os links abrem os vídeos originais no YouTube: Backing Tracks Channel, Studio Closet, TGuitar e Music Jam Tracks.
