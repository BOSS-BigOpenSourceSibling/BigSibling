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

Em um formulário de outro projeto, vi a descrição: Como temos medo de frustrar um iniciante e afastá-lo de contribuir com projetos de código aberto, decidimos adotar esses requisitos mínimos. E achei muito elegante para explicar a necessidade do mínimo. - @emmenezes

- **Você já conseguiu contribuir?**

Essa pergunta é de *Sim* ou *Não* e causa muitas dúvidas na organização, pois não sabemos o que a pessoa quer dizer com isso. A sugestão é mudar o campo para aberto ou a pergunta continuar seguida por um campo aberto para a pessoa especificar qual foi o tipo de contribuição.

- **Você já quis contribuir com algum software livre?**

Essa pergunta causa o mesmo tipo de confusão da anterior. A sugestão é que seja uma pergunta com opções, por exemplo:

- Não, pois não conhecia antes o que é software livre
- Não, pois não sabia que era possível contribuir
- Sim, já quis ou já contribui

- **Estado**

No questionário dessa temporada, é possível escolher o estado que está no modelo "Amazonas- AM". Dessa forma, é muito difícil fazer o filtro de região, pois é preciso colocar estado por estado. Para facilitar na próxima temporada, poderíamos colocar "Amazonas - AM (Norte)", assim poderíamos separar uma cor para cada região, facilitando a visualização.

Além disso, nos encontramos numa situação esquisita: algumas pessoas marcaram que moram no interior do Distrito Federal, enquanto acreditamos que o Distrito tem apenas região central e região periférica. Para resolver isso, é importante colocar uma observação embaixo sobre nosso critério de localização.

- **Novos campos**

Durante as reuniões, foi observado como os contextos pessoais entre as participantes são muito distintos, e talvez pudesse ser interessante ter campos de idade, se a pessoa está transicionando de área/se é a primeira área/se já atua, e talvez um cmapo se a pessoa tem filhos, pois pode priorizar esses outros grupos que teriam menos oportunidades.

- **Adição de vídeo explicativo sobre a BOSS**

Para reafirmar o conceito do projeto, foi sugerido que no formulário de inscrição houvesse um vídeo explicado todos os detalhes do treinamento e tirando as principais dúvidas.

- **Primeira página do formulário com perguntas que confirmem que a pessoa pode participar**

Para dar mais comprometimento e seriedade na inscrição, foi sugerido que a primeira página do formulário fosse exclusiva para perguntas obrigatórias que têm apenas uma resposta, como: você tem disponibilidade de participar das aulas síncronas segundas e quartas, você sabe o básico de programação, você tem disponibilidade durante os três meses do projeto, etc. Com o propósito de desincentivar candidaturas de pessoas que não estão tão interessadas, e assim evitar evasões.

- **Plataforma para formulário e compartilhamento de planilhas**

Ao entrarmos em contato com um possível parceiro, foi justificado que não poderiam compartilhar nosso formulário por este ter sido feito no Google Forms e portanto levantar questões de segurança e privacidade de dados. Isso inicia uma discussão importante sobre as ferramentas que estamos usando hoje em dia e que podem ir contra nosso propósito de usar plataformas de código aberto e seguras. Uma vantagem do Google é a possibilidade de associar os dados do formulário com planilhas e assim podemos compartilhar facilmente entre nós, manusear e criar gráficos. Logo, se desejamos mudar, precisamos encontrar um programa que tenha esses mesmos serviços. Uma possibilidade citada é migrar o máximo de coisas possíveis para o GitHub e, pouco a pouco, deixarmos de usar os serviços do Google.

## Melhoria 02 - Processo de contato com as pessoas selecionadas

A etapa de contato foi muito complicada durante essa temporada então, antes de propôr solução, é importante destacar os vários tipos de dificuldades encontradas:

- Demora no retorno das pessoas solecionadas
- Submissões com dados incorretos, que dificultaram encontrar as pessoas
- Situação em que a pessoa não tinha disponibilidade nos horários
- Tempo muito curto entre seleção e começo, gerando um início com pessoas mentoras sem par
- 1ª e 2ª chamada realizadas após o começo das aulas
- Falta de centralização de informações, ou seja, às vezes alguém entrava em contato ou desistia e a organização demorava a ser notificada

Para tentar solucionar ou, pelo menos, dimiuir essas dificuldades, tivemos algumas ideias:

- **Aumentar o tempo de seleção**

O processo de seleção em si pode ser feito em um dia em grupo, mas aumentando o tempo, temos mais chances de confirmar as pessoas participantes antes do início da Temporada, evitando os casos de pessoas mentoras sem par e os casos de a pessoa já começar atrasada

- **Pedir contatos redundantes**

Um dos motivos da demora foram os contatos incorretos ou incompletos, ou seja, e-mails faltando algum caractere ou usuários de telegram inexistentes. Para evitar isso, seria interessante, pedir para a pessoa digitar duas vezes o e-mail e solicitar também número de telefone (WhatsApp), além de ressaltar a semana de retorno para que quem se inscreveu fique de olho.

- **Outro modelo de seleção**

Uma ideia sugerida por @Andressa e conversada durante uma reunião da mentoria foi selecionar participantes, e colocar no grupo. A partir da interação e acompanhamento das aulas, as pessoas mais engajadas poderiam ter também o processo de mentoria. Isso garante que as pessoas vão ter um retorno rápido do contato, vou conhecer o projeto e querem de fato participar.

Outras ideias nessa linha foram:

- Adicionar uma etapa de entrevista para se aproximar da pessoa inscrita
- Adicionar um campo de "Por que você quer participar?" para garantir que a pessoa sabe o que é, qual o propósito, e se encaixa nos seus objetivos, não preenchendo um formulários apenas por responder etc

- **Diagnóstico das saídas**

É muito importante que seja feita uma coletânea dos motivos de saída para que possamos entender bem o que aconteceu (precisamos chamar 29 pessoas para preencher 15 vagas), sendo que houve casos de desistência, de não resposta e de não retorno ao contato direto, onde a pessoa respondeu o e-mail, mas não mensagens. Alguns dos motivos observados foram: falta de tempo, outra oportunidade que apareceu na mesma época, impossibilidade de participar das atividades síncronas.

## Melhoria 03 - Divulgação das inscrições

Nesta temporada, aumentamos em uma semana as inscrições para podermos divulgar em palestras, mas um problema que a prática de estender prazos traz é o aumento de inscrições. Quanto mais inscrições, mais dados teremos que analisar, e mais trabalho teremos. Amamos quem se inscreve, mas é preciso ter limites mais restritos para lidar com as demandas.

A proposta é preparar antes de qualquer inscrição uma lista de projetos para entrar em contato e firmar parcerias, pois se divulgarmos bem, podemos ter um período de inscrição ainda menor.

## Melhoria 04 - Mapa de Oportunidades

As inscrições ainda não acabaram, mas estamos de coração partido pela quantidade de candidaturas. Temos mais de 100 pessoas inscritas para apenas 15 vagas. Para lidar com a quantidade de "Nãos" que teremos que dizer, poderíamos começar uma campanha para montar um mapa de oportunidades no Brasil para que essas pessoas não fiquem desamparadas.

A ideia é montar um mapa e mostrar os projetos semelhantes à BOSS separados por cidade, estado, região ou até se forem nacionais. As informações disponibilizadas podem ser nome do projeto, link para conhecer mais, e o modelo do programa (mentoria por temporada, curso etc).

Seria interessante ser um projeto colaborativo e que aceite sugestões de qualquer pessoa, mas que tenha alguns critérios mínimos, como inclusão de grupos sub-representados, ser gratuito etc.

## Melhoria 05 - BOSS responde

Com a proposta recente de recomendarmos nossos vídeos para que as pessoas que não forem selecionadas possam acompanhá-los, há uma possibilidade muito grande de haver dúvidas às quais seria bom conseguir responder.

Uma sugestão é aproveitarmos este gancho para lançar desafios de escrita técnica para as pessoas mentoradas, nos quais as convidaríamos a responder a alguma pergunta que se sintam confiantes para falar sobre. Isto poderia ter o formato de post de blog (como acontece com a Outreachy) ou para ser publicado em nosso perfil do Twitter, ou em outra plataforma a definir.

## Melhoria 06 - Revisão de todo conteúdo didático

No formulário de inscrição, recebemos respostas de pessoas autistas que solicitaram conteúdos acessíveis. A partir disso, podemos desenvolver um plano para tornar acessível todo nosso conteúdo. Para isso, é fundamental a participação de pessoas com deficiência para fazerem uma leitura crítica dos nossos conteúdos.

## Sugestão 01 - Talk Like a BOSS

Durante as reuniões de acompanhamento da monitoria, são citadas situações que as participantes têm e poderia ser interessante transformar essas questões que elas trazem para serem temáticas do Talk Like a BOSS, como forma de aproximar essas pessoas dessa parte da iniciativa, e abordar tópicos que não são tão discutidos nas plataformas. Dentro dessa temática, também poderia ser interessante de mesas com pessoas da área de psicologia, pois muitos pontos são trazidos sobre esse assunto (ansiedade na hora de estudar, criação de patamares pessoais super-elevados, dificuldade de se fazer as coisas sozinha, dificuldade de pedir ajuda) .

## Sugestão 02 - Processo de Mentoria

Alguns problemas que Big Sibblings compartilham no grupo já foram solucionados por outras pessoas em momentos anteriores, então talvez fosse interessante ter no repositório uma pasta apenas com recomendações gerais e aprendizados do ciclo para que possamos mais rapidamente resolver as dificuldades. Como exemplo, poderíamos ter um documento que reúne todas as dicas de como fazer um one-on-one, e algumas perguntas com sugestões de resposta (minha little sibling tem dificuldades de fazer coisas sem acompanhamento, eu percebo que a pessoa que mentoro não consegue fazer perguntas mesmo tendo dúvidas, etc).

## Melhorias e sugestões avulsas

Essas questões foram abordadas em reuniões e não foram devidamente catalogadas ou encaixadas nas categorias anteriores de Melhorias ou Sugestões. Até que sejam organizadas, vão ser listadas aqui sem ordem.

- Fazer semanas testes com as pessoas selecionadas para ver o interesse e o engajamento, com o objetivo de evitar casos de sumiço e desinteresse
- Fazer uma palestra ou chamada sobre o projeto para divulgação nas redes sociais, e esclarecer bem a proposta, para evitar casos onde a pessoa entra e nem sabe o que está acontecendo
- Como podemos criar um campo no formulário para identificar uma pessoa interessada? Uma sugestão é ter um campo aberto para a pessoa falar um pouco de si, e assim diagnosticarmos melhor em que momento de carreira a pessoa se encontra e suas condições de vida, e ter um campo para justificar seu interesse em participar do projeto, garantindo que ela compreenda melhor no que está se candidatando
- Trabalhar mais no treinamento das Big Siblings sobre qual o propósito da mentoria. Durante as semanas, houve relatos de diferentes tipos de one-on-one: mais focados no lado profissional, no lado pessoal, em desenvolver os próprios projetos como um pareamento. Todos são usos corretos do one-on-one, mas talvez explanar isso logo no início permita que todas as pessoas tenham novas dimensões do quanto podem explorar nas conversas
- A respeito do modelo de ensino, duas sugestões: há um interessenas atividades simultâneas com a pessoa que apresenta, onde tanto ela quanto quem está assistindo faz as mesmas coisas, e também alguns assuntos técnicos às vezes são abordados muito rapidamente e quem não tem tanta familiariedade com a área pode se sentir confuso.
- A evasão de participantes é um ciclo vicioso, pois desestimula também quem continua nas atividades, além dos outros efeitos negativos
- É preciso diagnosticar o porquê e como resolver a dificuldade de acompanhar o programa na 2ª metade
- Houve mais de um caso onde a pessoa começou a se afastar com o acúmulo de atividades. Penso eu, Emme, se talvez um apoio psicológico não individual poderia servir de suporte básico para lidarmos com isso, talvez uma consultoria sobre como podemos melhorar ou trazer talks e conversas abertas entre a organização e participantes. Em todos os casos, há o cíclico uma ou duas tarefas não feitas que se acumulam com mais, então não há vontade de pedir ajuda em grupos, e a situação pode culminar no afastamento da pessoa sem retorno ao contato de ninguém da organização
- Seria interessante termos um resumo semanal de atividades para colocarmos no grupo das Big Siblings, assim as atualizamos e elas não precisam procurar por essa informação para entender o desenvolvimento de sua Little Sibling
- Pedir redes sociais para formas de contato alternativa
- Pedir autorização para telefonar se preciso (informar que foi selecionada/entrar em contato em caso de sumiço)
- Pedir contato de alguma pessoa de confiança para contato em caso de emergência
- Ter alguma recompensa "física" ao final do treinamento, como uma blusa/brinde/certificado(?)
- Pensar em atividades extras como mentoria no LinkedIn, porque nessa temporada várias pessoas estavam atrás de oportunidade, e podemos conciliar isso com o objetivo do projeto
- Fazer issues no próprio repositório da BOSS para as little darem uma olhada e quem sabe se engajarem

</div>
