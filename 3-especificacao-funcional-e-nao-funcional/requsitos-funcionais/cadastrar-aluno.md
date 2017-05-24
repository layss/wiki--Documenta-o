### 3.5.4 \[RF004\] Cadastrar Aluno

| Prioridade: | Essencial \(X\) | Importante | Desejável |
| :--- | :--- | :--- | :--- |
| **Ator \(es\)** | Adminidtrador |  |  |
| **Requisitos associados** | Não há |  |  |

Descrição: Este caso de uso deve permitir inclusão dos alunos

Pré-condições: Não há.

Pós-condições: Os alunos terão acesso às aulas.

#### Fluxo principal

1. O caso de uso inicia quando o administrador seleciona a opção Cadastrar Aluno.
2. O sistema apresenta formulário para preenchimento, com os campos: nome, turma, e-mail, senha, telefone e curso.
3. O professor preenche as informações solicitadas pelo formulário.
4. O administrador escolhe a opção Incluir \[FA004\].
5. O sistema realiza as validações dos campos informados \[FE004\].
6. O administrador escolhe a opção “confirmar”.
7. O sistema retorna com a seguinte mensagem “Aluno cadastrado com sucesso” 
8. O caso de uso de encerra.

#### Fluxos alternativos

##### \[FA004\] – Aluno já cadastrado

1. No passo \(4\) do fluxo principal caso já exista o aluno cadastrado \[FA004\]
2. O sistema deverá retornar a seguinte mensagem: “ALUNO JÁ CADASTRADO”.
3. O caso de uso se encerra

#### Fluxos de erro

##### \(FE004\) – Erro de validação no Cadastro do Aluno.

Pré-condições

Um ou mais campos do formulário apresentam um dos seguintes problemas:

1. Campo obrigatório não preenchido;
2. Campo com formato inválido;

2.5.5 \[RF005\] Editar Aluno

Prioridade:

X Essencial Importante Desejável

Ator \(es\):

Administrador

Requisitos

associados:

Não há

Descrição:

Este caso de uso deve permitir a edição de dados dos alunos pela administração.

Pré-condições:

Aluno está cadastrado.

Pós-condições:

O administrador poderá editar os dados dos alunos.

Fluxo principal

1. O caso de uso inicia quando o administrador seleciona a opção“Editar Aluno”.

1. O sistema apresenta a mensagem: “TEM CERTEZA QUE DESEJA EDITAR”

\[FA005\]

1. O administrador seleciona a opção “SIM”.

1. O sistema apresenta a mensagem: ALTERADO COM SUCESSO!

1. O caso de uso de encerra.

Fluxos alternativos

\[FA005\] – Editar Aluno

1. No passo \(2\) do fluxo principal caso o administrador seleciona a opção

“NÃO”

1. O caso de uso se encerra

2.5.6 \[RF006\] Remover Aluno

Prioridade:

X Essencial Importante Desejável

Ator \(es\):

Administrador

Requisitos

associados:

Não há

Descrição:

Este caso de caso de uso permitir remover o aluno

Pré-condições:

Aluno deverá está cadastrado no sistema.

Pós-condições:

O administrador terá como remover o aluno do sistema.

Fluxo principal

1. O caso de uso inicia quando o administrador seleciona a opção“Remover Aluno”.

1. O sistema apresenta a mensagem: “TEM CERTEZA QUE DESEJA REMOVER”

\[FA006\]

1. O administrador seleciona a opção “SIM”.

1. O sistema apresenta a mensagem: REMOVIDO COM SUCESSO!

1. O caso de uso de encerra.

Fluxos alternativos:

\[FA006\] – Remover Aluno

1. No passo \(2\) do fluxo principal caso o administrador seleciona a opção “NÃO”

1. O caso de uso se encerra

2.5.7 \[RF007\] Visualizar Pontuação

Prioridade:

X Essencial Importante Desejável

Ator \(es\):

Professor

Requisitos

associados:

Não há

Descrição:

Este caso de uso deve permitir que, os professores de cada disciplina cadastrada no

sistema tenha um espaço reservado para visualizar a pontuação de seus alunos nos

exercícios realizados.

Pré-condições:

Professor deverá está cadastrado no sistema.

Pós-condições:

Os professores de cada disciplina cadastrada no sistema poderão visualizar a

pontuação de seus alunos nos exercícios realizados, podendo ver o desempenho de

cada individuo.

Fluxo principal

1. O caso de uso inicia quando o professor seleciona a opção Visualizar Pontuação.

1. O sistema apresenta os exercícios realizados pelos alunos e suas pontuações

1. O caso de uso de encerra.



