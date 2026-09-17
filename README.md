# TUIDG — Interactive Mechanisms

Pacote integrado com seis simulações independentes:

1. `rotating-interaction.html` — Meronic Builder
2. `compalpha-rotating-interaction.html` — Rotating Interaction entre dois Compalphas
3. `cyclical-interaction.html` — Cyclical Interaction 2D/3D
4. `ic-2d-laboratory.html` — IC 2D Laboratory
5. `double-slit-compalpha.html` — Double Slit
6. `cyclic-current.html` — Cyclic Current

O arquivo `index.html` reúne as seis simulações em abas. Cada mecanismo permanece em um HTML independente e pode ser aberto separadamente pelo botão **Open separately**.

## Publicação no GitHub Pages

1. Extraia o arquivo ZIP.
2. Envie `index.html`, os seis arquivos de simulação e, opcionalmente, este `README.md` para a mesma pasta do repositório.
3. Mantenha exatamente os nomes dos arquivos.
4. Confirme a substituição do `index.html` antigo.
5. Faça o commit e aguarde a publicação do GitHub Pages.
6. Recarregue o site com `Ctrl+F5` caso o navegador ainda mostre uma versão anterior.

Não é necessário instalar bibliotecas nem executar uma etapa de compilação. O hub carrega apenas a aba utilizada e envia `TUIDG_TAB_ACTIVE` às simulações, pausando as animações das abas ocultas.

## Links diretos por aba

- `index.html#rotating` — Meronic Builder
- `index.html#compalpha-ri` — Rotating Interaction
- `index.html#cyclical` — Cyclical Interaction
- `index.html#laboratory` — IC 2D Laboratory
- `index.html#double-slit` — Double Slit
- `index.html#current` — Cyclic Current
