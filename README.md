### Projeto VidFlow, Assistir vídeos riquíssimos de conteúdo, Graças a variáveis de API do Node 🎞️

#### Fique a vontade para navegar, em caso de dúvidas estou disponível 24/7 para você 🫵

<div>
    <img src='./img/1.png'/>
</div>

#### Link para o Site 🎯

<div>
    <a href="https://trophy-gamma.vercel.app" target="_blank"><img src="https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white" target="_blank"></a>
</div>

#### ⬇️Pode me chamar no⬇️

<div> 
    <a href="https://www.linkedin.com/in/vinicius-ribeiro-4690741ba/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
    <a href="https://wa.me/5511943232223" target="_blank"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" target="_blank"></a>
    <a href="www.youtube.com/@Devdebotas" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" target="_blank"></a>
    <a href="vinii.viniciusribeiro@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a> 
    <h2>vinii.viniciusribeiro@gmail.com</h2>
</div>

#### Tecnologias utilizadas neste projeto 🤖

[![HTML](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](#)
[![GIT](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)](#)
[![JSON](https://img.shields.io/badge/json%20web%20tokens-323330?style=for-the-badge&logo=json-web-tokens&logoColor=pink)](#)
[![PowerShell](https://img.shields.io/badge/powershell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)](#)
[![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](#)
[![VScode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](#)

#### Conhecimentos Adquiridos durante o processo 🤓

(Back End)

- Identificar o Node.js como um ambiente de execução JavaScript (JavaScript Runtime):

* O Node.js é capaz de executar arquivos JavaScript, assim como os navegadores;

* Ele é capaz de realizar operações que os navegadores não conseguem, como: criação de servidores e APIs, leitura e escrita de arquivos, conversão de código, entre outras;

* Naturalmente, ele não consegue executar código JavaScript específico do front-end, como as APIs de manipulação do DOM;

- Executar seu primeiro programa Node.js!

* Criamos e executou um simples script, que imprimia uma frase no terminal;

* Para isso, usamos o comando node nome-do-arquivo.js dentro da pasta do arquivo;

- Criar o arquivo package.json com o comando npm init:

* Esse arquivo documenta as informações do projeto, inclusive as dependências;

- Identificar o que é o NPM (Node Package Manager):

* É o gerenciador de pacotes do Node e vem instalado junto com ele;

* Um pacote é um projeto escrito em Node que foi publicado no site do NPM, o qual podemos acessar para conferir informações de qualquer pacote, como instruções de uso, versões, etc;

* Podemos utilizar a linha de comando do NPM para instalar e executar pacotes Node;

- Executar um pacote com npm init <inicializador>:

* Executamos o comando npm init @eslint/config@0.4.6, que executa o pacote @eslint/create-config na versão 0.4.6;

* A execução desse pacote torna o terminal interativo. Ao final das perguntas, esse pacote também pede para instalar o eslint no projeto;

- Executar um pacote com npx <pacote>:

* O npx executa um pacote que foi instalado no projeto;

- Instalar um pacote com npm install <pacote>:

* Instalamos o Prettier com npm install --save-dev --save-exact prettier@3.0.3.

- Identificar opções de instalação no comando npm install <pacote>:

* --save-dev ou -D: instala um pacote como dependência de desenvolvimento;

* --save-exact ou -E: documenta que o pacote deve ser instalado por outras pessoas exatamente na versão que nós utilizamos;

- Diferenciar pacotes locais e globais:

* Ao instalar e desinstalar pacotes, podemos utilizar a opção -g (ou --global) para indicar que queremos realizar a operação de forma global;

* Para executar um pacote local, é necessário escrever npx no início do comando. Para executar um pacote global, não é necessário;

- Versionar as dependências do seu projeto:

* Aprendemos sobre o versionamento semântico e que os números se referem a Major Version, Minor Version e Patch Version (versões maiores, menores e de correção);

* O NPM utiliza alguns caracteres especiais para indicar faixas de versões compatíveis.

* O circunflexo (^) indica que queremos uma versão igual ou maior à especificada da dependência, mas sem aumentar o número da major version. Exemplo: ^1.5.0 é compatível com 1.5.0, 1.5.2 e 1.6.0, mas não é compatível com 2.0.0 ou maiores;

- Facilitar a execução de comandos com scripts:

* Você pode definir seus próprios scripts na seção "scripts" do package.json;

* Para executar um script, basta executar npm run <nome-do-script>;

- Utilizar a CDN do Axios:

* É a forma mais simples de utilizar seu código-fonte;

* Porém, não temos um controle de versionamento que o NPM nos fornece;

* Também não temos o IntelliSense (auto-completamento) do VSCode para o Axios;

- Migrar um projeto para o Vite:

* Criamos um projeto Vite com npm create vite@4.4.1;

* Migramos os arquivos, dependências e scripts necessários;

- Utilizar o Axios junto com o NPM, como uma dependência de produção:

* Em um projeto Vite, conseguimos usar a sintaxe import axios from "axios" para utilizar o Axios diretamente em um arquivo JS;

* Colocar o nome de um pacote NPM diretamente dentro do caminho da importação é uma sintaxe que funciona apenas em um ambiente Node.js;

* Ou seja, essa sintaxe funcionou porque o Vite nos disponibiliza um servidor Node que, além de entender a sintaxe, transforma ela para um código que os navegadores consigam entender;

* Normalmente, o caminho de importação no front-end sempre inicia com um caminho relativo ou absoluto. Exemplos: "./caminho", "../caminho", "/caminho";

- Diferenciar uma dependência de desenvolvimento de uma dependência de produção:

* Uma dependência de desenvolvimento vai atuar apenas em ambiente de desenvolvimento, como o ESLint, Prettier, JSON Server e o próprio Vite; elas não serão utilizadas no ambiente de produção, quando o nosso site estiver no ar em um endereço da web;

* Já uma dependência de produção precisa ter seu código-fonte importado mesmo quando nosos site for para produção, que é o caso do Axios. Isso porque utilizamos diretamente os métodos do Axios para realizar requisições HTTP nos arquivos JS que irão para produção;

- Realizar um build local e criar um servidor de prévia de produção:

* Isso foi realizado com os comandos npm run build e npm run preview.

- Dinamizar o código de acordo com o ambiente de execução do projeto:

* Utilizamos a variável de ambiente do Vite import.meta.env.PROD, que informa se estamos em ambiente de produção ou não;

* Fizemos isso para que informações de produção (como links de APIs em produção) sejam utilizadas, de fato, apenas em produção. Enquanto localmente, iremos trabalhar apenas com serviços locais, como o JSON Server;

- Realizar deploy do seu projeto!

* Utilizamos o GitHub e a Vercel para criar um link que qualquer pessoa pode acessar.

(Front End)

- Organizar os arquivos e pastas do projeto;

- Transformar o layout do Figma em código;

- Construir o cabeçalho, barra lateral e seção de categorias do VidFlow;

- O que é e como instalar a API Fake JSON Server;

- Como fazer a busca dos dados na API com o Fetch;

- Como lidar com .then e com Promises;

- Como manipular o DOM para exibir os dados da API;

- Como usar o .catch para capturar erros;

- Evitar o “Callback Hell”;

- Refatorar o código assíncrono com Async/await;

- Realizar tratamento de erros com os blocos Try-Catch-Finally;

- Tratar erros personalizados com o throw new Error;

- mplementar uma barra de pesquisa para filtrar vídeos por título;

- Refatorar o código para torná-lo mais sucinto e organizado;

- Implementar funcionalidade ao filtro de categorias.
