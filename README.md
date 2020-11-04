# Typescript Nuxt Template

A basic and clean nuxt and typescript template to start a project.

## Requirements

- Yarn (package manager).

## How to use

1. Clone the repository.
2. Navigate to project folder.
3. Run `yarn install` command to install dependencies.
4. Run `yarn dev` to start a development server.

## Default scripts

- Run `yarn dev` to start a development server.
- Run `yarn build` to generate production files.
- Run `yarn start` to start a production server.

## Generate static website

To generate a static website you have to add a couple of lines to the nuxt configuration file:

```javascript
export default {
	ssr: false,
	target: 'static',
	// { ... }
};
```

Once this is done, you can run `yarn generate` to generate a static website.
