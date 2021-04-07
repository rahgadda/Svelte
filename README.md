# Svelte

## Overview
- It is a free and open-source front end JavaScript framework.
- Keyfeature of Svelte
  - It is a compiler.
    ![](./01-Images/01-Compiler.png) 
    - It has `no depenecies` for execution.
    - Does not require `Virtual DOM` as all the prework is done during compilation.
    - Svelte code is then compiled into `vanilla JavaScript`.
  - It provides as a `small bundle size`.
  - Relies on `Templates` instead of using extenssion langauages like `JSX`.
    - It has good readability as HTML, CSS and JS are available in single `.svelte` file.
    - The structure of `.svelte` file is given below
      ```markdown
      <script>
        export let name;
      </script>

      <style>	
        h1 {
            color: purple;
        }
      </style>

      <h1>{name}</h1>
      ```
      - The `script` tag, which is an optional JavaScript block.
      - The `style` tag, which is another optional block like a common HTML style tag.
      - The `template` block, is only required block that contains presentation/view of components.
  - `Reactivity` is built into the language/framework itself.
  - Product grade Svelte Apps can be created using legacy `Sapper` or upgraded `Svelte Kit`.

## History
- It is created by `Rich Harris` and maintained by the `Svelte core team members`.
- Rich Harris created Svelte at `New York Times`. 
  - In 2016, he started a small project with below:
    - JavaScript compiler that would produce quality code
    - Be light and does not abstraction of the DOM
    - Super-fast loading time 
    - Fast performance
  - In mid-November 2016, he made his first commit
  - Four days later, the first beta is available
  - Ten days after this beta, on November 26, 2016, he published a blog [frameworks-without-the-framework](https://svelte.dev/blog/frameworks-without-the-framework)
  - Three days after this blog, `Svelte v1.0.0` was born.
  - With a big cleanup, `v2.0.0` was released in `April 2018`
  - A complete overhaul `v3.0.0` was released in `April 2019`
- Along with Svelte; NYT it is home for creators of `BackboneJS`, `UnderscoreJS`, and `D3`.

## Modules


## Appendix
- [Svelte Kit](https://svelte.dev/blog/whats-the-deal-with-sveltekit)
- [Rich Harris What-is-svelte](https://gist.github.com/Rich-Harris/0f910048478c2a6505d1c32185b61934)
- [svelte.dev](https://svelte.dev/tutorial/basics)