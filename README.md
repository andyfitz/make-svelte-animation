# Make Animation Template (Svelte)



## Development server

Install all necessary dependencies `npm install`

Run `npm run dev` for a dev server. Navigate to `http://localhost:5000/`.

## Building for Make

It's a good idea to run `npm run validate` to check for any Svelte specific and Typescript errors in your code.

Run `npm run build` to build the project with correct resource pathing for the sake of deploying to make.

The build artifacts will be stored in the `/public/build` directory.

## Importing into Make

When importing into Make be sure to import from the `/public` folder.

The following `data` inputs are available as well.
