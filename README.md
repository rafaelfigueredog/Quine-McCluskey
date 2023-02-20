# Quine-McCluskey
The Quine-McCluskey algorithm is a method used to simplify boolean expressions. This is an implementation of the algorithm using Python.

##  Installation

1. Clone the repository: `git clone https://github.com/rafaelfigueredog/Quine-McCluskey.git`
2. Change to the project directory: `cd Quine-McCluskey`

## Usage 

~~~bash
python main.py
~~~

# Example Usage

~~~yml
Simplificador de Expressões Booleanas:
Versão 2.1

Digite um numero inteiro entre 1 e 10:
Nº Variáveis: 3 # Number of outputs on truth table. 
Vamos lá! voce selecionu 3 variáveis. 
Digite entre espaços as 8 saídas da tabela verdade.
Saídas: 0 1 0 1 0 1 0 1 # Outputs of truth table from 0 to 7.

Implicantes (Ordem 0):
('1', '001')
('3', '011')
('5', '101')
('7', '111')

Implicantes (Ordem 1):
('1,3', '0-1')
('1,5', '-01')
('3,7', '-11')
('5,7', '1-1')

Implicantes (Ordem 2):
('1,3,5,7', '--1')

Primos Implicantes 
('1,3,5,7', '--1')

Primos Implicantes Essenciais
('1,3,5,7', '--1')

Expressão Bool. Simplificada 

S = C
~~~

## How it Works
The Quine-McCluskey algorithm works by comparing the minterms of a boolean expression to each other and grouping those that differ by only one bit. It continues to group the resulting terms until no more grouping is possible. The resulting groups are used to generate the simplified boolean expression.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
This project was completed as part of my university coursework. I would like to thank my professor and classmates for their help and support.
