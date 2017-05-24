### DICIONÁRIO DE DADOS

##### Entidade: **ITEM**

| Atributo | Classe | Domínio | Tamanho | Descrição |
| :--- | :--- | :--- | :--- | :--- |
| IDTBL\_ITEM | Determinante | INTEGER | 11 | Número sequencial que identificará o código do item |
| ID\_ADMINISTRADOR | Determinante | INTEGER | 11 | Número sequencial que identificará o código do administrador |
| IDDISCICLINA | Determinante | INTEGER | 11 | Número sequencial que identificará o código da disciplina |
| NOME | Simples | VARCHAR | 255 | Nome de definição do item |
| DESCRIÇÃO | Simples | LONG TEXT |  | Detalhamento das características do item |
| IMG\_1 | Simples | VARCHAR | 255 | Imagem 1 do item |
| IMG\_2 | Simples | VARCHAR | 255 | Imagem 2 do item |
| IMG\_3 | Simples | VARCHAR | 255 | Imagem 3 do item |
| IMG\_4 | Simples | VARCHAR | 255 | Imagem 4 do item |
| IMG\_5 | Simples | VARCHAR | 255 | Imagem 5 do item |
| DATACADASTRO | Simples | DATETIME |  | Data do cadastro do item |
| BOLATIVO |  | SMALLINT | 6 |  |
| observação | Simples | LONTEXT |  | Outras informações importantes do item |

##### 

##### Entidade: **ADMINISTRADOR**

| Atributo | Classe | Domínio | Tamanho | Descrição |
| :--- | :--- | :--- | :--- | :--- |
| Idtbl\_administrador | Determinante | INTEIRO | 11 | Número sequencial |
| Nome | Simples | VACHAR | 255 | Nome de definição do administrador |
| Senha | Multivalorado | VACHAR | 80 | Identificação de caracteres criptografados |
| Datacadastro | Simples | DATETIME | 10 | Data do cadastro do administrador |

##### 

##### Entidade: **AVALIAÇÃO**

| Atributo | Classe | Domínio | Tamanho | Descrição |
| :--- | :--- | :--- | :--- | :--- |
| IDTBL\_AVALICAO | Determinante | INTEGER | 11 | Número sequencial que identificará o código da avaliação |
| COD\_ALUNO | Determinante | INTEGER | 11 | Número sequencial que identificará o código do aluno |
| COD\_ITEM | Determinante | INTEGER | 11 | Número sequencial que identificará o código do item |
| NOTA | Simples | INTEGER | 11 | Valor numérico para identificar a nota da avaliação |
| DATACADASTRO | Simples | DATETIME |  | Data do cadastro da avaliação |



##### Entidade: **ALUNO** 	

| Atributo | Classe | Domínio | Tamanho | Descrição |
| :--- | :--- | :--- | :--- | :--- |
| IDTBL\_ALUNO | Determinante | INTEGER | 11 | Número sequencial que identificará o código do aluno |
| NOME | Simples | VARCHAR | 255 | Nome de definição do aluno |
| SENHA | Simples | VARCHAR | 255 | Identificação de caracteres criptografados |
| DATACADASTRO | Simples | DATETIME | 10 | Data do cadastro do aluno |



##### Entidade: **PROFESSOR**

| Atributo | Classe | Domínio | Tamanho | Descrição |
| :--- | :--- | :--- | :--- | :--- |
| IDTBL\_PROFESSOR | Determinante | INTEGER | 11 | Número sequencial que identificará o código do professor |
| NOME | Simples | VARCHAR | 255 | Nome de definição do professor |
| SENHA | Simples | VARCHAR | 255 | Identificação de caracteres criptografados |
| CODDISCIPLINA | Simples | INTEGER | 11 | Código que identificará a disciplina |
| DATACADASTRO | Simples | DATETIME |   | Data do cadastro do professor |



##### Entidade: **DISCIPLINA** 	

| Atributo | Classe | Domínio | Tamanho | Descrição |
| :--- | :--- | :--- | :--- | :--- |
| IDTBL\_DISCIPLINA | Determinante | INTEGER | 11 | Número sequencial que identificará o código da disciplina |
| ID\_PROFESSOR | Determinante | INTEGER | 11 | Número sequencial que identificará o código do professor |
| NOME\_CURSO | Simples | VARCHAR | 255 | Nome de definição do curso |
| NOME | Simples | VARCHAR | 255 | Nome de definição do professor |
| DATACADASTRO | Simples | DATETIME |   | Data do cadastro da disciplina |



