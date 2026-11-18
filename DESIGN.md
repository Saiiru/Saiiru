# GitHub profile — NIGHTFORGE / SAIRU

**Revisão:** 2026-11-18. **Escopo:** branch de revisão; não modifica o sistema Artix nem o design system Nightwatch.

## Origem e atribuição

Fonte visual analisada: [mille-okws/mille-okws](https://github.com/mille-okws/mille-okws). O perfil usa painéis SVG estáticos para identidade, linguagem, operações numeradas, cartões de projeto e pesquisa. A referência não declara licença no repositório consultado, portanto **nenhum SVG original foi copiado ou republicado**. Recriamos uma composição original com a mesma organização conceitual, usando esquema tático, fichas, painéis e cores observadas.

Outros projetos da autora consultados:
- [StudyGrandPrix](https://github.com/mille-okws/StudyGrandPrix): tema por equipe; CSS com #070a0a, #00d7b9, #35ffe3, #ff4d4d e #ffb020.
- [pestinha](https://github.com/mille-okws/pestinha): UI PySide6, controles/estados; verde #63e56f, superfícies #0c1f13 e foco legível.
- [MushroomCloud](https://github.com/mille-okws/MushroomCloud): HUD escuro/verde com visualização científica.
- [NokiaOS](https://github.com/mille-okws/NokiaOS): menu embarcado monocromático e estados simples.
- [ControleDeEdital](https://github.com/mille-okws/ControleDeEdital): HTML/CSS preto-e-branco com cartões de progresso.
- [MascarenhasMarketing](https://github.com/mille-okws/MascarenhasMarketing): bento e landing page escura; coral #ff6a3d e violeta #7b5cff.

Esses trabalhos são referências de padrões de UI, **não bibliotecas prontas ou código incorporado**.

## Decisões

- 900 px de largura base para painéis principais; SVGs estáticos responsivos no GitHub com `viewBox`.
- Perfil público com nome, áreas e SENAI em andamento; não inventar experiência, métricas, resultados, conclusão de integração ou certificação.
- Quatro projetos com URLs existentes: OpenKORA, Nightwatch UI, Neovim e TFT Test.
- Matrix como paleta principal. Jedi, Sith e Cyberpunk como modos com tokens reutilizáveis.
- Sem JavaScript, `foreignObject`, serviços externos, imagens remotas, fontes carregadas por rede ou animações obrigatórias no README.
- Não atribuir métricas, builds ou telemetria aos SVGs. Estados de projeto são descritivos.
- Textos alternativos no README; SVGs com `title`. Os cartões são links reais, mas a documentação mais detalhada deve ficar nos repositórios.
- Alteração isolada nesta branch para revisão antes de mesclar.

## Cores (extraídas do perfil de referência)

`#060d09` fundo; `#0a1510` superfície; `#31533f` borda; `#6f8a7a` texto secundário; `#e6f2ea` texto principal; `#8af0bb` acento; `#007a33` sinal; `#e0a526` âmbar.

## Modos

Consultar [THEMES.md](THEMES.md), [palettes.json](themes/palettes.json) e [tokens.css](themes/tokens.css). Esses arquivos são documentação portátil; sua presença **não modifica automaticamente** o Quickshell, Neovim ou Nightwatch UI.

## Verificação

- Validar sintaxe XML dos SVGs.
- Conferir que todos os links de projetos existem e que os caminhos de imagem são locais.
- Renderizar prévias dos SVGs e verificar legibilidade no desktop e em largura reduzida.
- Revisar nomes, estado real de projetos e contrastes visuais antes da integração.

**Atenção:** este visual é inspirado em universos de ficção, sem usar logomarcas ou ícones oficiais.
