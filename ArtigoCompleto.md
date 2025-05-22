# Scrum: Uma Explicação Completa

## Sumário
1. [Introdução](#introdução)
2. [História e Origem do Scrum](#história-e-origem-do-scrum)
3. [O que é Scrum?](#o-que-é-scrum)
4. [Princípios e Valores do Scrum](#princípios-e-valores-do-scrum)
5. [Papéis no Scrum](#papéis-no-scrum)
   - [Product Owner](#product-owner)
   - [Scrum Master](#scrum-master)
   - [Time de Desenvolvimento](#time-de-desenvolvimento)
6. [Eventos do Scrum](#eventos-do-scrum)
   - [Sprint](#sprint)
   - [Sprint Planning](#sprint-planning)
   - [Daily Scrum](#daily-scrum)
   - [Sprint Review](#sprint-review)
   - [Sprint Retrospective](#sprint-retrospective)
7. [Artefatos do Scrum](#artefatos-do-scrum)
   - [Product Backlog](#product-backlog)
   - [Sprint Backlog](#sprint-backlog)
   - [Incremento](#incremento)
8. [Implementando o Scrum](#implementando-o-scrum)
9. [Desafios Comuns e Soluções](#desafios-comuns-e-soluções)
10. [Conclusão](#conclusão)
11. [Referências](#referências)

## Introdução

No cenário atual de desenvolvimento de produtos e serviços, a agilidade e a capacidade de adaptação tornaram-se fatores críticos para o sucesso. As organizações buscam constantemente métodos que permitam responder rapidamente às mudanças do mercado, entregar valor de forma contínua e manter a qualidade em seus produtos. Neste contexto, o Scrum emergiu como uma das metodologias ágeis mais populares e eficazes.

Este documento apresenta uma explicação detalhada sobre o Scrum, abordando sua história, conceitos fundamentais, estrutura, papéis, eventos, artefatos e práticas recomendadas. O objetivo é fornecer um entendimento completo sobre como o Scrum funciona e como pode ser aplicado em diferentes contextos organizacionais para maximizar a eficiência e a qualidade das entregas.

Seja você um profissional que está começando a explorar metodologias ágeis ou alguém que busca aprofundar seus conhecimentos sobre o Scrum, este material oferece uma visão abrangente e prática que pode ser aplicada em projetos reais.

## História e Origem do Scrum

O Scrum tem suas raízes em um artigo publicado pela Harvard Business Review em 1986, intitulado "The New New Product Development Game" (O Novo Jogo de Desenvolvimento de Novos Produtos), escrito por Hirotaka Takeuchi e Ikujiro Nonaka. Neste artigo, os autores descreveram uma abordagem holística para o desenvolvimento de produtos, onde equipes pequenas e multifuncionais produziam resultados excepcionais.

A metáfora utilizada pelos autores foi baseada no jogo de Rugby, especificamente na formação chamada "scrum", onde jogadores se agrupam em formação para reiniciar o jogo após uma interrupção. Esta analogia foi escolhida para representar a ideia de equipes trabalhando de forma coesa, com papéis interconectados, em vez do tradicional modelo sequencial ou "de corrida de revezamento".

Em 1993, Jeff Sutherland, juntamente com sua equipe na Easel Corporation, desenvolveu o processo Scrum para desenvolvimento de software, inspirado pelo artigo de Takeuchi e Nonaka. Posteriormente, Ken Schwaber formalizou o processo para a indústria de software no primeiro artigo sobre Scrum, publicado na conferência OOPSLA (Object-Oriented Programming, Systems, Languages & Applications) em 1995.

Em 2001, Sutherland e Schwaber estavam entre os 17 signatários do Manifesto Ágil, um documento que estabeleceu os valores e princípios fundamentais do desenvolvimento ágil de software. O Scrum tornou-se então um dos frameworks ágeis mais adotados globalmente.

Desde sua criação, o Scrum evoluiu através da experiência prática de milhares de projetos em todo o mundo. Em 2010, Sutherland e Schwaber escreveram o primeiro Guia do Scrum, que tem sido atualizado periodicamente para refletir a evolução das melhores práticas.

## O que é Scrum?

O Scrum é um framework leve que ajuda pessoas, times e organizações a gerar valor através de soluções adaptativas para problemas complexos. Em essência, o Scrum é:

- **Um framework, não uma metodologia**: O Scrum não prescreve técnicas específicas para fazer o trabalho, mas oferece uma estrutura dentro da qual várias técnicas e processos podem ser empregados.

- **Baseado no empirismo**: O Scrum é fundamentado na teoria do controle de processo empírico, que afirma que o conhecimento vem da experiência e que as decisões devem ser baseadas no que é conhecido.

- **Iterativo e incremental**: O trabalho é dividido em ciclos curtos e regulares chamados Sprints, permitindo feedback frequente e adaptação contínua.

- **Focado na entrega de valor**: O objetivo principal é entregar produtos de alto valor que atendam às necessidades dos usuários.

O Scrum é especialmente eficaz para projetos complexos onde os requisitos são emergentes ou mudam frequentemente, e onde a inovação, flexibilidade e produtividade são cruciais. Embora tenha sido inicialmente desenvolvido para gerenciamento de projetos de software, o Scrum tem sido aplicado com sucesso em diversos setores e tipos de projetos.

## Princípios e Valores do Scrum

O Scrum é sustentado por valores fundamentais que orientam as interações, comportamentos e decisões da equipe:

### Valores do Scrum

1. **Compromisso**: Os membros da equipe se comprometem pessoalmente com o alcance dos objetivos da equipe Scrum.

2. **Coragem**: Os membros da equipe têm coragem para fazer a coisa certa e trabalhar em problemas difíceis.

3. **Foco**: Todos focam no trabalho da Sprint e nos objetivos da equipe Scrum.

4. **Abertura**: A equipe e as partes interessadas concordam em ser abertas sobre todo o trabalho e os desafios de sua execução.

5. **Respeito**: Os membros da equipe respeitam uns aos outros como pessoas capazes e independentes.

### Pilares do Scrum

O Scrum é baseado em três pilares fundamentais que sustentam a implementação do controle de processo empírico:

1. **Transparência**: Aspectos significativos do processo devem ser visíveis aos responsáveis pelos resultados. A transparência requer que esses aspectos sejam definidos por um padrão comum para que os observadores compartilhem um entendimento comum do que está sendo visto.

2. **Inspeção**: Os usuários do Scrum devem inspecionar frequentemente os artefatos e o progresso em direção a um objetivo para detectar variações indesejáveis. A inspeção não deve ser tão frequente que atrapalhe o trabalho.

3. **Adaptação**: Se um inspetor determina que um ou mais aspectos de um processo desviaram-se dos limites aceitáveis, e que o produto resultante será inaceitável, o processo ou o material sendo processado deve ser ajustado. O ajuste deve ser feito o mais rápido possível para minimizar desvios adicionais.

## Papéis no Scrum

O Scrum define três papéis principais que formam a Equipe Scrum. Cada papel tem responsabilidades específicas e trabalha em colaboração para alcançar os objetivos do projeto.

### Product Owner

O Product Owner (PO) é o responsável por maximizar o valor do produto resultante do trabalho da Equipe de Desenvolvimento. É a única pessoa responsável por gerenciar o Product Backlog, o que inclui:

- Expressar claramente os itens do Product Backlog
- Ordenar os itens do Product Backlog para alcançar melhor as metas e missões
- Garantir o valor do trabalho realizado pela Equipe de Desenvolvimento
- Garantir que o Product Backlog seja visível, transparente e claro para todos
- Garantir que a Equipe de Desenvolvimento entenda os itens do Product Backlog no nível necessário

O Product Owner é uma pessoa, não um comitê. Ele pode representar os desejos de um comitê no Product Backlog, mas aqueles que desejam alterar a prioridade de um item devem convencer o Product Owner.

Para que o Product Owner tenha sucesso, toda a organização deve respeitar suas decisões. Estas decisões são visíveis no conteúdo e na priorização do Product Backlog. Ninguém pode forçar a Equipe de Desenvolvimento a trabalhar a partir de um conjunto diferente de requisitos.

### Scrum Master

O Scrum Master é responsável por promover e apoiar o Scrum como definido no Guia do Scrum. Os Scrum Masters fazem isso ajudando todos a entender a teoria, práticas, regras e valores do Scrum.

O Scrum Master é um líder servidor para a Equipe Scrum. Ele ajuda aqueles que estão fora da Equipe Scrum a entender quais de suas interações com a Equipe Scrum são úteis e quais não são. O Scrum Master ajuda todos a mudar essas interações para maximizar o valor criado pela Equipe Scrum.

#### Serviços do Scrum Master ao Product Owner:
- Garantir que objetivos, escopo e domínio do produto sejam entendidos por todos na Equipe Scrum
- Encontrar técnicas para o gerenciamento efetivo do Product Backlog
- Ajudar a Equipe Scrum a entender a necessidade de itens do Product Backlog claros e concisos
- Entender o planejamento do produto em um ambiente empírico
- Garantir que o Product Owner saiba como organizar o Product Backlog para maximizar valor

#### Serviços do Scrum Master à Equipe de Desenvolvimento:
- Treinar a Equipe de Desenvolvimento em autogerenciamento e interdisciplinaridade
- Ajudar a Equipe de Desenvolvimento a criar produtos de alto valor
- Remover impedimentos ao progresso da Equipe de Desenvolvimento
- Facilitar eventos Scrum conforme solicitado ou necessário
- Treinar a Equipe de Desenvolvimento em ambientes organizacionais nos quais o Scrum não é totalmente adotado e compreendido

#### Serviços do Scrum Master à Organização:
- Liderar e treinar a organização na adoção do Scrum
- Planejar implementações Scrum dentro da organização
- Ajudar funcionários e partes interessadas a entender e aplicar o Scrum
- Causar mudanças que aumentem a produtividade da Equipe Scrum
- Trabalhar com outros Scrum Masters para aumentar a eficácia da aplicação do Scrum na organização

### Time de Desenvolvimento

A Equipe de Desenvolvimento consiste em profissionais que realizam o trabalho de entregar um incremento potencialmente utilizável do produto ao final de cada Sprint. Somente membros da Equipe de Desenvolvimento criam o incremento.

As Equipes de Desenvolvimento são estruturadas e autorizadas pela organização para organizar e gerenciar seu próprio trabalho. A sinergia resultante otimiza a eficiência e eficácia da Equipe de Desenvolvimento como um todo.

As Equipes de Desenvolvimento têm as seguintes características:
- São auto-organizadas. Ninguém (nem mesmo o Scrum Master) diz à Equipe de Desenvolvimento como transformar o Product Backlog em incrementos de funcionalidade potencialmente utilizáveis
- São multifuncionais, com todas as habilidades necessárias para criar um incremento do produto
- O Scrum não reconhece títulos para os membros da Equipe de Desenvolvimento que não seja o de Desenvolvedor, independentemente do trabalho que está sendo realizado pela pessoa
- O Scrum não reconhece sub-equipes na Equipe de Desenvolvimento, independentemente dos domínios que precisam ser abordados, como teste, arquitetura, operações ou análise de negócios
- Membros individuais podem ter habilidades especializadas e áreas de foco, mas a responsabilidade pertence à Equipe de Desenvolvimento como um todo

O tamanho ideal da Equipe de Desenvolvimento é pequeno o suficiente para permanecer ágil e grande o suficiente para completar um trabalho significativo dentro de uma Sprint. Menos de três membros na Equipe de Desenvolvimento diminui a interação e resulta em ganhos de produtividade menores. Equipes de Desenvolvimento com mais de nove membros exigem muita coordenação. Equipes grandes geram muita complexidade para um processo empírico gerenciar. O Product Owner e o Scrum Master não são contados no número de membros da Equipe de Desenvolvimento, a menos que também estejam executando o trabalho do Sprint Backlog.

## Eventos do Scrum

O Scrum prescreve cinco eventos formais para inspeção e adaptação. Esses eventos são projetados para criar regularidade e minimizar a necessidade de reuniões não definidas no Scrum. Todos os eventos são time-boxed, ou seja, têm uma duração máxima. Uma vez que uma Sprint começa, sua duração é fixa e não pode ser reduzida ou estendida.

### Sprint

O coração do Scrum é a Sprint, um time-box de um mês ou menos durante o qual um incremento de produto "Pronto", utilizável e potencialmente liberável é criado. As Sprints têm durações consistentes ao longo de um esforço de desenvolvimento. Uma nova Sprint começa imediatamente após a conclusão da Sprint anterior.

As Sprints contêm e consistem no Sprint Planning, Daily Scrums, o trabalho de desenvolvimento, a Sprint Review e a Sprint Retrospective.

Durante a Sprint:
- Não são feitas mudanças que possam colocar em perigo o objetivo da Sprint
- As metas de qualidade não diminuem
- O escopo pode ser clarificado e renegociado entre o Product Owner e a Equipe de Desenvolvimento conforme mais é aprendido

Cada Sprint pode ser considerada um projeto com horizonte não maior que um mês. Como projetos, as Sprints são usadas para realizar algo. Cada Sprint tem uma definição do que deve ser construído, um design e um plano flexível que guiará a construção, o trabalho e o produto resultante.

As Sprints são limitadas a um mês de calendário. Quando o horizonte de uma Sprint é muito longo, a definição do que está sendo construído pode mudar, a complexidade pode aumentar e o risco pode aumentar. As Sprints permitem previsibilidade, garantindo a inspeção e adaptação do progresso em direção a uma meta pelo menos a cada mês de calendário.

Uma Sprint pode ser cancelada antes que o time-box da Sprint termine. Somente o Product Owner tem a autoridade para cancelar a Sprint, embora ele possa fazê-lo sob influência das partes interessadas, da Equipe de Desenvolvimento ou do Scrum Master. Uma Sprint seria cancelada se o objetivo da Sprint se tornasse obsoleto. Isso pode ocorrer se a empresa mudar de direção ou se as condições do mercado ou da tecnologia mudarem.

### Sprint Planning

O trabalho a ser realizado na Sprint é planejado no Sprint Planning. Este plano é criado com o trabalho colaborativo de toda a Equipe Scrum.

O Sprint Planning é time-boxed para um máximo de oito horas para uma Sprint de um mês. Para Sprints mais curtas, o evento geralmente é mais curto. O Scrum Master garante que o evento ocorra e que os participantes entendam seu propósito. O Scrum Master ensina a Equipe Scrum a mantê-lo dentro do time-box.

O Sprint Planning responde às seguintes perguntas:
- O que pode ser entregue no Incremento resultante da próxima Sprint?
- Como o trabalho necessário para entregar o Incremento será realizado?

#### Tópico Um: O que pode ser feito nesta Sprint?

A Equipe de Desenvolvimento trabalha para prever a funcionalidade que será desenvolvida durante a Sprint. O Product Owner discute o objetivo que a Sprint deve alcançar e os itens do Product Backlog que, se completados na Sprint, atingirão o objetivo da Sprint. A Equipe Scrum inteira colabora sobre o entendimento do trabalho da Sprint.

A entrada para esta reunião é o Product Backlog, o último Incremento do produto, a capacidade projetada da Equipe de Desenvolvimento durante a Sprint e o desempenho passado da Equipe de Desenvolvimento. O número de itens selecionados do Product Backlog para a Sprint é de responsabilidade exclusiva da Equipe de Desenvolvimento. Somente a Equipe de Desenvolvimento pode avaliar o que pode realizar durante a próxima Sprint.

Durante o Sprint Planning, a Equipe Scrum também elabora um Objetivo da Sprint. O Objetivo da Sprint é uma meta que será atingida dentro da Sprint através da implementação do Product Backlog, e fornece orientação para a Equipe de Desenvolvimento sobre por que ela está construindo o Incremento.

#### Tópico Dois: Como o trabalho escolhido será realizado?

Depois de definir o objetivo da Sprint e selecionar os itens do Product Backlog para a Sprint, a Equipe de Desenvolvimento decide como construirá essa funcionalidade em um Incremento de produto "Pronto" durante a Sprint. Os itens do Product Backlog selecionados para esta Sprint, mais o plano para entregá-los, é chamado de Sprint Backlog.

A Equipe de Desenvolvimento geralmente começa projetando o sistema e o trabalho necessário para converter o Product Backlog em um Incremento de produto funcional. O trabalho pode ser de tamanho ou esforço estimado variável. No entanto, trabalho suficiente é planejado durante o Sprint Planning para que a Equipe de Desenvolvimento possa prever o que acredita que pode ser feito na próxima Sprint. O trabalho planejado pela Equipe de Desenvolvimento para os primeiros dias da Sprint é decomposto até o final desta reunião, muitas vezes em unidades de um dia ou menos. A Equipe de Desenvolvimento se auto-organiza para assumir o trabalho no Sprint Backlog, tanto durante o Sprint Planning quanto conforme necessário durante a Sprint.

O Product Owner pode ajudar a esclarecer os itens do Product Backlog selecionados e fazer concessões. Se a Equipe de Desenvolvimento determinar que tem muito ou pouco trabalho, ela pode renegociar os itens do Product Backlog selecionados com o Product Owner. A Equipe de Desenvolvimento também pode convidar outras pessoas para participar, a fim de fornecer conselhos técnicos ou de domínio.

Ao final do Sprint Planning, a Equipe de Desenvolvimento deve ser capaz de explicar ao Product Owner e ao Scrum Master como pretende trabalhar como uma equipe auto-organizada para atingir o Objetivo da Sprint e criar o Incremento previsto.

### Daily Scrum

O Daily Scrum é um evento de 15 minutos para a Equipe de Desenvolvimento. O Daily Scrum é realizado todos os dias da Sprint. Nele, a Equipe de Desenvolvimento planeja o trabalho para as próximas 24 horas. Isso otimiza a colaboração e o desempenho da equipe, inspecionando o trabalho desde o último Daily Scrum e prevendo o trabalho que poderia ser feito antes do próximo. O Daily Scrum é realizado no mesmo horário e local todos os dias para reduzir a complexidade.

A Equipe de Desenvolvimento usa o Daily Scrum para inspecionar o progresso em direção ao Objetivo da Sprint e a tendência de progresso para completar o trabalho no Sprint Backlog. O Daily Scrum otimiza a probabilidade de a Equipe de Desenvolvimento atingir o Objetivo da Sprint. Todos os dias, a Equipe de Desenvolvimento deve entender como pretende trabalhar em conjunto como uma equipe auto-organizada para atingir o Objetivo da Sprint e criar o Incremento esperado até o final da Sprint.

A estrutura da reunião é definida pela Equipe de Desenvolvimento e pode ser conduzida de diferentes maneiras, desde que se concentre no progresso em direção ao Objetivo da Sprint. Algumas Equipes de Desenvolvimento usarão perguntas, outras serão mais baseadas em discussões. Aqui está um exemplo do que pode ser usado:

- O que eu fiz ontem que ajudou a Equipe de Desenvolvimento a atingir o Objetivo da Sprint?
- O que eu farei hoje para ajudar a Equipe de Desenvolvimento a atingir o Objetivo da Sprint?
- Vejo algum impedimento que impeça a mim ou a Equipe de Desenvolvimento de atingir o Objetivo da Sprint?

O Scrum Master garante que a Equipe de Desenvolvimento tenha a reunião, mas a Equipe de Desenvolvimento é responsável por conduzir o Daily Scrum. O Scrum Master ensina a Equipe de Desenvolvimento a manter o Daily Scrum dentro do time-box de 15 minutos.

O Daily Scrum é uma reunião interna da Equipe de Desenvolvimento. Se outros estiverem presentes, o Scrum Master garante que eles não interrompam a reunião.

Os Daily Scrums melhoram a comunicação, eliminam outras reuniões, identificam impedimentos para remoção, destacam e promovem a rápida tomada de decisões e melhoram o nível de conhecimento da Equipe de Desenvolvimento. Este é um evento crucial de inspeção e adaptação.

### Sprint Review

Uma Sprint Review é realizada no final da Sprint para inspecionar o Incremento e adaptar o Product Backlog, se necessário. Durante a Sprint Review, a Equipe Scrum e as partes interessadas colaboram sobre o que foi feito na Sprint. Com base nisso e em quaisquer mudanças no Product Backlog durante a Sprint, os participantes colaboram nas próximas coisas que poderiam ser feitas para otimizar o valor. Esta é uma reunião informal, não uma reunião de status, e a apresentação do Incremento destina-se a obter feedback e fomentar a colaboração.

Esta é uma reunião time-boxed de no máximo quatro horas para uma Sprint de um mês. Para Sprints mais curtas, o evento geralmente é mais curto. O Scrum Master garante que o evento ocorra e que os participantes entendam seu propósito. O Scrum Master ensina todos a mantê-lo dentro do time-box.

A Sprint Review inclui os seguintes elementos:
- Os participantes incluem a Equipe Scrum e principais partes interessadas convidadas pelo Product Owner
- O Product Owner explica quais itens do Product Backlog foram "Prontos" e quais não foram
- A Equipe de Desenvolvimento discute o que foi bem durante a Sprint, quais problemas encontraram e como esses problemas foram resolvidos
- A Equipe de Desenvolvimento demonstra o trabalho que está "Pronto" e responde a perguntas sobre o Incremento
- O Product Owner discute o Product Backlog como está. Ele projeta prováveis datas de conclusão com base no progresso até a data (se necessário)
- O grupo todo colabora sobre o que fazer a seguir, de modo que a Sprint Review forneça informações valiosas para as próximas reuniões de Sprint Planning
- Revisão de como o mercado ou o uso potencial do produto pode ter mudado o que é mais valioso a fazer a seguir
- Revisão da linha do tempo, orçamento, capacidades potenciais e mercado para a próxima versão prevista do produto

O resultado da Sprint Review é um Product Backlog revisado que define os prováveis itens do Product Backlog para a próxima Sprint. O Product Backlog também pode ser ajustado em geral para atender a novas oportunidades.

### Sprint Retrospective

A Sprint Retrospective é uma oportunidade para a Equipe Scrum inspecionar a si mesma e criar um plano de melhorias a serem implementadas durante a próxima Sprint.

A Sprint Retrospective ocorre após a Sprint Review e antes da próxima Sprint Planning. Esta é uma reunião time-boxed de no máximo três horas para uma Sprint de um mês. Para Sprints mais curtas, o evento geralmente é mais curto. O Scrum Master garante que o evento ocorra e que os participantes entendam seu propósito. O Scrum Master ensina todos a mantê-lo dentro do time-box. O Scrum Master participa como um membro da equipe na reunião, com responsabilidade pelo framework Scrum.

O propósito da Sprint Retrospective é:
- Inspecionar como a última Sprint foi em relação a pessoas, relacionamentos, processos e ferramentas
- Identificar e ordenar os principais itens que foram bem e as potenciais melhorias
- Criar um plano para implementar melhorias na forma como a Equipe Scrum faz seu trabalho

O Scrum Master encoraja a Equipe Scrum a melhorar, dentro do framework do processo Scrum, seu processo de desenvolvimento e práticas para torná-los mais eficazes e agradáveis para a próxima Sprint. Durante cada Sprint Retrospective, a Equipe Scrum planeja maneiras de aumentar a qualidade do produto, melhorando o processo de trabalho ou adaptando a definição de "Pronto", se apropriado e não em conflito com os padrões do produto ou da organização.

Ao final da Sprint Retrospective, a Equipe Scrum deve ter identificado melhorias que implementará na próxima Sprint. A implementação dessas melhorias na próxima Sprint é a adaptação à inspeção da própria Equipe Scrum. Embora melhorias possam ser implementadas a qualquer momento, a Sprint Retrospective fornece uma oportunidade formal focada na inspeção e adaptação.

## Artefatos do Scrum

Os artefatos do Scrum representam trabalho ou valor para fornecer transparência e oportunidades para inspeção e adaptação. Os artefatos definidos pelo Scrum são especificamente projetados para maximizar a transparência das informações-chave, necessárias para garantir que as Equipes Scrum tenham sucesso na entrega de um Incremento "Pronto".

### Product Backlog

O Product Backlog é uma lista ordenada de tudo que é conhecido ser necessário no produto. É a única fonte de requisitos para quaisquer mudanças a serem feitas no produto. O Product Owner é responsável pelo Product Backlog, incluindo seu conteúdo, disponibilidade e ordenação.

Um Product Backlog nunca está completo. O desenvolvimento mais inicial dele apenas estabelece os requisitos inicialmente conhecidos e melhor entendidos. O Product Backlog evolui à medida que o produto e o ambiente em que ele será usado evoluem. O Product Backlog é dinâmico; ele muda constantemente para identificar o que o produto precisa para ser apropriado, competitivo e útil. Se um produto existe, seu Product Backlog também existe.

O Product Backlog lista todas as características, funções, requisitos, melhorias e correções que constituem as mudanças a serem feitas no produto em versões futuras. Os itens do Product Backlog têm os atributos de descrição, ordem, estimativa e valor. Os itens do Product Backlog muitas vezes incluem descrições de teste que provarão sua completude quando "Pronto".

À medida que um produto é usado e ganha valor, e o mercado fornece feedback, o Product Backlog torna-se uma lista maior e mais exaustiva. Os requisitos nunca param de mudar, então um Product Backlog é um artefato vivo. Mudanças nos requisitos de negócios, condições de mercado ou tecnologia podem causar mudanças no Product Backlog.

Múltiplas Equipes Scrum frequentemente trabalham juntas no mesmo produto. Um Product Backlog é usado para descrever o trabalho futuro no produto. Um atributo de Product Backlog que agrupa itens pode então ser empregado.

O refinamento do Product Backlog é o ato de adicionar detalhes, estimativas e ordem aos itens no Product Backlog. Este é um processo contínuo, em que o Product Owner e a Equipe de Desenvolvimento colaboram sobre os detalhes dos itens do Product Backlog. Durante o refinamento do Product Backlog, os itens são revisados e revisados. A Equipe Scrum decide como e quando o refinamento é feito. O refinamento geralmente consome não mais que 10% da capacidade da Equipe de Desenvolvimento. No entanto, os itens do Product Backlog podem ser atualizados a qualquer momento pelo Product Owner ou a critério do Product Owner.

Itens de Product Backlog de ordem mais alta são geralmente mais claros e mais detalhados do que os de ordem mais baixa. Estimativas mais precisas são feitas com base na maior clareza e maior detalhe; quanto menor a ordem, menos detalhes. Os itens do Product Backlog que ocuparão a Equipe de Desenvolvimento para a próxima Sprint são refinados para que qualquer item possa ser razoavelmente "Pronto" dentro do time-box da Sprint. Os itens do Product Backlog que podem ser "Prontos" pela Equipe de Desenvolvimento dentro de uma Sprint são considerados "Preparados" para seleção em uma reunião de Sprint Planning. Os itens do Product Backlog geralmente adquirem este grau de transparência através das atividades de refinamento descritas acima.

A Equipe de Desenvolvimento é responsável por todas as estimativas. O Product Owner pode influenciar a Equipe de Desenvolvimento, ajudando-a a entender e selecionar trade-offs, mas as pessoas que realizarão o trabalho fazem a estimativa final.

### Sprint Backlog

O Sprint Backlog é o conjunto de itens do Product Backlog selecionados para a Sprint, mais um plano para entregar o Incremento do produto e atingir o Objetivo da Sprint. O Sprint Backlog é uma previsão da Equipe de Desenvolvimento sobre qual funcionalidade estará no próximo Incremento e o trabalho necessário para entregar essa funcionalidade em um Incremento "Pronto".

O Sprint Backlog torna visível todo o trabalho que a Equipe de Desenvolvimento identifica como necessário para atingir o Objetivo da Sprint. Para garantir a melhoria contínua, ele inclui pelo menos uma melhoria de processo de alta prioridade identificada na Retrospectiva anterior.

O Sprint Backlog é um plano com detalhes suficientes para que as mudanças no progresso possam ser entendidas no Daily Scrum. A Equipe de Desenvolvimento modifica o Sprint Backlog ao longo da Sprint, e o Sprint Backlog emerge durante a Sprint. Esta emergência ocorre à medida que a Equipe de Desenvolvimento trabalha através do plano e aprende mais sobre o trabalho necessário para atingir o Objetivo da Sprint.

À medida que novo trabalho é necessário, a Equipe de Desenvolvimento o adiciona ao Sprint Backlog. À medida que o trabalho é executado ou completado, o trabalho restante estimado é atualizado. Quando elementos do plano são considerados desnecessários, eles são removidos. Somente a Equipe de Desenvolvimento pode mudar seu Sprint Backlog durante uma Sprint. O Sprint Backlog é uma imagem altamente visível, em tempo real, do trabalho que a Equipe de Desenvolvimento planeja realizar durante a Sprint, e pertence exclusivamente à Equipe de Desenvolvimento.

#### Monitoramento do Progresso da Sprint

A qualquer momento em uma Sprint, o trabalho total restante nos itens do Sprint Backlog pode ser somado. A Equipe de Desenvolvimento acompanha este trabalho total restante pelo menos para cada Daily Scrum para projetar a probabilidade de atingir o Objetivo da Sprint. Ao acompanhar o trabalho restante ao longo da Sprint, a Equipe de Desenvolvimento pode gerenciar seu progresso.

### Incremento

O Incremento é a soma de todos os itens do Product Backlog completados durante uma Sprint e o valor dos incrementos de todas as Sprints anteriores. Ao final de uma Sprint, o novo Incremento deve estar "Pronto", o que significa que deve estar na condição utilizável e atender à definição de "Pronto" da Equipe Scrum. Um incremento é um corpo de trabalho inspecionável e concluído que apoia o empirismo no final da Sprint. O incremento é um passo em direção a uma visão ou meta. O incremento deve estar na condição utilizável independentemente de o Product Owner decidir liberá-lo realmente ou não.

## Implementando o Scrum

Implementar o Scrum em uma organização requer planejamento, comprometimento e uma mudança cultural. Aqui estão algumas etapas para uma implementação bem-sucedida:

1. **Educação e Treinamento**: Garanta que todos os envolvidos compreendam os princípios, valores e práticas do Scrum. Considere treinamentos formais para papéis-chave como Scrum Masters e Product Owners.

2. **Comece Pequeno**: Inicie com um projeto piloto ou uma equipe pequena antes de expandir para toda a organização. Isso permite aprender e adaptar com menos riscos.

3. **Defina Claramente os Papéis**: Certifique-se de que todos entendam suas responsabilidades dentro do framework Scrum. Evite sobreposições ou lacunas nas responsabilidades.

4. **Estabeleça uma Definição de "Pronto"**: Crie uma definição clara do que significa um item estar "Pronto". Isso garante qualidade e entendimento compartilhado.

5. **Crie um Ambiente Propício**: Forneça o espaço físico e as ferramentas necessárias para que as equipes Scrum trabalhem efetivamente. Isso pode incluir quadros visuais, ferramentas de gerenciamento de projetos ágeis e espaços para reuniões diárias.

6. **Meça e Adapte**: Utilize métricas para avaliar o progresso e a eficácia da implementação do Scrum. Esteja aberto a fazer ajustes com base no feedback e nos resultados.

7. **Cultive a Cultura Ágil**: Promova valores como transparência, inspeção, adaptação, respeito e coragem em toda a organização.

8. **Obtenha Apoio da Liderança**: O suporte da alta administração é crucial para o sucesso da implementação do Scrum. Garanta que os líderes compreendam e apoiem a mudança.

## Desafios Comuns e Soluções

Implementar o Scrum pode apresentar vários desafios. Aqui estão alguns dos mais comuns e possíveis soluções:

### Resistência à Mudança
**Desafio**: Membros da equipe ou stakeholders resistem à adoção do Scrum.
**Solução**: Eduque sobre os benefícios, envolva as pessoas no processo de mudança, demonstre sucessos iniciais e forneça treinamento adequado.

### Falta de Comprometimento da Liderança
**Desafio**: A alta administração não apoia totalmente a implementação do Scrum.
**Solução**: Demonstre o valor do Scrum através de métricas e histórias de sucesso, eduque os líderes sobre os benefícios e envolva-os no processo.

### Dificuldade em Manter o Time-box
**Desafio**: Eventos Scrum frequentemente ultrapassam o tempo alocado.
**Solução**: Use timers visíveis, tenha um facilitador forte, prepare-se adequadamente para as reuniões e pratique a disciplina de respeitar os limites de tempo.

### Product Backlog Mal Gerenciado
**Desafio**: O Product Backlog está desorganizado, não priorizado ou muito detalhado/vago.
**Solução**: Realize sessões regulares de refinamento do backlog, treine o Product Owner em técnicas eficazes de gerenciamento de backlog e use critérios claros para priorização.

### Equipes Não Auto-organizadas
**Desafio**: A equipe espera que alguém lhes diga o que fazer ou como fazer.
**Solução**: Treine a equipe em auto-organização, remova barreiras à autonomia, forneça coaching e dê tempo para a equipe amadurecer.

### Definição de "Pronto" Inadequada
**Desafio**: Não há clareza sobre quando um item está realmente completo.
**Solução**: Colaborativamente crie uma definição clara de "Pronto", revise-a regularmente e garanta que todos a compreendam e sigam.

### Falta de Transparência
**Desafio**: Informações importantes não são compartilhadas abertamente.
**Solução**: Use radiadores de informação (como quadros Scrum físicos ou digitais), promova uma cultura de honestidade e abertura, e celebre quando problemas são identificados precocemente.

### Scrum Mecânico
**Desafio**: A equipe segue as práticas do Scrum mecanicamente, sem entender o propósito.
**Solução**: Eduque sobre os princípios por trás das práticas, encoraje a experimentação e adaptação, e foque nos resultados em vez de apenas seguir o processo.

## Conclusão

O Scrum é um framework poderoso que tem transformado a maneira como as organizações abordam projetos complexos. Sua ênfase na entrega iterativa e incremental de valor, combinada com mecanismos integrados para inspeção e adaptação, permite que as equipes respondam eficazmente às mudanças e entreguem produtos que realmente atendam às necessidades dos usuários.

Os princípios e valores do Scrum - transparência, inspeção, adaptação, compromisso, coragem, foco, abertura e respeito - formam a base para uma cultura organizacional que valoriza a colaboração, a melhoria contínua e a entrega de valor.

Embora o Scrum tenha suas raízes no desenvolvimento de software, sua aplicabilidade se estende a qualquer projeto complexo onde a incerteza é alta e a adaptabilidade é crucial. Desde marketing e recursos humanos até educação e saúde, o Scrum tem sido aplicado com sucesso em diversos setores.

Implementar o Scrum não é apenas adotar um conjunto de práticas; é abraçar uma nova maneira de pensar e trabalhar. Requer comprometimento, paciência e uma disposição para aprender e adaptar continuamente. Os desafios são reais, mas os benefícios - maior satisfação do cliente, melhor qualidade do produto, maior engajamento da equipe e maior agilidade organizacional - fazem do Scrum uma abordagem valiosa para o trabalho complexo no mundo em rápida evolução de hoje.

## Referências

1. Schwaber, K., & Sutherland, J. (2020). The Scrum Guide: The Definitive Guide to Scrum: The Rules of the Game.

2. Takeuchi, H., & Nonaka, I. (1986). The New New Product Development Game. Harvard Business Review.

3. Sutherland, J. (2014). Scrum: The Art of Doing Twice the Work in Half the Time. Crown Business.

4. Cohn, M. (2009). Succeeding with Agile: Software Development Using Scrum. Addison-Wesley Professional.

5. Rubin, K. S. (2012). Essential Scrum: A Practical Guide to the Most Popular Agile Process. Addison-Wesley Professional.

6. FIA Business School. (2024). O que é Scrum, como aplicar a metodologia e exemplos. https://fia.com.br/blog/scrum/

7. Voitto. (2020). Qual a origem do Scrum? Entenda o surgimento desse framework! https://voitto.com.br/blog/artigo/surgimento-do-scrum

8. Busca Ágil. (2021). Papéis, Eventos e Artefatos do Scrum. https://www.buscaagil.com.br/post/pap%C3%A9is-eventos-e-artefatos-do-scrum

9. Miro. (2023). Artefatos do Scrum: o que são? Pra que servem? Veja exemplos. https://miro.com/pt/agile/o-que-sao-artefatos-no-scrum/