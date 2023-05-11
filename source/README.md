<h1 align="center"><code>phydim.js</code></h1>

<p align="center">Physics Dimensions</p>

## ⚙️ Installation

```terminal
npm i phydim
```

## 📖 Usage

#### ▣ Import

```js
// ES6
import phydim from "phydim";

// commonjs
const phydim = require("phydim");
```

#### ▣ All methods

```js
// • All data
console.log(phydim.all());                  // { meter: 'L', kilogram: 'M', ...}

// • Random data
console.log(phydim.random());               // { name: 'weber', dimension: 'ML^2/T^2I^-1' }

// • From id
console.log(phydim.id(4));                  // { name: 'kelvin', dimension: 'Θ' }

// • From name
console.log(phydim.name("coulomb"));        // { name: 'coulomb', dimension: 'IT' }

// • From dimension
console.log(phydim.dimension("MT^-2I^-1")); // { name: 'tesla', dimension: 'MT^-2I^-1' }
```

---

[Support me on Patreon](https://www.patreon.com/axorax) — 
[Check out my socials](https://github.com/axorax/socials)