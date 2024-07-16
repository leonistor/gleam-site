# gleam agency site

See [TODO.org](TODO.org) for development tasks.


## inspiration

- https://www.akqa.com

## development

prerequisites: [bun.sh](https://bun.sh)

- install dependencies: `bun install`
- run dev server: `bun run dev`
- build: `bun run build`
- unit tests: `bun run test:unit`
- install playwright for integration test `bunx playwright install`
- integration tests: `bun run test:integration`

---

## components

- [whatsapp button](https://codepen.io/demoonkevin/pen/MvPEpV)
- gooey btn: https://svelte-ux.techniq.dev/docs/components/Gooey
- https://magicui.design/docs/components/shimmer-button
- animated headline: https://github.com/elron/svelte-animated-headline

## deploy guides

- cloudflare: https://medium.com/@nicoletsylvain/how-to-to-setup-svelte-tailwindcss-daisyui-and-deploy-to-cloudflare-9deee49db418
- netlify: https://www.netlify.com/blog/2020/05/25/deploying-svelte-apps-to-netlify/
- vercel: https://vercel.com/docs/v2/build-steps/svelte

## sveltekit guides

- favicon: https://evilmartians.com/chronicles/how-to-favicon-in-2021-six-files-that-fit-most-needs
- better favicon: https://www.youtube.com/watch?v=T8uBpU8NcFE
- fonts +other: https://scottspence.com/posts/customising-fonts-in-tailwind-css-and-daisyui

## tailwind resources

- https://flowrift.com/c/banner
- https://www.hyperui.dev/
- https://wind-ui.com/components/
- templates: https://htmlrev.com/free-tailwind-templates.html

## tailwind components/elements

- https://magicui.design/docs
- https://ui.aceternity.com/components


## tailwind plugins

- fluid typography: https://fluid.tw/
- 3d transform: https://xpd-kasun.github.io/tailwind-3dtransform-plugin/

---

## color palette - proposal 1

[coolors palette](https://coolors.co/ee6352-08b2e3-efe9f4-57a773-484d6d)

```
- Tailwind

{ 'coffee': { DEFAULT: '#765341', 100: '#18110d', 200: '#2f211a', 300: '#473227', 400: '#5f4234', 500: '#765341', 600: '#a17058', 700: '#b99481', 800: '#d1b7ab', 900: '#e8dbd5' }, 'platinum': { DEFAULT: '#e8e8e8', 100: '#2e2e2e', 200: '#5d5d5d', 300: '#8b8b8b', 400: '#bababa', 500: '#e8e8e8', 600: '#ededed', 700: '#f1f1f1', 800: '#f6f6f6', 900: '#fafafa' }, 'silver': { DEFAULT: '#bfbfbf', 100: '#262626', 200: '#4d4d4d', 300: '#737373', 400: '#999999', 500: '#bfbfbf', 600: '#cccccc', 700: '#d9d9d9', 800: '#e6e6e6', 900: '#f2f2f2' }, 'coral': { DEFAULT: '#fc814a', 100: '#401501', 200: '#812a02', 300: '#c13f03', 400: '#fb560a', 500: '#fc814a', 600: '#fd9b6e', 700: '#fdb492', 800: '#fecdb7', 900: '#fee6db' }, 'rich_black': { DEFAULT: '#031927', 100: '#010508', 200: '#010a0f', 300: '#020f17', 400: '#02141e', 500: '#031927', 600: '#09517d', 700: '#1089d4', 800: '#50b4f2', 900: '#a8d9f8' } }

- CSV

765341,e8e8e8,bfbfbf,fc814a,031927

- With #

#765341, #e8e8e8, #bfbfbf, #fc814a, #031927

- Array

["765341","e8e8e8","bfbfbf","fc814a","031927"]

- Object

{"Coffee":"765341","Platinum":"e8e8e8","Silver":"bfbfbf","Coral":"fc814a","Rich black":"031927"}

- Extended Array

[{"name":"Coffee","hex":"765341","rgb":[118,83,65],"cmyk":[0,30,45,54],"hsb":[20,45,46],"hsl":[20,29,36],"lab":[39,12,16]},{"name":"Platinum","hex":"e8e8e8","rgb":[232,232,232],"cmyk":[0,0,0,9],"hsb":[0,0,91],"hsl":[0,0,91],"lab":[92,0,0]},{"name":"Silver","hex":"bfbfbf","rgb":[191,191,191],"cmyk":[0,0,0,25],"hsb":[0,0,75],"hsl":[0,0,75],"lab":[77,0,0]},{"name":"Coral","hex":"fc814a","rgb":[252,129,74],"cmyk":[0,49,71,1],"hsb":[19,71,99],"hsl":[19,97,64],"lab":[67,43,50]},{"name":"Rich black","hex":"031927","rgb":[3,25,39],"cmyk":[92,36,0,85],"hsb":[203,92,15],"hsl":[203,86,8],"lab":[8,-3,-12]}]

- XML

<palette>
  <color name="Coffee" hex="765341" r="118" g="83" b="65" />
  <color name="Platinum" hex="e8e8e8" r="232" g="232" b="232" />
  <color name="Silver" hex="bfbfbf" r="191" g="191" b="191" />
  <color name="Coral" hex="fc814a" r="252" g="129" b="74" />
  <color name="Rich black" hex="031927" r="3" g="25" b="39" />
</palette>
```

