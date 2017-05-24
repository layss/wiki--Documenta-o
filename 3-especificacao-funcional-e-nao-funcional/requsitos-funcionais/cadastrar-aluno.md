### 3.5.4 \[RF004\] Cadastrar Aluno

| Prioridade: | Essencial \(X\) | Importante | Desejável |
| :--- | :--- | :--- | :--- |
| **Ator \(es\)** | Adminidtrador |  |  |
| **Requisitos associados** | Não há |  |  |

**Descrição: **Este caso de uso deve permitir inclusão dos alunos

**Pré-condições:** Não há.

**Pós-condições: **Os alunos terão acesso às aulas.

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



