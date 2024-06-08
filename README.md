<h1 align="center">Projeto – Evoluir.Ti</h1>

<div align="center">
    <img src="./Imagens/Logo_Atomic_Code.jpeg" style="width:480px; height:480px"/>
</div>

# Sumário

- <a href="#introducao">Introdução</a>
- <a href="#ciclo_vida">Ciclo de Vida</a>
- <a href="#analise_de_tarefas">Análise de Tarefas, Usuário e Funções</a>
- <a href="#requisitos">Especificação de Requisitos</a>
- <a href="#projeto_conceitual">Projeto Conceitual e Especificaçao do Design</a>
- <a href="#implementacao">Implementação</a>
- <a href="#conclusao">Conclusão</a>

<h1 id="introducao">Introdução</h1>

É um projeto idealizado para solucionar os desafios na hora da avaliação dos trabalhos dos alunos da Univiçosa durante o Simpósio de Produção Acadêmica - SIMPAC. Dentre os desafios, está a automatização da organização de projetos, otimização do tempo e a melhora da entrega dos resultados. De acordo com a demanda proposta pela CEO da NUPEX (Núcleo de Apoio à Pesquisa e Extensão da Univiçosa) Eliene da Silva Martins Viana, o que antes era feito no papel, agora terá que ser implementado em uma aplicação web responsiva que estará disponível para dispositivos móveis e também para desktops.

Pela grande falta de praticidade na hora das avaliações e por terem que entregar uma folha preenchida com cada grupo para cada avaliador, nossa aplicação será de uma grande ajuda, visto que ela automatizará toda essa questão de gestão de trabalhos e suas respectivas notas, o que poupará tempo e dinheiro.

<h1 id="ciclo_vida">Ciclo de Vida</h1>

Um modelo de ciclo de vida nas atividades de design de interfaces é um
framework ou abordagem que descreve as etapas pelas quais um projeto de
interface passa, desde o conceito inicial até a implementação e manutenção.
Ele fornece uma estrutura para os designers seguirem e ajuda a garantir que
todos os aspectos do design sejam considerados e tratados adequadamente
ao longo do processo. O modelo utilizado no projeto Evoluir.Ti foi o Modelo
Estrela (Hartson e Hix, 1989).

## Modelo Estrela

O modelo estrela de design de interfaces, também conhecido como “Star Model”, é um modelo de ciclo de vida com uma abordagem que visa criar interfaces de usuário eficazes e centradas no usuário. Este modelo é chamado assim devido à sua estrutura central, que é cercada por cinco componentes principais, semelhantes aos raios de estrela.

<div align="center">
    <img src="./Imagens/Ciclo_de_Vida.png" style="width:600px; height:480px"/>
    <p>Figura 1 - Modelo de Ciclo de Vida Estrela</p>
</div>

<h1 id="analise_de_tarefas">Análise de Tarefas, Usuário e Funções</h1>

## Cenário Atual

Atualmente, o processo de avaliação e entrega do SIMPAC é realizado de forma manual. Este processo envolve a coleta de avaliações dos trabalhos acadêmicos em formato de papel. Tal abordagem resulta em alguns problemas:
1. **Erros Humanos:** A manipulação manual dos documentos aumenta a probabilidade de erros, tanto na coleta quanto na avaliação dos trabalhos.
2. **Ineficiente e Demorado:** A necessidade de lidar com documentos físicos torna o processo lento e ineficiente, causando atrasos significativos e dificultando a gestão das avaliações.
3. **Precisão dos Resultados:** A precisão dos resultados é comprometida, uma vez que a natureza manual do processo aumenta a possibilidade de erros e inconsistências na avaliação dos trabalhos.

## Análise de Tarefas

Para transformar o processo manual em uma aplicação web responsiva, é necessário
identificar e analisar cada tarefa envolvida.

### Submissão dos trabalhos:
- **Usuários:** Alunos
- **Tarefa:** Submeter trabalhos acadêmicos via plataforma online.
- **Função necessária:** Formulário de submissão com suporte a uploads de arquivos.
### Organização dos trabalhos:
- **Usuários:** Administradores
- **Tarefa:** Classificar e organizar trabalhos submetidos por esses alunos e designar
trabalhos aos avaliadores, compilar e calcular resultados das avaliações feitas por
esses avaliadores.
- **Função necessária:** uma interface com gerenciamento dos trabalhos submetidos
com filtragem e categorização e um Sistema de distribuição automatizada com
notificações. Sistema de tabulação automática com geração de relatórios.
### Avaliação:
- **Usuários:** Avaliadores
- **Tarefa:** Avaliar trabalhos e inserir notas/comentários aos alunos.
- **Função necessária:** Interface de avaliação com campos para notas e
comentários.
### Divulgação dos resultados:
- **Usuários:** tanta pode ser alunos quanto avaliadores e administradores
- **Tarefa:** Acessar os resultados das avaliações submetidas .
- **Função necessária:** Página de resultados fácil e acessível ao usuário com opções de exportação a esses resultados .

## Storytelling

Há muito tempo, em um mundo acadêmico não tão distante, um dedicado organizador enfrentava um desafio épico. Seu nome era Marcos, e ele liderava a organização do SIMPAC, um prestigiado simpósio de produção acadêmica. A missão de Marcos era grandiosa: garantir que cada participante recebesse uma avaliação justa e rápida.

No entanto, o destino lhe impôs um obstáculo formidável. Cada processo avaliativo exigia horas intermináveis de trabalho manual, desde a separação dos projetos até o redirecionamento correto. E como se isso não bastasse, o cálculo das notas finais era uma tarefa hercúlea, consumindo não apenas o tempo de Marcos, mas também a paciência de todos os envolvidos.

Em meio a esse cenário desafiador, surge uma luz de esperança. Uma solução inovadora, construída com maestria em Design de Interação (UI) e Experiência do Usuário (UX), estava prestes a transformar a jornada de Marcos. Essa ferramenta revolucionária prometia aliviar o fardo do trabalho manual, trazendo eficiência e agilidade ao processo avaliativo.

Ao adotar essa solução, Marcos não apenas se libertou das amarras do trabalho tedioso, mas também se tornou uma verdadeira heroí na busca por resultados rápidos e justos. O SIMPAC, antes repleto de desafios, floresceu com uma entrega de resultados que deixou todos boquiabertos.

E assim, a história de Marcos e a ferramenta de Design de Interação se tornou um conto lendário no mundo acadêmico. O SIMPAC não era mais apenas um simpósio, mas sim um exemplo vivo de como a inovação, aliada ao design inteligente, pode transformar desafios em triunfos.

No final, Marcos não era apenas um organizador; ela se tornou uma verdadeiro guardião da eficiência, mostrando que, com a ferramenta certa, até mesmo os desafios mais formidáveis podem ser superados. E assim, a cada SIMPAC subsequente, a lembrança da jornada de Marcos continuava a inspirar e guiar aqueles que buscavam a excelência na produção acadêmica.

## Stakeholders

- Gestores/Organizadores do SIMPAC
- Avaliadores e Grupos Avaliados
- Público Afetado pelos Resultados

## Personas

Baseado no storytelling, as personas foram criadas para representar os stakeholders.

<div align="center">
    <img src="./Imagens/Persona-1_page-0001.jpg" style="width:1280px; height:720px"/>
    <p>Figura 2 - Persona do Marcos Silva</p>
    <img src="./Imagens/Persona-1_page-0002.jpg" style="width:1280px; height:720px"/>
    <p>Figura 3 - Persona da Luana Pereira</p>
</div>

## Mapa de Empatia

Para entender melhor as necessidades dos stakeholders, utilizamos o mapa de empatia, assim tivemos uma visão de onde focar nossos estudos para criarmos uma solução de agrado a todos.

<div align="center">
    <img src="./Imagens/Mapa_de_Empatia_1.pdf.png" style="width:1280px; height:720px"/>
    <p>Figura 3 - Mapa de Empatia do Marcos Silva</p>
    <img src="./Imagens/Mapa_de_Empatia_2.pdf.png" style="width:1280px; height:720px"/>
    <p>Figura 4 - Mapa de Empatia da Luana Pereira</p>
</div>

<h1 id="requisitos">Especificação de Requisitos</h1>

## Objetivos do Projeto

O principal objetivo desse projeto é entregar a melhor experiência possível para os administradores e avaliadores dos trabalhos, tornando o evento do SIMPAC mais dinâmico e organizado. Mas não só isso, também focamos em entregar uma aplicação que esteja disponível para que os mais diversos usuários possam desfrutar dos trabalhos entregues pelos alunos, seja por curiosidade, por fins acadêmicos ou até mesmo para inspiração.

## Desafio

- Garantir a atribuição equitativa, eficiente e apropriada de avaliadores para os trabalhos, levando em consideração a disponibilidade de cada um.
- Agilizar a coleta e o processamento das notas de forma mais automatizada.
- Assegurar a justiça e imparcialidade nas avaliações, mantendo a qualidade.
- Gerenciar uma alta carga de trabalho, incluindo a avaliação simultânea de múltiplos trabalhos.

## Prototipação

Link para o protótipo no Figma:
https://www.figma.com/file/3RcvZjYx66Hn4ibVR8qiTA/SIMPAC-PROJETO?type=design&node-id=0%3A1&mode=design&t=T04ho3tIh2vIzivS-1

<h2 id="projeto_conceitual">Projeto Conceitual e Especificaçao do Design</h2>

## Fluxograma

- Foi organizado um fluxograma para orgarnizar as informações, identificar ações que podem ser feitas para os objetivos da organização ou avaliador.

<div align="center">
    <img src="./Imagens/Fluxograma%20SIMPAC.png" style="width:1280px; height:740px"/>
    <p>Figura 5 - Fluxograma do Sistema</p>
</div>


## Wireframe

A partir do fluxograma, foi criado então o wireframe, que é uma representação visual básica e esquemática da estrutura de nossa aplicação web. Seu objetivo principal pe definir a distribuição de elementos da natela, sem se preocupar muito com detalhes visuais.

- Pela tela inicial será possível observar informações como em qual edição o evento se encontra. E qual caminho o usuario gostaria de seguir.
- Para todas escolhas elas serão necessárias um login para confirmar a identidade porém alguns podem ser organizadores e terão um maior nível de acesso.
- O administrador poderá criar os trabalhos para serem avaliados, alterar eles caso tenham cometido erros ou até mesmo apagar, conferir os resultados, checar os avaliadores cadastrados além de poder adicionar ou excluir caso seja necessário.
-  O Avaliador quando terminar suas avaliações lhe será mostrado uma tabela com informações de seus votos e caso o mesmo queira trocar ele terá a oportunidade.
- Para os resultados, que serão disponíveis apenas à organização do evento, lhe será disposto um login e ao entrar, basta escolher o curso que deseja olhar no momento, e será mostrado uma tabela com as notas tanto em poster quanto apresentações orais.

![Wireframe](./Imagens/Wireframe.png)

<h1 id="implementacao">Implementação</h1>

Essa fase será feita no próximo semestre, nas disciplinas de **Arquitetura de Software** e **Projeto de Sistemas para Internet**, por questões de complexidade do projeto.

<h1 id="conclusao">Conclusão</h1>

A aplicação se encontra na metade do caminho, temos uma boa base de requisitos já definidos e validados, protótipos de baixo e de médio nível, como também, um de alto nível muito dinâmico e intuitivo. Também temos nossas personas, mapas de empatia e fluxograma.

Para nossa próxima etapa, iremos refinar tudo que já fizemos até então, através de levantamentos de requisitos de baixo nível, de testes, re-design se preciso, entre outros métodos. Também criaremos uma documentação mais detalhada, tudo para facilitar a etapa final que é a implementação. Mais detalhes do protótipo se
encontra no link: https://github.com/ViniFontes73/ProjetoSIMPAC