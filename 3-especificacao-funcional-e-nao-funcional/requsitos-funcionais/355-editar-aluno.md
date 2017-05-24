  
		@page { margin: 2cm }  
		h4 { margin-left: 1.5cm; margin-top: 0cm; margin-bottom: 0cm; direction: ltr; color: \#000000; line-height: 150%; text-align: justify; page-break-inside: avoid; widows: 2; orphans: 2 }  
		h4.western { font-family: "Arial", sans-serif; so-language: pt-BR; font-weight: normal }  
		h4.cjk { font-family: "Times New Roman", serif; so-language: zh-CN; font-weight: normal }  
		h4.ctl { font-family: "Arial", sans-serif; so-language: ar-SA; font-style: italic }  
		h3 { text-indent: 1.25cm; margin-top: 0.35cm; margin-bottom: 0cm; direction: ltr; color: \#000000; text-align: justify; page-break-inside: avoid; widows: 2; orphans: 2 }  
		h3.western { font-family: "Arial", sans-serif; font-size: 12pt; so-language: pt-BR; font-weight: normal }  
		h3.cjk { font-family: "Times New Roman", serif; font-size: 12pt; so-language: zh-CN; font-weight: normal }  
		h3.ctl { font-family: "Arial", sans-serif; font-size: 12pt; so-language: ar-SA }  
		p { text-indent: 1.25cm; margin-bottom: 0.25cm; direction: ltr; color: \#000000; line-height: 120%; text-align: justify; widows: 2; orphans: 2 }  
		p.western { font-family: "Arial", sans-serif; font-size: 12pt; so-language: pt-BR }  
		p.cjk { font-family: "Calibri", sans-serif; font-size: 12pt; so-language: zh-CN }  
		p.ctl { font-family: "Arial", sans-serif; font-size: 11pt; so-language: ar-SA }  
		a:link { color: \#0000ff }  
	

1. 1. 1. ### **\[RF005\] Editar Aluno**

| **Prioridade:** |  Essencial \(X\) |  Importante |  Desejável |
| :--- | :--- | :--- | :--- |
| **Ator \(es\)** | Adiministrador |  |  |
| **Requisitos associados:** | Não há |  |  |

  
  


#### Descrição:

 Este caso de uso deve permitir a edição de dados dos alunos pela administração.

####  

#### Pré-condições:

 Aluno está cadastrado.

  


#### Pós-condições:

#### O administrador poderá editar os dados dos alunos.

  
  


#### Fluxo principal

 1. O caso de uso inicia quando o administrador seleciona a opção“Editar Aluno”.

 2. O sistema apresenta a mensagem: “TEM CERTEZA QUE DESEJA EDITAR” \[FA005\]

 3. O administrador seleciona a opção “SIM”.

 4. O sistema apresenta a mensagem: ALTERADO COM SUCESSO!

 5. O caso de uso de encerra.

####  

#### Fluxos alternativos

####  \[FA005\] – Editar Aluno

 1. No passo \(2\) do fluxo principal caso o administrador seleciona a opção “NÃO”

 2. O caso de uso se encerra

  


  
  


