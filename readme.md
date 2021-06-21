# Curso ESLint y Prettier

## Agenda - 02 - Instalando y configurando ESLint

    * Instalar ESLint
    * Instalar Extension
    * Configurar ESLint

    1.- npm i eslint -D    ---> como dependencia de desarrollo.
    2.- npx eslint --init   ---> para cunfigurar eslint

    Elegir la 3.
    Elegir la 2 commonJS
    Elegir none of these
    elegir  NO
    Elegir node
    Elegir  Elegir erbnb
    Elegir yes

luego modificar el pakage.json
1.- "lint": "eslint src/app.js"
2.- Luego instalar eslint en vscode

# Instalar eslint Para que no haya conflicto entre prettier y eslint

prettier
/
npm i -D eslint-config-prettier

<!-- Para mostrar advertencias en eslint -->

eslint-plugin-prettier prettier
