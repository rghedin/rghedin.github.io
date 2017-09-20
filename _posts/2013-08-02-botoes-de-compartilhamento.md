---
layout: post
title: "Botões de redes sociais são necessários na web?"
date: 2013-08-02 19:50 -03:00
---
![Redes sociais!!!]({{ site.baseurl }}/assets/social-icons.png)

Redes sociais já representam uma parte significativa no gráfico de origem dos acessos da maioria dos sites. Essa constatação valida toda a atenção que elas recebem e ratifica os esforços em facilitar o trânsito de conteúdo entre os dois espaços. Apesar de toda essa importância, muita gente não gosta dos botões de compartilhamento das redes sociais hoje onipresentes na web. Há bons motivos para justificar essa aversão e, para a alegria desses, alguns exemplos apontam que o maior temor em uma eventual remoção deles, o da queda no fluxo de visitas originadas em redes sociais, pode não ocorrer na prática.

### De onde os botões vieram?

Quando as redes sociais começaram a se popularizar era comum ver, no rodapé dos posts de blogs simples a grandes portais, um punhado de ícones delas. Quanto mais, melhor. Não importava se alguns botões contemplassem redes com dez usuários, nenhum deles leitor do seu espaço, o que imperava era a ideia do "e se…" Era uma abordagem meio burra que pegava carona no boom de redes sociais de então (da "Web 2.0", lembra?). Felizmente, uma mentalidade que já foi superada.

Superada? Talvez seja mais correto falar em _evolução_. Porque depois dessa fase inicial, os botões não sumiram, eles se transformaram, ficaram dinâmicos -- ou "preguiçosos" para os usuários, afinal agora basta um clique para mandar o link para seu perfil.

Essa possível evolução enxugou a quantidade de botões, restando hoje apenas os mais relevantes. Twitter e Facebook são figurinhas fáceis, mas é cada vez mais comum se deparar com botões do LinkedIn, Pinterest, Tumblr, Google+ e alguns outros poucos. Como eles computam e informam a quantidade de compartilhamentos e facilitam esse ato ao extremo, criou-se a sensação de que a mera presença deles é mais que um incentivo, é um fator imprescindível para que o leitor compartilhe o conteúdo, coisa que, em última instância, aumenta a repercussão e as visitas que o site recebe.

Apesar de parecer uma fórmula hermética, sem espaço para falhas, não é de hoje que se discute os prós e contras dos botões de compartilhamento e se os (supostos) benefícios que eles trazem justificam os males que vêm de carona.

### Botões de compartilhamento funcionam?

Ano passado Oliver Reichenstein, do Information Architects, publicou [um longo artigo](http://ia.net/blog/sweep-the-sleaze/) defendendo a remoção completa dos botões de compartilhamento. O cerne da argumentação (nada científica, é bom esclarecer) é de que não é preciso relembrar as pessoas de que o Twitter existe. Grandes são as chances, aliás, de elas terem chegado ao seu blog a partir de lá. E se o seu conteúdo for realmente bom, ele será passado para frente, as pessoas farão o compartilhamento natural e manualmente, copiando e colando o link no Twitter, Facebook etc.

Um estudo da Tynt demonstrou que [82% de todo o compartilhamento feito em redes sociais na web](http://www.marketwire.com/press-release/tynt-reveals-82-of-all-content-sharing-online-occurs-via-copy-paste-1726715.htm) passa pelo `Ctrl + C, Ctrl + V`. Prova irrefutável? Não. Se vários estudos deixam questões complexas sem um parecer definitivo (café e celular que o digam), basear-se em apenas um para encerrar a discussão é imprudente. E há uma agravante nesse caso: se você pesquisar [quem é a Tynt](http://tynt.com/ "Tynt"), descobrirá que ela desenvolve uma solução que aperfeiçoa... a cópia de conteúdo em sites — com o software dela instalado, além do conteúdo selecionado pelo leitor vai também, para a área de transferência, a URL da página em questão. Há um interesse aí em promover a cópia de links em detrimento dos botões.

Ainda assim, o discurso de Reichenstein se mantém por outros argumentos em acréscimo àquele primeiro. Ele fala sobre a questão de branding, de desperdício (ou cessão) de espaço para as marcas das redes sociais e de como isso soa como desespero por parte do site:

> &#8220;(…) Mas esses botões [de compartilhamento] funcionam? É difícil dizer. O que sabemos ao certo é que esses botões mágicos promovem as suas próprias marcas — e eles tendem a fazê-lo parecer um pouco desesperado. Não muito desesperado, só um pouquinho.&#8221;

Argumento último esse parecido com [o defendido por Marco Arment](http://www.marco.org/2012/05/30/sweep-the-sleaze), criador do Instapaper. E muitos outros, como [o pessoal do Theme Foundry](http://thethemefoundry.com/blog/you-dont-need-sharing-buttons/).

Para quem mantém um site, seja pelo emocional, seja pelas estatísticas, é difícil resistir à tentação de ver os números de compartilhamento crescendo. É um feedback poderoso para o psicológico, parece que alguém de fato leu e gostou do que escrevemos. É mais potente que contadores de visitas, mais imediato e provável que comentários e, importante, _há casos_ onde eles realmente mexem com os números de visitação. Mas fora desses, existe uma queda de braço ferrenha em curso, onde duelam o "parecer desesperado" e o "ver os números crescendo". E tudo isso considerando como certa a ideia de que esses botões estão mesmo sendo usados; além da incerteza de que eles serão úteis, disponibilizá-los ali é comprar o risco de ver o [comportamento de manada](http://pt.wikipedia.org/wiki/Comportamento_de_manada) agir negativamente no seu domínio e um monte de zeros passar a jogar contra. Além de não ajudar, tudo isso ainda acaba com a sua auto-estima se você é desses que ligam para números.

Se o aspecto (e risco) psicológico não for suficiente para convencê-lo, existem [outros argumentos anti-botões](http://www.searchenginejournal.com/too-many-social-media-sharing-buttons-make-your-site-less-social/48240/) tão fortes quanto. Os que mais pesam, para mim, são os pontos do desempenho e da privacidade.

### Lentidão e desrespeito à privacidade

Quem já teve a curiosidade de abrir o código-fonte de uma página que contém botões de compartilhamento e ver como eles operam, deve saber do que estou falando. Há, no mínimo, um JavaScript e um `iframe` que carrega _uma página inteira_ dentro da sua para que o botão funcione.

Recentemente [mexi a fundo no layout deste blog](https://www.facebook.com/rghedin/posts/10151673523207652). A minha intenção inicial era torná-lo responsivo, mas aproveitei o ensejo para submetê-lo a uma dieta. De longe, o corte que teve mais impacto no desempenho foi o dos botões de compartilhamento. Usando a [ferramenta de tempo de carregamento da Pingdom](http://tools.pingdom.com/fpt/), vi o número de requisições cair de quase 60 para cerca de 10, o tamanho do site diminuir em mais de 1 MB e o tempo de carregamento, em cinco segundos. Esse ganho monstruoso em desempenho (um sinal que [o Google considera](http://googlewebmastercentral.blogspot.com.br/2010/04/using-site-speed-in-web-search-ranking.html) e seus leitores, mais ainda) não foi em decorrência apenas dos botões de Facebook e Twitter que mantinha aqui até então. Entretanto, eles eram, de longe, os maiores responsáveis pelo sobrepeso do meu pequeno blog.

O preço que se paga é alto. Não bastasse o impacto negativo no desempenho do site, esses botões ainda operam como cavalos de Troia para suas respectivas redes: todo mundo que chega aqui e vê os botões tem essa visita computada pelo Facebook, pelo Twitter, pelo Pinterest, por todos. Existem extensões que impedem esse comportamento, mas acrescentam uma camada extra para o usuário — acabando com a praticidade, o principal apelo "client-side" dos botões. Outras, impedem o seu carregamento, como [a (excelente) Disconnect](http://gizmodo.uol.com.br/disconnect-2-defende-sua-privacidade/).

Os botões de compartilhamento [flertam com a publicidade](http://www.forbes.com/sites/roberthof/2012/05/10/are-those-little-sharing-buttons-the-future-of-online-advertising/), essa malvada que ainda paga as nossas contas. Chamo de "malvada" mais por [incompetência nossa](http://www.rodrigoghedin.com.br/blog/paywall-crowdfunding-modelo-negocio-web) do que dos anunciantes, mas como já disse em outras oportunidades há muito espaço para desenvolver melhor a publicidade na web. Nessa, incentivar um modelo intrusivo, que viola a privacidade dos usuários e parece não querer sair do lugar em vez de outros inovadores, pode soar meio… hipócrita. Preguiçoso, no mínimo.

### "Eu tiro os botões do meu site se você me prometer que as visitas não cairão"

Desculpe, mas isso eu não posso prometer. O máximo que posso dizer é que estou apostando nessa onda "button-free" e indicar alguns casos onde tal postura não afetou a visitação — pelo contrário, fez com que ela _aumentasse_.

O [Smashing Magazine](http://www.smashingmagazine.com/), popular blog de web design, há tempos removeu os botões. Depois disso, viu a quantidade de visitantes vindos do Facebook [_subir_](http://twitter.com/smashingmag/status/204955763368660992). A mágica? Como as pessoas passaram a compartilhar os links diretamente em suas Linhas do Tempo, onde as interações têm mais visibilidade em vez dos cliques no botão "Curtir", esse efeito foi notado.

Pesquisando por aí você encontra [alguns relatos similares](http://blog.mainstreethost.com/a-hot-button-issue-do-social-sharing-buttons-work), mas nada tão expressivo quanto o exemplo acima — motivo pelo qual, tal qual neste texto que você está lendo, o do Smashing Magazine é sempre lembrado. E, talvez na mesma medida, você também se deparará com [relatos](http://www.niemanlab.org/2012/05/how-important-are-all-those-ugly-tweet-buttons-to-news-sites/) [_opostos_](http://www.currybet.net/cbet_blog/2012/05/give-share-buttons-their-due.php), que dão peso aos botões de compartilhamento. Reichenstein voltou a tratar do assunto em [um follow up do seu post original](http://ia.net/blog/sweep-the-sleaze-reactions/) e, com uma série de métricas, pesquisas e relatos, incluindo esses opostos, chegou à resposta mais óbvia (mas, ainda assim, mais acertada): não é uma questão binária, não dá para sentenciar que botões são ruins ou são bons para todos os casos sem exceção.

Para o meu pequeno blog aqui, acredito que eles sejam dispensáveis. A baixa visitação que ele tem me impede de analisar o que a remoção representará nesses termos. Desculpe! O que fiz foi incluir, no rodapé e de forma bem discreta (muito, até), links crus para compartilhar o conteúdo no Facebook e no Twitter. Eles não pesam e não violam a sua privacidade, mas trazem facilidade. Se funciona ou não? Novamente, o alcance do meu blog não dá margem para esse tipo de análise.

### Por que esse papo agora?

Ler [as justificativas para o redesign do SplatF](http://www.splatf.com/2013/03/splatf-3-welcome/), do Dan Frommer, deu-me o estalo de revisitar esse assunto e expandi-lo. O SplatF ganhou um layout novo, responsivo e muito bonito, mas com um pecado: ele preserva o botão de compartilhamento do Twitter mesmo quando formatado para smartphones.

Por quê?

Se na web a presença dos botões de compartilhamento é uma área cinza, onde o certo e o errado se alternam caso a caso, na palma da mão a questão me parece meio consolidada: eles são inúteis. Seja em um layout exclusivo ou na formatação de um responsivo, botões de compartilhamento em smartphones e tablets deveriam ser abolidos porque a única vantagem que representam, a comodidade, é ultrapassada pela do próprio sistema.

Todo mundo usa Twitter, Facebook, Google+ e Tumblr via apps no celular e no tablet. Raramente fazemos login nas versões web. Não precisa, nunca. O botão de compartilhamento parte da premissa de que você está logado nessas redes sociais, uma premissa perfeitamente válida em um contexto onde a web é o principal canal de interação — no caso, em desktops e notebooks. Se alguém clica em um desses botões a partir do navegador do smartphone, terá que fazer login para, só então, o compartilhamento ser concluído. É uma etapa extra e desnecessária. Você _já está_ logado nesses sites, só não via web. O pote de ouro está nos apps.

Tanto no iOS (com algumas restrições), quanto no Android, o navegador e vários apps de leitura (read it later, agregadores de feeds) compartilham nativamente. No Android a situação é mais cômoda graças ao sistema de compartilhamento ser mais flexível. Se estou lendo um texto no navegador e quero compartilhá-lo, o faço a partir do app do Twitter — vide a imagem abaixo. Essa forma de trabalho integrada, aliás, foi o meu maior elogio ao Android na [análise do Nexus 4](http://www.gizmodo.com.br/review-nexus-4/). Funciona, funciona bem demais e é mais rápido do que usar o botão oficial do Twitter estampado na página.

![Botões de compartilhamento no Android]({{ site.baseurl }}/assets/botoes-compartilhamento.jpg)

Hábitos antigos demoram a morrer e temos (jornalistas de tecnologia) uma inclinação de "dumbficar" usuários leigos. Mas eles são espertos, sabem atualizar o iOS, sabem usar o Dropbox, sabem inclusive compartilhar conteúdo através do sistema. É um movimento ainda tímido mas que, a longo prazo, tem potencial para acabar de vez com os botões de compartilhamento sem prejuízo algum. [Windows 8](http://windows.microsoft.com/pt-br/windows-8/charms#1TC=t1) e [OS X](http://www.apple.com/br/osx/whats-new/#facebook), sistemas desktop onde a web ainda é forte, já flertam meio desajeitados com essa possibilidade. Em breve não precisaremos mais "sujar" nossos sites com botões de redes sociais para garantir algumas visitas vindas de lá.
