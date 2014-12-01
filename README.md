SpartanPlayground
================================

### Requirements

- **Install Node**
	from [nodejs.org](http://nodejs.org/)
- **Install XTC CLI**
	`npm i -g xtc-cli`


> Update node with [n](https://github.com/tj/n) and npm via `npm i -g npm` (warnings may be ignored)

### Startup

- **Run XTC Server**
	`xtc start`

- **Run FE Build**
	`xtc build`

- **Open in Browser**
	[`localhost:3000`](http://localhost:3000)

### Fiddle around

> Create 'develop' branch

- adjust [61-grid.less](https://github.com/SimonHarte/SpartanPlayground/tree/master/frontend/base/css/61-grid.less) if needed
- solve [playground examples](http://localhost:3000/playground) to get yourself accustomed to Spartan

> Refer to [the docs](https://github.com/SimonHarte/SpartanGrid) for help!

### Using PHP Environment

There's a Terrific Micro installation for PHP users, not much explanation here because I expect you to know what to do ;)

- set up a virtual host pointing to [`project root`/terrific](https://github.com/SimonHarte/SpartanPlayground/tree/master/terrific)
- make a host entry
- open `whatever-you-called.it/playground` in your browser

> Assets will still be imported from xtc, so you have to adjust those files and add new files to [imports.less](https://github.com/SimonHarte/SpartanPlayground/blob/master/terrific/assets/css/imports.less)
