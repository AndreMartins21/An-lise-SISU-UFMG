<p align = "center"> 
 <img src = "https://user-images.githubusercontent.com/64978311/115966529-5df93f00-a504-11eb-9330-d67492b1253b.png"/>
 </p>

## 📂 Arquivo: 

[SISU UFMG](https://www.ufmg.br/sisu/wp-content/uploads/2021/04/M%C3%A1ximos-e-M%C3%ADnimos-ap%C3%B3s-Chamada-regular.pdf)
(Clique para acessar o PDF contendo todas as informações)

## Objetivo:

**/>** Esse repositório foi de grande valia para os seguintes aspectos: 

- Responder algumas questões que podem surgir em torno do arquivo contendo as notas da primeira edição do SISU UFMG;

- Melhorar meu desempenho na prática de analises de dados, me fazendo aprender a manipular arquivos não convencionais, como foi o caso desse PDF;

- Me fez aprender mais acerca de Regex (Regular Expression)
<br>

**/>** Questões analisadas nesse repositório:

- Maior nota por modalidade selecionada para o SISU UFMG 2021;

- Cursos com as maiores notas POR MODALIDADE (Cotas e A.C.);

- Cursos com as menores notas POR MODALIDADE (Cotas e A.C.);

- Menor nota por modalidade selecionada para o SISU UFMG 2021.

## Instruções:


**</>** O arquivo Excel [***Dashboard Sisu.xlsx***](https://github.com/AndreMartins21/SISU-UFMG/blob/main/Dashboard%20Sisu.xlsx), contém, dinamicamente, o resultado de toda a análise realizada. Segue abaixo uma pequena amostra desse dashboard:

![image](https://user-images.githubusercontent.com/64978311/116014377-57092400-a60b-11eb-8e68-af41f52f2b62.png)

--------------------------------------------------------------

**</>** No arquivo [***DFbruto.ipynb***](https://github.com/AndreMartins21/SISU-UFMG/blob/main/DFbruto.ipynb), está contido todo o processo de construção do dataframe bruto a partir do PDF. Nele, utilizei três bibliotecas do Python: 

```
. PyPDF2 = Utilizada para transformar o conteúdo de um PDF em uma string;

. Regex = Trata-se das expressões regulares, que facilitam expressivamente o trabalho de buscas por cadeias de caractéres específicos em uma string;

. Pandas = Ferramenta essencial para manipulação, filtração e análise de dados. 
```
--------------------------------------------------------------

**</>** Já no arquivo [***DFespecífico.ipynb***](https://github.com/AndreMartins21/SISU-UFMG/blob/main/DFespec%C3%ADfico.ipynb) há o procedimento de criação do dataframe específico para ser usado no Excel. Em tal arquivo, fiz uso das librarys:
```
. Numpy = Biblioteca do Python usada para criação de arrays multidimensionais (Utilizei-a como testes em alguns casos)

. Pandas
```

## Parceria:

- Para a efetivação de todo o trabalho de análise, elaborei tudo conjuntamente ao parceiro Gilmar:

🔗 Github: [https://github.com/Gilnior](https://github.com/Gilnior)

