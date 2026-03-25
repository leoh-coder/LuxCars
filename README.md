# LuxCars

Catálogo de carros de luxo — HTML5 e CSS3 puro, sem framework nenhum.

Criei esse projeto no 1º semestre de ADS como trabalho de web. Alguns semestres depois resolvi voltar e dar uma vida melhor: redesign completo, código limpo e responsividade. Ficou bom.

## Páginas

- Início — Hero com os logos das marcas, clica e vai pra página da marca

- Porsche 911 Carrera GTS
- Mercedes-AMG GT 63 PRO
- BMW M8 Gran Coupé
- Audi R8 Performance V12
- Sobre a LuxCars

## Stack

HTML5 + CSS3. Google Fonts (Playfair Display + Montserrat). Nenhuma dependência.

## Algumas escolhas que fiz

Fundo escuro com dourado porque todo catálogo de carro usa branco — quis fugir disso.

Variáveis CSS pras cores porque ficar repetindo `#b8963e` em 30 lugares é cilada.

Cada página tem seu `<style>` interno escopado pela classe do `<body>`, o `style.css` fica só com o global. Assim uma página não quebra a outra.

Classes em português porque o projeto todo tá em português, faz sentido.

## Como rodar

```bash
git clone https://github.com/leoh-coder/LuxCars.git
cd LuxCars
```

Abre o `index.html` no navegador. Só isso.

---

Leonardo Henrique — ADS
