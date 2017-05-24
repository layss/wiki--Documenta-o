### 3.5.5 **\[RF005\] Editar Aluno**

| **Prioridade:** | Essencial \(X\) | Importante | Desejável |
| :--- | :--- | :--- | :--- |
| **Ator \(es\):** | Adiministrador |  |  |
| **Requisitos associados:** | Não há |  |  |

**Descrição:** Este caso de uso deve permitir a edição de dados dos alunos pela administração.

**Pré-condições:** Aluno está cadastrado.

**Pós-condições: **O administrador poderá editar os dados dos alunos.

#### Fluxo principal

1. O caso de uso inicia quando o administrador seleciona a opção“Editar Aluno”.
2. O sistema apresenta a mensagem: “TEM CERTEZA QUE DESEJA EDITAR” \[FA005\]
3. O administrador seleciona a opção “SIM”.
4. O sistema apresenta a mensagem: ALTERADO COM SUCESSO!
5. O caso de uso de encerra.

#### Fluxos alternativos

##### \[FA005\] – Editar Aluno

* No passo \(2\) do fluxo principal caso o administrador seleciona a opção “NÃO”
* O caso de uso se encerra



