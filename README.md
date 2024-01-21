# tailwind



https://shubham01015.github.io/tailwind/


AIzaSyAqKMAYLdXHpw93B-aA0sxbYnI0fW7VH7k

```bash
npm init -y
```
```bash
npm install -D tailwindcss postcss autoprefixer
```
```bash
npx tailwindcss init
```
```bash
npx tailwindcss init -p
```
```bash
npm i vite
```

tailwind.config.js
```bash
/** @type {import('tailwindcss').Config} */
const colors = require('tailwindcss/colors')

module.exports = {
  content: [    './pages/**/*.{html,js}',
  './components/**/*.{html,js}'],
  theme: {
    colors: {
      transparent: 'transparent',
      current: 'currentColor',
      primary: '#23a991',
      secondary: '#455174',
      'white': '#ffffff',
      'body': '#181c28',
      'green': '#23a991',
      'mini': '#262d41',
    }
  },
  plugins: [],
}
```
package.json

```bash
  "scripts": {
    "start": "vite"
  },
  ```