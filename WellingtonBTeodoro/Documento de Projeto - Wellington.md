# SUMÁRIO

1. [Descrição de Projeto](#1-Descrição-de-Projeto)   
2. [Termo de Abertura de Projeto](#2-Termo-de-Abertura-do-Projeto)
3. [EAP](#3-EAP)   
4. [Quadro de Componentes Principais do Projeto](#4-Quadro-de-Componentes-Principais-do-Projeto)
5. [Quadro de Tempo das Etapas da EAP](#5-Quadro-de-Tempo-das-Etapas-da-EAP)  
6. [Quadro de Equipe das Etapas da EAP](#6-Quadro-de-Equipe-das-Etapas-da-EAP)  
7. [Diagrama de Rede](#7-Diagrama-de-Rede)  
8. [Quadro de Riscos](#8-Quadro-de-Riscos)  
9. [Gráfico de Gantt](#9-Gráfico-de-Gantt)

# 1 Descrição de Projeto

## 1.1 Objetivo
> O projeto tem como intuito descrever e detalhar todas as etapas que compõem o desenvolvimento da releitura arquitetural de um gerador de função digital de tecnologia baseado na fabricante Minipa do modelo MFG-4201A.

## 1.2 Metodologia
> Descrever e detalhar o desenvolvimento, execução e a metodologia aplicada em todas as atividades do projeto. Apresentar as fases de execução do projeto, constando cronograma de atividades com períodos das ações, quadros e diagramas mensurando os parâmetros demonstrativos e organizacionais.
> Uma forma de mensurar as etapas é através dos marcos do projeto, que são definidas pelas etapas consideradas pontos chaves informando quando será finalizada uma determinada atividade do projeto.

## 1.3 Topologia do Equipamento
> Construção do equipamento gerador de função digital, tem como base de funcionamento a geração de sinais elétricos com diferentes formas de onda, frequência e amplitude de tensão, que podem ser utilizados em diversas áreas da tecnologia eletrônica. Com base no esquemático original, fez-se a verificação dos principais componentes que compõem a estrutura do gerador, pesquisando-se as descrições técnicas para a identificação do funcionamento dos mesmos. Além disto, como importante etapa, realiza-se o levantamento dos valores para o embasamento do orçamento previsto do projeto.

## 1.4 Recursos Humanos
> Para desenvolvimento do projeto, necessita-se uma equipe multidisciplinar, que é composta por integrantes que atuam em áreas diferentes mas que se completam para o desenvolvimento do projeto. Cada equipe/integrante reúne alguma caracteristica que o torna importante para a continuidade do projeto, que os quais devem ser divididos através de um equilíbrio disciplinar.

# 2 Termo de Abertura de Projeto


## **2.1. Nome do Projeto**

> Gerador de Função Digital

## **2.2 Gestor do Projeto**

> Wellington Batista Teodoro

## **2.3 Objetivo do Documento**

>Este documento tem como objetivo autorizar formalmente o início de um projeto e contém informações necessárias para o entendimento do projeto, fornecendo uma visão macro do produto a ser desenvolvido.

## **2.4 Objetivo do Projeto**

>Construção de um equipamento utilizado para gerar sinais senoidais, triangulares, quadrados, rampa, todos com diversas frequências e amplitudes, sendo utilizado em laboratórios como fonte de sinal para testes de equipamentos eletrônicos.
>
>Dentro do projeto divide-se em quatro partes, com os quais são compostos pelos componentes principais:
>
>   **Placa Principal:**
>
> -   MC 10116;
> -   GAL 16V8; 
>-   89C52;
>-   75107AN;
>-   7426; 
>-   LINE FILTER.
>
>   **Placa do Display:** 
>   
>-   74HC138; 
>-   LED(Display) 3.6x6; 
>-   FND(7-SEG) LTD-4708G;
>
>**Outros Componentes:**
>
>-   Power Switch Push/Pull;  
>-   Power Transformer;
>-   Conector BNC-RB;  
>-   Painel Frontal;
>-   KNOB;    
>-   AC INLET;   
>-   FUSE 250V 0.2A;  
>-   Voltage Selector.
>
> **Gabinete:**
> 
>-   Pé Borracha Pequeno;    
>-   Pé Borracha Grande;    
>-   Borracha de Proteção;    
>-   Serigrafia;    
>-   Chassi Frontal.

## **2.5 Justificativa**

>Oferecer uma ampla faixa de aplicações tanto em eletrônica analógica como digital, nos campos de engenharia, produção, manutenção, educação e hobistas.

## **2.6 Escopo**

>-   Pesquisa do produto analisado, para compreender os valores a serem captados para a realização do projeto, e o tempo necessário para a implementação do mesmo;
>
>-  Avaliação de riscos para possíveis imprevistos;
>  
>-  Formação eficaz da equipe baseado nas demandas necessárias pelas etapas do processo;
>     
>-  Gerenciamento do tempo para estipular prazos reais;
>
>-   Reuniões periódicas para avaliação de imprevistos e avanços;

## **2.7 Equipe Básica**


|**Nome do Participante**|**Papel desempenhado**                           |
|------------------------|-------------------------------------------------|
|**`Wellington`**            |Gestor                  					   |
|**`Karen`**      			 |Design de Gabinete/Painel           		   |
|**`Matheus`**	  			 |Desenvolvimento de Circuitos				   |
|**`Gabriel`**    			 |Compra de Componentes           			   |
|**`Henrique`**   			 |Design de Software/Firmware            	   |
|**`Elias`**	  			 |Relator das etapas/Desenvolvimento do Manual |


## **2.8 Prazo Previsto**

>**25/06/2019**

## **2.9 Restrições**

>1. Exceder recursos e/ou tempo, solicitações não razoáveis do cliente.
>
>2. Tempo de importação dos componentes;
>
>3. Prazo para fabricação de componentes terceirizados;

## **2.10 Aprovação**


|**Responsável** |**Data**                       |**Assinatura**               |
|----------------|-------------------------------|-----------------------------|
|**Wellington Batista Teodoro**|**26/02/2019**   |                             |


# 3 EAP

> A estrutura analítica do projeto, tem como função separar o projeto em pequenas partes deixando-o mais articulado e de fácil controle, possibilitando uma visão estruturada do que deve ser entregue. É estruturada no formato de árvore hierárquica orientando às entregas que precisam ser feitas para completar um projeto. 

![EAP](https://github.com/LPAE/pje_tec_19_1/blob/master/GabrielSCaetano/diretorio_imagens/EAP.jpg)

# 4 Quadro de Componentes Principais do Projeto 

> O Quadro de Componentes visa listar as principais tecnologias que compõem o sistema eletrônico do gerador de função, com base no esquemático original. Fez-se também o levantamento dos preços e os fornecedores para ter-se uma ideia geral dos custos de componentes do projeto.

![Quadro de Componentes](https://github.com/LPAE/pje_tec_19_1/blob/master/GabrielSCaetano/diretorio_imagens/quadro_de_componentes.jpg)

# 5 Quadro de Tempo das Etapas da EAP

> Com base na estrutura analítica do projeto, o quadro de tempo é confeccionado escrevendo as tarefas a serem realizadas, juntamente com o prazo de tempo estimado para a conclusão das mesmas.

![Quadro de Tempo](https://github.com/LPAE/pje_tec_19_1/blob/master/GabrielSCaetano/diretorio_imagens/quadro_de_Tempo.jpg)

# 6 Quadro de Equipe das Etapas da EAP

> A partir do quadro de tempo e da equipe responsável pelo projeto, define-se os encarregados pelas tarefas com base nas suas competências.

![Quadro de Equipe](https://github.com/LPAE/pje_tec_19_1/blob/master/GabrielSCaetano/diretorio_imagens/quadro_de_Equipe.jpg)

# 7 Diagrama de Rede

> Diagrama de Redes representa de forma gráfica a sequência em que as etapas do projeto são priorizadas e concluídas, apresentando as relações entre as atividades. Dentro de cada tarefa é possível identificar o responsável, o tempo de início e conclusão, incluindo os conceitos de início e término mais cedo e mais tarde. O gráfico também apresenta o caminho crítico do projeto, que aponta as tarefas que demandam mais atenção em relação ao tempo de início e conclusão.

![Quadro do Diagrama de Redes](https://github.com/LPAE/pje_tec_19_1/blob/master/GabrielSCaetano/diretorio_imagens/diagrama_de_rede_quadro.jpg)

![Diagrama de rede](https://github.com/LPAE/pje_tec_19_1/blob/master/GabrielSCaetano/diretorio_imagens/diagrama_de_rede.jpg)

# 8 Quadro de Riscos  

> Diante das atividades anteriormente estipuladas, define-se um quadro que expressa os riscos decorrentes no projeto, bem como suas consequências, suas chances de ocorrência, impacto no projeto e quais os planos de ação para resolução dos mesmos.

## 8.1 Plano de Gerenciamento de Riscos

> O gerenciamento de riscos é determinado a partir da EAP identificando em cada pacote de trabalho os riscos advindos de ameaças e oportunidades ao longo do desenvolvimento deste projeto.
Espera-se que durante o ciclo de vida deste projeto o gerente de projeto seja capaz de minimizar as consequências dos eventos adversos (ameaças) e maximizar os resultados dos eventos favoráveis (oportunidades). Tanto ameaças quanto oportunidades são eventos que podem ou não acontecer sendo assim são riscos.

## 8.2 Metodologia

> A metodologia implementada incluirá os seguintes planos e processos:
> - 1: Reuniões a cada marco de projeto com os gestores de cada área.
> - 2: Criação de relatórios que deverão ser apresentados a cada novo marco do projeto ou reuniões extraordinárias.
> - 3: Acompanhamento da entrega dos serviços terceirizados mediante inspeção.

## 8.3 Identificar os riscos

> A identificação dos riscos será definido a partir de suas causas como por exemplo
o "atraso na entrega dos componentes", e correlacionado com seu pacote de trabalho
definido anteriormente na estrutura analítica.
No quadro de identificação de riscos temos uma breve descrição do risco, os pacotes
de trabalho onde o risco está presente, as consequências, as chance, o nível
de impacto e um plano de resposta. A responsabilidade por mitigar e ou prevenir é
de cada gestor

![Quadro de Riscos](https://github.com/LPAE/pje_tec_19_1/blob/master/GabrielSCaetano/diretorio_imagens/quadro_de_riscos.jpg)

> Fatores de Risco Evidenciados
> O risco está presente em qualquer empresa, em qualquer setor. Nesse sentido, o objetivo da pesquisa é identificar os tipos de risco evidenciados no Quadro de Riscos. Os riscos podem ser classificados em: risco baixo, risco médio e risco alto. A classificação de cada risco é medida de acordo com as consequências que este pode vir a causar.
Atividades que se tornam dependentes umas das outras ou que envolvem fornecedores podem se tornar fatores de risco alto quando  

# 9 Gráfico de Gantt 

> É utilizado como uma ferramenta de controle de produção para ilustrar o avanço das etapas de um projeto. Os intervalos de tempo representando o início e fim de cada fase aparecem como barras horizontais sobre gráfico. Nele podem ser visualizadas as tarefas de cada  membro da equipe, assim como o tempo para realizá-la.

![Atividades Gantt](https://github.com/LPAE/pje_tec_19_1/blob/master/GabrielSCaetano/diretorio_imagens/gantt_1.jpg)

![Gráfico Gantt](https://github.com/LPAE/pje_tec_19_1/blob/master/GabrielSCaetano/diretorio_imagens/GANTT_2.jpg)

 