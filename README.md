# chatapp
 Chat de aplicativo usando a biblioteca Channels.

* Projeto usado no tutorial do site da biblioteca Channels.

* Channels é uma biblioteca que traz um suporte a modo assíncrono no Django.

* É um chat bem clássico. Entra entra no site, digita o nome de uma sala, e pode escrever na sala, podendo também ver mensagens que outras pessoas estão escrevendo na sala.

* É um site relativamente simples, mas ensina bem como funciona programação assíncrona, conversa entre o Javascript e o Django, além de vários conceitos interessantes de desenvolvimento web.

* Instruções para instalação:
    - Instale o Python e utilize o pip para instalar o framework Django, Channels. Nesse projeto foi o utilizado o Python 3.11.5, Django 4.2.6, Channels 4.0.0 e Channels-redis 4.1.0, para interface com servidor Redis.

    - Aplique as solicitações de migration para poder utilizar os models, principal o session.

    - Tenha um servidor Redis aberto na porta 6379. Nesse projeto, foi utilizado o Redis 7, assim como sugerido no tutorial do site.

    - Basicamente isso, aplique o "python manage.py runserver" para iniciar.