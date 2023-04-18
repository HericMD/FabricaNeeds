**<u>Endpoints FabricaNeeds</u>**

/category

**[GET]** http://localhost:8000/categories - retorna todas as categorias registradas.

**[GET]** http://localhost:8000/categories/{id} - retorna os detalhes de uma categoria específica.

**[POST]** http://localhost:8000/categories - cria uma nova categoria.

**[PUT]** http://localhost:8000/categories/{id} - atualiza as informações de uma categoria específica.

**[PATCH]** http://localhost:8000/categories/{id} - atualiza parcialmente as informações de uma categoria específica.

**[DELETE]** http://localhost:8000/categories/{id} - remove uma categoria específica.

/user (será consumido por outra API eventualmente)

**[GET]** http://localhost:8000/users - retorna todos os usuários registrados.

**[GET]** http://localhost:8000/users/{id} - retorna os detalhes de um usuário específico.

**[POST]** http://localhost:8000/users - cria um novo usuário

**[PUT]** http://localhost:8000/users/{id} - atualiza as informações de um usuário específico.

**[PATCH]** http://localhost:8000/users/{id} - atualiza parcialmente as informações de um usuário específico.

**[DELETE]** http://localhost:8000/users/{id} - remove um usuário específico.

/item

**[GET]** http://localhost:8000/items - retorna todos os itens registrados.

**[GET]** http://localhost:8000/items/{id} - retorna os detalhes de um item específico.

**[POST]** http://localhost:8000/items - cria um novo item

**[PUT]** http://localhost:8000/items/{id} - atualiza as informações de um item específico.

**[PATCH]** http://localhost:8000/items/{id} - atualiza parcialmente as informações de um item específico.

**[DELETE]** http://localhost:8000/items/{id} - remove um item específico.

/recurrency_type

**[GET]** http://localhost:8000/recurrency_types- retorna todos os tipos de recorrências registrados.

**[GET]** http://localhost:8000/recurrency_types/{id} - retorna os detalhes de um tipo de recorrência específico.

**[POST]** http://localhost:8000/recurrency_types - cria um novo tipo de recorrência

**[PUT]** http://localhost:8000/recurrency_types/{id} - atualiza as informações de um tipo de recorrência específico.

**[PATCH]** http://localhost:8000/recurrency_types/{id} - atualiza parcialmente as informações de um tipo de recorrência específico.

**[DELETE]** http://localhost:8000/recurrency_types/{id} - remove um tipo de recorrência específico.

/need

**[GET]** http://localhost:8000/needs - retorna todas as demandas registradas.

**[GET]** http://localhost:8000/needs/{id} - retorna os detalhes de uma demanda específica.

**[POST]** http://localhost:8000/needs - cria uma nova demanda

**[PUT]** http://localhost:8000/needs/{id} - atualiza as informações de uma demanda específica.

**[PATCH]** http://localhost:8000/needs/{id} - atualiza parcialmente as informações de uma demanda específica.

**[DELETE]** http://localhost:8000/needs/{id} - remove uma demanda específica.



/need_event

**[GET]** http://localhost:8000/need_events - retorna todos os eventos registrados.

**[GET]** http://localhost:8000/need_events/{id} - retorna os detalhes de um evento específico.

**[POST]** http://localhost:8000/need_events - cria um novo evento.

**[PUT]** http://localhost:8000/need_events/{id} - atualiza as informações de um evento específico.

**[PATCH]** http://localhost:8000/need_events/{id} - atualiza parcialmente as informações de um evento específico.

**[DELETE]** http://localhost:8000/need_events/{id} - remove um evento específico.

/event_status

**[GET]** http://localhost:8000/event_statuses- retorna todos os tipos de status registrados.

**[GET]** http://localhost:8000/event_statuses/{id} - retorna os detalhes de um tipo de status específico.

**[POST]** http://localhost:8000/event_statuses - cria um novo tipo de status.

**[PUT]** http://localhost:8000/event_statuses/{id} - atualiza as informações de um tipo de status específico.

**[PATCH]** http://localhost:8000/event_statuses/{id} - atualiza parcialmente as informações de um tipo de status específico.

**[DELETE]** http://localhost:8000/event_statuses/{id} - remove um tipo de status específico.


**<u>Regras de negócio</u>**

RN001 - O usuário deve possuir um email, nome e senha para se cadastrar;

RN002 - O usuário deve estar logado para realizar ações;

RN003 - Ações incluem cadastrar e atender demandas;

RN004 - Cada demanda pode conter um ou vários itens;

RN005 - Cada demanda deve ter apenas um usuário;

RN006 - As demandas devem ter prazo;

RN007 - As recorrências devem terminar antes de 31 de dezembro do ano em que a need foi criada;

**<u>Requisitos funcionais:</u>**

RF001 - O sistema deve manter demandas;

RF002 - O sistema deve manter itens;

RF003 - O sistema deve manter categorias;

RF004 - O sistema deve manter os tipos de recorrência;

RF005 - O sistema deve manter os status dos eventos;

RF006 - O sistema deve manter eventos;

RF007 - O sistema deve manter usuários;


**<u>Requisitos não-funcionais:</u>**

RNF001 - O sistema deve funcionar rapidamente;

RNF002 - O sistema deve ser dinâmico;

RNF003 - O sistema deve utilizar Django como Backend;

RNF004 - O sistema deve utilizar VueJS para o Frontend;

RNF005 - O sistema deve ser estável para futuras modificações


