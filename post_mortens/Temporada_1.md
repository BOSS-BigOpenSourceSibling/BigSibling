# Post Mortem BOSS 2020_02

<div align="justify">

Esse documento foi criado com o objetivo de identificar, durante e após a realização da primeira edição da BOSS, pontos de melhoria para edições futuras. Esses pontos serão discutidos em reuniões ao final desse primeiro ciclo, em que possíveis soluções serão levantadas e analisadas.

## Melhoria 01 - Plataforma centralizada da BOSS

O período de inscrição dessa primeira rodada da BOSS foi um tanto quanto conturbado, principalmente pela falta de centralização de informações. Muitas mentoradas e possíveis participantes ficaram confusas sobre o que o projeto visa, como se inscrever e a diferença entre as frentes da BOSS. Acabou que as informações foram espalhadas pelas redes sociais, cada uma de uma forma, o que pode causar confusão e inconsistência. Acho esse um ponto importante para o crescimento do projeto.

Sugestão: Durante o período entre o fim desse ciclo e o próximo, criarmos um site em que centralizamos tudo, informações, formulários de inscrição, links das nossas plataformas, etc.

## Melhoria 02 - Formulário de Inscrição

Nosso formulário essa rodada deixou um tanto a desejar, o que acabou levantando algumas problemáticas. Divulgamos que teríamos vagas específicas para pessoas trans, pessoas pretas, mas não nos atentamos a isso no formulário e acabamos tendo que checar no telegram. Acabou que essa rodada ficou sem uma mentorada trans. Importante ressaltar que algumas dessas melhorias seriam muito beneficiadas caso houvesse uma plataforma própria da BOSS. Tendo isso em vista, alguns pontos de melhoria que podem ser aplicados:

- **Nome da Pessoa Participante** 

Realmente precisamos do nome legal da pessoa? O nome é uma questão muito delicada para pessoas trans, principalmente para aquelas que ainda não conseguiram retificar os documentos legais. Tendo em vista que não precisamos dessa informação para nada, seria bom trocar o campo **Nome** para **Como gostaria de ser chamada?**. Isso abriria a possibilidade para essas pessoas colocarem o que quiserem, e também mostra que estamos preocupadas com o conforto das participantes.

- **Identidade de Gênero**

Essa também é uma questão delicada. Nesse caso, sinto que poderiamos nos inspirar no [Outreachy](https://www.outreachy.org/). No formulário de inscrição, existe uma lista extensa de opções para a participante. Também existe um campo **Self Identify** em que a participante pode utilizar um gênero que não está listado.

![Campo no Formulário do Outreachy](../docs/imagens/OutreachyGenderForm.png)

- **Campo de pronomes**

Adicionar um campo referente ao pronome pelo qual a pessoa prefere ser chamada.

- **Campo de etnia**

Como queremos ajudar todas as minorias, um outro ponto importante é a etnia. O Brasil é um país muito diverso, com muitas pessoas de outros países e culturas. Além disso, um grupo muito sub representado e que sofre muito preconceito são os povos indígenas. Acho importante deixarmos claro que queremos acolher essas pessoas e que teremos vagas específicas para elas.

- **Campo de identidade racial**

Outro pecado que sofremos foi divulgar vagas específicas para pessoas que sofrem racismo, mas não nos atentamos a isso no formulário. Precisou que a Bruna Pinos ficasse olhando as fotos no telegram, o que causou muito desconforto e sentimento de **se eu não fizer ninguém vai se atentar a isso**. Por isso, esse é outro ponto muito importante.

Referências importantes para quando formos implementar essa parte: Seguir o [Guia de Implementação do Quesito Raça/Cor/Etnia](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjp3ZLe5bfsAhXwGLkGHUChCYYQFjAEegQIBxAC&url=http%3A%2F%2Fbvsms.saude.gov.br%2Fbvs%2Fpublicacoes%2Fguia_implementacao_raca_cor_etnia.pdf&usg=AOvVaw0Z4dPkk7MT7hZ0r9U3jgmO) e ler essa [thread](https://twitter.com/munihin_/status/1316212880233172992?s=20) para se informar no assunto.

- **Campo de pessoa com deficiências**

Outro ponto importante são as pessoas com deficiências, que também sofrem muito preconceitos e são deixadas de lado na área. Vale discutirmos sobre, mas acho que apenas um campo sim/não basta, para que não deixe alguém desconfortável. Podemos deixar o campo em que a pessoa especifique como opcional.

- **Campo de sugestões maneira de dar conteúdo**

Campo para que as participantes possam colocar como seria uma boa maneira de passar o conteúdo para elas durante a BOSS, por qualquer motivo que seja. Assim, incentivamos pessoas que precisam de uma maneira de tratamento diferente a se sentirem acolhidas. Exemplos: Pessoas com deficiência, pessoas com TDAH, etc. Campo opcional.

- **Campo de Sugestões de como não dar conteúdo**

Assim como o campo acima, porém dessa vez darmos a oportunidade da pessoa expor o que seria terrível se fizéssemos. Também visando acolher mais pessoas que sofrem preconceitos. Campo opcional.

## Melhoria 03 - Data da BOSS

Ao início do projeto, definimos que a BOSS ocorreria seguindo o mesmo calendário da UnB, o que acaba sendo bem próximo do calendário de outras faculdades também. Porém, como grande parte do nosso público alvo como mentoradas acabam sendo pessoas que estão na faculdade, seria essa realmente a melhor data? Durante essas semanas de projeto é perceptível o quanto algumas mentoradas estão tendo dificuldades ao conseguir se manter em dia com as atividades e conteúdos, por estarem ocupadas com faculdade e estágios.

Sugestão: Poderíamos mudar a data da BOSS para acontecer entre Dezembro-Março e Final de Junho - Agosto(Essa data ainda teria overlap com calendário estudantil, mas também pegaria as férias de julho e apenas o inícío do semestre.). Além disso, conversando com a Anna, ela deu a ideia de prepararmos as mentoradas também para tentar engajar em programas como o Gsoc e Outreachy. Isso também solucionaria um de nossas preocupações, que era para onde essas mentoradas poderiam ir e aprimorar seus conhecimentos após a BOSS.

## Melhoria 04 - Milestones para as fases do projeto
Seria interessante que o repositório de cada edição seja organizado previamente para "iniciar os trabalhos". Uma ideia é termos uma área específica para que as participantes possam contribuir e ver os resultados efetivos de suas contribuições. As tarefas da semana que são passadas poderiam vir em formato de issues em milestones específicas. <br>Por exemplo, a parte de contribuição com o bot seria uma milestone e a inserção de utters e intents por parte das participantes seriam issues a serem resolvidas.
Assim, teríamos vários ganhos, como:
- um repositório inicialmente "vazio" que vai evoluindo à medida em que as pessoas colaboram (evolução visual ainda);
- percepção sobre quem tem mais facilidade e quem apresenta maior dificuldade em aspectos determinados;
- exploraremos a ideia do pareamento, pois cada issue pode ser designada uma a dupla definida no dia da apresentação do conteúdo (não é necessária especificação sobre como resolver ou a temática da contribuição, apenas atribuir uma issue para possibilitar que a pessoa efetivamente se sinta finalizando uma tarefa);
- Aprimorar o uso do github e suas funcionalidades, como desenvolvimento em um mesmo branch, contribuição usando co-authored, atribuição de revisores, linkar PR's com issues específicas, marcar uma milestone, fechar issues, etc.
- Aumento do senso de pertencimento na comunidade;
- Ao final do projeto, teremos rastreabilidade de contribuição e um repositório organizadamente incrementado.

## Melhoria 05 - Preparar cronograma semanal
Enviar um email de forma regular e semanal para as participantes informando sobre o cronograma da semana para que o grupo do telegram sirva apenas para interação entre as pessoas e reforço sas informações do email. Desta forma, nada importante será perdido e teremos a certeza de que todas as pessoas terão visto os avisos.

## Melhoria 06 - Criar um momento para incentivar as dúvidas
As participantes apresentaram dificuldades em deixar suas dúvidas públicas no grupo, a maioria das vezes não enviam dúvidas por iniciativa pessoal e algumas vezes não respondem no grupo. Então seria interessante dedicar um dia ou momento aberto para que todas as pessoas compartilhem suas dúvidas e/ou erros que surgiram, corrigidos ou não. Isso pode incentivar a prática de externalizar dúvidas em grupo.

## Melhoria 07 - Otimizar os formulários de acompanhamento
Para esta edição o formulário de acompanhamento foi utilizado da seguinte forma: um formulário por semana para todas as mentoradas, o mesmo para o formulário das mentoras. Porém, isso dificulta o real acompanhamento do progresso de cada pessoa uma vez que é necessário ficar abrindo formulário por formulário para conseguir um comparativo. Então, como melhoria, podemos criar um formulário individual para cada pessoa, de forma que ele seja alimentado toda semana. Assim, será possível abrir o forms de uma determinada pessoa e ter todas as informações dela de forma compilada, além dos gráficos gerados pelo forms que auxiliarão demais na hora de avaliar o desenvolvimento da pessoa ao longo do tempo.

## Melhoria 08 - Expandir Social Media

Notamos nessa temporada da BOSS que nosso conteúdo ajuda não só as little sisters, mas muitas pessoas por ai. Tivemos um caso de uma desenvolvedora que estava aprendendo junto aos nossos vídeos e até fez um dos nossos exercícios. A Talk Like a BOSS também é muito importante, pois fala de assuntos muito importantes e que podem inspirar pessoas em momentos difíceis.

Tendo isso em vista, acho que nosso social media está muito fraco hoje, com pouco engajamento e, consequentemente, com pouco poder para divulgar nossas iniciativas. Acaba que estamos fazendo muitas coisas ao mesmo tempo, e mexer no Twitter (como é meu caso) fica em segundo plano. Sugiro que tenhamos uma pessoa voltada apenas para isso, de maneira que ela tenha estratégias para melhorar nosso Youtube, Twitter e Instagram. Não precisa ser necessariamente alguém que esteja hoje no time, podemos considerar chamar alguém de fora que gostaria de ajudar.

Obs: Levantada por uma little sister.

## Melhoria 09 - Como podemos melhorar e incentivar o engajamento das little sisters?

Notamos nessa temporada que esse é um ponto muito delicado e que afeta muito todas as little sisters. Em especial, é importante lembrar que nossas iniciativas não vão mudar um costume e ensinamento que foi passado para a pessoa em meros 3 meses, mas que será um ponto de partida para que a little sister possa entrar em contato com essas habilidades em um ambiente seguro. É muito importante deixarmos claro que participar das atividades, como a Talk Like a BOSS, é **opcional**.

Dito isso, ainda estamos pecando muito nesse aspecto e faltando com atividades para que as incentivem de maneira leve a desenvolver essas habilidades de convívio. Podemos discutir:
- Atividades;
- Dinâmicas;
- Conteúdos;

O que tem ajudado nessa temporada: jogarmos juntas, pareamentos little sis e big sis, talk like a BOSS.

## Melhoria 10 - Fazer checkpoint com mentoras e mentoradas
Para essa edição tivemos o checkpoint entre todos envolvidos no projeto apenas ao final do projeto. Porém, o checkpoint é de extrema importância para a melhoria contínua dos conteúdos, mentorias e todos processos envolvidos na iniciativa. Então para as edições futuras um checkpoint semanal, ou até quinzenal, seria o ideal para que os pontos de melhoria possam ser identificados rapidamente, e assim ajustados.


</div>
