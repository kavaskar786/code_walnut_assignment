# Front-End Technical Test

Welcome to CodeWalnut's front-end technical test using React and the [PokeAPI](https://pokeapi.co/)! The PokeAPI provides an extensive REST and GraphQL API for fetching Pokémon data. In this test, you will build a Pokémon app that utilizes the PokeAPI, and you can choose from different levels of difficulty depending on your experience.

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/CW-Codewalnut/codewalnut-front-end-tech-test.git
```

### 2. Install Dependencies

We are using `pnpm` for package management. If you haven't installed `pnpm` yet, you can install it globally by running:

```bash
npm install -g pnpm
```

Once you have `pnpm` installed, run:

```bash
pnpm install
```

### 3. Available Styling Options

The project is set up with **Tailwind CSS** as the default styling solution. However, you can opt to use any of the following:

- **Tailwind (default)**: Already configured in `src/app/globals.css`.
- **CSS**: You can create and use custom CSS styles by modifying or adding to `src/app/globals.css`.
- **Sass**: A basic Sass configuration is already in place. Add your styles to `src/styles/globals.scss`.

You are free to use any styling approach you prefer, these are just the options set up for you already in this project.

### 4. Running the App

To start the development server, run:

```bash
pnpm dev
```

This will launch the app in development mode at [http://localhost:3000](http://localhost:3000).

# Instructions/ workflow

## Pokemon Listing Page

The pagelist page is the home page for this pokemon explorer website

Inside this page we can able to search/sort and also able to choose the type of pokemon.

when the user clicks the particuar card. the details of that particular pokemon is visible along with the graphical representation. and also able to add the pokemon to the team.

## Pokemon search page.

In this page user can able to search using the name and Id of the pokemon

## Teams page

Here user can able to manage the pokemons in the teams.. they can able to remove the pokemons..

## Login page

Typical login page.. using chache and local storage..

## Register page

Typical login page.. using chache and local storage.
