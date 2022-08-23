# Calculando Spread

## 1. Google Colab (para quem não tem Python e Jupyter Notebook instalado na máquina)
- Abrir a página https://colab.research.google.com/
- Se precisar, realize o login no google e em seguida na tela que aparecer ir em upload e escolhe esse arquivo, ou então utilize github e cole a link abaixo
```
https://github.com/joaoxfernando/Calculando-Spread/blob/main/Calculando%20Spread.ipynb
```
- Pode partir para o próximo passo

## 2. Como utilizar


Só será necessário alterar os dados de algumas variáveis da célula abaixo. Os dados são:
- nome_empresa = preencher com o nome da empresa (pode preencher da maneira que lhe agradar. O comando .lower() no final irá converter o nome para minúscula, pois será utilizado para criar o arquivo .xslx no final do processo.
- par_tickers > Preencher com os pares das ações que deseja comparar, sempre adicionando o sufixo .SA, exemplo:
    - Os tickers 'BBDC3' e 'BBDC4' vão ficar **'BBDC3.SA'** e **'BBDC4.SA'**
- data_inicial e data_final: período que irá realizar a comparação, deverá ser preenchida no formato ANO-MÊS-DIA.

Após esse processo, não será necessário realizar mais nenhuma edição.

Basta apertar ctrl + enter até a útlima célula (5x) ou então ir no menu **Cell > Run all**

Ao final do processo será gerado o arquivo .xlsx que poderá ser baixado caso esteje rodando esse notebook no Google Colab