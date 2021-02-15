# Sobre o teste

Este teste consiste em desenvolver uma aplicação simulando rotinas utilizado no nosso dia à dia.

## O que você deve fazer

> Requisítos para desenvolvimento deste teste:
- Electron
- Javascript
- VueJS 2
- Node ( acima da versão 8 )
- NPM ou YARN


## Sobre o teste
 1. Faça a instalação e configuração do Electron, o aplicativo deve abrir maximizado ( fullsize window );
 2. Faça uma chamada REST API, você precisa listar pelo menos 6 imagens, 3 acima e 3 abaixo, para isso utilize o "axios" para obter as fotos na api > (https://picsum.photos/);
3. Construa uma classe JS onde você precisará utilizar os seguintes eventos dentro das funções criadas na Classe:
 >> Faça uso do ipcMain.handle e ipcRenderer.invoke ( electron ) para emitir um alerta no clique de cada imagem ( o alerta pode ser um nome dado à imagem clicada )
4. Criar um auto update da aplicação no electron, para isso você precisará ter uma conta no github, o auto update seria ex: Versão do projeto  V.0.1 para V.0.2
5. Faça o versionamento do código e suba no seu github, construa um README para instalação do projeto.



## Docs de apoio
- https://www.electronjs.org/docs
- https://vuejs.org/v2/guide/
- https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Classes


## License
[MIT](https://choosealicense.com/licenses/mit/)
