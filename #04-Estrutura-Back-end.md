Estrutura de pastas e arquivos

O projeto é feito partindo de um padrão MVC mas pode conter alguns adicionais para auxiliar.

**/database/ -\>**  Devem conter apenas arquivos que não seram compilados, como migrations e seeders.

**/database/seeder -\>** Pasta de seeder

**/database/migrations -\>** Pasta de migrations

**/dist -\>** Pasta onde fica os arquivos após compilados, não deve ser commitada, onde o servidor roda

**/src -\>** Pasta de desenvolvimento, em sua maioria typescript

**/src/models -\>** Pasta de models (Comunicação com o banco de dados), os arquivos aqui são em JS, criados pelo sequilize. Para facilitar, a maior parte das funções deve ser criada na pasta services que sera em typescript

**/src/controllers -\>** Pasta de controllers

**/src/services -\>**  Pasta para complementar os models, de preferencia os controllers fazem referencia a esta, e esta aos models

**/src/routes -\>** Página para definir os routes