# Análise de Sentimentos com Language Studio no Azure AI

Sentiment and opinion mining é uma solução da plataforma Language Studio, da Azure, que permite detectar sentimentos positivos, negativos e neutros a partir de sentenças. Esse repositório mostra alguns exemplos de testes na plataforma. Os procedimentos foram realizados como parte do Bootcamp Microsoft Azure AI Fundamentals, da DIO.


## Criar um recurso Azure Language Service
Para ser possível usar o Language Studio, é essencial que você possua um recurso para a plataforma associado a sua conta Azure. Isso pode ser feito por meio dos seguintes passos:

### Acessar https://portal.azure.com
Criar um novo recurso Language Service através da opção Create Resource.
Esperar o deploy do recurso terminar.
Selecionar recurso no Language Studio.
Com o recurso Language Service criado, é preciso conecta-lo ao Language Studio. Para isso, basta seguir os seguintes passos:

### Acessar o Language Studio.
Na página inicial, acessar os recursos criados através do botão "Select a resouce".
View all resources.
Preencha as informações e selecione o recurso recém criado.
Set default resource.
Selecionando e testando o serviço no Language Studio.
Ao retornar a página inicial após concluídos os passos anteriores, é possível ver a lista de serviços disponíveis para teste na plataforma. Nesse experimento foi usado o serviço "Analyze sentiment and mine opinions", na aba "Classify text".


## Resultados
Ao acessar o serviço é possível carregar o texto a ser analisado, selecionar sua linguagem e também ativar a opção de opinion mining. Para esse experimento, selecionei um capítulo do livro de Genesis, da Bíblia.

### Language Studio Services
Abaixo podemos ver o resultado da análise de sentimento de todo o texto. De acordo com os resultados, o texto é majoritariamente positivo (73%). Além disso, podemos ver o resultado em cada sentença, apresentarei dois exemplos abaixo.

![Captura de tela 2024-03-21 150006](https://github.com/matheusantunes-silva/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/156004284/15df4f7a-4ce9-408d-bffb-9743de952170)

![Captura de tela 2024-03-21 145621](https://github.com/matheusantunes-silva/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/156004284/b11523b4-e4e4-45dd-9ea5-51d86dd063d1)

![Captura de tela 2024-03-21 145720](https://github.com/matheusantunes-silva/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/156004284/22345935-b282-4b64-8580-9fc544653a3e)


Abaixo é possível observar a funcionalidade de opinion mining funcionando:

![Captura de tela 2024-03-21 145755](https://github.com/matheusantunes-silva/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/156004284/75ec60c5-6ebf-4f95-ba73-438f9b811559)


## Conclusão e Insights
As ferramentas de análise de sentimentos e opiniões têm sido amplamente utilizadas na automação da análise de feedbacks de serviços, permitindo a categorização de avaliações de clientes de forma eficiente. No entanto, essas ferramentas demonstram melhor desempenho em textos onde a expressão de sentimentos é clara, como em comentários e avaliações de produtos. Isso pode ser atribuído à limitação das ferramentas em analisar apenas uma sentença por vez, sem considerar o contexto completo do texto. Sugere-se que uma tecnologia mais avançada capaz de estabelecer conexões entre sentenças e compreender o contexto global do texto possa apresentar resultados mais precisos e abrangentes nessa análise.
