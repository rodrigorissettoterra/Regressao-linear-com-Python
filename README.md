REGRESSÃO LINEAR
<ul>
 	<li>Conhecendo o Dataset
<ul>
 	<li>Importando bibliotecas</li>
 	<li>Bibliotecas opcionais</li>
 	<li>O Dataset e o Projeto</li>
 	<li>Leitura dos dados</li>
 	<li>Visualizar os dados</li>
 	<li>Verificando o tamanho do dataset</li>
</ul>
</li>
 	<li>Análises Preliminares
<ul>
 	<li>Estatísticas descritivas</li>
 	<li>Matriz de correlação</li>
</ul>
</li>
 	<li>Comportamento da Variável Dependente (Y)</li>
 	<li>Análises gráficas
<ul>
 	<li>Plotando a variável dependente (y)</li>
</ul>
</li>
 	<li>Box Plot
<ul>
 	<li>Importando biblioteca seaborn</li>
 	<li>Box plot da variável dependente (y)</li>
</ul>
</li>
 	<li>Box Plot com Duas Variáveis
<ul>
 	<li>Investigando a variável dependente (y) segundo determinada característica</li>
 	<li>Configurações de estilo e cor da biblioteca seaborn</li>
</ul>
</li>
 	<li>Distribuição de Frequências
<ul>
 	<li>Distribuição de frequências da variável dependente (y)</li>
</ul>
</li>
 	<li>Variável Dependente X Variáveis Explicativas (pairplot)
<ul>
 	<li>Gráficos de dispersão entre as variáveis do dataset</li>
 	<li>seaborn.pairplot</li>
 	<li>Plotando o pairplot fixando somente uma variável no eixo y</li>
</ul>
</li>
 	<li>Variável Dependente X Variáveis Explicativas (jointplot)
<ul>
 	<li>seaborn.jointplot</li>
 	<li>Plotando um jointplot com a reta de regressão estimada</li>
</ul>
</li>
 	<li>Variável Dependente X Variáveis Explicativas (lmplot)
<ul>
 	<li>seaborn.lmplot</li>
 	<li>Plotando um lmplot utilizando uma terceira variável na análise (tipo I)</li>
 	<li>Plotando um lmplot utilizando uma terceira variável na análise (tipo II)</li>
</ul>
</li>
 	<li>Estimando um Modelo de Regressão Linear para o Consumo</li>
 	<li>Regresão Linear
<ul>
 	<li>Importando o train_test_split da biblioteca scikit-learn</li>
 	<li>Criando uma Series (pandas) para armazenar o Consumo de Cerveja (y)</li>
 	<li>Criando um DataFrame (pandas) para armazenar as variáveis explicativas (X)</li>
 	<li>Criando os datasets de treino e de teste</li>
 	<li>Verificando os tamanhos dos arquivos gerados pela função train_test_split</li>
 	<li>Importando LinearRegression e metrics da biblioteca scikit-learn</li>
 	<li>Instanciando a classe LinearRegression()</li>
 	<li>Utilizando o método fit() do objeto "modelo" para estimar nosso modelo linear utilizando os dados de TREINO (y_train e X_train)</li>
 	<li>Obtendo o coeficiente de determinação (R²) do modelo estimado com os dados de TREINO</li>
 	<li>Gerando previsões para os dados de TESTE (X_test) utilizando o método predict() do objeto "modelo"</li>
 	<li>Obtendo o coeficiente de determinação (R²) para as previsões do nosso modelo</li>
</ul>
</li>
 	<li>Obtendo Previsões Pontuais
<ul>
 	<li>Dados de entrada</li>
 	<li>Gerando previsão pontual</li>
 	<li>Criando um simulador simples</li>
</ul>
</li>
 	<li>Interpretação dos Coeficientes Estimados
<ul>
 	<li>Obtendo o intercepto do modelo</li>
 	<li>Obtendo os coeficientes de regressão</li>
 	<li>Confirmando a ordem das variáveis explicativas no DataFrame</li>
 	<li>Criando uma lista com os nomes das variáveis do modelo</li>
 	<li>Criando um DataFrame para armazenar os coeficientes do modelo</li>
 	<li>Interpretação dos Coeficientes Estimados</li>
</ul>
</li>
 	<li>Análises Gráficas das Previsões do Modelo
<ul>
 	<li>Gerando as previsões do modelo para os dados de TREINO</li>
 	<li>Gráfico de dispersão entre valor estimado e valor real</li>
 	<li>Obtendo os resíduos</li>
 	<li>Gráfico de dispersão entre valor estimado e resíduos</li>
 	<li>Utilizando os resíduos ao quadrado</li>
 	<li>Plotando a distribuição de frequências dos resíduos</li>
</ul>
</li>
 	<li>Comparando Modelos
<ul>
 	<li>Estimando um novo modelo com a substituição da variável explicativa Temperatura Máxima pela Temperatuda Média</li>
 	<li>Criando os datasets de treino e de teste</li>
 	<li>Instanciando a classe LinearRegression()</li>
 	<li>Utilizando o método fit() do objeto "modelo_2" para estimar nosso modelo linear utilizando os dados de TREINO (y2_train e X2_train)</li>
 	<li>Obtendo o coeficiente de determinação (R²) do novo modelo estimado e comparando com o resultado do modelo anterior</li>
 	<li>Gerando previsões para os dados de TESTE (X_test e X2_test) utilizando o método predict() dos objetos "modelo" e "modelo_2"</li>
 	<li>Obtendo o coeficiente de determinação (R²) para as previsões dos dois modelos</li>
</ul>
</li>
 	<li>Outras Métricas de Regressão
<ul>
 	<li>Métricas da regressão</li>
 	<li>Obtendo métricas para o modelo com Temperatura Média</li>
 	<li>Obtendo métricas para o modelo com Temperatura Máxima</li>
</ul>
</li>
 	<li>Salvando e Carregando o Modelo Estimado
<ul>
 	<li>Dados de entrada</li>
 	<li>Gerando previsão pontual</li>
 	<li>Criando um simulador simples</li>
 	<li>Salvando o modelo estimado</li>
 	<li>pickle (https://docs.python.org/3/library/pickle.html)
<ul>
 	<li>Em um novo notebook/projeto Python</li>
</ul>
</li>
</ul>
</li>
</ul>
