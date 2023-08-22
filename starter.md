npm init
npm install -D @tsconfig/node-lts
npm i -D @types/node

add to package.json script section
"start": "npx tsc && node dist/index.js"
