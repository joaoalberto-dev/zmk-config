# zmk-config — Sofle v2

Firmware ZMK (v0.3) para Sofle v2 com nice!nano v2.

## Gerar firmware
Todo push dispara o GitHub Actions. Baixe o artefato `firmware` na aba **Actions**.

## Gravar
1. Ligue a metade no USB e dê **dois toques rápidos no reset**: aparece um drive (`NICENANO`).
2. Copie o `.uf2` correspondente:
   - esquerda: `sofle_left-nice_nano_v2-zmk.uf2`
   - direita:  `sofle_right-nice_nano_v2-zmk.uf2`
3. Se as metades pararem de se falar: grave `settings_reset-nice_nano_v2-zmk.uf2` nas duas, depois o firmware normal, e reinicie as duas ao mesmo tempo.

## Editar o layout
- No arquivo `config/sofle.keymap`, ou
- No **ZMK Studio** (https://zmk.studio) com a esquerda no USB. Para destravar: segure LOWER + RAISE e aperte TAB.

## Mapa das camadas
https://joaoalberto-dev.github.io/zmk-config/ (arquivo em `docs/index.html`)
