# Projeto Novo Eleitor - App híbrido

## Sobre o projeto

Aplicativo desenvolvido através do ionic framework para comunicação com o sistema backend do projeto novo eleitor (https://github.com/ops-org/projeto-novo-eleitor).

Este será portável para as plataformas Android e IOS e seu codebase poderá ser aproveitado para uma possível aplicação desktop pelo fato de utilizar tecnologias conhecidas para web.

## Informações úteis

Esse sistema é desenvolvido por meio do Ionic Framework. O Ionic é um framework que utiliza várias tecnologias do mercado para o desenvolvimento rápido de aplicações móveis Híbridas por meio do Cordova e Angular 2+.


## Para iniciar os trabalhos nesse projeto

* NodeJS versão 8 ou superior;
* NPM (para a instalação dos pacotes)
* Um bom editor à sua escolha;

Para começar a trabalhar nesse projeto:

* Clone esse projeto;
* Instale as dependencias do projeto;
* Inicie o serviço do Ionic;
* Instale a ferramenta para executar o projeto no seu celular com livereload; (opcional)
  * Para Android - https://play.google.com/store/apps/details?id=io.ionic.devapp;
  * Para iOS - https://itunes.apple.com/us/app/ionic-devapp/id1233447133?mt=8;
* Ajude-nos implementando melhorias;
* Submeta-nos um Pull Request com sua alteração.

    $ npm install;
    $ ionic serve -c
    $ # caso queira instalar uma versão compilada direto no android, faça:
    $ ionic cordova run android; 

Assim que é rodado o "*ionic serve -c*" você abre o aplicativo **Ionic DevApp**, e se loga na mesma rede do computador onde está sendo desenvolvido. A aplicação achará o projeto e você poderá carregar o projeto de maneira dinâmica enquanto desenvolve. 

## Tecnologias utilizadas nesse projeto

* AngularJS 5.2 (https://angularjs.org);
* HTML/CSS/JS; (Stack padrão para frontend WEB);
* Android SDK (Caso esteja testando para a plataforma Android) [Dispensável caso utilize o Ionic Devapp]
* Xcode (Caso utilize um Mac e queira realizar build para a plataforma iOS) [Dispensável caso utilize o ionic Devapp diretamente no seu iPhone]

## Precisando de ajuda?

Em caso de dúvidas, por favor, abra um issue no github que tentaremos responder de maneira mais rápida possível.
