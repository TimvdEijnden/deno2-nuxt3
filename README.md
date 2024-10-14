# Nuxt 3 powered by Deno 2.0

<img height="100" src="public/deno2.png" title="Deno 2 logo"/>

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) and [Deno documentation](https://docs.deno.com/) to learn more.

Make sure to check out the **[deno.json](deno.json)** file to see how the tasks are configured.

## Setup with deno 2

Clone the repository:

```sh
git clone https://github.com/TimvdEijnden/deno2-nuxt3.git
```

Make sure to install the dependencies using deno:

```bash
deno install
````

## Development Server

Start the development server on `http://localhost:3000`:

```bash
deno task dev
```

## Production build

Build the application for production:

```bash
deno task build
```

Preview the production build on `http://localhost:3000`:

```bash
deno task preview
```

No node needed al all. Just Deno.