# SistemasOperativos-2022-2023

*Conteudos da Unidade Curricular de Sistemas Operativos do curso de ***Engenharia Informática 3º ano*** do IADE/Universidade Europeia*

A unidade curricular de Sistemas Operativos pretende dotar os alunos dos princípios básicos e semiavançados sobre os principais conceitos da gestão de recursos realizada a nível de um sistema operativo.
A evolução tecnológica e a cada vez maior quantidade e diversidade de equipamentos existentes que necessitam de sistemas operativos para a sua correta e produtiva utilização (além de desktops/servidores, também mobile, IoT, etc) é o enquadramento principal para a diversidade de sistemas apresentados em case studies e em diversas análises realizadas em sala de aula.

Além da perspetiva histórica sobre a evolução das gerações dos sistemas, o conteúdo técnico baseia-se na descrição das componentes de sistemas operativos, sobretudo no que diz respeito a gestão de processos, threads, memória e I/O.
Dá-se especial relevância aos conceitos associados à gestão de processos em ambientes multiprogramados e multiutilizador, com especial atenção às evoluções tecnológicas que os processadores introduziram nos últimos anos e permitiram uma evolução na gestão de processos nos Sistemas Operativos.
Todas os conteúdos são também enquadrados nos novos conceitos de utilização de sistemas operativos mobile e em sistemas embebidos e até em sistemas tem tempo-real por forma a cobrir um leque variado de aplicações dos sistemas operativos.

TO DO ***Esforço requerido aos alunos: 6 ECTS, com 42 horas em aula e 126 horas fora do ambiente de aula***

### Horário 
| Dia | Hora | Turma |
| :-----------: | :-----------: | :----------: |
| quarta-feira | 08:00 - 10:40 | T1 |

## Programa
### Aulas Teóricas
-	Revisões
- Sistemas Operativos
- Conceitos de Sistemas Operativos
- Os sistemas operativos como fornecedores de serviços
- Virtualização e Cloud
- Processos e Threads
- Comunicação Inter-Processos 
- UNIX Operating System
- Programação em Shell Bash 
- Gestão de Memória
- Gestão de Periféricos
- Criptografia, segurança e AAA

*Slides com conteudos disponiveis no Canvas*

### Aulas Práticas:
- 

### Planeamento PREVISTO (pode sofrer ALTERAÇÕES!!!)
| Aula | Semana | Aula |
| :-----------: | :-----------: | :---------- |
| 01 | 30 jan | Apresentação; Introdução a Redes de Computadores & Aplicações; Introdução ao Modelo OSI  |
| 02 | 06 fev | Modelo OSI - tecnologias (ethernet, wifi, 5g)  e layer 2 - VLANs, etc;	Modelo OSI - layer 3/routing; Modelo OSI - layer 4/transporte; ***Laboratório 1 ([pré-requisito 0.1](https://github.com/pmrosa-classes/Redes-EI-2022-2023/blob/main/AulasLabsPraticos/AulasLabsPraticos.md#01-instalação-do-cisco-packet-tracer-labs-13-e-6) para elaborar o laboratório)***  |
| 03 | 13 fev | Modelo OSI - camadas aplicacionais; Internet (história/breve); TCP/IP arquitetura, Unicast, Multicast; ***Laboratório 2 ([pré-requisito 0.1](https://github.com/pmrosa-classes/Redes-EI-2022-2023/blob/main/AulasLabsPraticos/AulasLabsPraticos.md#01-instalação-do-cisco-packet-tracer-labs-13-e-6) para elaborar o laboratório)***|
| 04 | 20 fev | TCP/IP pacotes IP / layer IP; TCP/IP ICMP, TCP, UDP / layer transporte; TCP/IP endereçamento IPv4; |
| 05 | 27 fev | TCP/IP endereçamento IPv4 ; ***Laboratório 3 ([pré-requisito 0.2](https://github.com/pmrosa-classes/Redes-EI-2022-2023/blob/main/AulasLabsPraticos/AulasLabsPraticos.md#02-instalação-de-máquinas-virtuais-em-equipamentos-dos-alunos-labs-24-e-5) para elaborar o laboratório)***|
| 06 | 06 mar | TCP/IP endereçamento IPv4 (inclui subnetting); |
| 07 | 13 mar | TCP/IP endereçamento IPv4 (inclui subnetting); ***Laboratório 4 ([pré-requisito 0.2](https://github.com/pmrosa-classes/Redes-EI-2022-2023/blob/main/AulasLabsPraticos/AulasLabsPraticos.md#02-instalação-de-máquinas-virtuais-em-equipamentos-dos-alunos-labs-24-e-5) para elaborar o laboratório)*** |
| 08 | 20 mar | ***Semana sem aulas*** |
| 0 | 27 mar | Inicio do estudo de alguns Protocolos TCP/IP; **Entrega do trabalho Routing-I**  |
|   | 03 abr | **Páscoa**|
| 09 | 10 abr | Protocolos (DNS, DHCP, HTTP, SNMP, etc) – essencial: saber exatemente como se resolvem os nomes; saber exatamente como se distribui endereçamento IP dinamicamente; IPv4 vs IPv6 enquadrar IPv6 como “obrigatório” nos dias de hoje; **Apresentação do trabalho Routing-I** |
| 10 | 17 abr | ***Laboratório 5 ([pré-requisito 0.2](https://github.com/pmrosa-classes/Redes-EI-2022-2023/blob/main/AulasLabsPraticos/AulasLabsPraticos.md#02-instalação-de-máquinas-virtuais-em-equipamentos-dos-alunos-labs-24-e-5) para elaborar o laboratório)***; **Entrega do trabalho Routing-II** |
| 11 | 24 abr | IPv6 features e endereçamento (inclui diferentes dimensões de redes e distinções na divisão com IPv4); IPv6 e serviços (DNSv6 e DHCPv6); Laboratório 5; **Apresentação do trabalho Routing-II** |
| 12 | 01 mai | IoT enquadrar com serviços de Cloud/associar a virtualização; Fog computing; necessidades de networking, armazenamento em IoT; exemplos práticos (smart homes, buildings, cities, veículos autónomos, etc); referencia a big data; referencia a segurança em IOT, nem que seja apenas com exemplos estilo Mirai botnet, etc); ***Laboratório 6 ([pré-requisito 0.1](https://github.com/pmrosa-classes/Redes-EI-2022-2023/blob/main/AulasLabsPraticos/AulasLabsPraticos.md#01-instalação-do-cisco-packet-tracer-labs-13-e-6) para elaborar o laboratório)***; **Entrega Trabalho Captura de pacotes com Wireshark/tcpdump** | 
| 13 | 08 mai | Apoio ao trabalho prático Networking/IoT; (possível salvaguarda para a realização de laboratórios atrasados, caso seja possível); **Apresentação do Trabalho Captura de pacotes com Wireshark/tcpdump** |
| 14 | 15 mai | **Teste Escrito** ; **Entrega do Trabalho Final** |
| 15 | 22 mai | **Apresentações dos Trabalhos Práticos** |

### Sumários
Os sumários das aulas podem ser consultados *aqui* (brevemente disponível)

## Avaliação Continua

### 1. Regras de Avaliacao Continua

De acordo com o **Regulamento Geral de Avaliação de Conhecimentos e Competências da Universidade Europeia.** (REG-046lV08 retirado do Portal do Docente em 27.01.2023), os alunos poderão fazer **avaliação continua** sendo que essa avaliação *inclui vários momentos de avaliação*

Recorde-se que, segundo o regulamento "*(...)A avaliação contínua é aquela que, com caráter regular e constante, decorre
durante o período letivo, refletindo uma permanente interação entre o docente e o estudante, através da realização de vários instrumentos de avaliação, executados individualmente e/ou em grupo.*"

Sendo assim:
- Ainda segundo o regulamento: *Os elementos de avaliação utilizados têm de contemplar uma ponderação igual ou superior a 4O% referente à avaliação individual no cálculo da classificação final da unidade curricular*.
- A realização do teste escrito será realizado durante as aulas na data marcada na calendarização da UC

Nesta UC são instrumentos da avaliação contínua:
- o Trabalho Prático (60%) em grupo que no trabalho final inclui apresentação
- o Teste Escrito Individual Final (40%). 

**Notas Muito Importantes:** 

**I** Não são admitidos à realização da prova escrita de avaliação continua, os estudantes que obtiverem uma classificação inferior a 8 (oito) valores na média dos elementos de avaliação previstos, neste caso o o Trabalho Prático (40%) em grupo. Poderá, no entanto, não realizar alguns trabalhos desde que a média seja de no minimo 8 valores (sem arredondamentos). 

**II** Os alunos que iniciem com Avaliação Continua têm até 30 dias antes da última aula para passarem para Avaliação Final. Data indicativa para o fazerem é até **26 de abril**

**III:** Os alunos que continuem no sistema de Avaliação Continua e que tenham más notas em elementos de avaliação já posteriormente aos 30 dias antes da última aula, vão para Exame de Recurso não podendo passar a Avaliação Final.

**IV:** Os alunos que, estando em Avaliação Continua, não obtenham o número de presenças obrigatórios, passam para Exame de Recurso não podendo passar a Avaliação Final.

**V** Os alunos deverão ter uma taxa de presenças de 70% nas aulas ou 40% nos casos excecionados no regulamento.

### 2. Elementos da Avaliação Continua 

#### 1. Trabalhos Práticos (60%)
Enunciados dos [Trabalhos Práticos](https://github.com/pmrosa-classes/SistemasOperativos-2022-2023/blob/main/TrabsP/README.md) da unidade curricular. Este trabalho é em grupo (aconselhado 3 alunos).

Importante respeitar as datas de entrega. Não serão aceites adiamentos.

#### 3. Teste Escrito (40%)

Teste Escrito unico a realizar na data marcada na calendarização (penultima semana de aulas).

## Avaliação Final

Ainda de acordo com o mesmo regulamento, os estudantes têm o direito a optar pelo regime de **avaliação final** (avaliação por exame) que integra uma prova escrita, ou outros elementos, sobre a matéria toda lecionada. Esta avaliação final ainda não está completamente definida mas, ou terá também elementos distintos da prova escrita, ou terá 60% do valor teórico/prático escrito (portanto relacionado com os laboratórios e trabalhos práticos).

## Presenças

Os alunos podem acompanhar a percentagem de aulas a que assistem através da disponibilização pública, em Google Sheets, referente à sua turmas:
- Presenças da [T01](https://docs.google.com/spreadsheets/d/e/2PACX-1vTMy_qe4OHB00CZkNnUHM5vwgfh-NAXmvV0Iw97bwfDhC_wPiRoRPmBdslhEjiprcHu2RkLrXByPwSB/pubhtml?gid=1412701734&single=true)
- Presenças da [T02](https://docs.google.com/spreadsheets/d/e/2PACX-1vTMy_qe4OHB00CZkNnUHM5vwgfh-NAXmvV0Iw97bwfDhC_wPiRoRPmBdslhEjiprcHu2RkLrXByPwSB/pubhtml?gid=933545162&single=true)

## Método Pedagógico
Aos alunos é fornecida toda a documentação utilizada durante as aulas, nomeadamente ficheiros pdf com os slides das aulas teóricas (Plataforma Canvas). Será também dado apoio aos projetos na maior parte das aulas.

## Discord
Deverá ser util juntarem-se ao Discord da cadeira: https://discord.gg/WTbk3rv5 (invite criado em 28.01.2023).

Para terem acesso aos canais do Discord devem alterar o vosso *nick* para PrimeiroUltimo nome no servidor e colocar uma mensagem em **#general** com "Numero - Primeiro&UltimoNome" para serem atribuídos os roles adequados.

## Grupos
Os trabalhos práticos são em grupo e deve ser preenchida a tarefa respetiva no Canvas até dia 10 de fevereiro: https://mycampus.pt/courses/7345/assignments/8738.

A contituição dos grupos será disponibilizada [aqui](https://docs.google.com/spreadsheets/d/e/2PACX-1vTMy_qe4OHB00CZkNnUHM5vwgfh-NAXmvV0Iw97bwfDhC_wPiRoRPmBdslhEjiprcHu2RkLrXByPwSB/pubhtml?gid=592821258&single=true) 

## Resumo do Calendário da UC e Tarefas
*(em atualização)*
- até 10 de fevereiro - Constituição dos grupos [Tarefa no Canvas](https://mycampus.pt/courses/13292/assignments/23225)
- até 10 de fevereiro - Escolha dos temas para os trabalhos teóricos [Tarefa no Canvas](https://mycampus.pt/courses/13292/assignments/23224)
- semana de 13 de fevereiro - Apresentação à turma das propostas dos trabalhos práticos.
- até à semana de 13 de março para apresentação de segunda proposta (corrigida) ou de relatórios intermédios, nos trabalhos onde tal é solicitado.
- até 19 de maio - Entrega do trabalho prático
- semana de 22 e 26 de maio - Apresentações dos trabalhos práticos

## Bibliografia
- Tanenbaum, Andrew S., Modern Operating Systems (4ª Edição) Prentice-Hall
- Alves Marques, Carlos Ribeiro, Rodrigo Rodrigues, Paulo Ferreira Luís Veiga Fundamentos de Sistemas Operativos (2ª Edição) FCA 

## Log
- 2023.01.29: Disponibilização do Repositório.
