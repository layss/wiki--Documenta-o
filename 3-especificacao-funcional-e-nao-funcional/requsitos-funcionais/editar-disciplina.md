###  3**3.5.9 \[RF010\] Editar Disciplina**

| **Prioridade:** |  Essencial \(X\) |  Importante |  Desejável |
| :--- | :--- | :--- | :--- |
| **Ator \(es\):** | Administrador |  |  |
| **Requisitos associados:** | Não há |  |  |

  
**Descrição:** Este caso de caso de uso permitir editar os conteúdos da disciplina no sistema.

**Pré-condições:** As disciplinas devem está cadastradas no sistema.

**Pós-condições:** O administrador terá como editar algum dado da disciplina.

#### Fluxo principal

1.   O caso de uso inicia quando o administrador seleciona a opção “Editar Disciplina”.
2.   O sistema apresenta a mensagem: “TEM CERTEZA QUE DESEJA EDITAR” \[FA010\]
3.   O administrador seleciona a opção “SIM”.
4.   O sistema apresenta a mensagem: ALTERADO COM SUCESSO!
5.   O caso de uso de encerra.

#### Fluxos alternativos

##### \[FA010\] – Editar Disciplina

*  No passo \([2](#_Fluxo_principal)\) do fluxo principal caso o administrador seleciona a opção “NÃO”
*  O caso de uso se encerra

  


