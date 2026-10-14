# Away 10A — Demo V9

## Ficheiros
- `index.html`: aplicação estática Away 10A.
- `away_10a_dados_2026-27.json`: calendário e catálogo de locais.
- `away_10a_schema.json`: esquema JSON.

## Funcionalidades
- Calendário de jogos e página própria para cada deslocação.
- Locais agrupados por paragem em viagem, refeição, comida rápida/cafés e acessos ao estádio.
- Pesquisa e filtros.
- Seleção de locais para um percurso personalizado no Google Maps.
- Reordenação manual das paragens com setas para cima/baixo.
- **Novo na V9:** alternância entre ida ao jogo e regresso a Lisboa; no regresso, os pontos de partida/destino são invertidos e a ordem das paragens selecionadas é invertida automaticamente.

## Testar
Abra `index.html` num navegador. Os dados estão incorporados no HTML para a demo funcionar localmente. Na publicação web, o HTML tenta carregar o JSON externo.

## Limitações importantes
A aplicação não calcula tempos ou desvios automaticamente nem otimiza o percurso. A inversão de ida/regresso é uma conveniência de planeamento, não uma garantia de que os locais estejam abertos ou sejam adequados ao sentido escolhido. Confirme datas, horários, acessos e funcionamento dos estabelecimentos antes de uma deslocação. Os locais não foram visitados pessoalmente e não constituem recomendações baseadas em experiência direta.
