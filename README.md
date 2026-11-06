# ESO para personas adultas · CADIR

Landing page for CADIR's (Asociación Capacidades Diferentes y Responsables, Valencia) adult ESO programme.

Live: https://fpsbasicacadir.vercel.app

## Development

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # static output in dist/
```

Built with Astro and plain CSS. Fonts: Fraunces and Figtree (self-hosted via Fontsource).

## Content to review

The programme details are realistic placeholders. Search the code for `REVISAR` to find them:

- `src/components/ComoFunciona.astro`: steps, levels and modules, ámbitos.
- `src/components/Logros.astro`: figures (courses, group size, cost).
- `src/components/Testimonio.astro`: example testimonial. Replace with a real one, with permission.
- `src/components/FAQ.astro`: age, cost, schedule, validations.

## Form

`src/components/Formulario.astro` validates on the client and shows a success state. It does not send data yet (see the `TODO: connect backend` comment). Options: Web3Forms, Formspree or a Vercel function.

## Photo credits

All photos are from Unsplash (Unsplash License):

- Centre for Ageing Better: `hero.jpg`, `senior.jpg`
- Monica Melton: `tutor.jpg`
- Vitaly Gariev: `clase.jpg`
- Jud Mackrill: `hombre.jpg`
- Gabriel Ogulu: `sonrisa.jpg`
