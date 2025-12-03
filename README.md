PA-X Gender Scrollytelling

This is a [`Svelte`] project. It includes a deployment setup using [`gh-pages`] to publish the built site to GitHub Pages.

### Prerequisites

- [`Node.js`] 
- [`npm`] installed globally

### Installation

npm install

### Development

npm run dev 

### Build

npm run build 

### Deployment

npm run deploy

### Update

1. Replace 2 csv files with updates:  
   `pax_gender_v[new_version].csv`, `pax_v[new_version].csv`

2. Update file names in `App.svelte` on line 456:

```js
// LOAD PAX
let path = [
	"./data/pax_v9.csv",
	"./data/pax_gender_v9.csv",
	"./data/gender_categories.csv",
];