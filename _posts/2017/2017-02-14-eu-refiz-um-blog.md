---
layout: post
title: "Eu (re)fiz um blog"
date: 2017-02-14 18:20 -0300
categories: meta
---
Estava insatisfeito com este blog no WordPress. Sabe quando você exagera na dose ao resolver um problema? A solução funciona, mas parece tão… inadequada para o problema que passa a ser, ela própria, um incômodo. Era assim que me sentia com o WordPress para publicar essas poucas palavras esporádicas num blog que leva o meu nome.

Então, comecei a buscar por alternativas. Sistemas de blogs estáticos eram a solução mais óbvia. O WordPress é um gerador de sites dinâmico. Funciona, mas é um exagero para isto aqui. Na prática, ser um sistema dinâmico significa que cada vez que alguém acessa um post, o pedido do navegador ao servidor por uma cópia desse post desencadeia todo um processo interno que envolve um banco de dados e outras ações de que não convém falar. Tudo para entregar umas poucas linhas de texto. É um exercício enorme e quase sempre injustificado.

Um sistema estático, por outro lado, é só um monte de arquivos, como esses que você salva no seu computador, colados num template e servidos assim, “crus”, do jeito que foram escritos. Ele não tem sequer uma área administrativa, um painel web onde se escreve os posts. Para publicar alguma coisa aqui, eu escrevo o post em qualquer editor de textos no meu computador, salvo o arquivo e faço um commit no GitHub.

Pois é, eu também ficava travado nessa parte de “fazer um commit no GitHub”. Tentarei explicar mesmo não dominando esse negócio.

Desde que tomei conhecimento dos sistemas estáticos, há uns quatro anos, era a parte do GitHub que me impedia de brincar com eles. O GitHub é um sistema muito popular entre programadores. Ele permite gerenciar versões de códigos e receber colaborações de outros programadores, mantendo tudo registrado, organizado e facilmente recuperável. Eu uso ele, na verdade só o básico do básico, para manter o layout do [Manual do Usuário](https://www.manualdousuario.net) atualizado. Usar o GitHub para gerar um blog estático não é muito diferente, mas até sacar as nuances que distinguem as duas atividades foi um sofrimento, potencializado por tutoriais muito ruins que o buscador retorna aos desesperados ignorantes em busca de uma luz.

De qualquer modo, após bater bastante a cabeça na parede, deu certo. Criei o blog localmente com o Jekyll, o sistema estático que escolhi; importei o conteúdo do finado WordPress para ele; fiz o template, aí criei meu blog no GitHub Pages, que é gratuito e resolve bem para algo despretensioso como é o meu caso; por fim, direcionei esse domínio bacana, ghed.in, para lá. Depois acabei ativando o Cloudflare, uma CDN gratuita, para ter um certificado SSL (o cadeado de site seguro, o que garante que nenhum bisbilhoteiro saiba que você esteve visitando este blog).

O mais legal, e isso era uma meta pessoal, é que este blog não emprega uma linha sequer de JavaScript. Essa linguagem, diferentemente de outras como o PHP, roda localmente, no próprio navegador. Ela serve para uma infinidade de coisas, de registrar a sua visita aos sites (e monitorar seus hábitos de navegação por eles) a criar efeitos especiais nas páginas. Em muitos casos, é usada em excesso, o que gera dois inconvenientes: aumenta o tempo de carregamento e o consumo de dados e aumenta as chances de um site quebrar ou funcionar erroneamente. Não preciso de nada disso aqui.

Ao visitar este blog, você não deixa nada para trás e eu peço pouquíssimo em troca. Em posts sem imagens, como este, míseros 10 kB de tráfego — apenas como referência, um tweet besta como aquele meu do “vou beber água” exige 2,34 MB, ou 2285 kB por três palavras. Ah, e também alguns minutos do seu tempo, se ler tudo até o final. Eu realmente não acho que o que escrevo aqui tenha lá muito valor, então exigir mais do que isso seria (olha o termo aí de novo) um exagero.

No mais, gosto desse visual espartano, utilitário. Deixei apenas o básico, o essencial para que você me leia. Nada além, nada aquém. Estou restaurando os posts antigos aos poucos, um a um, manualmente. Nesse trabalho, aproveito para revisar os erros (gramaticais, ortográficos e da minha cabeça). Está sendo legal revisitar coisas que escrevi há dez anos. As que sobraram daquela época, pelo menos.

Se quiser ser avisado dos futuros posts, o que é uma boa já que não tenho ideia de quando escreverei aqui novamente, [assine o feed](https://blog.ghed.in/feed.xml) ou [esta newsletter](https://newsletter.ghed.in) que acabei de criar só para isso. E obrigado pela sua atenção!
