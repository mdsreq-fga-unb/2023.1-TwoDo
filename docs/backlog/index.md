## Historico de Revisão

| Data     | Versão | Descrição                  | Autor(es)                                                                          |
|----------|--------|----------------------------|---------------------------------------------------------------------------------------------|
|01/05/2023|   0.1  | Definição do backlog do produto        |[Arthur](https://github.com/Arthrok)

## 1. Épicos


| Épico| Descrição                                                       |
|------|-----------------------------------------------------------------|
| E1   | Disponibilizar um fórum de dúvidas para os usuários do sistema.  |
| E2   | Estabelecer um sistema de ranking para classificar usuários.     |
| E3   | Realizar a administração de usuários.      |
| E4   | Implementar um chat de comunicação para interação entre usuários.|

## 2. Features

| Épico | Feature | Descrição                                                         |
|-------|---------|-------------------------------------------------------------------|
| E1    | FT01    | Gerenciar avisos para os usuários do sistema.                      |
| E1    | FT02    | Gerenciar perguntas feitas pelos usuários.                         |
| E1    | FT03    | Gerenciar respostas dadas pelos usuários.                          |
| E2    | FT04    | Gerenciar ranqueamento de usuários com base em sua atividade.      |
| E2    | FT05    | Gerenciar ranqueamento de perguntas com base em sua popularidade.  |
| E2    | FT06    | Gerenciar ranqueamento de respostas com base em sua qualidade.     |
| E2    | FT07    | Gerenciar ranqueamento de avisos com base em sua relevância.       |
| E3    | FT08    | Gerenciar usuários do sistema, incluindo exclusões.                |
| E3    | FT09    | Gerenciar autenticação de dados dos usuários.                      |
| E4    | FT01    | Gerenciar mensagens enviadas pelos usuários.                       |
| E4    | FT02    | Gerenciar histórico de conversas.                                  |

## 3. User Stories

<table>
<thead>
<tr>
<th>Épico</th>
<th>Feature</th>
<th>US</th>
<th>Descrição</th>
<th>Critérios de Aceitação</th>
<th>Prioridade</th>
</tr>
</thead>
<tbody>
<tr>
<td>E1</td>
<td>FT01</td>
<td>US01</td>
<td>Eu, como usuário, gostaria de cadastrar avisos para informar notícias de acontecimentos como monitorias</td>
<td>Caracteres especiais devem ser aceitos ao criar aviso<br><br>Números devem ser aceitos ao criar aviso<br><br>Avisos devem ter identificações diferentes<br><br> Os avisos devem ser adicionadas em alguma engenharia<br><br>O corpo do aviso deve ser obrigatório<br><br>O título do aviso deve ser obrigatório<br><br>O filtro do aviso deve ser obrigatório<br><br>A engenharia do aviso deve ser obrigatória</td>
<td>Alta</td>
</tr>
<tr>
<td>E1</td>
<td>FT01</td>
<td>US02</td>
<td>Eu, como usuário, gostaria de visualizar uma lista de avisos feitos para ficar ciente dos acontecimentos da Universidade.</td>
<td>É permitida a visualização de um aviso por vez<br><br>Uma lista de avisos já feitos anteriormente deve ser visualizada<br><br>Os avisos podem estar separadas por área de conhecimento<br><br>A visualização deve conter o nome e o curso do usuário que fez o aviso</td>
<td>Alta</td>
</tr>
<tr>
<td>E1</td>
<td>FT01</td>
<td>US03</td>
<td>Eu, como usuário, gostaria de apagar meus avisos para caso de escrita incorreta ou passagem de prazo</td>
<td>A exclusão pode ser feita a qualquer momento sem limite de tempo após sua publicação<br><br>Somente o autor do aviso pode apagá-lo</td>
<td>Alta</td>
</tr>
<tr>
<td>E1</td>
<td>FT01</td>
<td>US04</td>
<td>Eu, como usuário gostaria de salvar os avisos que me interessem, para não perde-los e poder verifica-los mais facilmente depois</td>
<td>Os avisos salvos devem ser visualizados numa aba a parte chamada "avisos"<br><br>Deve-se exibir apenas o nome do aviso salvo na lista de visualização</td>
<td>Alta</td>
</tr>
<tr>
<td>E1</td>
<td>FT02</td>
<td>US05</td>
<td>Eu como usuário gostaria de ser capaz de publicar perguntas para tirar minhas dúvidas</td>
<td>Caracteres especiais devem ser aceitos ao criar pergunta <br><br> Números devem ser aceitos ao criar pergunta <br><br> Perguntas devem ter identificações diferentes <br><br> As perguntas devem ser adicionadas em alguma engenharia<br><br>O corpo da pergunta deve ser obrigatório<br><br>O título da pergunta deve ser obrigatório<br><br>O filtro da pergunta deve ser obrigatório<br><br>A engenharia da pergunta deve ser obrigatória</td>
<td>Alta</td>
</tr>
<tr>
<td>E1</td>
<td>FT02</td>
<td>US06</td>
<td>Eu como usuário gostaria de visualizar perguntas para fins de busca e estudo</td>
<td>É permitida a visualização dos detalhes de uma pergunta  <br><br> Uma lista de perguntas já feitas anteriormente deve ser visualizada <br><br> As perguntas podem estar separadas por área de conhecimento <br><br> A visualização deve conter o nome e o curso do usuário que fez a pergunta</td>
<td>Alta</td>
</tr>
<tr>
<td>E1</td>
<td>FT02</td>
<td>US07</td>
<td>Eu como usuário gostaria de pesquisar perguntas por tema para fins de estudo</td>
<td>A busca deve ser feita através de um filtro por matérias</td>
<td>Alta</td>
</tr>
<tr>
<td>E1</td>
<td>FT02</td>
<td>US08</td>
<td>Eu como usuário gostaria de poder deletar as minhas perguntas para caso de escrita incorreta</td>
<td>A exclusão pode ser feita a qualquer momento sem limite de tempo após sua publicação <br><br> Somente o autor da pergunta pode apagá-la</td>
<td>Alta</td>
</tr>
<tr>
<td>E1</td>
<td>FT02</td>
<td>US09</td>
<td>Eu como usuário gostaria de salvar as perguntas que me interessem, para não perde-los e poder verifica-los mais facilmente depois</td>
<td>As perguntas salvas devem ser visualizadas numa aba a parte chamada "perguntas"<br><br>Deve-se exibir apenas o nome da pergunta salva na lista de visualização</td>
<td>Alta</td>
</tr>
<tr>
<td>E1</td>
<td>FT03</td>
<td>US10</td>
<td>Eu como usuário gostaria de poder responder todas as perguntas disponibilizadas no forum para fins de ajudar outros usuarios</td>
<td>Caracteres especiais devem ser aceitos ao criar respostas;<br><br>Números devem ser aceitos ao criar respostas;<br><br>Respostas devem ter identificações diferentes;<br><br>Uma resposta não poderá existir se não existir um usuário e uma pergunta para criá-la<br><br>O corpo da resposta deve ser obrigatório</td>
<td>Alta</td>
</tr>
<tr>
<td>E1</td>
<td>FT03</td>
<td>US11</td>
<td>Eu como usuário gostaria de ser capaz de visualizar as respostas para fins de soluções de dúvidas</td>
<td>Uma lista de respostas deve ser visualizada <br><br> A visualização deve conter o nome e o curso do usuário que fez a pergunta <br><br> As respostas devem ser visualizadas somente em perguntas específicas</td>
<td>Alta</td>
</tr>
<tr>
<td>E1</td>
<td>FT03</td>
<td>US12</td>
<td>Eu, como usuário, gostaria de deletar minhas respostas para fim de escrita incorreta</td>
<td>A exclusão pode ser feita a qualquer momento sem limite de tempo após sua publicação<br><br>Somente o autor da resposta pode apagá-la</td>
<td>Alta</td>
</tr>
<tr>
<td>E2</td>
<td>FT04</td>
<td>US13</td>
<td>Eu como usuário gostaria de dar nota para os outros usuários para mudar suas posições no ranking</td>
<td>A votação será feita por estrelas</td>
<td>Alta</td>
</tr>
<tr>
<td>E2</td>
<td>FT04</td>
<td>US14</td>
<td>Eu como usuário gostaria de visualizar a minha posição no ranking geral para fins de melhora-la</td>
<td>O rankeamento precisa ser em ordem decrescente (do mais votado para o menos votado)</td>
<td>Alta</td>
</tr>

<tr style="color:yellow">
<td>E2</td>
<td>FT04</td>
<td>US15</td>
<td>Eu como usuário gostaria de editar meus avisos em caso de erro de digitação e etc.</td>
<td></td>
<td>Alta</td>
</tr>

<tr style="color:yellow">
<td>E2</td>
<td>FT04</td>
<td>US16</td>
<td>Eu como usuário gostaria de editar minhas perguntas em caso de erro de digitação e etc.</td>
<td></td>
<td>Alta</td>
</tr>

<tr style="color:yellow">
<td>E2</td>
<td>FT04</td>
<td>US17</td>
<td>Eu como usuário gostaria de editar minhas respostas em caso de erro de digitação e etc.</td>
<td></td>
<td>Alta</td>
</tr>


<tr>
<td>E2</td>
<td>FT05</td>
<td>US18</td>
<td>Eu como usuário gostaria de visualizar as perguntas do fórum conforme a ordem de rankeamento para saber as perguntas mais e menos relevantes</td>
<td>O rankeamento precisa ser em ordem decrescente (do mais votado para o menos votado)</td>
<td>Alta</td>
</tr>
<tr>
<td>E2</td>
<td>FT05</td>
<td>US19</td>
<td>Eu como usuário gostaria de avaliar as perguntas feitas por outros usuários&nbsp;para fins de nivelamento</td>
<td>A votação será feita por estrelas</td>
<td>Alta</td>
</tr>
<tr>
<td>E2</td>
<td>FT06</td>
<td>US20</td>
<td>Eu, como usuário, gostaria de avaliar as respostas fornecidas para fim de destaque das melhores respostas</td>
<td>A votação será feita por estrelas</td>
<td>Alta</td>
</tr>
<tr>
<td>E2</td>
<td>FT06</td>
<td>US21</td>
<td>Eu, como usuário, gostaria de visualizar as respostas em ordem de rankeamento, para saber as melhores respostas fornecidas</td>
<td>O rankeamento precisa ser em ordem decrescente (do mais votado para o menos votado)</td>
<td>Alta</td>
</tr>
<tr>
<td>E2</td>
<td>FT07</td>
<td>US22</td>
<td>Eu, como usuário, gostaria de avaliar os avisos postados para fim de destaque dos mais importantes</td>
<td>A votação será feita por estrelas</td>
<td>Alta</td>
</tr>
<tr>
<td>E2</td>
<td>FT07</td>
<td>US23</td>
<td>Eu, como usuário, gostaria de visualizar os avisos em ordem de rankeamento, para saber quais sao os principais avisos da faculdade</td>
<td>O rankeamento precisa ser em ordem decrescente (do mais votado para o menos votado)</td>
<td>Alta</td>
</tr>
<tr>
<td>E3</td>
<td>FT08</td>
<td>US24</td>
<td>Eu como usuário gostaria de me cadastrar no sistema para utilizar suas funcionalidades</td>
<td>O cadastro precisa conter: nome completo, curso do aluno, matricula, celular, alem de um email e uma senha <br><br> Não é possivel cadastrar um email existente <br><br> Não é possivel cadastrar uma matricula existente</td>
<td>Alta</td>
</tr>
<tr>
<td>E3</td>
<td>FT08</td>
<td>US25</td>
<td>Eu como usuário gostaria de visualizar os meus dados cadastrais em uma aba de perfil para poder conferir se as informações estão corretas</td>
<td>Todas as informações utilizadas no cadastro devem estar disponíveis nesta aba, menos matrícula e senha<br><br>É permitida a visualização de um usuario por vez<br><br>Uma lista de usuários deve ser visualizada</td>
<td>Alta</td>
</tr>
<tr>
<td>E3</td>
<td>FT08</td>
<td>US26</td>
<td>Eu como usuário gostaria de ter a possibilidade de buscar outros usuários para poder averiguar as perguntas que um usuário já fez</td>
<td>A busca deve ser feita por nome</td>
<td>Alta</td>
</tr>
<tr>
<td>E3</td>
<td>FT08</td>
<td>US27</td>
<td>Eu como usuário gostaria de editar os dados do meu perfil para caso alguma informação tenha sido preenchida incorretamente possa ser mudada</td>
<td>Todos os dados podem ser atualizados a qualquer momento sem limite de quantidade</td>
<td>Alta</td>
</tr>
<tr>
<td>E3</td>
<td>FT08</td>
<td>US28</td>
<td>Eu como usuario gostaria de ter a possibilidade de deletar minha conta para caso não deseje mais utilizá-la</td>
<td>Ao excluir a conta, todas as atividades do usuário serão excluídas</td>
<td>Alta</td>
</tr>
<tr>
<td>E3</td>
<td>FT09</td>
<td>US29</td>
<td>Eu como usuário gostaria de realizar login com email e senha para adentrar no sistema</td>
<td>O login pode ser feito atraves de email e senha</td>
<td>Alta</td>
</tr>
<tr>
<td>E3</td>
<td>FT09</td>
<td>US30</td>
<td>Eu como usuário gostaria de ter a possibilidade de recuperar minha senha através do email caso eu a esqueça</td>
<td>O e-mail deve ser autenticado em até 10 minutos</td>
<td>Alta</td>
</tr>

<tr style="color:yellow">
<td>E4</td>
<td>FT01</td>
<td>US31</td>
<td>Como um usuário, eu quero ser capaz de enviar mensagens públicas para outros usuários em tempo real, para que eu possa ter conversas públicas com outros usuários sem precisar atualizar a página.</td>
<td></td>
<td>Alta</td>
</tr>

<tr style="color:yellow">
<td>E4</td>
<td>FT01</td>
<td>US32</td>
<td>Como um usuário, eu quero ser capaz de enviar mensagens privadas para outros usuários, para que eu possa ter conversas privadas que não são visíveis para outros usuários.</td>
<td></td>
<td>Alta</td>
</tr>

<tr style="color:yellow">
<td>E4</td>
<td>FT01</td>
<td>US33</td>
<td>Como um usuário, eu quero ser notificado quando uma nova mensagem privada for enviada para mim, para que eu possa saber imediatamente quando uma nova mensagem chegou e respondê-la.</td>
<td></td>
<td>Alta</td>
</tr>

<tr style="color:yellow">
<td>E4</td>
<td>FT01</td>
<td>US34</td>
<td>Como um usuário, eu quero ser capaz de excluir minhas próprias mensagens enviadas, para que eu possa corrigir erros ou remover mensagens inapropriadas que enviei por engano.</td>
<td></td>
<td>Alta</td>
</tr>

<tr style="color:yellow">
<td>E4</td>
<td>FT01</td>
<td>US35</td>
<td>Como um usuário, eu quero ser capaz de silenciar ou bloquear outros usuários que estão me incomodando com mensagens privadas não solicitadas, para que eu possa controlar minha experiência de comunicação.</td>
<td></td>
<td>Alta</td>
</tr>

<tr style="color:yellow">
<td>E4</td>
<td>FT01</td>
<td>US36</td>
<td>Como um usuário, eu quero ser capaz de relatar mensagens públicas inapropriadas ou ofensivas enviadas por outros usuários, para que o administrador possa lidar com essas mensagens e tomar as medidas adequadas.</td>
<td></td>
<td>Alta</td>
</tr>

<tr style="color:yellow">
<td>E4</td>
<td>FT02</td>
<td>US37</td>
<td>Como um usuário, eu quero ser capaz de visualizar todo o meu histórico de conversas com outro usuário, para que eu possa rever as informações e referências discutidas.</td>
<td></td>
<td>Alta</td>
</tr>

<tr style="color:yellow">
<td>E4</td>
<td>FT02</td>
<td>US38</td>
<td>Como um usuário, eu quero ser capaz de pesquisar meu histórico de conversas por palavra-chave ou data específica, para que eu possa encontrar informações importantes de forma rápida e fácil.</td>
<td></td>
<td>Alta</td>
</tr>

<tr style="color:yellow">
<td>E4</td>
<td>FT02</td>
<td>US39</td>
<td>Como um usuário, eu quero ser capaz de arquivar ou excluir conversas antigas que não são mais relevantes para mim, para manter minha lista de conversas organizada e fácil de usar.</td>
<td></td>
<td>Alta</td>
</tr>

<tr style="color:yellow">
<td>E4</td>
<td>FT02</td>
<td>US40</td>
<td>Como um usuário, eu quero que meu histórico de conversas mais recentes sejam recuperados e carregados mais rapidamente.</td>
<td></td>
<td>Alta</td>
</tr>

</tbody>
</table>