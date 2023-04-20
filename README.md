# **Endpoints FabricaNeeds**

<<<<<<< HEAD
=======

>>>>>>> FabricaNeedsBranch
## Criação e teste API REST:

<br>

## **/category**

**[GET]** http://localhost:8000/categories/get - retorna todas as categorias registradas.

**[GET]** http://localhost:8000/categories/{id} - retorna os detalhes de uma categoria específica.

**[POST]** http://localhost:8000/categories/post - cria uma nova categoria.

**[PUT]** http://localhost:8000/categories/put - atualiza as informações de uma categoria específica.

**[PATCH]** http://localhost:8000/categories/patch - atualiza parcialmente as informações de uma categoria específica.

**[DELETE]** http://localhost:8000/categories/delete - remove uma categoria específica.

<br>

## **/user** (será consumido por outra API eventualmente)

**[GET]** http://localhost:8000/users/get - retorna todos os usuários registrados.

**[GET]** http://localhost:8000/users/{id} - retorna os detalhes de um usuário específico.

**[POST]** http://localhost:8000/users/post - cria um novo usuário.

**[PUT]** http://localhost:8000/users/put - atualiza as informações de um usuário específico.

**[PATCH]** http://localhost:8000/users/patch - atualiza parcialmente as informações de um usuário específico.

**[DELETE]** http://localhost:8000/users/delete - remove um usuário específico.

<br>

## **/item**

**[GET]** http://localhost:8000/items/get - retorna todos os itens registrados.

**[GET]** http://localhost:8000/items/{id} - retorna os detalhes de um item específico.

**[POST]** http://localhost:8000/items/post - cria um novo item.

**[PUT]** http://localhost:8000/items/put - atualiza as informações de um item específico.

**[PATCH]** http://localhost:8000/items/patch - atualiza parcialmente as informações de um item específico.

**[DELETE]** http://localhost:8000/items/delete - remove um item específico.

<br>

## **/recurrency_type**

**[GET]** http://localhost:8000/recurrency_types/get- retorna todos os tipos de recorrências registrados.

**[GET]** http://localhost:8000/recurrency_types/{id} - retorna os detalhes de um tipo de recorrência específico.

**[POST]** http://localhost:8000/recurrency_types/post - cria um novo tipo de recorrência.

**[PUT]** http://localhost:8000/recurrency_types/put - atualiza as informações de um tipo de recorrência específico.

**[PATCH]** http://localhost:8000/recurrency_types/patch - atualiza parcialmente as informações de um tipo de recorrência específico.

**[DELETE]** http://localhost:8000/recurrency_types/delete - remove um tipo de recorrência específico.

<br>

## **/need**

**[GET]** http://localhost:8000/needs/get- retorna todas as demandas registradas.

**[GET]** http://localhost:8000/needs/{id} - retorna os detalhes de uma demanda específica.

**[POST]** http://localhost:8000/needs/post - cria uma nova demanda.

**[PUT]** http://localhost:8000/needs/put - atualiza as informações de uma demanda específica.

**[PATCH]** http://localhost:8000/needs/patch - atualiza parcialmente as informações de uma demanda específica.

**[DELETE]** http://localhost:8000/needs/delete - remove uma demanda específica.

<br>

## **/need_event**

**[GET]** http://localhost:8000/need_events/get- retorna todos os eventos registrados.

**[GET]** http://localhost:8000/need_events/{id} - retorna os detalhes de um evento específico.

**[POST]** http://localhost:8000/need_events/post - cria um novo evento.

**[PUT]** http://localhost:8000/need_events/put - atualiza as informações de um evento específico.

**[PATCH]** http://localhost:8000/need_events/patch - atualiza parcialmente as informações de um evento específico.

**[DELETE]** http://localhost:8000/need_events/delete - remove um evento específico.

<br>

## **/event_status**

**[GET]** http://localhost:8000/event_statuses/get- retorna todos os tipos de status registrados.

**[GET]** http://localhost:8000/event_statuses/{id} - retorna os detalhes de um tipo de status específico.

**[POST]** http://localhost:8000/event_statuses/post - cria um novo tipo de status.

**[PUT]** http://localhost:8000/event_statuses/put - atualiza as informações de um tipo de status específico.

**[PATCH]** http://localhost:8000/event_statuses/patch - atualiza parcialmente as informações de um tipo de status específico.

**[DELETE]** http://localhost:8000/event_statuses/delete’ - remove um tipo de status específico.

<br>

## **Regras de negócio**

### **/category**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/user**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/item**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/recurrency_type**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** -

<br>

### **/need**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/need_event**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/event_status**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

## ***Alterar**

**RN001** - O usuário deve possuir um email, nome e senha para se cadastrar;

**RN002** - O usuário deve estar logado para realizar ações;

**RN003** - Ações incluem cadastrar e atender demandas;

**RN004** - Cada demanda pode conter um ou vários itens;

**RN005** - Cada demanda deve ter apenas um usuário;

**RN006** - As demandas devem ter prazo;

**RN007** - As recorrências devem terminar antes de 31 de dezembro do ano em que a need foi criada;

<br>

## **Requisitos Funcionais:**

### **/category**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/user**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/item**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/recurrency_type**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** -

<br>

### **/need**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/need_event**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/event_status**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

## ***Alterar**

**RF001** - O sistema deve manter demandas;

**RF002** - O sistema deve manter itens;

**RF003** - O sistema deve manter categorias;

**RF004** - O sistema deve manter os tipos de recorrência;

**RF005** - O sistema deve manter os status dos eventos;

**RF006** - O sistema deve manter eventos;

<br>

## **Requisitos Não-funcionais:**

### **/category**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/user**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/item**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/recurrency_type**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** -

<br>

### **/need**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/need_event**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

### **/event_status**

**RN001** - 

**RN002** - 

**RN003** - 

**RN004** - 

<br>

## ***Alterar**

**RNF001** - O sistema deve funcionar rapidamente;

**RNF002** - O sistema deve ser dinâmico;

**RNF003** - O sistema deve utilizar Django como Backend;

**RNF004** - O sistema deve utilizar VueJS para o Frontend;

**RNF005** - O sistema deve ser estável para futuras modificações



