# Software de manutenção de subestação elétrica: DGA++
<p align="center">
  <img src="https://s2.glbimg.com/e93cDdjv-JNAZGaHVcNfSzUC-gw=/0x0:1280x960/984x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_59edd422c0c84a879bd37670ae4f538a/internal_photos/bs/2021/c/Z/fstZ3dQ1uBfLQVdkgLtA/whatsapp-image-2021-01-08-at-14.53.41.jpeg" />
</p>
Foto: LMTE/Divulgação


## Sobre o que é este software?
Este software, nomeado de DGA++, foi desenvolvido por mim como projeto final de estágio do curso de Engenharia Elétrica, na empresa [Albras (Grupo Hydro)](https://www.hydro.com/pt-BR/sobre-a-hydro/a-hydro-no-mundo/north-america/brasil/barcarena/albras/), no ano de 2020 e recebeu segundo lugar dentre os melhores projetos.

O software foi concebido baseado em conceitos de ciência e análise de dados, no que tange à utilização e oportunidade de registro e utilização de informações úteis para auxiliar tomadores de decisão com dados.
Para a execução, utilizou-se a framework Electron, para desenvolvimento desktop, com as linguagens/tecnologias: Java Script, HTML, CSS, NodeJS, SQL.

OBS: Algumas informações sensíveis foram omitidas nas imagens utilizando barras.

_Para melhore entender o software, é necessário entender seu contexto de funcionamento_

## Como funciona a manutenção de uma subestação?
O bom funcionamento de um transformador é de grande importância para a integridade de um sistema de energia elétrica, já que este é peça fundamental no tratamento e transmissão da eletricidade e seu estado operacional influencia diretamente na estabilidade do sistema. Assim como outros equipamentos, durante sua operação o transformador é submetido a uma variedade de problemas térmicos e elétricos que pode levar a falhas. Tais falhas geram uma série de gases que são retidos pelo óleo isolante. A concentração e relativa proporção destes gases no óleo é usada para fazer a detecção e eliminação destas falhas.

A função dos engenheiros tomadores de decisão é realizar os testes nas amostras de óleo, analisar a quantidade de gases e decidir qual ação realizar naquele equipamento a partir daí.

### Como é feito hoje em dia
- Coleta-se óleo e envia-se ao laboratório;
- O laboratório retorna um documento impresso com a quantidade de cada gás;
- O engenheiro lê documento a documento utilizando métodos de cálculo e experiência para interpretar os valores.

Isso pode acarretar em alguns problemas, como:
- Não há visualização da tendência dos equipamentos nem do panorama geral da subestação;
- Análise limitada, muitas vezes, a somente 1 método;
- Método empírico de interpretação.

## Solução: Software DGA++
![image](https://user-images.githubusercontent.com/67600860/153218899-8ea041b0-66ce-4c5e-beda-c54dd13ab240.png)

O software foi feito pensado nas dores e nos requisitos do grupo de engenheiros responsáveis pela manutenção. No primeiro mês foram feitas reuniões para entender o problema e decidir que métodos e tecnologias seriam utilizados. Com o DGA++, os engenheiros tem uma ferramenta que os permite ter análises mais completas, rápidas e gerais sobre o estado operativo de um equipamento e de todo parque da subestação.

As principais melhorias e features são:

#### Análise por 3 métodos clássicos
O software realiza os cálculos de 3 métodos clássicos na teoria de manutenção, que são: Rogers, IEC e Duval.

![image](https://user-images.githubusercontent.com/67600860/153226269-49b4380c-cbfe-4fd6-8db9-29533eca6b5b.png)

#### Gráficos de tendência
Com os gráficos de tendência, os engenheiros conseguem entender quais equipamentos são mais prováveis de apresentar falhas.

![image](https://user-images.githubusercontent.com/67600860/153229413-b60856fe-cdc0-46c8-ba74-db6f49ed464a.png)


#### Mapa visual - Dashboard
1.Relação prioridade do equipamento por tipo de falha. Para os engenheiros decidirem em qual transformador atuar primeiro.

![image](https://user-images.githubusercontent.com/67600860/153227349-f9043f9d-628c-4ed8-96c7-de8fd7929d3c.png)

2.Gráfico comparando a quantidade de cada um dos principais gases entre os grupos de transformadores, para identificar se existe algum que está produzindo muito mais gases que os outros.

![image](https://user-images.githubusercontent.com/67600860/159984090-0fc60b35-fd24-4276-bdab-89c4fdac6e99.png)

3.Gráfico que relaciona os tipos de falhas dos equipamentos no tempo, para identificação de padrões.

![image](https://user-images.githubusercontent.com/67600860/153227828-22060ebe-1a58-449a-844c-4bcf8b5fe5ea.png)

4.Gráfico que correlaciona o tipo de falha com a quantidade registrada dos gases, para identificar padrões e outliers.

![image](https://user-images.githubusercontent.com/67600860/153228118-530b86c1-d5f9-4869-96dc-fb6b7aec6173.png)

#### Relatório PDF
Relatório PDF para armazenamento de informações bem como para suprir demandas de registro empresariais.

![image](https://user-images.githubusercontent.com/67600860/153228634-2b587768-b888-48f2-8369-5532f50fcd8c.png)

## Resultados alcançados

Após a implementação do software, os engenheiros perceberam aumento de:

* Confiabilidade no processo de manutenção dos equipamentos;
* Número de informações úteis sobre os equipamentos;
* Rapidez no processo de análise e consequente tomada de decisão.

A seguir, depoimento de Afonso Bitencourt, Gerente de Área de Energia & Utilidades na Albras:


https://user-images.githubusercontent.com/67600860/153223809-54735157-6a90-463a-ab84-3a774682a972.mp4


