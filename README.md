

## Instalação

Clone este repositório e dê um `npm install` para instalar todas a dependências.

## OBS
 
A API's estão na pasta `src/environments` `apiKey` 

`src/environment.ts`
```
export const environment = {
  ...
  apiEndpoint: '//gateway.marvel.com/v1/public/',
  apiKey: '<Sua chave public aqui>'
};
```
você pode cadastrar sua **public** key aqui > [Marvel Developer Portal](http://developer.marvel.com/)


Execute o comando `ng serve` para startar a aplicação. Você será redirecionado para http://localhost:4200


## Dependencias
rxjs, nodejs, express, material design
