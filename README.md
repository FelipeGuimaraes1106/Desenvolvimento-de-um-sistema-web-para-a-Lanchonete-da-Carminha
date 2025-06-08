
# Termo de Requisitos de Alto Nível

## Desenvolvimento de um sistema Web para a Lanchonete da Carminha

<p align="center"><img src= "/Imagens/Logo.png"></p>

<p align="center"> Figura 1 - Logo da empresa</p>

## INDRODUÇÃO

Este projeto tem como propósito criar e prototipar um sistema de software responsivo para a Lanchonete da Carminha, visando facilitar o gerenciamento de pedidos em dispositivos móveis e computadores. A iniciativa tem como meta digitalizar e automatizar as encomendas, tornando o processo mais eficiente e organizado, beneficiando tanto os clientes quanto a administração interna do estabelecimento .


## DESAFIO

O principal desafio é criar um sistema de software responsivo para a Lanchonete da Carminha, que funcione perfeitamente tanto em smartphones quanto em computadores, garantindo uma gestão eficiente dos pedidos. Para alcançar esse objetivo, algumas etapas são essenciais:
**Entender as Necessidades**
 É crucial realizar uma análise detalhada das demandas específicas da lanchonete, garantindo que as funcionalidades indispensáveis para o gerenciamento de encomendas sejam contempladas. Isso inclui traduzir requisitos gerais em especificações técnicas claras, que servirão como base para o desenvolvimento do sistema.
 
**Aperfeiçoar o Protótipo**
O protótipo inicial precisa ser ajustado para oferecer uma experiência de uso simples e prática. Isso demanda testes de usabilidade, coleta de opiniões de todas as partes envolvidas e melhorias contínuas, assegurando que a solução atenda às expectativas dos usuários finais.

**Planejar a Evolução do Sistema**
 O projeto deve ser pensado de forma a acompanhar as mudanças no mercado e as novas necessidades da lanchonete. Isso envolve a criação de um planejamento estratégico, com marcos bem definidos e uma organização eficiente dos recursos, garantindo que o sistema continue evoluindo e entregando valor com o tempo.
 
Em resumo, o desafio é desenvolver uma solução prática e fácil de usar, aperfeiçoar o protótipo por meio de análises e ajustes constantes, e assegurar que o sistema esteja preparado para crescer junto com as demandas da Lanchonete da Carminha
.

## CONTEXTO

Hoje, não é segredo, muito menos exagero, dizer que os aplicativos de celulares
já fazem parte do dia a dia das pessoas. A adoção de ferramentas digitais no
empreendimento se tornou fundamental para o sucesso de empresas, especialmente em setores como alimentação e serviços. Segundo dados da [App Annie](https://www.digitalinformationworld.com/2022/01/app-annie-publishes-data-revealing.html), o tempo médio diário que as pessoas passam em aplicativos de celular cresceu 30% entre 2020 e 2021. Além disso, uma pesquisa da [Think with Google](https://www.thinkwithgoogle.com/marketing-strategies/app-and-mobile/mobile-app-marketing-insights/) revelou que 89% dos consumidores utilizam aplicativos móveis para interagir com empresas.

As encomendas de cento de salgados para eventos e festividades são uma das
principais fontes de lucro da Lanchonete Da Carminha. Porém, a ausência de
um sistema automatizado tem gerado desafios, como interrupções no atendimento
durante horários de pico (das 17h às 19h), falhas na coleta de informações e dificuldade no
controle e monitoramento dos pedidos, comprometendo a eficiência e a satisfação
dos clientes. Dessa forma, um sistema de gerenciamento de
pedidos para a Lanchonete Da Carminha proporcionaria diversas vantagens,
tais como:

**Facilidade de acesso:**
  > Assim como plataformas do ramo, como
  > [Jhon's Pizza](https://www.instagram.com/johnspizzaoficial/?hl=pt) e [Mais Pizza Delivey](https://pedir.delivery/app/maispedidosdelivery/menu),
  > utilizam aplicativos para melhorar a experiência
  > do usuário, a implementação de um sistema próprio garantiria
  > navegação rápida e intuitiva.

**Fidelização de clientes:**
  > O sistema pode ser configurado para coletar dados e mapear
  > o comportamento dos clientes, permitindo a criação de
  > campanhas personalizadas que aumentam a fidelidade e a retenção.

**Aumento da credibilidade e reconhecimento da marca:**
  > Um aplicativo próprio gera confiança nos consumidores
  > e melhora a visibilidade no mercado, criando uma imagem
  > mais sólida e confiável da empresa.

Além disso, o uso de tecnologia para automação dos processos internos,
como controle de estoque e geração de relatórios, pode **aumentar a
produtividade e otimizar a gestão da lanchonete**. Soluções como essas
são essenciais para manter a competitividade e se adaptar às demandas do
consumidor moderno, que busca conveniência e agilidade no atendimento.

## CICLO DE VIDA
O modelo estrela (ou Star Model) é uma abordagem iterativa e centrada no usuário para o ciclo de vida do desenvolvimento de software. Ele prioriza a flexibilidade e a adaptação contínua às necessidades e feedbacks dos usuários ao longo do processo de desenvolvimento. Esse modelo é particularmente eficaz em projetos com requisitos dinâmicos ou em que a validação constante com os usuários é essencial para o sucesso do sistema. Ao promover um desenvolvimento ágil e adaptativo, o modelo estrela se alinha às práticas modernas de engenharia de software e ao desenvolvimento centrado no usuário, garantindo que o produto final atenda de forma eficaz às expectativas e necessidades dos stakeholders.

<p align="center"><img src= "/Imagens/Ciclo_Vida_Estrela.png"></p>

## WHY?

### QUEM UTILIZARÁ O SISTEMA?

Considerando o contexto da Zona da Mata de Minas Gerais, com foco na
microrregião de Viçosa, os **potenciais usuários** do sistema incluem
principalmente os moradores das cidades de Viçosa, Ervália e Teixeiras,
conforme indicado pela cliente. No entanto, há a possibilidade de que o
aplicativo seja adotado também pelos habitantes das outras 12 cidades
que compõem a região.

Em uma análise mais precisa, baseada no repertório dos usuários do
estabelecimento, discutido com a proprietária da Lanchonete Da Carminha,
os **principais perfis** encontrados são organizadores de eventos e
responsáveis por lares que residem em Teixeiras ou Viçosa. Moradores que
organizam eventos, como aniversários, casamentos ou confraternizações,
tendem a buscar soluções práticas e saborosas que atendam suas
necessidades de forma eficiente.

### QUAIS SERIAM OS PROBLEMAS?

Com base na identificação dos perfis, bem como dos potenciais usuários,
estima-se que a maioria possua um **conhecimento técnico em informática de nível básico a intermediário**, o que pode gerar desafios relacionados
à usabilidade, como dificuldade de navegação e entendimento de funcionalidades
mais complexas. Esses fatores exigem que o desenvolvimento do aplicativo
siga rigorosamente as melhores práticas de *UX/UI* (Experiência e Interface
do Usuário), garantindo uma interface intuitiva, acessível e de fácil aprendizado.

Outro possível problema é a **diversidade de dispositivos utilizados
pelos usuários**, que podem variar entre *smartphones* mais modernos e
modelos antigos, o que demanda uma aplicação responsiva e eficiente em
diferentes plataformas e tamanhos de tela.

Além disso, é importante considerar possíveis **dificuldades
relacionadas à conectividade à internet em áreas menos urbanizadas** da
região, o que reforça a necessidade de otimização de performance para
minimizar o consumo de dados e garantir o funcionamento adequado mesmo
em redes de baixa velocidade.

### STORYTELLING

Era uma tarde de uma sexta-feira movimentada na Lanchonete Da Carminha. O sol forte da
cidade marcava o fim de mais um dia típico de funcionamento do estabelecimento, que abre
de segunda-feira a sábado, das 9h às 21h. Entre 17h e 19h, o horário de pico, dezenas
de pessoas lotam a lanchonete. Felipe, o atendente mais experiente, já estava
acostumado com o frenesi, mas sabia que aquele período sempre reservava surpresas. Na mesa
do fundo, uma pessoa fazia uma encomenda para um aniversário, enquanto na fila de espera
outros discutiam quais salgados da prateleira escolheriam para comer. Tudo corria como
de costume até que o **WhatsApp começou a disparar sem parar**.

Mensagens e chamadas de novos pedidos pipocavam em sequência. **O número crescente de solicitações se misturava com as ordens feitas
presencialmente**. Felipe, correndo entre a cozinha e o balcão, tentava
gerenciar todas as demandas, mas algo estava saindo de controle. \"Você
confirmou aquele pedido de cento de coxinhas?\", questionou Carminha, a
dona da lanchonete, com uma mistura de urgência e preocupação. \"Acho
que sim\", respondeu Felipe, enquanto tentava lembrar qual cliente havia
feito o pedido.

O telefone tocava, mais uma mensagem chegava, e a fila não parava de
crescer. O bloco de anotações de Felipe não tinha mais utilidade. A
escrita apressada, inelegível para ele mesmo, começou a gerar uma confusão de informações. Muitas pessoas aguardavam mais do que o normal (acima de 15 minutos), e
alguns saíam visivelmente irritados. **Ele sabia que a qualidade do
atendimento estava comprometida, mas o que ele poderia fazer?**

Enquanto Felipe se desdobrava para não deixar ninguém esperando, **um
erro grave aconteceu:** o pedido de salgados para um casamento foi trocado com o de um aniversário. O pior de tudo? Ambos já haviam
deixado o estabelecimento, sem deixar nenhum número para contato,
confiando apenas no acordo verbal de que retornariam no dia combinado
para buscar suas encomendas.

\"Nunca deveria ter acontecido isso!\", exclamou Carminha, desesperada
ao perceber a gravidade da situação. Ela se sentia perdida, sem saber
por onde começar a resolver o problema. O **caos de gerenciar tudo
manualmente estava cobrando seu preço**, e a falta de controle sobre os
pedidos só tornava as coisas mais difíceis. Felipe, mesmo dando seu
melhor, começava a perceber que o processo, repleto de falhas e
improvisos, estava desmoronando lentamente, como uma barragem prestes a
ruir.  

Foi então que a ideia de um sistema automatizado brilhou na mente de
Carminha. \"Se houvesse uma maneira de centralizar esses pedidos,
organizar tudo sem depender de bilhetes, anotações e mensagens
confusas\... talvez pudéssemos evitar isso no futuro\", pensou ela,
observando o caos crescente. E Felipe, ainda que cansado, concordava
silenciosamente. **O sistema de gerenciamento de pedidos não era mais
uma opção, era uma necessidade**.

Com o **sistema de gerenciamento de pedidos** que será implementado,
Felipe e Carminha esperam finalmente organizar as solicitações de maneira
clara e eficiente. A ideia é que todas as solicitações de pedidos cheguem
diretamente pelo sistema, eliminando a necessidade de lidar com bilhetes,
anotações confusas e mensagens dispersas. Isso também deverá evitar a
interrupção do fluxo de atividades presenciais por ligações, trazendo mais
tranquilidade ao atendimento e melhorando a qualidade do serviço.

Além disso, a interface planejada para o sistema será simples e acessível,
permitindo uma **experiência descomplicada tanto para os funcionários do
estabelecimento quanto para os usuários**. A expectativa é que o novo processo
de efetuar pedidos seja ágil e intuitivo, otimizando a gestão interna e
fortalecendo a fidelidade dos clientes que valorizam uma abordagem prática
e eficiente.

A implementação do sistema será um passo essencial para o **funcionamento
sustentável do negócio**. Espera-se que ele não só solucione os problemas
que hoje geram confusões e atrasos, mas também traga eficiência, organização
e maior controle sobre o fluxo de pedidos, permitindo que a equipe se
concentre em outras atividades essenciais e impulsionando o crescimento da
Lanchonete Da Carminha.

## WHO?

### PERSONAS E MAPAS DE EMPATIA

As personas são ferramentas fundamentais para guiar o desenvolvimento de
soluções mais alinhadas às necessidades reais dos usuários. Elas
representam perfis fictícios, mas baseados em dados e comportamentos de
usuários típicos, permitindo uma visão clara dos desafios, expectativas
e objetivos de quem vai utilizar o sistema. A seguir, são apresentadas
as personas fictícias que orientaram o desenvolvimento deste projeto, destacando
seus principais pontos de dor e como o sistema irá resolver esses
desafios.

<img src= "/Imagens/Persona01.png">

<p align="center">Figura 2 - Persona 01</p>

<img src="/Imagens/Persona_02.png">

<p align="center">Figura 3 - Persona 02</p>

### Mapas de empatia
<img src= "/Imagens/MapaDeEmpatia1.png">

<p align="center">Figura 4 - Mapa de Empatia 01</p>

<img src= "/Imagens/MapaDeEmpatia2.png">

<p align="center">Figura 5 - Mapa de Empatia 02</p>

Após o levantamento das personas, é essencial aprofundar a compreensão
desses usuários para garantir que o produto entregue seja de qualidade e
atenda exatamente às suas necessidades. Tal processo envolve analisar seus
comportamentos, dores, expectativas e motivações, permitindo criar
soluções que realmente resolvam seus problemas e ofereçam uma
experiência eficaz e satisfatória. Para isso, desenvolvemos mapas de
empatia para cada uma das personas apresentadas:
# 📊 AVALIAÇÃO - Análise de Tarefa, Usuários e Função

## 🔍 Análise Hierárquica de Tarefas (HTA)

A **HTA (Hierarchical Task Analysis)** é uma metodologia utilizada para quebrar metas complexas em submetas e ações menores, ajudando a compreender as atividades realizadas pelos usuários ao interagir com um sistema.

Essa técnica permite organizar as tarefas em uma estrutura hierárquica, facilitando a compreensão da sequência e da lógica por trás da execução de cada ação. As tarefas são representadas como uma árvore: tarefas simples permanecem inalteradas, enquanto as mais complexas são divididas em etapas até o nível mais básico.

Também é possível destacar elementos como tarefas:
- Opcionais
- Alternativas
- Repetitivas
- Ubíquas  

O processo de análise inclui:
- Definição de objetivos  
- Coleta de dados  
- Construção de diagramas ou tabelas  

Essa técnica é útil tanto para compreender o estado atual quanto para redesenhar sistemas, contribuindo para interfaces mais intuitivas e centradas no usuário.

📄 **[Link para acessar o documento de Análise Hierárquica de Tarefas da Lanchonete da Carminha]**

---

## 🧩 Análise de Tarefas

A equipe se baseou em conversas anteriores com os stakeholders e em requisitos coletados durante a fase de planejamento. Realizou-se uma reunião virtual com os principais interessados, discutindo como o sistema poderia facilitar o dia a dia e melhorar a experiência do cliente.

Foi utilizada a técnica de decomposição das tarefas em níveis (HTA), o que ajudou a organizar os processos como:
- Realizar pedidos  
- Atualizar cardápio  
- Atender o cliente  

A análise revelou os principais fluxos de uso e apontou oportunidades para funcionalidades futuras que podem automatizar tarefas.

---

## 👥 Usuários

Para garantir usabilidade e utilidade, os perfis dos usuários foram reformulados com dados realistas e específicos. Foram utilizados:
- Personas  
- Mapas de empatia  
- Storytelling  

Esses materiais foram validados por usuários reais (dona e funcionários da lanchonete), que reconheceram as representações como fiéis à realidade. Isso garantiu decisões de design mais centradas nas pessoas.

---

## ⚙️ Função

A análise funcional identificou e definiu os papéis dos usuários no sistema, mapeando o fluxo de uso para:

- Fazer pedidos  
- Visualizar cardápio  
- Registrar vendas  
- Acompanhar status dos pedidos  

As funções foram validadas em sessões práticas com os stakeholders. O feedback confirmou que o sistema atende bem ao contexto da lanchonete.

---

## ✅ Conclusão

A análise completa de tarefas, usuários e funções permitiu:
- Entendimento aprofundado da operação da lanchonete  
- Desenvolvimento alinhado às expectativas reais  
- Garantia de que o sistema é eficiente, organizado e intuitivo  

---

# 🛠 ENGENHARIA DE REQUISITOS

## 🔍 Elicitação de Requisitos

Realizada por meio de uma reunião com a cliente, que descreveu os principais entraves do sistema atual.  
Os requisitos foram documentados a **nível de usuário**, com explicações simples e compreensíveis.

📄 **[Documento de Requisitos a Nível de Usuário]**

---

## 🧪 Especificação de Requisitos

Os requisitos do nível de usuário foram refinados para o **nível de sistema**, a fim de orientar os programadores na fase de desenvolvimento.

📄 **[Documento de Requisitos a Nível de Sistema (site)]**  
📄 **[Documento de Requisitos a Nível de Sistema (mobile)]**

---

## 📊 Diagramas

Diagramas elaborados para fornecer uma visão clara do sistema:

- **Diagrama de Casos de Uso:** Funcionalidades e interações do usuário  
- **Diagrama de Classes:** Estrutura das classes e seus relacionamentos  
- **Diagrama de Colaboração:** Interações entre objetos do sistema  
- **Diagrama de Atividades:** Fluxo das atividades e transições  
- **Diagrama de Sequência:** Troca de mensagens entre objetos  
- **Diagrama de Estados:** Estados e eventos que afetam os objetos  

📄 **[Link para visualizar os diagramas]**

---

## 🧾 AVALIAÇÃO - Especificação de Requisitos

### ✔️ Validação de Requisitos com o Cliente

Foi realizada uma reunião no modelo **workshop** para validação dos requisitos do sistema e do protótipo.

A equipe apresentou os requisitos um a um, solicitando aprovação ou sugestões da cliente. O protótipo também foi exibido, e a cliente sugeriu melhorias voltadas à:

- Navegabilidade  
- Usabilidade  

Essas sugestões foram documentadas, os requisitos foram refinados, e o sistema foi adaptado conforme o feedback recebido.

---

Se quiser, posso transformar tudo isso em um `README.md` completo ou dividir em arquivos separados como `avaliacao.md`, `engenharia_requisitos.md`, etc. Deseja isso?

## IDENTIDADE VISUAL - EMPRESA

A identidade visual do aplicativo desenvolvido para a Lanchonete Da Carminha
foi projetada para **reforçar o reconhecimento da marca e criar uma experiência
coesa e imersiva para o usuário**, conectando diretamente o design aos produtos
comercializados. Esse cuidado contribui para a consolidação da padronização visual 
da marca, ao mesmo tempo em que auxilia na construção de um imaginário atrativo e
consistente para os usuários.A escolha das cores principais se baseia em tons que 
remetem aos salgados, como o dourado e o marrom suave, que evocam a crocância e a 
cor dos produtos fritos, aproximando o usuário da experiência visual de consumo.

A tipografia e os ícones foram pensados para manter uma **comunicação
clara e amigável**, ao mesmo tempo que refletem a tradição e o
acolhimento da marca. Assim, a identidade visual reforça a **qualidade
artesanal dos salgados e a confiança que a lanchonete construiu ao longo
dos anos com seus clientes**.


<p align="center"><img src= "/Imagens/Salgados_cores.png"></p>
<p align="center">Figura 6 - Tipografia</p> 


### WIREFRAME

O wireframe desenvolvido para o sistema de gerenciamento da Lanchonete
Da Carminha teve como objetivo **delinear a estrutura visual e funcional
da interface**, seguindo os requisitos funcionais e não funcionais
definidos em conjunto com o cliente. Essas diretrizes foram detalhadas
no [Relatório de Requisitos de Alto Nível](https://drive.google.com/file/d/1meUePSfUTvfPofdZQQscJHWof1wMx8iu/view?usp=sharing).

Assim, o esboço detalhado foi elaborado com o propósito de ser um
protótipo de baixo para médio nível com o intuito de **detalhar a
experiência do usuário (UX)**, permitindo que todas as funcionalidades
essenciais sejam **claramente dispostas**, facilitando futuras melhorias
e refinamentos no design.

**Principais telas e suas respectivas funcionalidades:**

- Tela Inicial: A primeira interação do usuário ocorre na tela inicial, onde ele pode escolher o **tamanho do salgado que deseja encomendar**. O sistema oferece duas categorias:
  - Salgados Tamanho Festa: opção de salgados fritos ou assados.
  - Salgados Tamanho Mini: salgados fritos ou congelados.

Cada uma dessas opções é apresentada de forma destacada, permitindo que o usuário tenha uma visão clara e intuitiva das possibilidades. O design segue princípios de UI centrados na simplicidade e no fácil entendimento.

- Tela de Produtos: Após a seleção da categoria, o usuário será direcionado para a tela de produtos, que exibirá apenas os itens disponíveis na categoria escolhida. Cada item é acompanhado de:

  - **Imagem** do produto;
  
  - **Nome** do produto e descrição curta;
    
  - **Preço**;
    
  - **Botões de** **adição e subtração de quantidade**: permitem ao usuário aumentar ou diminuir a quantidade de itens de forma dinâmica e intuitiva;
    
  - **Botão de adicionar ao carrinho**: facilita o processo de compra, mantendo a simplicidade e a fluidez da navegação.

Também foram incluídas opções para **menu, pesquisa de produtos e acesso ao carrinho**, com ícones visíveis e de fácil acesso, sem sobrecarregar a interface.

- Tela do Carrinho de Compras: o carrinho de compras foi projetado para fornecer um resumo claro e preciso dos itens selecionados. Nele, o usuário encontrará:

  - **Resumo dos produtos escolhidos**: exibe o nome, quantidade e preço de cada item;

  - **Total do pedido**: calculado automaticamente à medida que novos itens são adicionados ou removidos;

  - **Formas de pagamento**: uma área para o cliente selecionar entre opções como pagamento via cartão, boleto ou outros métodos disponíveis. Cada método de pagamento é acompanhado de ícones facilmente reconhecíveis, facilitando a navegação e escolha do usuário.

<!-- -->

- Campo para observações: nesta área, o cliente pode inserir instruções específicas, como preferências de entrega ou detalhes adicionais sobre os produtos.

**Wireframe completo - Versão Celular:**

Interface Inicial:

<img src= "/Imagens/PrototipoCel_01.png">

Interface do carrinho e formas de pagamento:
<html><br></html>
<img src= "/Imagens/PrototipoCel_02.png">
<img src= "/Imagens/PrototipoCel_03.png">

**Wireframe completo - Versão Computador:**

Interface Inicial:<html><br></html>
<img src= "/Imagens/PrototipoPC_01.png">

Interface do carrinho e formas de pagamento:
<img src= "/Imagens/PrototipoPC_02.png">

### PROTÓTIPO DE ALTA FIDELIDADE

Utilizamos o Figma como ferramenta para criação deste protótipo para
**tornar o Wireframe funcional e verificar correções** que seriam feitas
para uma melhor experiência do usuário.

- [Protótipo de alta fidelidade (Celular)](https://www.figma.com/proto/99dnTB5dV1rzrPMmA1wqq6/Prot%C3%B3tipo?node-id=226-1133&node-type=frame&t=xVMpYs12HWpPS9RN-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1)

- [Protótipo de alta fidelidade (Computador)](https://www.figma.com/proto/99dnTB5dV1rzrPMmA1wqq6/Prot%C3%B3tipo?node-id=223-186&node-type=frame&t=sc8woxdXphHAgA5o-1&scaling=min-zoom&content-scaling=fixed&page-id=172%3A209)

***(Para que a experiência com o protótipo seja a melhor possível, ao
entrar neste link no canto superior direito haverá um ícone para
maximizar a tela, clique neste ícone para que o protótipo fique melhor
utilizável).***

### APRESENTAÇÃO AO CLIENTE

1.**Realização de Pitch e teste de usabilidade:**

Durante a fase de testes, foi realizado um teste de usabilidade com a
proprietária, Carminha, para avaliar a **facilidade de uso e a eficácia do
protótipo desenvolvido**. O teste consistiu em uma sessão em que a cliente
explorou o site e realizou a simulação de pedidos, desde a seleção dos itens
até a confirmação do pedido. Os resultados foram positivos, com Carminha
destacando a facilidade de navegação, a clareza das informações
apresentadas e a rapidez do processo. Feedbacks adicionais incluíram elogios
à organização da interface e à funcionalidade intuitiva, o que proporcionou uma
experiência de usuário satisfatória.

2.**Vídeo Explicativo do Protótipo:**

Também foi elaborado um vídeo detalhado apresentando o protótipo do sistema, com uma demonstração completa de todas as funcionalidades e opções de navegação. O vídeo foi disponibilizado à cliente.

- [Apresentação do Protótipo](https://drive.google.com/file/d/1tNClL53ounabVYKw7yDvW9kc81QnnzY4/view?usp=sharing)

## 6.CONCLUSÃO

Com este projeto, concluímos o Projeto Integrador proposto como parte da
disciplina de Design de Interação, sob a orientação da professora
Cristiane Aparecida Lana. O trabalho foi iniciado com a idealização de
uma empresa fictícia, especializada na elaboração de **soluções
responsivas e eficientes para negócios**. A missão foi estudar a
viabilidade de implementação de um sistema de gerenciamento de pedidos
para a Lanchonete Da Carminha, com o objetivo de resolver problemas como
sobrecarga de informações, erros na coleta de pedidos e o impacto
negativo na experiência dos clientes durante horários de pico.

Para isso, foram adotadas boas práticas no processo de desenvolvimento
de software, ajustando-se às limitações da disciplina. As atividades
foram organizadas por meio de sprints, com reuniões semanais, análise de tarefas, especificação de requisitos,
encontros regulares com stakeholders, além de avaliações constantes de
usabilidade e comunicabilidade. O **trabalho em equipe** foi essencial,
compreendendo a importância de cada etapa e função (CEO, *Scrum Master*,
Analista de Sistemas, *Product Owner* e Designer), bem como a **relevância
do esforço coletivo para a realização de um projeto sustentável***.

Como resultado, o sistema proposto demonstrou ser uma **solução prática
e eficiente, com grande potencial para facilitar o controle de pedidos,
fidelizar clientes e auxiliar na criação de campanhas personalizadas**.
Essas melhorias trarão benefícios tanto para os usuários quanto para a
gestão da lanchonete, permitindo que o empreendimento esteja mais bem
preparado para enfrentar os desafios do mercado atual, oferecendo um
serviço de alta qualidade, com maior eficiência operacional e um
significativo aumento na satisfação dos clientes.

Este projeto foi desenvolvido pelos alunos:

- Felipe Guimarães Gouveia, Estudante de Desenvolvimento de Software da UNIVIÇOSA.
  > [Linkedin](http://linkedin.com/in/felipe-guimar%C3%A3es-122456183)
  > [GitHub](https://github.com/FelipeGuimaraes1106)

- Luana Fialho da Silva, Estudante de Desenvolvimento de Software da UNIVIÇOSA.
  > [Linkedin](http://www.linkedin.com/in/luana-fialho)
  > [GitHub](https://github.com/luana-fialho)

- João Henrique da Silva Oliveira Nunes Aguiar, Estudante de Desenvolvimento de Software da UNIVIÇOSA.
  > [Linkedin](http://www.linkedin.com/in/jo%C3%A3o-henrique-da-silva-oliveira-nunes-de-aguiar-b416a6335)
  > [GitHub](https://github.com/JoaoHenriqueAguiar)

- Sávio Angelo Ferreira, Estudante de Desenvolvimento de Software da UNIVIÇOSA.
  > [Linkedin](https://www.linkedin.com/in/s%C3%A1vio-angelo-ferreira-188374335/)
  > [GitHub](https://github.com/Savio-Ferreira)

- Thiago de Paula Fernandes, Estudante de Desenvolvimento de Software da UNIVIÇOSA.
  > [Linkedin](http://www.linkedin.com/in/thiagopfernandes)
  > [GitHub](https://github.com/ThiagopFernandes01)
  >
  > 
**-Trabalho Orientado pela Profa. Cristiane Aparecida Lana.**
