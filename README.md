<body>
	<h1>Projeto de Seleção de Região de Perfuração: Maximizando o Lucro na Exploração de Petróleo</h1>
	<h2>Descrição do Projeto:</h2>
	<p>A empresa de mineração Oleobrás precisa encontrar o melhor lugar para um novo poço de petróleo. Para isso, é necessário coletar parâmetros de poços de petróleo na região selecionada e construir um modelo para prever o volume de reservas nos novos poços. Em seguida, os poços com os maiores valores estimados são escolhidos e a região com o maior lucro total para os poços de petróleo selecionados é selecionada. A técnica de bootstrapping é usada para analisar o lucro potencial e riscos.</p>
	<h2>Descrição dos Dados:</h2>
	<p>Os dados de exploração geológica para as três regiões estão armazenados em arquivos csv: geo_data_0.csv, geo_data_1.csv, geo_data_2.csv. Cada arquivo contém os seguintes campos:</p>
	<ul>
		<li>Id: (identificador único de poço de petróleo)</li>
		<li>f0, f1, f2: (três características de pontos)</li>
		<li>product: (volume de reservas no poço de petróleo, em milhares de barris).</li>
	</ul>
	<h2>Etapas do Projeto:</h2>
	<ol>
		<li>Coletar os parâmetros de poços de petróleo na região selecionada: a qualidade de petróleo e o volume de reservas.</li>
		<li>Construir um modelo para prever o volume de reservas nos novos poços e testá-lo para cada região.</li>
		<li>Armazenar todos os valores necessários para o cálculo de lucro em variáveis separadas e calcular o volume de reservas suficiente para desenvolver um novo poço sem prejuízos.</li>
		<li>Escrever uma função para calcular o lucro de um conjunto de poços de petróleo selecionados e predições do modelo, escolhendo os poços com os valores mais altos de predições e sumarizando o volume alvo de reservas de acordo com essas predições.</li>
		<li>Calcular riscos e lucro para cada região usando a técnica de bootstrapping com 1000 amostras, encontrando lucro médio, intervalo de confiança de 95% e risco de prejuízo. Selecionar a região com o lucro médio mais alto e risco de prejuízo inferior a 2.5%.</li>
	</ol>
</body>
</html>
