# Léxico

## 1. Introdução

Na engenharia de requisitos, um léxico é um recurso utilizado para organizar e definir o vocabulário específico de um domínio de aplicação. Ele serve como um glossário estruturado, onde são documentados termos essenciais e suas definições para que todos os envolvidos no projeto (desenvolvedores, analistas, clientes, entre outros) compartilhem o mesmo entendimento dos conceitos. A utilização de um léxico é fundamental para reduzir ambiguidades, garantir consistência na comunicação e facilitar a documentação e o aprendizado dos termos do projeto.

## 2. Metodologia

Para classificar os léxicos, utilizaremos a metodologia do **Léxico Ampliado da Linguagem (LAL)**, uma abordagem que organiza o vocabulário do domínio de aplicação de forma a melhorar a comunicação e o entendimento entre os stakeholders. No LAL, cada vocábulo é descrito por meio de uma estrutura específica, facilitando a compreensão dos conceitos fundamentais e assegurando uma documentação consistente.

Cada vocábulo será estruturado com base nos seguintes atributos:

- **Classificação**: Define o tipo de termo, indicando o papel que ele desempenha dentro do sistema. As principais classificações incluem:
  - **Objeto**: Refere-se a qualquer entidade ou item tangível ou abstrato no sistema, como "Documento".
  - **Agente**: Representa quem ou o que executa ações no sistema, como "Cliente" ou "Administrador".
  - **Ação**: Define atividades ou processos realizados pelos agentes, como "Enviar" ou "Cadastrar".
  - **Estado**: Indica uma condição ou situação de um objeto ou agente, como "Ativo" ou "Pendente".
  - **Evento**: Representa uma ocorrência ou situação que gera uma mudança no estado do sistema, como "Login" ou "Encerramento de Sessão".

- **Sinônimo**: Lista palavras ou expressões alternativas que podem ser usadas no lugar do termo, ajudando a reforçar o entendimento e a uniformidade terminológica do léxico.

- **Noção**: Fornece uma definição breve e direta do termo, explicando o que ele representa ou realiza no contexto do sistema. A noção deve ser objetiva e evitar ambiguidade para garantir um entendimento claro.

- **Impacto**: Descreve como o termo influencia ou se relaciona com outros elementos do sistema, indicando, por exemplo, dependências ou interações importantes para o funcionamento ou o comportamento do sistema.

Essa estrutura permite que o LAL capture não apenas as definições dos termos, mas também seus significados e relações contextuais, promovendo uma visão mais completa e profunda do vocabulário do domínio e facilitando o trabalho colaborativo em torno dos requisitos do sistema.


## 3. Vocábulos

### L01 - HostHub

| Léxico            | HostHub                                                                                       |
| ----------------- | --------------------------------------------------------------------------------------------- |
| **Classificação** | Objeto                                                                                       |
| **Sinônimos**     | Plataforma, Aplicativo                                                                        |
| **Noção**         | Sistema responsável por conectar anunciantes de imóveis a possíveis interessados em alugá-los |
| **Impacto**       | Facilita o processo de divulgação, busca, reserva e gestão de imóveis                         |

### L02 - Imóvel

| Léxico            | Imóvel                                                                                                       |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Objeto                                                                                                       |
| **Sinônimos**     | Propriedade, Residência                                                                                      |
| **Noção**         | Propriedade disponível para aluguel ou venda, podendo ser um apartamento, casa, ou sala comercial            |
| **Impacto**       | Representa o item central do aplicativo, sendo visualizado, reservado, favoritado e avaliado pelos usuários  |

### L03 - Anúncio

| Léxico            | Anúncio                                                                                                      |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Objeto                                                                                                       |
| **Sinônimos**     | Publicação                                                                                                   |
| **Noção**         | Postagem que descreve um imóvel, contendo detalhes como fotos, vídeos, localização e preço                   |
| **Impacto**       | Fornece informações relevantes para que os usuários tomem decisões sobre aluguel ou compra                   |

### L04 - Usuário

| Léxico            | Usuário                                                                                                      |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Agente                                                                                                       |
| **Sinônimos**     | Cliente                                                                                                      |
| **Noção**         | Pessoa cadastrada na plataforma, podendo ser anunciante ou interessado em imóveis                            |
| **Impacto**       | Interage com o sistema realizando buscas, reservas e dando feedback sobre imóveis                            |

### L05 - Anunciante

| Léxico            | Anunciante                                                                                                   |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Agente                                                                                                       |
| **Sinônimos**     | Proprietário, Dono                                                                                           |
| **Noção**         | Usuário responsável por cadastrar e gerenciar os imóveis disponíveis para aluguel ou venda                   |
| **Impacto**       | Publica anúncios e responde a interessados, mantendo o conteúdo atualizado e atrativo                        |

### L06 - Hóspede

| Léxico            | Hóspede                                                                                                      |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Agente                                                                                                       |
| **Sinônimos**     | Locatário                                                                                                    |
| **Noção**         | Usuário que realiza a reserva de um imóvel para aluguel                                                      |
| **Impacto**       | Gera demanda por imóveis e interage com o sistema para realizar reservas e avaliações                        |

### L07 - Cadastro de Usuário

| Léxico            | Cadastro de Usuário                                                                                          |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Registro                                                                                                     |
| **Noção**         | Processo pelo qual uma pessoa se registra no sistema como usuário                                            |
| **Impacto**       | Permite que o usuário acesse funcionalidades como busca, reserva e interação com anunciantes                 |

### L08 - Cadastro de Imóvel

| Léxico            | Cadastro de Imóvel                                                                                           |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Inclusão de Propriedade                                                                                      |
| **Noção**         | Ato de adicionar um novo imóvel ao sistema, com todas as informações relevantes                              |
| **Impacto**       | Atualiza a base de dados do sistema, tornando o imóvel disponível para consulta e reserva                    |

### L09 - Reserva

| Léxico            | Reserva                                                                                                      |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Agendamento                                                                                                  |
| **Noção**         | Ato de solicitar o aluguel de um imóvel para um período específico                                           |
| **Impacto**       | Bloqueia o período selecionado e notifica o anunciante sobre o interesse do hóspede                          |

### L10 - Disponibilidade

| Léxico            | Disponibilidade                                                                                              |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Estado                                                                                                       |
| **Sinônimos**     | Livre, Ocupado                                                                                               |
| **Noção**         | Status de um imóvel, indicando se está ou não disponível para reserva                                        |
| **Impacto**       | Orienta as buscas dos usuários, filtrando apenas imóveis disponíveis                                         |

### L11 - Filtro

| Léxico            | Filtro                                                                                                       |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Refinamento                                                                                                  |
| **Noção**         | Ferramenta que permite ao usuário especificar critérios para busca, como preço, localidade e categoria       |
| **Impacto**       | Facilita a localização de imóveis de acordo com as preferências do usuário                                   |

### L12 - Localidade

| Léxico            | Localidade                                                                                                   |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Objeto                                                                                                       |
| **Sinônimos**     | Localização, Área                                                                                            |
| **Noção**         | Região onde o imóvel está localizado                                                                         |
| **Impacto**       | Permite que o usuário busque por imóveis em regiões específicas                                              |

### L13 - Faixa de Preço

| Léxico            | Faixa de Preço                                                                                               |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Atributo                                                                                                     |
| **Sinônimos**     | Intervalo de Preço                                                                                           |
| **Noção**         | Intervalo de valor que o usuário está disposto a pagar pelo imóvel                                           |
| **Impacto**       | Permite que o usuário refine a busca com base em seu orçamento                                               |

### L14 - Categoria do Imóvel

| Léxico            | Categoria do Imóvel                                                                                          |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Atributo                                                                                                     |
| **Sinônimos**     | Tipo de Imóvel                                                                                               |
| **Noção**         | Classificação do imóvel como apartamento, casa ou sala comercial                                             |
| **Impacto**       | Orienta a busca, permitindo filtrar imóveis por tipo                                                         |

### L15 - Descrição do Imóvel

| Léxico            | Descrição do Imóvel                                                                                          |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Informação                                                                                                   |
| **Sinônimos**     | Detalhes                                                                                                     |
| **Noção**         | Texto descritivo com características e informações adicionais do imóvel                                      |
| **Impacto**       | Auxilia os usuários a conhecerem melhor o imóvel antes de fazer uma reserva                                  |

### L16 - Perfil do Usuário

| Léxico            | Perfil do Usuário                                                                                            |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Objeto                                                                                                       |
| **Sinônimos**     | Conta, Identidade                                                                                            |
| **Noção**         | Informações cadastradas do usuário, incluindo nome, contato e histórico de atividades                        |
| **Impacto**       | Personaliza a experiência do usuário e permite melhor gerenciamento de suas interações com o sistema         |

### L17 - Visualização de Imóvel

| Léxico            | Visualização de Imóvel                                                                                       |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Exibição                                                                                                     |
| **Noção**         | Ato de acessar as informações detalhadas de um imóvel específico                                             |
| **Impacto**       | Permite ao usuário explorar as características do imóvel e considerar sua reserva                            |

### L18 - Chat

| Léxico            | Chat                                                                                                         |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Mensagens                                                                                                    |
| **Noção**         | Canal de comunicação direta entre o interessado e o anunciante                                               |
| **Impacto**       | Facilita o esclarecimento de dúvidas e negociações entre as partes                                           |

### L19 - Alertas de Disponibilidade

| Léxico            | Alertas de Disponibilidade                                                                                   |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Evento                                                                                                       |
| **Sinônimos**     | Notificações de Disponibilidade                                                                              |
| **Noção**         | Notificação que avisa o interessado quando um imóvel de interesse fica disponível                            |
| **Impacto**       | Mantém o usuário informado sobre mudanças de status dos imóveis que ele acompanha                            |

### L20 - Feedback

| Léxico            | Feedback                                                                                                     |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Avaliação                                                                                                    |
| **Noção**         | Opinião ou comentário deixado pelos usuários sobre sua experiência com o imóvel ou anfitrião                 |
| **Impacto**       | Influencia a reputação do imóvel e do anfitrião, auxiliando futuros interessados                              |

### L21 - Publicação

| Léxico            | Publicação                                                                                                   |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Divulgação                                                                                                   |
| **Noção**         | Ato de disponibilizar um anúncio de imóvel para o público da plataforma                                      |
| **Impacto**       | Torna o imóvel visível para os usuários interessados em alugar ou comprar                                   |

### L22 - Visualização

| Léxico            | Visualização                                                                                                 |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Exibição                                                                                                     |
| **Noção**         | Ato de acessar e ver as informações de um imóvel específico                                                  |
| **Impacto**       | Permite ao usuário explorar o conteúdo do anúncio do imóvel                                                  |

### L23 - Classificação

| Léxico            | Classificação                                                                                                |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Nota, Ranking                                                                                                |
| **Noção**         | Avaliação atribuída ao imóvel por usuários que já fizeram uma reserva                                        |
| **Impacto**       | Contribui para a reputação do imóvel, influenciando futuras reservas                                         |

### L24 - Avaliação

| Léxico            | Avaliação                                                                                                    |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Feedback                                                                                                     |
| **Noção**         | Comentários ou nota sobre a experiência do usuário em relação ao imóvel                                      |
| **Impacto**       | Ajuda a outros usuários na escolha de imóveis, promovendo transparência                                      |

### L25 - Favoritos

| Léxico            | Favoritos                                                                                                    |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Objeto                                                                                                       |
| **Sinônimos**     | Lista de Desejos                                                                                             |
| **Noção**         | Lista de imóveis que o usuário marcou como preferidos                                                        |
| **Impacto**       | Facilita o acompanhamento de imóveis do interesse do usuário                                                 |

### L26 - Aluguel

| Léxico            | Aluguel                                                                                                      |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Locação                                                                                                      |
| **Noção**         | Ato de alugar um imóvel por um período específico                                                            |
| **Impacto**       | Gera receita para o anunciante e permite ao usuário utilizar o imóvel temporariamente                        |

### L27 - Venda

| Léxico            | Venda                                                                                                        |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Comercialização                                                                                              |
| **Noção**         | Transferência definitiva de posse de um imóvel                                                               |
| **Impacto**       | Remove o imóvel do sistema de aluguéis e possibilita nova aquisição por outro usuário                        |

### L28 - Cancelamento

| Léxico            | Cancelamento                                                                                                 |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Evento                                                                                                       |
| **Sinônimos**     | Anulação                                                                                                     |
| **Noção**         | Ato de desistir de uma reserva ou processo de locação                                                        |
| **Impacto**       | Libera o imóvel para novas reservas e pode afetar a reputação do usuário                                     |

### L29 - Interessado

| Léxico            | Interessado                                                                                                  |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Agente                                                                                                       |
| **Sinônimos**     | Potencial Cliente                                                                                            |
| **Noção**         | Pessoa que demonstrou interesse em alugar ou comprar um imóvel                                               |
| **Impacto**       | Pode se tornar locatário ou comprador, gerando demanda para o sistema                                        |

### L30 - Perfil

| Léxico            | Perfil                                                                                                       |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Objeto                                                                                                       |
| **Sinônimos**     | Conta                                                                                                        |
| **Noção**         | Informações do usuário cadastradas na plataforma                                                             |
| **Impacto**       | Facilita a personalização da experiência do usuário                                                          |

### L31 - Editar Perfil

| Léxico            | Editar Perfil                                                                                                |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Atualizar Informações                                                                                        |
| **Noção**         | Processo de alteração dos dados cadastrados do usuário                                                       |
| **Impacto**       | Mantém os dados do usuário atualizados e relevantes                                                          |

### L32 - Sala Comercial

| Léxico            | Sala Comercial                                                                                               |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Objeto                                                                                                       |
| **Sinônimos**     | Escritório                                                                                                   |
| **Noção**         | Imóvel destinado a fins comerciais ou de escritório                                                          |
| **Impacto**       | Permite ao usuário procurar espaços adequados para fins comerciais                                           |

### L33 - Apartamento

| Léxico            | Apartamento                                                                                                  |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Objeto                                                                                                       |
| **Sinônimos**     | Flat                                                                                                         |
| **Noção**         | Unidade residencial em um edifício                                                                          |
| **Impacto**       | Fornece opção de moradia para usuários que buscam uma residência temporária ou permanente                    |

### L34 - Casa

| Léxico            | Casa                                                                                                         |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Objeto                                                                                                       |
| **Sinônimos**     | Residência                                                                                                   |
| **Noção**         | Imóvel residencial independente                                                                              |
| **Impacto**       | Oferece uma opção para quem procura privacidade e espaço próprio                                             |

### L35 - Login

| Léxico            | Login                                                                                                        |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Evento                                                                                                       |
| **Sinônimos**     | Autenticação                                                                                                 |
| **Noção**         | Processo de entrada do usuário no sistema utilizando credenciais                                             |
| **Impacto**       | Permite acesso às funcionalidades reservadas para usuários cadastrados                                       |

### L36 - Anfitrião

| Léxico            | Anfitrião                                                                                                    |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Agente                                                                                                       |
| **Sinônimos**     | Proprietário                                                                                                 |
| **Noção**         | Usuário responsável pela administração de imóveis anunciados                                                 |
| **Impacto**       | Publica e gerencia os imóveis disponibilizados na plataforma                                                 |

### L37 - Publicação

| Léxico            | Publicação                                                                                                   |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| **Classificação** | Ação                                                                                                         |
| **Sinônimos**     | Divulgação                                                                                                   |
| **Noção**         | Ato de tornar o anúncio visível na plataforma                                                                |
| **Impacto**       | Permite ao imóvel ser visualizado e acessado pelos usuários                                                  |

## 4. Referências

> Leite, J. C. S. do P., & Franco, A. P. M. (1990). "O Uso de Hipertexto na Elicitação de Linguagens de Aplicação". Anais do IV Simpósio Brasileiro de Engenharia de Software. Disponível em: https://sol.sbc.org.br/index.php/sbes/article/view/24172

> SERRANO, Milene. DSW-BASE - Glossário Léxico. Apresentação do Power Point.

## 5. Controle de Versionamento 

| Versão | Data da alteração |            Alteração             |                       Responsável                       |                         Revisor                         |
| :----: | :---------------: | :------------------------------: | :-----------------------------------------------------: | :-----------------------------------------------------: |
|  1.0   |    03/11/2024     |       Criação do artefato e adição de léxicos       |    [Arthur Trindade](https://github.com/trindadea), [Miguel Moreira](https://github.com/EhOMiguel)     |    |
