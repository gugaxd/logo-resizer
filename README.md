# logo sizer

Padroniza opticamente o tamanho de várias logos lado a lado. Cada logo é medida pela mancha
real, ignorando a margem vazia do arquivo, e a compensação óptica faz logos redondas e altas
crescerem e marcas largas encolherem até terem o mesmo peso visual. Exporta SVG (vetorial
quando a origem é SVG), PNG e JPG. Tudo roda no navegador.

Faz parte da família iniciada pelo [grid maker](https://github.com/gugaxd/gri.d.maker) e
compartilha o mesmo sistema visual.

## Onde ele está no ar

Dentro do hub [design tools](https://graphic-design-hub-two.vercel.app/), em `/logo-sizer/`.
O código publicado vive no repositório
[graphic-design-hub](https://github.com/gugaxd/graphic-design-hub), na pasta `logo-sizer/`.

**Este repositório é a versão independente.** Mudança feita aqui não altera o que está no ar:
ela precisa ser espelhada na pasta do hub. A única diferença entre as duas cópias é o
`HUB_URL` no topo de `src/LogoSizer.jsx` — aqui ele aponta para o hub publicado, lá é só `/`.

## Rodando localmente

```bash
npm install
npm run dev
```
