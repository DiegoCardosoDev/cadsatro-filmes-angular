

# APLICAÇÃO EM ANGULAR.


## Ambiente Local

## Simulando o Back-end

## Gerendo componente

Execute `ng generate component nome-do-componente` para criar um novo componente. Você também pode usuar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Execute `ng build` para gerar o compilado do projeto. O projeto vai ser criado dentro do diretório `dist/`. Adicionar `--prod` junto comando de build para gerar minificado e pronto para o ambiente de produção.


Execute `ng serve` para que o projeto suba localmente. Acesse a url `http://localhost:4200/`. O projeto já está com reload automático conforme as alterações que você realizar no código
![img1](https://user-images.githubusercontent.com/83510729/127482136-28b69adb-d6d9-4076-bfef-d7a68b661f49.png)
![page 1](https://user-images.githubusercontent.com/83510729/127482455-68a6ce83-6aa2-4e5a-a6f0-c4379a007f69.png)

#Execute `npm install -g json-server` para instalar globalmente o servidor json. Após a instalação entre na pasta do projeto e execute `json-server --watch db.json`, com isso um servidor será inicializado na url `http://localhost:3000/`, após a inicialização sera possível realizar requisições http.
![cad1](https://user-images.githubusercontent.com/83510729/127482496-17864290-6c5d-4975-9a19-a8cbc7b3e124.png)
![json](https://user-images.githubusercontent.com/83510729/127482515-c70b2b53-a60c-434f-b9f5-602c9492e312.png)
![json](https://user-images.githubusercontent.com/83510729/127482773-7644b10f-3052-4e86-9615-a6354bcbb285.png)


