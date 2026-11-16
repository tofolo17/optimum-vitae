# optimum-vitae

> 🇧🇷 [Português](#o-que-você-encontrará-neste-repositório) · 🇺🇸 [English](#what-will-you-find-in-this-repository)
>
> 🌐 Site no ar: [optimumvitae.com.br](https://optimumvitae.com.br)

## O que você encontrará neste repositório?

Página estática feita sob demanda para a startup Optimum Vitae, que oferece serviços de saúde e beleza em domicílio em
São Paulo e região.

A página busca apresentar os serviços oferecidos, missão, visão e valores e identidade visual. Isto, de maneira
responsiva e com um design agradável.

As seguintes ferramentas foram utilizadas: HTML, CSS, JS, Bootstrap 5 e Bootstrap Studio. Esta última é uma ferramenta
low-code que acelerou (e muito) a prototipação. Fora isto, o GitHub Pages é o responsável por manter a página no ar, que
tem se mostrado suficiente devido à baixa taxa de acesso.

A empresa autorizou a disponibilização do código-fonte, que ainda está sob manutenção.

### Estrutura

```
├── index.html        # a página (seção única, com âncoras)
├── CNAME             # domínio customizado do GitHub Pages
└── assets/
    ├── css/          # estilos próprios (Estilo.css)
    ├── js/           # scripts próprios (Autoral.js) e do template
    ├── bootstrap/    # Bootstrap 5
    ├── fonts/        # pacotes de ícones (Font Awesome, Ionicons...)
    └── img/          # logo e fotos dos serviços
```

### Como rodar localmente

Por ser um site estático, basta abrir o `index.html` no navegador. Para servi-lo como no GitHub Pages:

```bash
git clone https://github.com/tofolo17/optimum-vitae.git
cd optimum-vitae
python -m http.server 8000   # acesse http://localhost:8000
```

### Licença

[MIT](LICENSE)

---

## What will you find in this repository?

Static page made on demand for the startup Optimum Vitae, which offers health and beauty services at home in São Paulo
and nearby.

The page seeks to present all the services offered, its mission, vision and values, and visual identity. All this in a
responsive and pleasant design.

I used the following tools: HTML, CSS, JS, Bootstrap 5, and Bootstrap Studio. The last one is a low-code tool that
accelerated the prototyping. Besides, GitHub Pages is responsible for keeping the page online, which has proven to be
sufficient due to the low access rate.

The company has authorized the release of the source code, which is still under maintenance.

### Structure

```
├── index.html        # the page (single section, with anchors)
├── CNAME             # GitHub Pages custom domain
└── assets/
    ├── css/          # own styles (Estilo.css)
    ├── js/           # own scripts (Autoral.js) and template scripts
    ├── bootstrap/    # Bootstrap 5
    ├── fonts/        # icon packs (Font Awesome, Ionicons...)
    └── img/          # logo and service photos
```

### Running locally

Since it's a static site, just open `index.html` in a browser. To serve it as GitHub Pages does:

```bash
git clone https://github.com/tofolo17/optimum-vitae.git
cd optimum-vitae
python -m http.server 8000   # open http://localhost:8000
```

### License

[MIT](LICENSE)
