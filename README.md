<table width="100%">
  <!-- Linha 1: O Banner Azul Claro com o Texto -->
  <tr>
    <td bgcolor="#add8e6" align="center" valign="middle" style="padding: 30px; border-radius: 12px 12px 0 0;">
      <h1 style="color: #0d233a; margin: 0 0 8px 0; font-size: 32px; font-weight: 800; border-bottom: none;">🚂 PROJETO ANÁLISE DE DADOS</h1>
      <p style="color: #2c3e50; margin: 0; font-size: 18px; font-weight: 500;"><b>Análise de dados aplicada ao sistema ferroviário</b></p>
    </td>
  </tr>
  <!-- Linha 2: A Imagem do Trem Centralizada Logo Abaixo -->
  <tr>
    <td align="center" valign="middle" style="padding: 15px; background-color: #ffffff; border-radius: 0 0 12px 12px;">
      <img src="https://github.com/VanusaRibeiro/projetoanalisededados/blob/main/imgtrem.jpg" width="1500" style="width: 1500; max-width: 400px; height: 200px;            object-fit: cover; border-radius: 8px;" />
    </td>
  </tr>
</table>

1.Introdução

A análise de dados permite identificar padrões operacionais, melhorar a eficiência logística e auxiliar na tomada de decisões estratégicas.

Neste projeto foi desenvolvido um estudo utilizando dados ferroviários fictícios com foco em:<br>

limpeza e proteção de dados<br>
estatística descritiva<br>
clusterização hierárica/aglomeração<br>
visualização de dados categóricos<br>

2.Objetivos<br>
Objetivo Geral<br>

Analisar dados ferroviários utilizando técnicas de mineração e visualização de dados.<br>

Objetivos Específicos<br>

Realizar limpeza e tratamento dos dados<br>
Aplicar proteção/anomização de informações<br>
Executar análise estatística descritiva<br>
Aplicar clusterização hierárquica<br>
Visualizar dados categóricos<br>
Identificar padrões operacionais<br>

3.Fundamentação Teórica<br>
3.1 Mineração de Dados<br>

A mineração de dados consiste no processo de descoberta de padrões úteis em grandes conjuntos de dados.<br>

3.2 Estatística Descritiva<br>

A estatística descritiva é utilizada para resumir e organizar dados através de:<br>

média<br>
mediana<br>
frequência<br>
desvio padrão<br>
gráficos<br>

3.3 Clusterização Hierárquica<br>

A clusterização hierárquica agrupa objetos semelhantes em clusters.<br>

Foi utilizado o método aglomerativo com distância euclidiana.<br>

4.Metodologia<br>
4.1 Coleta dos Dados<br>

Foi utilizado um dataset ferroviário fictício contendo as seguintes variáveis:<br>

| Variável | Tipo |
| :--- | :--- |
| **linha** | categórica |
| **atraso_min** | numérica |
| **passageiros** | numérica |
| **carga_ton** | numérica |
| **clima** | categórica |
| **velocidade_media_kmh** | numérica |

4.2 Limpeza e Proteção de Dados<br>
Etapas realizadas:<br>
Remoção de duplicidades<br>
Após análise foram obtidos os seguintes insigts:<br><br>
<img src="https://github.com/VanusaRibeiro/projetoanalisededados/blob/main/status%20das%20viagens.png" width="800" style="width:800; max-width: 400px; height: 400px;            object-fit: cover; border-radius: 8px;" />

6. Resultados:<br>

Após a análise dos dados, foram identificados três grupos principais:<br>

viagens eficientes : 0<br>
viagens com alto atraso: 1<br>
viagens de alta carga: 2<br>

Resultado da Média por atrasos:<br>

linha<br>
LN-01    30.0<br>
LN-02    20.0<br>
LN-03    90.0<br>
LN-04    40.0<br>
LN-05    -5.0<br>

LN-03 - linha com resultado crítico paresentando maior atraso médio em todo o sistema;<br>
As linhas LN-01 (30.0), LN-02 (20.0) e LN-04 (40.0) apresentando atrasos moderados;<br>
LN-05 apresentando anomalias, indicando em média que as viagens nessa linha chegaram adiantadas.<br>

De acordo com os resultados do projetos foram observados um maior atraso em condições climáticas severas.<br>
<br>
7.Conclusão<br>

A aplicação de técnicas de mineração e visualização de dados:<br> permitiu identificar padrões relevantes no sistema ferroviário.<br>

A clusterização hierárquica possibilitou separar grupos operacionais semelhantes, enquanto as análises descritivas auxiliaram na compreensão dos indicadores ferroviários.<br>
Essa observação faz parte dos resultados principais obtidos após a análise de mineração e visualização dos dados ferroviários, que também identificaram outros padrões importantes:

Linha Crítica: A linha LN-03 foi a que apresentou o maior índice de atraso médio entre todas as analisadas<br>
Agrupamento (Cluster 1): O processo de clusterização hierárquica identificou um grupo específico de viagens (Cluster 1) caracterizado justamente por apresentar um alto atraso<br>
Métricas Gerais: O dataset registrou um atraso médio geral de 38 minutos, com picos que chegaram a 132 minutos.<br>
As visualizações categóricas facilitaram a interpretação dos dados e contribuíram para a análise exploratória.<br><br>

| Problema           | Target              |
| ------------------ | ------------------- |
| Predição de atraso | atraso_min          |
| Falha mecânica     | falha_detectada     |
| Consumo energético | consumo_energia_kwh |
| Risco de acidente  | severidade          |

<br>
De acordo com um script gerado para detectar falhas,foi observado que :<br>
TR-101 e TR-103 foram os únicos a registrar falhas mecânicas confirmadas dentro do conjunto de dados de manutenção analisados.<br>
O script filtra apenas as linhas onde a variável falha_detectada é igual a "SIM"<br>
No dataset ficticio, apenas esses dois trens atenderam a esse critério<br>
TR-101: Este trem registrou 1 falha no sistema de freios durante uma manutenção do tipo corretiva, <br>gerando um custo de BRL 45.000 e mantendo o ativo parado por 18; horas<br>
TR-103: Também registrou 1 falha, especificamente no motor elétrico.<br>
Esta foi a ocorrência mais crítica do levantamento, apresentando o maior custo (BRL 67.000) e o maior tempo de inatividade (24 horas)<br><br>

<img src="https://github.com/VanusaRibeiro/projetoanalisededados/blob/main/falhas%20detectadas.png" width="800" style="width:800; max-width: 200px; height: 100px;            object-fit: cover; border-radius: 8px;" />

Features utilizadas: Temperatura do motor Vibração, Clima, Distância, Histórico de manutenção, Pressão de freio, Idade do trem<br>

8. Tecnologias Utilizadas<br>
Python<br>
Pandas<br>
Scikit-learn<br>
Matplotlib<br>
Seaborn<br><br>
9. Referências
Han, J.; Kamber, M. Data Mining: Concepts and Techniques.
Montgomery, D. Estatística Aplicada.
Documentação oficial do Python
Documentação oficial do Pandas
Documentação oficial do Scikit-learn

