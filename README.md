# Site da Fundação Terra Mirim

Site estático de [terramirim.org.br](https://terramirim.org.br), publicado pelo GitHub Pages.

Recria as páginas institucionais do site antigo em WordPress, que saiu do ar em 2026. Os textos e as imagens vêm de cópias públicas do site antigo (Common Crawl e Internet Archive). É uma versão provisória, até o novo site ficar pronto.

## Como editar

- Cada página é um arquivo `index.html` dentro da pasta com o nome do endereço: `quem-somos/index.html` é `www.terramirim.org.br/quem-somos/`.
- O visual fica em `assets/style.css`. As imagens ficam em `assets/img/`.
- Não há etapa de compilação. Uma alteração enviada para a branch `main` aparece no site em poucos minutos.
- O arquivo `CNAME` diz ao GitHub Pages qual é o domínio. Não apague.

## Quando o novo site estiver pronto

Basta apontar o DNS de `terramirim.org.br` e `www` para o novo servidor e desativar o GitHub Pages neste repositório. O e-mail não depende deste site.

## Fontes

Os títulos usam a fonte D-DIN Condensed (Datto), licenciada sob a SIL Open Font License 1.1, a mesma usada pelo tema do site antigo.
