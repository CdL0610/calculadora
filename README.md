# calculadora


variavel operador chama todos os botões de operação (id*=operador sera todos com id parecido com operador

numeros.foreach insere o event click em cada um tecla de numero

variavel inserir numero chama o numero que sofre evento click e o manda para o display (para variavel dispaly) para ser exibido

operador.for each chama o botão de operação que sofrer um click

variavel atualizardisplay limpa o display se uma operação sofrer click, caso apenas numeros sejam digitados vão apenas sendo adicionados no display (BR vai adicionar a virgula de decimal caso haja alguma no calculo

variavel novonumero guarda na memoria o(s) numero(s) digitados antes da operção mesmo apos o display ser limpo

variavel selecionaroperdador guarda a operação que sofreu click mesmo após o display ser limpo mas com condição que não pode ser chamada em um numero novo

variavel operacao pendente vai verificar se operador esta indefinindo para encaminhar para calcular

variavel calcular vai calcular se houver operção pendente e atualiza o display com o resultado do calculo

variavel mapateclado direciona as teclas de teclado para as teclas da calculadora

variavel mapear teclado usa o evento keydown restrito apenas para as teclas presnetes na calculadora e aciona o click na tela

variavelnumeroanterior guarda o numero para fazer a operação e numeroatual apresneta o resultado apos a operação

variavel teclapermitida verifica se a tecla que sofre o keydown no teclado esta na calculadora (mapateclado), se for chama mapear teclado

eval pode realizar todas a operações matematicas basicas, emcurtando bastante a quantidade de linhas de codigo necessarias

variavel resultado usa o eval para realizar o calculo e o atualizarresultado manda para o display

igual usa getelementbyid para chamar os numeros e a operação para usar no calcular porem chama a variavel ativar igual que zera o valor de operador assim se clicar em oitro operador, não ira chamar calcular sem que use o igual outra vez

variavel limpar display (CE) seleciona valor do display como vazio sem cancelar o calculo por completo

variavel limpar calculo (C) seleciona o valor do display como vazio, operador como indefinindo, numero anterior como indefinido e chama numero novo

variavel backspace remove o ultimo numero usando o slice para remover o ultimo caractere

variavel inverter sinal chama atualizardisplay multiplicando o valor no display -1 (display.textcontent * -1) e chama novo numero para não realizar um caulculo com o valor negativo e o positivo

variavel decimal adiciona uma virgula com a contdição que ja não haja alguma no display (variavel existedecimal), se não houver valor nenhum em display (variavel existevalor), um zero sera adicionado antes da virgula 

varivel existedecimal verifica se ha uma virgula com (indexof(','). index of vai buscar o valor selecionado

variavel existevalor verificar se ha algum valor em display pelo tamanho (display.textcontent.legth>0)
