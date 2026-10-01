# Projetos de tradução com a comunidade R

Slides da apresentação na **[aMostra de Estatística - IME USP](https://www.ime.usp.br/~amostra/)**, em 01 de outubro de 2026.

Apresentação: [R-Ladies São Paulo](https://rladies-sp.org/), [Beatriz Milz](https://github.com/beatrizmilz) e [Geovana Lopes Batista](https://github.com/GeovanaLopes).

**Slides:** <https://r-ladies-sao-paulo.github.io/2026-amostra-ime-usp/>

## Conteúdo

- R-Ladies São Paulo
- Projetos de tradução com a comunidade R:
  - Pacote dados
  - Livro R para Ciência de Dados
  - DevGuide da rOpenSci
  - Tradução das mensagens do R
- Como participar e contribuir

## Como renderizar

Os slides são feitos com [Quarto](https://quarto.org/) e o [Quarto R-Ladies Theme](https://github.com/beatrizmilz/quarto-rladies-theme).

```bash
quarto render index.qmd
```

É preciso ter internet e os pacotes `jsonlite`, `dplyr`, `tibble` e `knitr` instalados: os dados sobre os capítulos da RLadies+ são baixados do [RLadies+ Meetup Archive](https://github.com/rladies/meetup_archive) a cada renderização.
