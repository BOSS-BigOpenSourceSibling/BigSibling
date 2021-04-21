# Post Mortem BOSS 2021_01

<div align="justify">

Esse documento foi criado com o objetivo de identificar, durante e após a realização da primeira edição da BOSS, pontos de melhoria para edições futuras. Esses pontos serão discutidos em reuniões ao final desse primeiro ciclo, em que possíveis soluções serão levantadas e analisadas.

## Melhoria 01 - Formulário de Inscrição

Em relação à temporada anterior, o formulário recebeu melhoria significativas e muito boas, no entanto, durante o processo de seleção e avaliação, foram percebidos alguns campos que poderiam ser úteis, acabaram perdendo seu valor por conta do modo que foram implantados, além de que poderiam haver mais campos. As sugestões são:

- **Sugestão geral - Alternativa "Prefiro não responder"**

Considerando que nosso projeto é voltado para pessoas de grupos subrepresentados; que os dados pessoais do formulário não são divulgados publicamente, e as pessoas mentoras não têm acesso a tais informações, exceto quando já estão em contato com as pessoas mentoradas selecionadas; e que precisamos do máximo de acurácia para fazer a seleção, já que há mais candidaturas do que vagas, a opção "Prefiro não responder" em respostas que são sensíveis aos nossos critérios de seleção atua contra o que estamos tentando alcançar, já que não nos permite identificar que a pessoa interessada é de fato parte dos grupos que queremos atender ou não. Embora esta opção seja interessante em espaços não seguros ou nos quais uma pessoa de grupo subrepresentado poderia ser excluída por suas características, para a BOSS, estas mesmas são fundamentais para que consigamos de fato atender às nossas metas e propósitos.

- **Cis ou trans**

Para fazer a separação entre pessoas cis e trans, foi preciso verificar cada resposta possível para separar as pessoas trans, entre as respostas possíveis, houve: homem trans, não-binário, genderqueer. Para facilitar essa limpeza, seria interessante um campo obrigatório com apenas as duas opções, e o campo seguinte para a identidade de gênero.

- **Você já estudou ou trabalhou na área de tecnologia?**

É uma pergunta muito importante, mas no lugar de ter as opções *Sim* ou *Nâo*, seria melhor que essa e outras perguntas obrigatórias para participar como *Você tem X horas por semana para se dedicar ao projeto?* ficassem na primeira página com apenas uma opção de seleção, *Sim*, assim não será preciso usar essas questões como filtro e há a possbilidade de inibir pessoas que não podem participar, mas se candidatariam para ver o que acontece. 

Além disso, dois detalhes sobre essa pergunta são importantes:
1. É preciso uma breve descrição de estudar ou trabalhar, no caso, talvez fosse possível tirar trabalhar, pois se a pessoa trabalha só pode ter estudado.É preciso explicar melhor o conceito de estudar para incluir também estudo autodidata, pois às vezes pode ficar sub-entendido de que se trata de estudo formal, quando não é obrigatório.
2. E é obrigatório, pelo menos por enquanto, que a pessoa tenha uma base em programação, pois o programa é curto, apenas 3 meses, e não é possível construir a base e concluir o projeto apenas nesse intervalo.

- **Você já conseguiu contribuir?** 

Essa pergunta é de *Sim* ou *Não* e causa muitas dúvidas na organização, pois não sabemos o que a pessoa quer dizer com isso. A sugestão é mudar o campo para aberto ou a pergunta continuar seguida por um campo aberto para a pessoa especificar qual foi o tipo de contribuição.

- **Você já quis contribuir com algum software livre?**

Essa pergunta causa o mesmo tipo de confusão da anterior. A sugestão é que seja uma pergunta com opções, por exemplo:
* Não, pois não conhecia antes o que é software livre
* Não, pois não sabia que era possível contribuir
* Sim, já quis ou já contribui

- **Estado**

No questionário dessa temporada, é possível escolher o estado que está no modelo "Amazonas- AM". Dessa forma, é muito difícil fazer o filtro de região, pois é preciso colocar estado por estado. Para facilitar na próxima temporada, poderíamos colocar "Amazonas - AM (Norte)", assim poderíamos separar uma cor para cada região, facilitando a visualização.

Além disso, nos encontramos numa situação esquisita: algumas pessoas marcaram que moram no interior do Distrito Federal, enquanto acreditamos que o Distrito tem apenas região central e região periférica. Para resolver isso, é importante colocar uma observação embaixo sobre nosso critério de localização.

- **Plataforma para formulário e compartilhamento de planilhas**

Ao entrarmos em contato com um possível parceiro, foi justificado que não poderiam compartilhar nosso formulário por este ter sido feito no Google Forms e portanto levantar questões de segurança e privacidade de dados. Isso inicia uma discussão importante sobre as ferramentas que estamos usando hoje em dia e que podem ir contra nosso propósito de usar plataformas de código aberto e seguras. Uma vantagem do Google é a possibilidade de associar os dados do formulário com planilhas e assim podemos compartilhar facilmente entre nós, manusear e criar gráficos. Logo, se desejamos mudar, precisamos encontrar um programa que tenha esses mesmos serviços. Uma possibilidade citada é migrar o máximo de coisas possíveis para o GitHub e, pouco a pouco, deixarmos de usar os serviços do Google.

## Melhoria 02 - Divulgação das inscrições

Nesta temporada, aumentamos em uma semana as inscrições para podermos divulgar em palestras, mas um problema que a prática de estender prazos traz é o aumento de inscrições. Quanto mais inscrições, mais dados teremos que analisar, e mais trabalho teremos. Amamos quem se inscreve, mas é preciso ter limites mais restritos para lidar com as demandas.

A proposta é preparar antes de qualquer inscrição uma lista de projetos para entrar em contato e firmar parcerias, pois se divulgarmos bem, podemos ter um período de inscrição ainda menor.

## Melhoria 03 - Mapa de Oportunidades

As inscrições ainda não acabaram, mas estamos de coração partido pela quantidade de candidaturas. Temos mais de 100 pessoas inscritas para apenas 15 vagas. Para lidar com a quantidade de "Nãos" que teremos que dizer, poderíamos começar uma campanha para montar um mapa de oportunidades no Brasil para que essas pessoas não fiquem desamparadas.

A ideia é montar um mapa e mostrar os projetos semelhantes à BOSS separados por cidade, estado, região ou até se forem nacionais. As informações disponibilizadas podem ser nome do projeto, link para conhecer mais, e o modelo do programa (mentoria por temporada, curso etc).

Seria interessante ser um projeto colaborativo e que aceite sugestões de qualquer pessoa, mas que tenha alguns critérios mínimos, como inclusão de grupos sub-representados, ser gratuito etc. 

## Melhoria 04 - BOSS responde

Com a proposta recente de recomendarmos nossos vídeos para que as pessoas que não forem selecionadas possam acompanhá-los, há uma possibilidade muito grande de haver dúvidas às quais seria bom conseguir responder. 

Uma sugestão é aproveitarmos este gancho para lançar desafios de escrita técnica para as pessoas mentoradas, nos quais as convidaríamos a responder a alguma pergunta que se sintam confiantes para falar sobre. Isto poderia ter o formato de post de blog (como acontece com a Outreachy) ou para ser publicado em nosso perfil do Twitter, ou em outra plataforma a definir.

## Melhoria 05 - Revisão de todo conteúdo didático

No formulário de inscrição, recebemos respostas de pessoas autistas que solicitaram conteúdos acessíveis. A partir disso, podemos desenvolver um plano para tornar acessível todo nosso conteúdo. Para isso, é fundamental a participação de pessoas com deficiência para fazerem uma leitura crítica dos nossos conteúdos.


</div>
