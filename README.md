# <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"> Condições, Loops e Exceções na Prática com Java
www.dio.me


#### Utilizando linguagem Java por:
- [Luiz Felipe](https://github.com/)
# Desafio 02 / 05 - Verificação de Número de Conta Bancária
## Descrição
Você está desenvolvendo um programa simples em Java para simular operações bancárias básicas. A aplicação deve permitir ao usuário realizar depósitos, saques e consultar o saldo em uma conta bancária virtual.

## Entrada


* O programa exibirá um menu com as seguintes opções:

Depositar
Sacar
Consultar Saldo
Encerrar
* O usuário escolherá uma dessas opções digitando o número correspondente.

## Saída

* Utilizando um switch, o programa realizará a operação escolhida pelo usuário.
* Se o usuário escolher:
 
   º 1: O programa solicitará o valor a ser depositado e atualizará o saldo. Além disso, deve imprimir o saldo atual com a mensagem "Saldo atual: {saldo com 1 casa decimal}".
  
   º 2: O programa solicitará o valor a ser sacado e verificará se há saldo suficiente. Sendo assim, deve imprimir "Saldo atual: {saldo com 1 casa decimal}" quando o saldo for suficiente e "Saldo insuficiente."

   º 3: O programa apenas exibirá o saldo atual da conta: "Saldo atual: {saldo com 1 casa decimal}".

   º 0: O programa encerrará, imprimindo "Programa encerrado.".

  
## Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.
<table>
  <thead>
    <tr align="left">
      <th>Entrada</th>
      <th>Saída</th>
    </tr>
  </thead>
  <tbody align="left">
    <tr>
      <td>
        1      
        50      
        2 
        100 
        0
      </td>
      <td>Saldo atual: 50.0
Saldo insuficiente.
Programa encerrado.
      </td>
    </tr>
    <tr>
      <td>3
          1
          550 
          0
      </td>
      <td>Saldo atual: 0.0
Saldo atual: 550.0
Programa encerrado.</td>
    </tr>
    <tr>
      <td>1
          1000
          2
          500
          0
</td>
      <td>Saldo atual: 1000.0
Saldo atual: 500.0
Programa encerrado.</td>   
    </tr>
  </tbody>
  <tfoot></tfoot>
</table>
