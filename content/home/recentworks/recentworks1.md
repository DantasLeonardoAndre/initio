+++
title = "Estratégia de Expansão de Filiais"
type = "recentwork"
weight = 2
date = "2015-06-24"
description= "A brief description of Hugo Shortcodes"
image= "/post/recentworks/Release7.PNG"
+++





A imagem que abre este post busca ilustrar a ideia de lançamento realizado a partir de análises desenvolvidas com o auxílio de máquinas. O projeto descrito neste post é justamente uma demanda que visa compreender a viabilidade de lançamentos, não de foguetes, mas de novas filiais dentro do ramo varejista de concessionárias. As análises desenvolvidas são o que dão suporte para melhor compreender os prós e contras existentes nas possíveis decisões para abertura de uma nova loja.   

Para que aconteça a abertura de novas filiais, uma série de decisões são necessárias e estas decisões passam por perguntas como:

- Existe regiões com áreas em branco ou pouco habitadas por concessionárias?
- Existe demanda em potencial nas regiões definidas para análise?
- Quão significativo são as características destas regiões quando analisado o volume de veículos vendidos?

Desta forma, o seguinte post busca descrever um projeto realizado para o grupo Ventura, maior detentor de concessionárias no estado no Ceará. O foco do projeto é embasar a argumentação dos gestores Carmais, com metodologias alicerçadas em dados, na busca por expandir as atuais fronteiras de seus negócios.



## Contextualização do Projeto

Projeto, no formato de estudo, tendo como principal objetivo embasar a argumentação, sobre a possibilidade de abertura de novas filiais, dos gestores Carmais (Grupo proprietário de extensa gama de concessionárias no estado do Ceará, Brasil), junto aos diretores regionais da fabricante General Motors (GM).

Embora este seja o objetivo final do projeto é importante colocar que este fora um objetivo que apenas fica claro nas últimas etapas do projeto. 

Como costumeiramente acontece dentro na área de Ciência de Dados e Analytics, muito envolvida pelas metodologias ágeis no desenvolvimento dos projetos, o foco real do projeto só se é descoberto ao longo do projeto, através, principalmente, de duas atividades principais e complementares, entregas períodicas de novas funcionalidades desenvolvidas e recorrente feedback do material desenvolvido ao longo da semana de trabalho. O processo iterativo contendo estas duas atividades está no cerne da re-priorização de esforços e real compreensão do foco do projeto, é o que permite redirecionar os esforços realizados para as entregas que irão gerar maior valor ao cliente final.

Desta forma, não diferente para este projeto, uma série de etapas fora desenvolvida, com entregas parciais que permitiam ao cliente melhor compreender, não só o poder das ferramentas e técnicas que poderiam ser utilizadas para abordar o problema, mas principalmente, para melhor se situar dentro do seu espaço-problema, promovendo representações visuais das áreas de impacto e permitindo ao cliente redirecionar o foco do projeto para as análises que mais gerariam valor na conclusão do trabalho. 

A descrição contida neste post é uma visão do projeto de um observador que enxerga o passado, que avalia um projeto já concluído e busca melhor organizar as ideias e as principais entregas necessárias para se atingir aquilo que, ao longo do projeto, surge como real objetivo com a sua conclusão. 
 

### Projeto



Para concretização do estudo, em primeira etapa, buscou-se averiguar a hipótese inicial, dada pelos gestores Carmais, de que, de fato, havia um mercado em potencial a ser explorado, sendo necessário compreender, primeiramente, as regiões pouco ou não habitadas ainda por concessionárias, para então determinar as regiões de análise, sendo necessário verificar, dentro destas regiões, métricas de emplacamentos para os vários bairros que as compõem, assim como estimar a quantidade de potenciais clientes existentes e como estariam distribuídos ao longo destas regiões, adicionando a análise demais áreas que não possuam dados capturados de emplacamentos. 

Desta forma, no primeiro momento, foi estudado através de estatísticas descritivas e modelos de visualização espacial, métricas de emplacamentos das principais fabricantes dentro das regiões de interesse do grupo, definidas pela análise das regiões pouco ou não habitadas por concessionárias, buscando entender, sob a ótica do volume de emplacamentos, o mercado em potencial a ser explorado.

Logo após compreender o volume de emplacamentos existentes nas regiões de interesse do grupo, buscou-se estimar a quantidade de potenciais clientes, utilizando bases públicas do IBGE na granularidade de setores censitários, através de premissas adotadas para a mínima quantidade de salários mínimos necessários para ser considerado um potencial cliente, assim como rendimento médio mensal das pessoas residindo nestas áreas.

Em um segundo momento do estudo, as métricas de emplacamentos foram analisadas com o intuito de melhor compreender as diferenças entre o grupo e as demais concorrentes existentes no mercado, trazendo insights sobre os modelos de veículos negociados dentro do portfólio do grupo, analisando o déficit comparativo, no saldo de emplacamentos, entre o grupo e concorrentes e, assim, permitindo compreender qual fabricante parceira teria prioridade na estratégia de expansão do grupo.

Na segunda etapa do estudo, aprofundou-se a visão da fabricante de maior destaque nas regiões de interesse do grupo, também trazendo métricas comparativas dos emplacamentos acontecidos nestas áreas, compreendendo a dinâmica atual do mercado já existente entre a fabricante de maior destaque e demais fabricantes.

Por fim, embora fosse possível compreender os benefícios provenientes da melhora na qualidade do serviço prestado, trazendo menor tempo de deslocamento para o mercado de clientes já existentes, é preciso compreender se, para a fabricante, isso também se traduziria em aumento significativo nas receitas, trazendo também maior participação do grupo Ventura dentro dos resultados absolutos.

Desta forma, na terceira e última etapa deste estudo, foi-se verificado, através de um modelo de regressão linear, o quanto da variabilidade na quantidade de emplacamentos é influenciado por duas variáveis:

- Distância do ponto central de cada bairro até a concessionárias mais perto.
- Quantidade de concessionárias presentes em um raio de 5Km em torno deste ponto central.


Este modelo apresenta semelhanças fortes com as metodologias utilizadas por grandes redes farmacêuticas para justificar o alto nível de investimentos que temos visto nos últimos anos, com algumas destas marcas duplicando a infraestrutura voltada para atender seus clientes.

Assim, o modelo proposto como última etapa do projeto visa embasar a ideia de aumento de receita proveniente da abertura de demais filiais, trazendo justificativas razoáveis para que as fabricantes, em parceria com suas principais revendedoras, planejem e confiem na extensão da rede de concessionárias como estratégia para alavancar os resultados ao longo dos próximos anos.


## Leonardo Dantas

Consultor em análise de dados com 4+ anos de experiência trabalhando em projetos para grandes empresas de diferentes segmentos do mercado como Fleury S.A., Souza Cruz Ltda., KPMG Consultoria Ltda., etc. Mente orientada para possibilidade de produtização dos serviços ao longo do período de desenvolvimento. Desde estagiário atuando em toda cadeia de atividades de consultoria, a começar por relacionamento com os clientes, apresentando portfólio de serviços e acompanhando os serviços já prestados, até as etapas de apresentação e fechamento do projeto (gestão do conhecimento), passando por atividades de entendimento de demandas/coleta de requisitos, atividades de desenvolvimento, como provas de conceito/estudos/projetos, e atividades de monitoramento e acompanhamento dos projetos em execução. Especialista na construção de fluxos ETL e no manuseio do software Alteryx Designer, ministrando cursos e treinamentos nesta ferramenta para grandes consultorias como Falconi Consultores S.A. e KPMG Consultoria Ltda. Movido por desafios e sempre interessado em buscar formas mais eficientes de se resolver problemas, acreditando fortemente que o potencial humano de tomar decisões coerentes pode ser significativamente alavancado com o uso de tecnologias da área de ciência de dados e de metodologias da área de analytics.




