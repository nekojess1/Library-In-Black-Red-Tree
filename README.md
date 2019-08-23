# Eleições  :page_with_curl:

### Professor: Tiago Alessandro Espínola Ferreira
### Período: 2019.1
### Disciplina: Algoritmos e estrutura de dados

### Alunos: 
- Jéssica Alves de Souza
- João Marcelo Alves
- Lucas Spicollys Leão de Lima
- Steffane Ribeiro da Silva
        
### O projeto consiste em aplicar os conhecimentos adquiridos na disciplina para fazer um projeto. Nós utilizamos como estrutura de dados a árvore rubro-negra, aplicando para a resolução de um problema real.

### Estrutura:  
Foram instanciadas duas árvores, a primeira foi utilizada para armazenar os números de todos os títulos válidos, chamada árvore de eleitores e a segunda para armazenar os números de todos os títulos que já votaram até o momento, chamada árvore de votação. 

### Proposta:  :clipboard:
A proposta do projeto foi de criar um sistema que consiga contar os votos e checar quais os títulos que realizaram o processo de votação e os que não votaram, tomando algumas medidas como:  verificar no momento que um indivíduo vota se o título de eleitor dele é válido e, verificar também, se este eleitor ainda não votou. 



Assim, o sistema construído foi composto de duas partes: Cadastramento de Títulos de Eleitor e Votação. 

**Entre as suas funcionalidades estão:**  


- Cadastrar título, Descadastrar título e Carregar títulos (onde os números são gerados automaticamente para preencher a árvore).

- Cadastrar candidatos (nome e número).

- Nova votação (onde a árvore de votação que guarda os títulos que já votaram é reiniciada e todas as informações guardadas são apagadas liberando a memória dinamicamente alocada).

- Adicionar voto (ler número do título e o voto).

- Gerar votos aleatórios (para encher a árvore de votação mais rapidamente).

- Apresentar o resultado parcial da eleição.

- Sair do programa encerrando-o e destruindo todas as estruturas.

Além disso, foi feito um menu para auxiliar o usuário na utilização do programa.


