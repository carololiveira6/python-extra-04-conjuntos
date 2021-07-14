## **Table of Contents**
- [Extra - Conjuntos](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1b_ee_01-conjuntos.html&ref=master#mcetoc_1egvsckqv3) 
  - [Objetivo](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1b_ee_01-conjuntos.html&ref=master#mcetoc_1f3b8ajms0)
  - [Preparativos](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1b_ee_01-conjuntos.html&ref=master#mcetoc_1f362b6b11)
  - [Fruits](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1b_ee_01-conjuntos.html&ref=master#mcetoc_1f45t7sub0)
  - [Emails](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1b_ee_01-conjuntos.html&ref=master#mcetoc_1f45t7sub1)
  - [Entradas e saídas](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1b_ee_01-conjuntos.html&ref=master#mcetoc_1egvoav555g)
- [Entregáveis](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1b_ee_01-conjuntos.html&ref=master#mcetoc_1egvoav555j) 
  - [Repositório](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1b_ee_01-conjuntos.html&ref=master#mcetoc_1egvrpv6k1l4)
- [Critérios de aceitação](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1b_ee_01-conjuntos.html&ref=master#mcetoc_1eh146n6m3) 
# **Extra - Conjuntos**
Para essa entrega, criará filtros a partir de operações entre conjuntos.
## **Objetivo**
Essa atividade foi elaborada para trabalhar seus conhecimentos sobre operações e funcionalidades dos conjuntos em Python.
## **Preparativos**
Todas as funções devem estar em um arquivo padrão main.py

Para definir suas funções, utilize o nome das funções idênticos aos destacados em cada um dos tópicos:
## **Fruits**
Utilize os conjuntos definidos [neste snippet](https://gitlab.com/-/snippets/2067562 "Fruits") para os exercícios a seguir:

- **spanish\_and\_brazilian\_fruits(spanish\_fruits, brazilian\_fruits)** 
  - **Parâmetros:** 
    - spanish\_fruits: Conjunto de frutas típicas da Espanha
    - brazilian\_fruits: Conjunto de frutas típicas do Brazil
  - **Procedimento:** Intersecção entre o conjunto spanish\_fruits e o conjunto brazilian\_fruits
  - **Retorno:** Uma **LISTA** contendo o resultado da operação entre os conjuntos
- **spanish\_and\_japan\_fruits(spanish\_fruits, japanese\_fruits)** 
  - **Parâmetros:**  
    - spanish\_fruits: Conjunto de frutas típicas da Espanha
    - japanese\_fruits: Conjunto de frutas típicas do Japão
  - **Procedimento:** Deve obter a intersecção entre o conjunto spanish\_fruits e o conjunto japanese\_fruits
  - **Retorno:** Uma **LISTA** contendo o resultado da operação entre os conjuntos
- **brazilian\_and\_japan\_fruits(brazilian\_fruits, japanese\_fruits)** 
  - **Parâmetros:**  
    - brazilian\_fruits: Conjunto de frutas típicas do Brazil
    - japanese\_fruits: Conjunto de frutas típicas do Japão
  - **Procedimento:** Deve obter a intersecção entre o conjunto brazilian\_fruits e o conjunto japanese\_fruits
  - **Retorno:** Uma **LISTA** contendo o resultado da operação entre os conjuntos
- **popular\_spanish\_or\_brazilian\_fruits(popular\_fruits, spanish\_fruits, brazilian\_fruits)** 
  - **Parâmetros:** 
    - popular\_fruits: Conjunto das frutas mais populares
    - spanish\_fruits: Conjunto das frutas típicas da Espanha
    - brazilian\_fruits: Conjunto das frutas típicas do Brasil
  - **Procedimento:** Deve obter a intersecção entre o conjunto popular\_fruits e a união entre os conjuntos spanish\_fruits e brazilian\_fruits
  - **Retorno:** Uma **LISTA** contendo o resultado da operação entre os conjuntos
- **popular\_only\_spanish\_fruits(popular\_fruits, spanish\_fruits, japanese\_fruits, brazilian\_fruits)** 
  - **Parâmetros:** 
    - popular\_fruits: Conjunto das frutas mais populares
    - spanish\_fruits: Conjunto das frutas típicas da Espanha
    - japanese\_fruits: Conjunto de frutas típicas do Japão
  - **Procedimento:** 
    - Intersecção entre o conjunto popular\_fruits e o conjunto resultante da seguinte operação
    - Diferença entre o conjunto spanish\_fruits e a união entre o conjunto japanese\_fruits e o conjunto brazilian\_fruits
  - **Retorno:** Uma **LISTA** contendo o resultado da operação entre os conjuntos
## **Emails**
Utilize os conjuntos definidos [neste snippet](https://gitlab.com/-/snippets/2007542 "Fruits") para os exercícios a seguir:

- **only\_yahoo\_emails(emails\_list)** 
  - **Parâmetros:** 
    - email\_list: Lista de emails
  - **Processamento:** 
    - Filtra da lista de emails apenas **aqueles que são do domínio yahoo**
    - **Elimina repetições** dentre os emails do domínio yahoo selecionados
  - **Retorno:** Retorna um **conjunto** contendo todos os emails **yahoo** sem repetição



- **only\_hotmail\_emails(emails\_list)** 
  - **Parâmetros:** 
    - email\_list: Lista de emails
  - **Processamento:** 
    - Filtra da lista de emails apenas **aqueles que são do domínio hotmail**
    - Elimina repetições dentre os emails do domínio hotmail selecionados
  - **Retorno:** Retorna um **conjunto** contendo todos os emails **hotmail** sem repetição
- **only\_br\_emails(emails\_list)** 
  - **Parâmetros:** 
    - email\_list: Lista de emails
  - **Processamento:** 
    - Filtra da lista de emails apenas **aqueles que terminam com "br"**
    - Elimina repetições dentre os emails selecionados
  - **Retorno:** Retorna um **conjunto** contendo todos os emails que terminam com "br" sem repetição
-----
## **Entradas e saídas**
- Confira [neste snippet](https://gitlab.com/-/snippets/2067567) os **resultados esperados** para os exercícios sobre **fruits**
- Confira [neste snippet](https://gitlab.com/-/snippets/2071254) os **resultados esperados** para os exercicios sobre **emails**
- **Atenção ->** O seus resultados nao necessitam estarem **exatamente** na ordem como do snippet, porém todos os itens devem estar no conjunto, veja a dica abaixo para uma melhor implementação dos testes

**Dica** **->** Para desenvolver os testes, dê uma olhada no método **sorted** : [How to Sort in Python](https://docs.python.org/pt-br/dev/howto/sorting.html)

-----
# **Entregáveis**
## **Repositório**
- Link do **repositório** do **GitLab**
- **Código fonte:** 
  - arquivo **main.py**.
- **Privacidade** 
  - Incluir **ka-br-out-2020-correcoes** como reporter.
-----
# **Critérios de aceitação**

|**pts**|**Dado**|**Quando**|**É esperado**|
| :-: | :-: | :-: | :-: |
|0.5|spanish\_and\_brazilian\_fruits|Executado os testes de acordo com a especificação para esta função|Que o retorno seja igual o especificado|
|0.5|spanish\_and\_japan\_fruits|Executado os testes de acordo com a especificação para esta função|Que o retorno seja igual o especificado|
|0.5|brazilian\_and\_japan\_fruits|Executado os testes de acordo com a especificação para esta função|Que o retorno seja igual o especificado|
|0.5|popular\_spanish\_or\_brazilian\_fruits|Executado os testes de acordo com a especificação para esta função|Que o retorno seja igual o especificado|
|0.5|popular\_only\_spanish\_fruits|Executado os testes de acordo com a especificação para esta função|Que o retorno seja igual o especificado|
|0.5|only\_yahoo\_emails|Executado os testes de acordo com a especificação para esta função|Que o retorno seja igual ao especificado|
|0.5|only\_hotmail\_emails|Executado os testes de acordo com a especificação para esta função|Que o retorno seja igual ao especificado|
|0.5|only\_br\_emails|Executado os testes de acordo com a especificação para esta função|Que o retorno seja igual ao especificado|


**Boa diversão, devs!😺**
























