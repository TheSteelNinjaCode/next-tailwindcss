Install Tailwindcss
https://tailwindcss.com/
npm install -D tailwindcss
npx tailwindcss init

NextJS tailwindcss
npx create-next-app@latest

Installing dependencies:

- react
- react-dom
- next
- typescript
- @types/react
- @types/node
- @types/react-dom
- tailwindcss
- postcss
- autoprefixer
- eslint
- eslint-config-next

VSC Extensions
https://tailwindcss.com/docs/editor-setup

Tailwind CSS IntelliSense
https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss
1 - VSC -> File -> Preference -> Settings -> files: associations -> Add item -> item = \*.css, value = tailwindcss
2 - VSC -> File -> Preference -> Settings -> editor: quick suggestions -> item = string, value = on

Prettier
Install VSC extension prettier
https://prettier.io/
search for default formatter and select prettier
Settings
file -> preference -> settings -> editor: default formatter -> prettier
file -> preference -> settings -> Editor: Format On Save
https://github.com/tailwindlabs/prettier-plugin-tailwindcss
npm install -D prettier prettier-plugin-tailwindcss

create file prettier.config.js
file: prettier.config.js
// prettier.config.js
module.exports = {
  plugins: ['prettier-plugin-tailwindcss'],
}

for all the fille inside the folder
npx prettier --check .

for a specific file
npx prettier ./styles/globals.css

to write the changes to the file
npx prettier ./styles/globals.css --write
or
npx prettier . --write

//=========================================================================//
Tailwindcss plugins

Tail-kit
https://www.tailwind-kit.com/
https://www.tailwind-kit.com/started

Headlessui
https://headlessui.com/
npm install @headlessui/react

Daisyui
https://daisyui.com/docs/themes/
npm i -D daisyui@latest

module.exports = {
plugins: [require("daisyui")],
}
