# Aplicação do Babel e Webpack do Bootcamp da DXC!
 
 Sejam bem vindos ao repositório! Aqui, tratei de algumas explicações sobre qual a importância do Babel e do Webpack. Outra coisa, saiba que vc pode utilizar esse projeto como um boilerplate pra uma aplicação futura. Abaixo seguem os códigos utilizados no decorrer do bootcamp.
 
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

-------
## Agradecimentos

Agradeço toda a equipe da [DXC](https://dxc.com/br/pt) pela oportunidade de trazer conteúdo de Javascript em suas apresentações do Bootcamp
