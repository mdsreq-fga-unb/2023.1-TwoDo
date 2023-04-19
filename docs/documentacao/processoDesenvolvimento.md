# Processo de Desenvolvimento
## Historico de Revisão

| Data     | Versão | Descrição                  | Autor(es)                                                                          |
|----------|--------|----------------------------|---------------------------------------------------------------------------------------------|
|18/04/2023|   0.1  | Definição das práticas do XP e Scrum       |[Arthur](https://github.com/Arthrok), [Eric](https://github.com/ericbky), [Pedro Lucas](https://github.com/lucasdray), [Yasmim](https://github.com/yaskisoba)| 

----------------------------------------------------------------

Para o desenvolvimento do produto, a equipe utilizará fundamentalmente terá algumas práticas como: comunicação, simplicidade, feedback, coragem e respeito. Na mesma linhagem, seguiremos de forma híbrida, algumas práticas de desenvolvimento de software envolvendo "XP" com o método de gerenciamento de projetos "Scrum", assim como seus valores, princípios, filosofias e práticas, com algumas básicas adaptações.

# Scrum

Scrum é um framework leve que ajuda pessoas,times e organizações a gerar valor por meio de soluções adaptativas para problemas complexos.

### Separação dos papéis

 O time será divido entre o Product Owner (PO), o Scrum Master e o Scrum Team.

### Práticas adotadas do Scrum

 - Definição do Product Backlog;
- Sprint Planning Meeting

- Sprint Backlog

- Adaptação do Daily Scrum

- Sprint Review

- Sprint Retrospective

----------------------------------

# XP (Extreming Programming)

XP é um estilo de desenvolvimento de software com foco na excelente aplicação de técnicas de programação, comunicação clara e trabalho em equipe.

O XP inclui uma filosofia de desenvolvimento de software baseada nos valores de comunicação, feedback, simplicidade, coragem e respeito.

### Práticas do XP que serão usadas

- [x] Jogo do planejamento
- [x] Programação em pares
- [x] Pequenas versões
- [x] Propriedade coletiva
- [ ] Metáforas
- [x] Integração contínua
- [x] Projeto Simples 
- [ ] Semana de 40 horas
- [x] Testes
- [x] Cliente Presente
- [x] Refatoração
- [x] Padronização de código
- [ ] Reunião diária 

<ul>
  <li><input type="checkbox" checked class="checkbox" id='TESTE'> Jogo do planejamento</li>
  <li><input type="checkbox" checked class="checkbox"> Programação em pares</li>
  <li><input type="checkbox" checked class="checkbox"> Pequenas versões</li>
  <li><input type="checkbox" checked class="checkbox"> Propriedade coletiva</li>
  <li><input type="checkbox"> Metáforas</li>
  <li><input type="checkbox" checked class="checkbox"> Integração contínua</li>
  <li><input type="checkbox" checked class="checkbox"> Projeto Simples</li>
  <li><input type="checkbox"> Semana de 40 horas</li>
  <li><input type="checkbox" checked class="checkbox"> Testes</li>
  <li><input type="checkbox" checked class="checkbox"> Cliente Presente</li>
  <li><input type="checkbox" checked class="checkbox"> Refatoração</li>
  <li><input type="checkbox" checked class="checkbox"> Padronização de código</li>
  <li><input type="checkbox"> Reunião diária</li>
</ul>

<script>
var checkbox = document.getElementsByClassName('checkbox')

for (var i = 0; i < checkbox.length; i++) {
    checkbox[i].addEventListener('click', (e) => {
    e.preventDefault()
})
}

</script>

