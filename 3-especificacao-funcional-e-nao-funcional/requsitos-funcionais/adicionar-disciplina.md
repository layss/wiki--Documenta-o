###  3.5.8 \[RF009\] Adicionar Disciplina

| **Prioridade: ** |  Essencial |  Importante |  Desejável |
| :--- | :--- | :--- | :--- |
| **Ator \(es\):** | Administrador |  |  |
| **Requisitos associados:** | Não há |  |  |

  
  


#### Descrição:

####  Este caso de uso permitir o administrador adicionar disciplinas no sistema.

  
  


#### Pré-condições:

####  Não há

  
  


#### Pós-condições:

####  O administrador poderá adicionar disciplinas no sistema.

  
  


#### Fluxo principal

 1. O caso de uso inicia quando o administrador seleciona a opção “Adicionar Disciplina”.

 2. O sistema apresenta o campo para adicionar a disciplinada desejada com os seguintes campos: nome, descrição e módulo.

 3. O administrador preenche o campo.

 4. O administrador escolhe a opção “Adicionar”

 5. O sistema retorna com a seguinte mensagem: “Disciplina adicionada com sucesso”

 6. O caso de uso de encerra.

  


####  Fluxos alternativos

####  \[FA009\] – Disciplina já Cadastrada

 1. No passo \(4\) do fluxo principal caso já exista disciplina cadastrada \[FA004\]

 2. O sistema deverá retornar a seguinte mensagem: “DISCIPLINA JÁ CADASTRADA”.

 3. O caso de uso se encerra.

  


#### Fluxos de erro

\[FE009\] - Erro de validação no Cadastro da Disciplina.

####  Pré-condições

#### Um ou mais campos do formulário apresentam um dos seguintes problemas:

 a. Campo obrigatório não preenchido;

 b. Campo com formato inválido;

  


