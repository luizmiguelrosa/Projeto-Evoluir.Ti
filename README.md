<h1 align="center">Projeto – Evoluir.Ti</h1>

<div align="center">
    <img src="./Imagens/Logo_Atomic_Code.jpeg" style="width:480px; height:480px"/>
</div>

# Sumário

- <a href="#introducao">Introdução</a>
- <a href="#ciclo_vida">Ciclo de Vida</a>
- <a href="#analise_de_tarefas">Análise de Tarefas, Usuário e Funções</a>
- <a href="#requisitos">Engenharia de Requisitos</a>
- <a href="#projeto_conceitual">Projeto Conceitual e Especificaçao do Design</a>
- <a href="#prototipacao">Prototipação</a>
- <a href="#implementacao">Implementação</a>
- <a href="#conclusao">Conclusão</a>

<h1 id="introducao">1. Introdução</h1>

É um projeto idealizado para solucionar os desafios na hora da avaliação dos trabalhos dos alunos da Univiçosa durante o Simpósio de Produção Acadêmica - SIMPAC. Dentre os desafios, está a automatização da organização de projetos, otimização do tempo e a melhora da entrega dos resultados. De acordo com a demanda proposta pela CEO da NUPEX (Núcleo de Apoio à Pesquisa e Extensão da Univiçosa) Eliene da Silva Martins Viana, o que antes era feito no papel, agora terá que ser implementado em uma aplicação web responsiva que estará disponível para dispositivos móveis e também para desktops.

Pela grande falta de praticidade na hora das avaliações e por terem que entregar uma folha preenchida com cada grupo para cada avaliador, nossa aplicação será de uma grande ajuda, visto que ela automatizará toda essa questão de gestão de trabalhos e suas respectivas notas, o que poupará tempo e dinheiro.

<h1 id="ciclo_vida">2. Ciclo de Vida</h1>

Um modelo de ciclo de vida nas atividades de design de interfaces é um
framework ou abordagem que descreve as etapas pelas quais um projeto de
interface passa, desde o conceito inicial até a implementação e manutenção.
Ele fornece uma estrutura para os designers seguirem e ajuda a garantir que
todos os aspectos do design sejam considerados e tratados adequadamente
ao longo do processo. O modelo utilizado no projeto Evoluir.Ti foi o Modelo
Estrela (Hartson e Hix, 1989).

## 2.1. Modelo Estrela

O modelo estrela de design de interfaces, também conhecido como “Star Model”, é um modelo de ciclo de vida com uma abordagem que visa criar interfaces de usuário eficazes e centradas no usuário. Este modelo é chamado assim devido à sua estrutura central, que é cercada por cinco componentes principais, semelhantes aos raios de estrela.

<div align="center">
    <img src="./Imagens/Ciclo_de_Vida.png" style="width:600px; height:480px"/>
    <p>Figura 1 - Modelo de Ciclo de Vida Estrela</p>
</div>

<h1 id="analise_de_tarefas">3. Análise de Tarefas, Usuário e Funções</h1>

## 3.1. Cenário Atual

Atualmente, o processo de avaliação e entrega do SIMPAC é realizado de forma manual. Este processo envolve a coleta de avaliações dos trabalhos acadêmicos em formato de papel. Tal abordagem resulta em alguns problemas:
1. **Erros Humanos:** A manipulação manual dos documentos aumenta a probabilidade de erros, tanto na coleta quanto na avaliação dos trabalhos.
2. **Ineficiente e Demorado:** A necessidade de lidar com documentos físicos torna o processo lento e ineficiente, causando atrasos significativos e dificultando a gestão das avaliações.
3. **Precisão dos Resultados:** A precisão dos resultados é comprometida, uma vez que a natureza manual do processo aumenta a possibilidade de erros e inconsistências na avaliação dos trabalhos.

## 3.2 Análise de Tarefas

Para transformar o processo manual em uma aplicação web responsiva, é necessário
identificar e analisar cada tarefa envolvida.

### 3.2.1. Submissão dos trabalhos:
- **Usuários:** Alunos
- **Tarefa:** Submeter trabalhos acadêmicos via plataforma online.
- **Função necessária:** Formulário de submissão com suporte a uploads de arquivos.
### 3.2.2. Organização dos trabalhos:
- **Usuários:** Administradores
- **Tarefa:** Classificar e organizar trabalhos submetidos por esses alunos e designar
trabalhos aos avaliadores, compilar e calcular resultados das avaliações feitas por
esses avaliadores.
- **Função necessária:** uma interface com gerenciamento dos trabalhos submetidos
com filtragem e categorização e um Sistema de distribuição automatizada com
notificações. Sistema de tabulação automática com geração de relatórios.
### 3.2.3. Avaliação:
- **Usuários:** Avaliadores
- **Tarefa:** Avaliar trabalhos e inserir notas/comentários aos alunos.
- **Função necessária:** Interface de avaliação com campos para notas e
comentários.
### 3.2.4. Divulgação dos resultados:
- **Usuários:** tanta pode ser alunos quanto avaliadores e administradores
- **Tarefa:** Acessar os resultados das avaliações submetidas .
- **Função necessária:** Página de resultados fácil e acessível ao usuário com opções de exportação a esses resultados .

## 3.3. Storytelling

Há muito tempo, em um mundo acadêmico não tão distante, um dedicado organizador enfrentava um desafio épico. Seu nome era Marcos, e ele liderava a organização do SIMPAC, um prestigiado simpósio de produção acadêmica. A missão de Marcos era grandiosa: garantir que cada participante recebesse uma avaliação justa e rápida.

No entanto, o destino lhe impôs um obstáculo formidável. Cada processo avaliativo exigia horas intermináveis de trabalho manual, desde a separação dos projetos até o redirecionamento correto. E como se isso não bastasse, o cálculo das notas finais era uma tarefa hercúlea, consumindo não apenas o tempo de Marcos, mas também a paciência de todos os envolvidos.

Em meio a esse cenário desafiador, surge uma luz de esperança. Uma solução inovadora, construída com maestria em Design de Interação (UI) e Experiência do Usuário (UX), estava prestes a transformar a jornada de Marcos. Essa ferramenta revolucionária prometia aliviar o fardo do trabalho manual, trazendo eficiência e agilidade ao processo avaliativo.

Ao adotar essa solução, Marcos não apenas se libertou das amarras do trabalho tedioso, mas também se tornou uma verdadeira heroí na busca por resultados rápidos e justos. O SIMPAC, antes repleto de desafios, floresceu com uma entrega de resultados que deixou todos boquiabertos.

E assim, a história de Marcos e a ferramenta de Design de Interação se tornou um conto lendário no mundo acadêmico. O SIMPAC não era mais apenas um simpósio, mas sim um exemplo vivo de como a inovação, aliada ao design inteligente, pode transformar desafios em triunfos.

No final, Marcos não era apenas um organizador; ela se tornou uma verdadeiro guardião da eficiência, mostrando que, com a ferramenta certa, até mesmo os desafios mais formidáveis podem ser superados. E assim, a cada SIMPAC subsequente, a lembrança da jornada de Marcos continuava a inspirar e guiar aqueles que buscavam a excelência na produção acadêmica.

## 3.4. Stakeholders

- Gestores/Organizadores do SIMPAC
- Avaliadores e Grupos Avaliados
- Público Afetado pelos Resultados

## 3.5. Personas

Baseado no storytelling, as personas foram criadas para representar os stakeholders.

<div align="center">
    <img src="./Imagens/Persona-1_page-0001.jpg" style="width:1280px; height:568px"/>
    <p>Figura 2 - Persona do Marcos Silva</p>
    <img src="./Imagens/Persona-1_page-0002.jpg" style="width:1280px; height:568px"/>
    <p>Figura 3 - Persona da Luana Pereira</p>
</div>

## 3.6. Mapa de Empatia

Para entender melhor as necessidades dos stakeholders, utilizamos o mapa de empatia, assim tivemos uma visão de onde focar nossos estudos para criarmos uma solução de agrado a todos.

<div align="center">
    <img src="./Imagens/Mapa_de_Empatia_1.pdf.png" style="width:1280px; height:720px"/>
    <p>Figura 4 - Mapa de Empatia do Marcos Silva</p>
    <img src="./Imagens/Mapa_de_Empatia_2.pdf.png" style="width:1280px; height:720px"/>
    <p>Figura 5 - Mapa de Empatia da Luana Pereira</p>
</div>

<h1 id="requisitos">4. Engenharia de Requisitos</h1>

## 4.1. Especificação de Requisitos

### 4.1.1. Elicitação de Requisitos

<hr>

Em uma reunião virtual em 4 de outubro de 2023, liderada pelo PO Vinicius Fontes, foram levantados os requisitos para o projeto da Atomic Code. A cliente destacou a necessidade de automatizar o processo manual de avaliação do SIMPAC, tornando-o mais simples e rápido. Decidiu-se criar uma prototipagem de uma aplicação web acessível por celular durante as avaliações, em vez de um aplicativo completo. A reunião esclareceu dúvidas e definiu um direcionamento para a primeira prototipagem.

### 4.1.2. Análise de Requisitos

<hr>

#### Atores
- Administrador
- Avaliador
- Usuário

#### Casos de Uso

- [Diagrama de Caso de Uso](./Imagens/Diagrama%20de%20Caso%20de%20Uso.pdf)

**Efetuar Login**
- Ator Principal: Usuário
- Descrição: Permite que o usuário faça login no sistema.
- Inclui: Verificar Senha
- Cenário Alternativo: Exibir Erro de Login

**Verificar Senha**
- Ator Principal: Sistema (sub-caso de Efetuar Login)
- Descrição: Verifica se a senha fornecida está correta.
- Extende: Exibir Erro de Login

**Exibir Erro de Login**
- Ator Principal: Sistema (sub-caso de Verificar Senha)
- Descrição: Exibe uma mensagem de erro se a senha estiver incorreta.
- Extendido por: Verificar Senha

**Recuperar Senha**
- Ator Principal: Usuário
- Descrição: Permite ao usuário recuperar a senha esquecida.
- Extende: Verificar Senha

**Filtrar Resultados**
- Ator Principal: Usuário
- Descrição: Permite que o usuário filtre os resultados apresentados pelo sistema.

**Visualizar Trabalhos**
- Ator Principal: Usuário
- Descrição: Permite ao usuário visualizar os trabalhos disponíveis no sistema.

**Gerenciar Trabalhos**
- Ator Principal: Administrador
- Descrição: Permite que o administrador gerencie os trabalhos no sistema.

**Gerenciar Usuários**
- Ator Principal: Administrador
- Descrição: Permite que o administrador gerencie os usuários do sistema.

**Atribuir Papel ao Avaliador**
- Ator Principal: Administrador
- Descrição: Permite que o administrador atribua o papel de avaliador a um usuário.

### 4.1.3. Objetivos do Projeto

<hr>

O principal objetivo desse projeto é entregar a melhor experiência possível para os administradores e avaliadores dos trabalhos, tornando o evento do SIMPAC mais dinâmico e organizado. Mas não só isso, também focamos em entregar uma aplicação que esteja disponível para que os mais diversos usuários possam desfrutar dos trabalhos entregues pelos alunos, seja por curiosidade, por fins acadêmicos ou até mesmo para inspiração.

### 4.1.4. Desafio

<hr>

- Garantir a atribuição equitativa, eficiente e apropriada de avaliadores para os trabalhos, levando em consideração a disponibilidade de cada um.
- Agilizar a coleta e o processamento das notas de forma mais automatizada.
- Assegurar a justiça e imparcialidade nas avaliações, mantendo a qualidade.
- Gerenciar uma alta carga de trabalho, incluindo a avaliação simultânea de múltiplos trabalhos.

### 4.1.5. Avaliação da Engenharia de Requisitos

<hr>

#### Requisitos de Alto Nível

##### 1. Aplicação web separada do site da Univiçosa

<blockquote>
<u><b>Consistência e Padrões</b></u>

**Avaliação:** Mantém a consistência com a marca, o que ajuda na identificação e confiança do usuário. A separação clara pode fortalecer a identidade da aplicação, mas deve garantir que elementos essenciais de branding sejam mantidos.<br>
**Sugestão:** Certificar-se de que os elementos visuais e a linguagem da marca Univiçosa sejam incorporados na nova aplicação para manter a consistência.
</blockquote>

<blockquote>
<u><b>Reconhecimento em vez de memorização</b></u>

**Avaliação:** A separação pode facilitar o reconhecimento do sistema como uma entidade distinta, mas pode exigir que os usuários aprendam uma nova interface.<br>
**Sugestão:** Minimizar a curva de aprendizado utilizando ícones e terminologias familiares aos usuários do site principal.
</blockquote>

##### 2. Uma área para os avaliadores, administrador e usuários comuns (Alunos e demais participantes)

<blockquote>
<u><b>Flexibilidade e Eficiência de Uso</b></u>

**Avaliação:** Facilita a personalização da experiência do usuário de acordo com suas necessidades específicas.<br>
**Sugestão:** Implementar configurações personalizáveis para diferentes tipos de usuários para aumentar a eficiência de uso.
</blockquote>

<blockquote>
<u><b>Controle e Liberdade do Usuário</b></u>

**Avaliação:** Usuários sabem claramente onde devem acessar suas áreas específicas, reduzindo a possibilidade de erro.<br>
**Sugestão:** Utilizar menus e navegações claras para separar as áreas de cada tipo de usuário, garantindo fácil acesso e minimização de erros.
</blockquote>

##### 3. Paleta de cores igual ao do site da Univiçosa

<blockquote>
<u><b>Estética e Design Minimalista</b></u>

**Avaliação:** A uniformidade nas cores mantém a interface limpa e familiar, ajudando na navegabilidade e na estética geral.<br>
**Sugestão:** Manter a paleta de cores consistente, mas explorar variações para destacar seções ou funcionalidades importantes.
</blockquote>

<hr>

#### Administrador

##### 4. Gestão de Trabalhos

<blockquote>
<u><b>Visibilidade do Status do Sistema</b></u>

**Avaliação:** É importante que o administrador tenha feedback claro sobre o status das operações (e.g., sucesso ou erro ao cadastrar um trabalho).<br>
**Sugestão:** Implementar mensagens de confirmação e alertas visuais claros após cada operação.
</blockquote>

<blockquote>
<u><b>Prevenção de Erros</b></u>

**Avaliação:** Formular validações de dados ajudam a evitar erros de entrada.<br>
**Sugestão:** Utilizar validações em tempo real e fornecer feedback imediato sobre erros nos formulários.
</blockquote>

##### 5. Administração de Usuário

<blockquote>
<u><b>Controle e Liberdade do Usuário</b></u>

**Avaliação:** Administradores devem ter a capacidade de desfazer ações (e.g., confirmação ao excluir um usuário).<br>
**Sugestão:** Incluir funcionalidades de desfazer e confirmações para ações críticas.
</blockquote>

<blockquote>
<u><b>Flexibilidade e Eficiência de Uso</b></u>

**Avaliação:** Interfaces de gerenciamento devem ser eficientes para admins experientes, com atalhos e operações rápidas.<br>
**Sugestão:** Prover atalhos de teclado e operações em massa para aumentar a eficiência administrativa.
</blockquote>

##### 6. Histórico de Trabalhos

<blockquote>
<u><b>Visibilidade do Status do Sistema</b></u>

**Avaliação:** O histórico deve ser fácil de acessar e deve fornecer feedback claro sobre a visualização dos dados.<br>
**Sugestão:** Incluir filtros e opções de busca para facilitar a navegação no histórico.
</blockquote>

<hr>

#### Avaliadores

##### 7. Dashboard de Avaliação

<blockquote>
<u><b>Consistência e Padrões</b></u>

**Avaliação:** Painéis personalizados devem seguir padrões de design consistentes para facilitar o uso.<br>
**Sugestão:** Utilizar uma estrutura de layout consistente com componentes reutilizáveis.
</blockquote>

<blockquote>
<u><b>Reconhecimento em vez de Memorização</b></u>

**Avaliação:** Critérios de avaliação e prazos devem ser visíveis e claros, evitando a necessidade de memorização.<br>
**Sugestão:** Destacar informações importantes em locais visíveis e de fácil acesso.
</blockquote>

##### 8. Visualização de Trabalhos

<blockquote>
<u><b>Visibilidade do Status do Sistema</b></u>

**Avaliação:** Detalhes dos trabalhos devem ser claros e acessíveis.<br>
**Sugestão:** Utilizar layouts organizados e clareza na apresentação dos detalhes dos trabalhos.
</blockquote>

<blockquote>
<u><b>Prevenção de Erros</b></u>

**Avaliação:** Facilitar a navegação e a visualização correta das informações dos trabalhos atribuídos.<br>
**Sugestão:** Incluir verificações de consistência e navegação intuitiva.
</blockquote>

##### 9. Registro de Avaliações

<blockquote>
<u><b>Flexibilidade e Eficiência de Uso</b></u>

**Avaliação:** Formulários de avaliação devem ser intuitivos e eficientes para permitir avaliações rápidas e precisas.<br>
**Sugestão:** Utilizar formulários dinâmicos e com feedback imediato para entradas.
</blockquote>

<blockquote>
<u><b>Reconhecimento em vez de Memorização</b></u>

**Avaliação:** Comentários e notas devem ser facilmente registráveis e editáveis.<br>
**Sugestão:** Incluir opções de edição rápida e salvar automaticamente rascunhos de avaliações.
</blockquote>

##### 10. Comunicação com Organizadores

<blockquote>
<u><b>Ajuda e Documentação</b></u>

**Avaliação:** Disponibilizar um meio de comunicação direto ajuda na resolução de problemas e dúvidas.<br>
**Sugestão:** Implementar chat de suporte ou sistema de tickets com resposta rápida.
</blockquote>

<hr>

#### Usuários Comuns

##### 11. Visualização de Trabalhos

<blockquote>
<u><b>Reconhecimento em vez de Memorização</b></u>

**Avaliação:** Navegação e visualização de trabalhos devem ser intuitivas, com informações importantes facilmente acessíveis.<br>
**Sugestão:** Implementar uma interface de usuário limpa e intuitiva, com acesso rápido às informações relevantes.
</blockquote>

##### 12. Funcionalidades Sociais (opcional)

<blockquote>
<u><b>Flexibilidade e Eficiência de Uso</b></u>

**Avaliação:** Recursos sociais devem ser opcionais e não devem interferir com as funções principais do sistema.<br>
**Sugestão:** Incluir opções de ativar/desativar funcionalidades sociais conforme a preferência do usuário.
</blockquote>

<blockquote>
<u><b>Ajuda e Documentação</b></u>

**Avaliação:** Incluir guias para uso de funcionalidades sociais pode ajudar usuários que não estejam familiarizados com elas.<br>
**Sugestão:** Disponibilizar tutoriais e FAQs para guiar os usuários no uso dessas funcionalidades.
</blockquote>

##### 13. Busca Avançada e Filtros

<blockquote>
<u><b>Estética e Design Minimalista</b></u>

**Avaliação:** A busca avançada deve ser clara e fácil de usar, com resultados atualizados dinamicamente conforme os filtros são aplicados.<br>
**Sugestão:** Implementar uma interface de busca simples com filtros visíveis e fáceis de aplicar.
</blockquote>

<blockquote>
<u><b>Consistência e Padrões</b></u>

**Avaliação:** Filtros e critérios de busca devem ser consistentes e intuitivos.<br>
**Sugestão:** Manter uma estrutura padronizada para os filtros e opções de busca, facilitando o reconhecimento e uso eficiente.
</blockquote>

<h1 id="projeto_conceitual">5. Projeto Conceitual e Especificaçao do Design</h1>

## 5.1. Fluxograma

Foi organizado um fluxograma para orgarnizar as informações, identificar ações que podem ser feitas para os objetivos da organização ou avaliador.

![Wireframe](./Imagens/Fluxograma%20SIMPAC.png)
<div align="center">
    <p>Figura 6 - Fluxograma do Sistema</p>
</div>


## 5.2. Wireframe

A partir do fluxograma, foi criado então o wireframe, que é uma representação visual básica e esquemática da estrutura de nossa aplicação web. Seu objetivo principal pe definir a distribuição de elementos da natela, sem se preocupar muito com detalhes visuais.

- Pela tela inicial será possível observar informações como em qual edição o evento se encontra. E qual caminho o usuario gostaria de seguir.
- Para todas escolhas elas serão necessárias um login para confirmar a identidade porém alguns podem ser organizadores e terão um maior nível de acesso.
- O administrador poderá criar os trabalhos para serem avaliados, alterar eles caso tenham cometido erros ou até mesmo apagar, conferir os resultados, checar os avaliadores cadastrados além de poder adicionar ou excluir caso seja necessário.
-  O Avaliador quando terminar suas avaliações lhe será mostrado uma tabela com informações de seus votos e caso o mesmo queira trocar ele terá a oportunidade.
- Para os resultados, que serão disponíveis apenas à organização do evento, lhe será disposto um login e ao entrar, basta escolher o curso que deseja olhar no momento, e será mostrado uma tabela com as notas tanto em poster quanto apresentações orais.

![Wireframe](./Imagens/Wireframe.png)

<h1 id="prototipacao">6. Prototipação</h1>

O protótipo desenvolvido está disponível para acesso através do nosso <a href="https://www.figma.com/proto/3RcvZjYx66Hn4ibVR8qiTA/SIMPAC-PROJETO?node-id=61-1171&scaling=contain&content-scaling=fixed">protótipo interativo</a>. Este protótipo foi criado utilizando a plataforma Figma, permitindo que qualquer pessoa possa testar e interagir com a interface que projetamos. Ao acessar o link, os usuários terão a oportunidade de explorar as funcionalidades e o layout da nossa aplicação de forma intuitiva e prática.

<h1 id="implementacao">7. Implementação</h1>

Essa fase será feita no próximo semestre, nas disciplinas de **Arquitetura de Software** e **Projeto de Sistemas para Internet**, por questões de complexidade do projeto.

<h1 id="conclusao">8. Conclusão</h1>

A aplicação se encontra na metade do caminho, temos uma boa base de requisitos já definidos e validados, protótipos de baixo e de médio nível, como também, um de alto nível muito dinâmico e intuitivo. Também temos nossas personas, mapas de empatia e fluxograma.

Para nossa próxima etapa, iremos refinar tudo que já fizemos até então, através de levantamentos de requisitos de baixo nível, de testes, re-design se preciso, entre outros métodos. Também criaremos uma documentação mais detalhada, tudo para facilitar a etapa final que é a implementação. Mais detalhes do protótipo se
encontra no link: https://github.com/ViniFontes73/ProjetoSIMPAC
