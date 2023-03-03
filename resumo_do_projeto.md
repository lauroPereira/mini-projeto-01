# mini-projeto-01
## Resumo do mini projeto

Dado que este projeto é individual, não há a necessidade de utilizar um *framework* como o *Scrum*, já que ele é indicado para a organização de **times** (com tamanho sugerido de até 10 pessoas). Ainda assim, algumas práticas do *Scrum* foram utilizadas para melhorar a organização, transparência e evolução do projeto, tais como:

* Organização das demandas em Kamban
* **D.o.R.** *(Definition of Ready)* e **D.o.D.** *(Definition of Done)*
* Épicos
* Sprints
* Planejamento
* retrospectiva
* timeboxing
	
### Organização das demandas em Kamban
O *Trello* foi a ferramenta escolhida para a organização dos objetivos e etapas para atingir cada um destes objetivos utilizando o [quadro kanban](https://trello.com/b/LTEN26SQ/mini-projeto-01).
	
### DoR e DoD
As definições de pronto para início (D.o.R.) e de pronto para entrega (D.o.D.) são baseadas nas etapas e tarefas do framework **CRISP-DM** *(Cross-industry Standard Process for Data Mining)*, que é o modelo organizacional mais utilizado nas empresas para gestão de projetos de mineração de dados.
	
### Épicos
Afim de dar maior **transparência ao andamento do projeto** foi realizada sua separação de macro temas (ou etapas necessárias para a conclusão do mesmo) como épicos.

Estes épicos podem ser acompanhados também no mesmo [quadro onde estão as tarefas](https://trello.com/b/LTEN26SQ/mini-projeto-01), da seguinte forma:
* Quando ainda estão pendentes, permanecem na primeira coluna (com o nome **"Épicos pendentes"**).
* Conforme sendo concluídos, serão movidos para a coluna de **"Concluído"**.
* *obs: Todas as demais colunas são para organização das tarefas, e não serão usadas para os Épicos*.

Além disso, cada tarefa do [quadro kanban](https://trello.com/b/LTEN26SQ/mini-projeto-01) possui uma **etiqueta cinza** informando à qual épico pertence.

### Sprints
O projeto foi iniciado no dia **20/02/2023** e a previsão de sua conclusão é dia **04/03/2023**.
Para que é a entrega do projeto seja efetuada até o *dead line* (data alvo) o prazo foi separado em 4 _sprints_, que serão identificadas com etiquetas coloridas em cada tarefa no [quadro kanban](https://trello.com/b/LTEN26SQ/mini-projeto-01):
* Sprint 1: 20/02 à 22/02
* Sprint 2: 23/02 à 25/02
* Sprint 3: 26/02 à 28/02
* Sprint 4: 01/03 à 03/03

### Planejamento
Ao início do projeto foi realizado o ***Release planning*** (que é o planejamento da entrega do projeto como um todo), onde foram listados todos os épicos necessário para atingimento do **objetivo final** e as suas **respectivas tarefas**, necessárias para conclusão de cada épico.

Além disso, ao início de cada *sprint* será realizada uma *planning* (planejamento) para **refinar as tarefas** (quebrando elas em sub-tarefas que podem ser visualizadas dentro dos cards no [quadro kanban](https://trello.com/b/LTEN26SQ/mini-projeto-01)) e **avaliar quais destas serão assumidas** para conclusão até o fim da *sprint*.
	
### Retrospectiva
Ao final de cada *sprint* será realizada uma retrospectiva para **avaliar o atingimento dos objetivos assumidos** e revisar o que precisa ser ajustado antes de iniciar a próxima *sprint*.

Além disso será elaborado um resumo incremental da *sprint* e publicado na [página de apresentação](https://github.com/lauroPereira/mini-projeto-01/README.md) do projeto.
	
### Timeboxing
* O timebox de cada uma das *sprints* é de 3 dias.
* Ao início de cada *sprint* haverá 30min para planning.
* Ao final de cada *sprint* haverá 30min para retrospectiva.

## Retrospectiva - sprint 1
dia: 23/02/2023
Infelizmente o resultado da primeira Sprint não foi atingido, duas tarefas ficaram pendentes devido ao curto período de tempo que foi possível dedicar às demandas.
Para a próxima Sprint é aconselhavel me comprometer com menos tarefas. Como não houve nenhum tipo de bloqueio durante a sprint, não é necessário mudar a forma de trabalho, somente com relação ao tempo dedicado ao projeto que precisa aumentar para evitar o risco de comprometer a entrega.

## Planning - sprint 2
dia: 23/02/2023
Para a Sprint o compromisso será de 3 taréfas ao invés de 4, e os dois objetivos da sprint serão:

* "Concluir o setup do projeto"
	* Criar a página do projeto no google colab
		* [página criada](https://colab.research.google.com/drive/1NR44I_VQvKYv11ShGCELIqZ3hS0iSzme#scrollTo=pHrzyRWmRmBK)

* "Definir a questão do negócio"
	* Compreender o objetivo de negócio
	* Atualizar o repositório do github e a página do colab com as informações da questão de negócio

***Após desenvolvimento dos itens definidos para a sprint foi identificado que eram menores do que o esperado e que havia espaço na sprint para a inclusão de novos itens, por isso foram acrescentadas os itens "Mapeamento dos dados" e "Construir um plano" do épico "Entendimento do negócio"***

## Retrospectiva - sprint 2

* O objetivo da sprint não foi atingido novamente.
* Foi identificado que a tarefa de construção do plano não pode ser concluída pois as etapas de exploração dos dados ainda não havia iniciado, e por isso a tarefa ficou bloqueada.
* O ritmo do projeto não está adequado, até agora **6 tarefas foram concluídas** e **9 estão pendentes** sendo que finalizei a sprint 2 de um total de 4, ou seja, foi concluído 40% do trabalho em 50% do tempo
* Devido ao atráso duas tarefas foram despriorizadas, por não serem críticas para o projeto, são elas:
	* Identificar dados anômalos (potencialmente errados)
	* Pesquisar dados externos relacionados ao problema do cliente

![image](https://user-images.githubusercontent.com/16515641/221435573-4f30f563-9a1d-4ae6-a53c-565540017082.png)

## Planning - sprint 3
* Foi realizado um novo refinamento ajustando as tarefas necessárias para cada épico e alterando a ordem da execução para não termos novos problemas de bloqueio
* Com estes ajustes o escopo do épico **"Entendimento de negócio"** foi reduzido e ele foi dado como concluído

* As tarefas que serão adicionadas ao backlog da sprint serão:
	* Tratamento inicial dos dados
		* Ajustar os tipos dos dados
	* Descrição dos dados
		* Analisar volume dos dados
		* Criar um glossário com cada coluna
	* Verificação da qualidade dos dados
		* Remover nulos (em dados críticos)
		* Remover duplicados
	* Construir um plano **(não entregue na sprint 2)**
		* Definir quais são as variáveis mais importantes do dataset
		* Criar uma estratégia macro para conseguir responder a pergunta de negócio do cliente
* SPRINT INICIADA
![image](https://user-images.githubusercontent.com/16515641/221435942-acc5fa8b-7882-46fe-9f7d-bee29b6c9ead.png)
 
## Retrospectiva - sprint 3
* O objetivo da sprint foi atingido com antecedencia
* Por isso foi possível repriorizar a análise de anomalia nos dados, e com isso foi possível remover da base de dados alguns imóveis sem banheiro ou quarto, e até mesmo um imóvel que constava com 33 quartos.
* Nessa Sprint foi possível avançar bastante no planejamento da execução das análises devido ao forte conhecimento da questão de negócio e dos dados disponíveis
* A estratégia se dividirá em 4 etapas:
	1. Análise por cidade para validar onde o mercado está mais aquecido
	2. Análise multivariada por categoria (variáveis de tamanho, qualidade, etc), para validar dentro de cada categoria qual variável tem maior correlação com o preço do imóvel obs: Validar se essa correlação se aplica a todas as cidades ou se é específica
	3. Através das variáveis/categorias com maior correlação, criar uma forma de classificar os imóveis
	4. Identificar os imóveis com valor mais fora do padrão entre classificação e valor* 


![image](https://user-images.githubusercontent.com/16515641/222621556-0ae8cdd5-c11d-42ad-bc9e-dde3dcbfebe6.png)


## Planning - sprint 4
* Para a Sprint 4, que é a última será necessário finalizar o épico de "Exploração de dados" que já foi concluído 50% na sprint anterior e a análise final.
* Devido à um imprevisto não foi possível trabalhar nos dias 28/02 e 01/03, o que colocou a entrega do projeto em risco, por isso será necessário total comprometimento para a conclusão do projeto dentro do prazo
* Para a conclusão de todo o trabalho restante preciso concluir 3 histórias priorizadas, e caso ainda haja tempo, a tarefa de pesquisa por dados externos pode ser repriorizada para aprimorar a conclusão final.

![image](https://user-images.githubusercontent.com/16515641/222622096-3f8c3df7-40ef-4417-ab4a-dedd5571d7b3.png)
