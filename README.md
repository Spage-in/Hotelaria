# Room Joy Service Hub

Crie um aplicativo bem simples que tenha apenas 3 botões principais no canto inferior da tela, centralizados. 
Botões:
Início
Pedidos
Recepção

Objetivo: um aplicativo que rede no navegador onde hospedes de hotel e pousadas podem solicitar serviços do quarto por meio desse app, como:
Troca de toalhas, troca de roupa de cama, limpeza, produtos de banho, água, etc.

O app conta com uma base de dados para cada quarto privado, onde será colocado um qr code no em cada quarto e irá direcionar para o link do app, na tela inicial o usuário terá que colocar o número do quarto, após dar ok será preciso confirmar se é esse número de quarto mesmo, após ele confirmar vai aparecer os botões.

Cada quarto terá uma tela privada, nenhum hospede poderá ver pedidos de outros quartos, será protegido por uma senha com os 4 ultimos número do telefone do hospede, configurado diretamente na hora do check-in. 

A administração do hotel/pousada terá uma dashboard privada, somente administração terá acesso por meio de login. Usuário não precisam de login.
Cores: preto, branco e cinza claro.
Layout: cantos de cards arredondados, estilo apple, sem sombras.

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://room-joy-service-hub.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/0b1dcc06-99d2-5ad3-855b-944a7aaba5c0).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
