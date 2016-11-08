# App

Criar um aplicativo que lista as séries de televisão mais populares atualmente, usando a API do [Trakt](https://trakt.tv) para isso (você deve se registrar no site para ter acesso à API).

O Web App segue o modelo Master-Detail. Na tela principal (master), é mostrada uma grid com os seriados. Ao final da grid, existe um botão de "Carregar Mais", que, quando clicado dispara uma nova request para trazer seriados adicionais.
![Master](https://github.com/finchsolucoes/recrutamento-front/raw/master/Master.png)

Quando uma das séries é clicada, o usuário é levado à página de detalhe (detail) onde informações adicionais sobre a série são exibidas.
![Detail](https://github.com/finchsolucoes/recrutamento-front/raw/master/Detail.png)

Ao clicar no logo situado na Nav Bar, o usuário é levado de volta pra tela principal.


# Regras

* É permitido o uso de bibliotecas externas, assim como gerenciadores de dependências. No entanto, você precisa justificar o porquê de estar usando aquela biblioteca

* Você deve incluir todas as instruções necessárias para executar o projeto e os testes (se houver)

* Na entrevista você será questionado sobre o seu código - o que o levou a tomar as decisões que tomou

* **Importante**: Caso tenha problemas em utilizar a API do Trakt para obter as imagens das séries, favor utilizar o serviço [lorempixel](http://lorempixel.com) para gerar thumbnails e as demais imagens de maneira dinâmica


# Requisitos

* Não pode ter erros / warnings no seu código JS (OK se for da library)

* Versão mínima ES 5.1

* É permitido o uso de bibliotecas externas, assim como gerenciadores de dependências

* Layout deve ser responsivo


# Extras

* Utilizar promises para as requests da API

* Código todo em ES 2015

* Utilizar algum Lint

* Testes unitários

* Testes end-to-end (E2E)


# Submissão

Crie um repositório no GitHub e adicione nele o código fonte. Ao terminar o teste, envie um email para nós com o endereço do seu repositório para que possamos conduzir a análise.
