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
