# Projeto desenvolvido para o bootcamp de engenharia de dados da DIO.
O projeto consistem em criar uma instância de um [banco de dados](https://github.com/julianazanelatto/power_bi_analyst/tree/main/M%C3%B3dulo%203/Desafio%20de%20Projeto) previamente fornecido na azure e transformar os dados.

## Transformação de dados
Tabelas extras foram criadas para ajudar a visualizar algumas questões. Em uma situação com um volume grande de dados, esta poderia não ser a melhor opção. Mas tendo em vista a pouca quantidade de dados, tabelas extras foram criadas para destacar as descobertas em relação aos dados, para atender questões solicitadas no desafio e para verificar a representação dos gráficos. 


Passos realizados:


1) Separei o campo de endereço dos funcionários em 5: House Number, Street Name, City e State.


2) Salary alterado para decimal Fixo.
O James é o único sem gerente associado, indicando que ele pode ser o chefe. Uma tabela mostrando funcionarios e gerentes foi criada, no caso do James o valor estava vazio e foi alterado para "chefe". Outro indicativo é que outros gerentes estão associados a ele e seu salário é maior.</li>


3) Não existem departamentos sem gerentes. James é responsável pelo departamento de Headquartes,Jennifer de admnistration e Franklyn de research. Uma tabela foi criada para que possa ser verificado essa questão.


4) Uma nova tabela foi criado juntando todos os funcionarios e departamentos para verificar se existem funcionários que ainda não estão associados a departamentos. Todos os departamentos possuem pelo menos um funcionário e todos os funcionários estão associados a um departamento.Além disso foi pedido para que nessa tabela mesclasse o nome e sobrenome.


5) Uma nova tabela departamento e local foi criada (solicitado pelo desafio).


6) Algumas taabelas foram estendidas para facilitar as consultas, como a tabela works_on. 


7) Para saber quantos colaboradores existem por gerente, foi utilizado o gráfico árvore hierárquica no relatório. (solicitado pelo desafio).

## Relatório
[Clique aqui para acessar o relatório publicado](https://app.powerbi.com/view?r=eyJrIjoiMDMwNmU3MGQtMWE5Zi00YzViLTk4NWYtMGExYzBkYzY1MzdiIiwidCI6ImRlMzBiODk3LWVhZGQtNDkxMS1iN2IxLTJlODExOGM1MDkzZCJ9)

<img src="Imagens\Relatorio.png" alt="">
