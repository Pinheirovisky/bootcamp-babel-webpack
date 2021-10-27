# bootcamp-react da DXC!
 
 ### Códigos utilizados:
 
 Iniciar o package.json:
 ```
 npm init -y
 ```
Instalar dependências do babel, após esse comando, será criado uma pasta 'node_modules':
```
npm install --save-dev @babel/cli @babel/preset-env @babel/core
```

Após criar um arquivo chamado 'main.js', gerar um arquivo chamado 'bundle.js' que transformará o seu código em um JS mais antigo:
```
npx babel main.js -o bundle.js --presets=@babel/env
```

Adiconar o script 'babel' no packjage.json:
```
babel ./main.js -o ./bundle.js --presets=@babel/env -w
```

Adicionar dependências do webpack:
```
npm install --save-dev @babel/cli @babel/preset-env @babel/core babel-loader webpack webpack-cli regenerator-runtime core-js
```

Adicionar o script 'gerador no package.json:
```
webpack -w
```
