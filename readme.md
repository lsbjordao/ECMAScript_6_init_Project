# Iniciar projeto ECMA Script 6 (ES6) no NodeJS

## Instale as dependências necessárias

```
npm install --save-dev @babel/core @babel/cli @babel/preset-env @babel/plugin-transform-runtime
```

## Crie o arquivo de configuração `.babelrc` na raiz do seu projeto

```
{
  "presets": ["@babel/preset-env"],
  "plugins": ["@babel/plugin-transform-runtime"]
}
```
## Adicione um script no arquivo `package.json` para compilar o código

```
{
  "scripts": {
    "build": "babel src -d dist"
  }
}
```

## Salve os scripts JS como `.mjs`
