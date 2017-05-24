### 3.5.1 **\[RF001\]Cadastrar Professor**

| **Prioridade:** | Essencial \(X\) | Importante | Desejável |
| :--- | :--- | :--- | :--- |
| **Ator \(es\)** | Adminidtrador |  |  |
| **Requisitos associados** | Não há |  |  |

**Descrição:** Este caso de uso deve permitir a adição dos professores no sistema.

**Pré-condições: **Não há

**Pós-condições: **O professor terá acesso ao sistema, com seu login e senha onde poderá fazer a avaliação dos alunos.

#### Fluxo principal

1. O caso de uso inicia quando o administrador seleciona a opção Cadastrar Professor.
2. O sistema apresenta formulário para preenchimento, com os campos: Nome do professor e nome da matéria, email e telefone.
3. O administrador preenche as informações solicitadas pelo formulário.
4. O administrador escolhe a opção Incluir \[FA001\].
5. O sistema realiza as validações dos campos informados \[FE001\].
6. O administrador escolhe a opção “confirmar”.
7. O sistema retorna com a seguinte mensagem “Professor cadastrado com sucesso”
8. O caso de uso de encerra.

#### Fluxos alternativos

#### \[FA001\] – Professor já cadastrado

1. No passo \(4\) do fluxo principal caso já exista o professor cadastrado
2. O sistema deverá retornar a seguinte mensagem: “PROFESSOR JÁ CADASTRADO”.
3. O sistema retorna para o passo \(3\) do fluxo principal
4. O caso de uso se encerra

#### Fluxos de erro

#### \[FE001\] – Erro de validação no Cadastro do Professor.

##### Pré-condições

Um ou mais campos do formulário apresentam um dos seguintes problemas:

1. Campo obrigatório não preenchido;
2. Campo com formato inválido;



