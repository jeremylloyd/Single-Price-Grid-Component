# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [Github](https://github.com/jeremylloyd/Single-Price-Grid-Component)
- Live Site URL: [Vercel](https://single-price-grid-component-five-ruddy.vercel.app/)

## My process

### Built with

- HTML
- CSS
- JS
- Svelte

### What I learned

- Svelte
  - By default, SvelteKit is configured to prefer static content be served from the `/static` directory. Use it instead of the `/images` directory I've used for previous projects
  - Components
    - Named according to the file - e.g. `Button.svelte`
    - Pass content to the component using slots
      - `<slot name='content'></slot>` in the component
      - `<p slot='content'></p>` in the page
    - Reference the component on the page with `<Button></Button>`
  - To generate a HTML element for each item in an array, try the `{#each array as item}` syntax
- Deployment
  - Github Pages can only handle static sites. Generally not the case for a Svelte app
  - Vercel was able to figure out I was using Sveltekit and do the low-level work behind the scenes. Helpful now, but I may want to learn more eventually if I want to deploy an app on Azure
  - [This link](https://blog.codedbyjordan.com/deploying-a-vite-app-with-github-actions) was a great reference
