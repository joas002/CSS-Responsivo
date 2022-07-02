# Unidades

## Unidades Fixas/Absolutas: px, cm, mm;

    - cm e mm: O CSS tem suporte, porém quase não são aproveitadas para web design;
    - px: É uma unidade fixa "normalizada", ela se adapta a densidade de píxels do device em questão;

## Unidades de viewport: vw, vh, vmin, vmax;
    - vw: porcentagem da largura da tela;
    - vh: porcentagem da altura da tela;
    - vmin: porcentagem do menor lado da tela;
    - vmax: porcentagem do maior lado da tela;

## Unidades de fonte: rem, em;
    - rem: trabalhará com uma fonte relativa ao elemento HTML raíz (body);
    - em: trabalhará com uma fonte relativa ao elemento pai (div, ou qualquer elemento que esteja englobando o filho em questão);

## Caso especial: % (porcentagem);
    - %: é bem semelhante às unidades de viewport (vw, vh...), porém considera como relativo o elemento pai mais próximo, ao invés do tamanho da tela;