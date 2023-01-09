# Projeto_individual_04


1-Existem outras entidades além de Cursos, Turmas e Alunos?

Existe uma entidade no qual os atributos são os dados dos professores.


2-Quais são os principais campos e tipos?

Os pricipais campos são as chaves primárias e os atributos definidos como 'not null' pos estes são essenciais na modelagem.


3-Como as entidades estão relacionadas?

Cursos possui relacionamento 1:1 com Cursos pois cada curso tem somente um professor e possuiu relacionamento de 1:n com Turmas pois as Turmas podem ter vários Cursos.
Turmas possui relacionamento de 1:n com Professores e de 1:n com Cursos.
Professores possui relacionamento de 1:1 com Cursos e 1:1 com Dados Professores
Alunos possuiu relacionamento de 1:n com Turmas.




