# Brainstorming

## Introdução

<div align="justify">
O brainstorming foi a técnica principal escolhida para a elicitação dos requisitos do projeto de corretagem de imóveis, onde anunciantes e interessados podem interagir, oferecendo e buscando imóveis para venda ou aluguel. Essa técnica permite que um grupo de pessoas gere ideias de forma criativa e colaborativa para identificar funcionalidades e requisitos para a plataforma.
</div>

## Objetivo

<div align="justify">
O principal objetivo do brainstorming foi gerar o maior número de ideias para entender e definir os requisitos funcionais e não funcionais do sistema. Todas as ideias foram consideradas, e após a fase de geração, foram registradas para uma análise detalhada e desenvolvimento do projeto. Esse processo promove a criatividade e a participação ativa dos envolvidos, fornecendo uma base para o desenvolvimento de uma plataforma eficiente.
</div>

## Metodologia

<div align="justify">
Para realizar o brainstorming, utilizamos o Teams como ferramenta de comunicação, permitindo que cada membro compartilhasse suas ideias com o grupo.

1. Primeiramente, analisamos o projeto como um todo e definimos os principais fluxos de interação entre anunciantes e interessados na plataforma. Esta etapa envolveu a definição de fluxos, como:

   - Cadastro e login de usuários;
   - Publicação de anúncios;
   - Busca de imóveis com filtros avançados;
   - Sistema de comunicação entre usuários.

2. Com os fluxos definidos, realizamos a fase de brainstorming, onde cada participante teve a oportunidade de compartilhar suas ideias e sugestões dentro de cada fluxo. Essa fase incentivou a troca aberta de ideias, promovendo a colaboração entre os membros do grupo.

3. Para organizar as ideias geradas, utilizamos o Miro como ferramenta colaborativa online, onde cada membro pôde adicionar post-its representando suas sugestões. O Miro serviu como um espaço visual para a organização e desenvolvimento das ideias de forma interativa.

4. Com base nas ideias coletadas no Miro, analisamos e documentamos os principais requisitos do projeto, incluindo funcionalidades necessárias e melhorias.
</div>

## Resultado

### Quadro Visual do Brainstorming

<div align="justify">
&emsp;&emsp;Como resultado da execução da técnica, obtivemos o artefato apresentado abaixo, que apresenta todas as ideias coletadas e priorizadas durante a realização do Brainstorming na ferramenta <a href="https://miro.com">Miro</a>.
</div>
<br>
<iframe width="768" height="432" src="https://miro.com/app/board/uXjVLKM9Yr4=/?share_link_id=535533674274" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>
<div align="center">Figura 1 - Brainstorming no Miro</div>
</div>
<br>

### Vídeo

<div align="center">
<video width="768" height="432" controls>
  <source src="URL_DO_VIDEO" type="video/mp4">
  Seu navegador não suporta a exibição do vídeo.
</video>
<div align="center">Figura 2 - Vídeo</div>
</div>

### Requisitos Elicitados

#### Requisitos Funcionais (RF)

- **RF01**: Cadastro de contas de usuários – Permitir que usuários criem contas como anunciantes e interessados, garantindo um processo de registro simples e seguro.
- **RF02**: Publicação de anúncios – Fornecer uma interface intuitiva para que os anunciantes possam criar e publicar anúncios de imóveis, com possibilidade de adicionar fotos, vídeos e descrições detalhadas.
- **RF03**: Classificação dos anúncios por tipo – Classificar automaticamente os anúncios como "aluguel" ou "venda" para facilitar a navegação dos usuários.
- **RF04**: Busca de imóveis com filtros e categorias – Oferecer uma ferramenta de busca abrangente que permita aos usuários filtrar imóveis por localidade, faixa de preço, número de quartos, tamanho e outras características, além de selecionar categorias específicas como apartamentos, casas, salas comerciais, etc.
- **RF05**: Sistema de mensagens entre usuários – Implementar uma funcionalidade de chat que possibilite a comunicação direta entre interessados e anunciantes, promovendo uma negociação mais ágil e segura.
- **RF06**: Notificações de novas mensagens e respostas – Enviar notificações em tempo real para usuários sobre novas mensagens e respostas em seus anúncios ou interações.
- **RF07**: Avaliações de imóveis e anunciantes – Permitir que os usuários façam avaliações dos imóveis visitados e dos anunciantes, contribuindo para a confiança e a reputação dentro da plataforma.
- **RF08**: Comentários em anúncios – Habilitar a seção de comentários em anúncios para que os interessados possam fazer perguntas ou deixar feedbacks sobre os imóveis.
- **RF09**: Salvar anúncios como favoritos – Oferecer a funcionalidade de marcar anúncios como favoritos para fácil acesso posterior e organização de preferências.
- **RF10**: Painel do usuário para gestão de anúncios – Disponibilizar um painel centralizado onde os anunciantes possam gerenciar seus anúncios, verificar estatísticas de visualizações e responder mensagens de interessados.

#### Requisitos Não Funcionais (RNF)

- **RNF01**: Escalabilidade – Projetar a plataforma de forma que possa crescer e se adaptar conforme o número de usuários e o volume de conteúdo aumentem ao longo do tempo, sem comprometer o desempenho ou a qualidade do serviço.
- **RNF02**: Compatibilidade – Garantir que a plataforma seja compatível com uma ampla variedade de navegadores da web, sistemas operacionais e dispositivos, para que os usuários possam acessá-la de qualquer lugar e em qualquer dispositivo de sua escolha.
- **RNF03**: Usabilidade e acessibilidade – Projetar uma interface de usuário intuitiva e fácil de usar, com navegação clara e recursos de acessibilidade que atendam às necessidades de todos os usuários.

## Tecnologias

Para o desenvolvimento da plataforma, consideramos as seguintes tecnologias:

- **Frontend**: React ou Angular, para construção de uma interface dinâmica e responsiva.
- **Backend**: NestJS ou Spring Boot, para gerenciar a lógica de negócios e as comunicações com o banco de dados.
- **Banco de Dados**: MySQL, para armazenamento estruturado dos dados da plataforma.

## Histórico de Versão

| Versão | Data da alteração |      Alteração       |                 Responsável                  |                   Revisor                    | Data de revisão |
| :----: | :---------------: | :------------------: | :------------------------------------------: | :------------------------------------------: | :-------------: |
|  1.0   |    03/11/2024     | Criação do documento | [Alexandre Beck](https://github.com/zzzBECK) | [Caio Berg](https://github.com/Caio-bergbjj) |   03/11/2024    |
