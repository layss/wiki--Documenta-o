## 2.2 Plano de Gerência de Configuração

Essa seção incorpora ao Plano de Projeto o Plano de Gerência de Configuração, que documenta as atividades e padrões de gerência de configuração a serem adotados durante o projeto.

### 2.2.1 Itens de configuração

A tabela abaixo identifica os itens que estarão sob a gerência de configuração, apresentando uma breve descrição de cada um.

### 2.2.2  Ferramentas, Ambiente e Infraestrutura

| **Item de Configuração** | **Descrição** |
| :--- | :--- |
| Sistema Operacional | Windows 7 Pro Peck 3 |
| Controle de Versão | [GIT](http://git-scm.com/) |
| Ambiente de Desenvolvimento \(IDE\) | Intel XDK |
| Editor de Diagramas |  [draw.io](http://draw.io/)  |
| Comunicação | WhatsApp |

###  2.2.3 Nomenclatura para identificadores

Modelo: \[Nome da Empresa\]\_\[Nome do Projeto\]\_\[Modelo do Artefato\]\_\[data da ultima atualização do documento \(ddmmaa\)\].doc

**Ex: Tewpo\_WIKI JK\_PlanoGerenciaConfiguracao\_210317.doc**

### 2.2.4 Numeração das versões

Deve-se seguir o seguinte padrão para a numeração dos builds:

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAckAAACuCAMAAABqZwYVAAAAY1BMVEUAAAAzMzMzM2YzZjMzZmZmMzNmM2ZmZjNmZmZmZplmmWZmmZmZZmaZZpmZmWaZmZmZmcyZzJmZzMzMmZnMmczMzJnMzMzMzP/M/8zM////zMz/zP///8z////8A/sAAAD///93Q9I+AAAAH3RSTlP///////////////////////////////////////8AzRl2EAAADx9JREFUeJztXelisyoQ5aZZzKKmJhqN+v6veZlhdUuMErF8nB9pIzqMHDgMI62EeLiC2sMFeCZdgWfSFXgmXYFn0hV4Jl2BZ9IVeCZdgWfSFXgmXYFn0hV4Jl2BZ9IVeCZdgWfSFXgmXYFn0hV4Jl2BZ9IVeCZdgWfSFXgmXYElJmO1tS9rlpSy4He26U2rKJAl8TTb9Yo3Kdpy4CDv/9AskK0dTLRcKtMkaZRk8vhPOdG4Z7KDh2qAxvi4ycP5VNOZ1rgNxrby8H2qbc9kF6lqAU1f876Dn+LU30vu8uhlsmnPZA/UpKXp614cC2dYLrXWLdTRn56Dn8Iz2QNNBOXIkdHK4dWVbxH3mK6v8ljy4tI38Ez2IVFtwKVUkTs1ImGoNh3Tmm5vZ1j2TPZCzWescQsZkswYNQg1JcoQOOxwawKRRuTkMMoMbDJZqVZAEZTNEs02rQU9KR5Qwz2cbVzhqhE5ddVkClZFQYtfc+3bfp62ArRFDhvvKr6qZhuX0Nc7m/lOz4NdeVeSF2gR59OAZbUuJbdab3OD2qppyozlrynYZbLYKRGUo2ZqJq0JlQaAUSjzPiY1UI1z1l3swi6TDX0y29aacsdamGxwSGrD3ujkOxGWmdSXfhzTl+1NnJXJTCYczIx3hN4J5yxsTME2kyqrI1TWlOGe4U625sISPZFkZGafC+tM5s22nr8AkUhIBwa1VZuHZy9/jcA6k0193Zm03B7uMzLnHegpgdCc2Rmwz2QjBHyYNNwZlKam4KbpeTliY1gBk/qEZjKTVtfHJpHm0mkP3az1lSTDCphM9WYxN2zq9hzc3gsyA1qG3na6VcI+k0WjuUOjtu+6aXMB5vomyXoNTG4bTBqOAzffaHI9RvsxZnUurDPZSQ0YzHA35mBjut1YqNrOmyvYZrK7fj8ata/smrJY6YsbsxHaLFhm8iFT22pvo9EQwjyTWhbQZPJvNiwzKZ8Ip9rgNKmvxpnUgyjbD5cbsMvkTWuT6CsNZJrJpz4RGF0yzYVVJtUC+9lYjbyOXz/i5jMm356c6yvJFU2StWUm5dyI1Gm69TIitMmkvpJc0yRZ22VSLkBO7Lu+F+QFLDKpL5nCMQYXhEUmVYzD8+aavl5fXGeRSfIaY6r4GuzVr3a3yofL2hOGF6k1z+SQb5ZqlgsQLRWgHnC90FfP5JBvdipW8Y22fNT0dTie8EwO+WalXrVXtBHLD/+ts4Jncsg3K/VKHT01j6v12n7oUs/kkG82qlVjr5Wa0x4OD+mrZ3LIN6v1e5iCZ9IVeCZdgWfSFXgmXYFn0hV4Jl2BZ9IVrIFJ+x5MwsrcXgGT1h2YCvtNp8M+k7brn4M1+W6dyTU1xudYkfe2mVxRU0yC7YGgYJnJ1bTDdKzlFuwyuZZWmIWV3IRVJper+qs1rUNhbTK5YM1frmoNVFpkcsmKv13XCqi0x+Sy9X6dSutcWmNy4Wq/X51tKm0xuXStC9Rne2Vup/7FK12kQrtLcytMWqjTeSptMOlw57G5plu+brcnZnuLusWZdD1WtraqW5pJ95evtlYDC9frc4Nfq3RZJv+JdL2d21yWyX/mCZqVFYHrqmOp8uWXBAsy+W/tGFo8lFyuQuspZrcrXI5J20RacGDhqXmh6qwTaSXZu2QQslBl9om0tDZYrqZvM0m0T8sgTmeZv88k2F8HkXb+P4es8usNvUAF9om0+p9WuCz9cSbt/58aBqv/ModwB75byRJMrohKdytfhsn1UOlu7QsxuRoqbdb9p5lcD4+11V3aC3ToBZj8pv3PYHma/ONMftP6x7C9IfWbzbGqMeMxA55JV+CZdAWeSVfgmXQFnklX4Jl0BZ5JVzCJySv5nV3tTAMvcZ37RsG/2L1HMUnIgf0Q32e/etFoUxGyadgsZvvnMJP7rFb3F18MVDvbhG7s56HbDGe/HtiUe/cF+9RIJtPwI6sjLBozBcaukVmbE03xV0ipq5cUr5FMlvDWJLa5itTaZxHDW5Oe9POGZz7P9G5idkISwFnpkZCz/uLlZE+CX3Z9ciHkOP+l97BTqGh7xj4r9C+jnzizwy/bmJ+QBtzJi+6C7l5I3fvkZcxUHHTtqsPTq7NHmhx/5igm6zjuZRLB3nYGDcRfBXqBohBT//wtk+qWQvV8J5JnzwM1Fl77mWSV4yc945d9P2PRGX9lR6I+9y4fu0dIcqk/af1R9zb6zHFMZodeJqOiTvGVxRlEHRkJ8hpCx5QWBdA9E/IfPfLYyfe+Zjin5XB9Qva07LlR74SdCHBv189kVKJ/FZ2xDrTukPpUxlAh8+9ONtSbbCPf1p6RfYHvdKdiQnYlPbAl40WDasCQODyleKEkZLTH7K/CeRSvO+3YR70p7gepDiAfwZtmGstkTRnpYbL5eeFvriOB6EsX9hrJXA7KgB2A4pC9wjd7/X7tEQBj2+ylZ/gZQDMz9/jBM3OhkgMvYgeYezlzb7xEgjjE/ZVr4nWTr/oLayVex7Y6REodTkpLXlU+kskkfM+k9mycmxXW1QJGHe+UTQW6F71nUn90rxcZc0/XrtZnXMAbxuOKfoI4BLTD0BgjEeJABWpHf2Q/8gWqGdk98K3koA4HOP2/1+I1mkmqG2tm8snds81kvR8hDielXcI816pCKsCJSQIUH9nL5TP9jdZ9lY9ksr6kb5kMSdm4BI6ggw8pX1zhmBajkj1fOzgCzL3kbQMeubqqg9I9IVyae7z9nm9Ere1IEk8RBwN9ajyT2Q5/BCAJcb+bCVOKMgtFrVQYaNMUKuKJSVDUxY2dvYXg5/BBSPHCvQdzj/aPOwQ1ff6lzL0qi8TBO2pavpXuXUlY1Dlezss+CcjgsnKSOCzKZL3FH7jQ2A+4KV/aK2u9tCbrYg9fD1gcsrK5Q5LXxX1Klf2Of9dOA3bc28FXdqe87IM1Ibur2whxqJrXgALw8C/kxwN2DpM6rhxh/QIfMMkj4isszYbcfMa0KYJ7ofrPnS7Zzlq3Lih/N95tYel90bMG08CM8QaEn/HQsKhiSlJwq1T/huSE7h6kNm4l7xTUvegT95h2sX5AqUhfiAPw9shloEsVABKi+V6uhxJyLOsSp4yUbOnpz4OBiMdjHFhb/se76QtxiDviIF4mr1ZkO3X9sV3WX7ln0hhYW8ZKHG7D4rChzPyW2uQHmQFdoGA8X/n1kPJ8J16eSVfgmXQFnklX4Jl0BZ5JV/AJk4Fc0AZT6Q9UPs8wTloq7p9EL5NFDI9UwrRqHC3JTv729kEUWwC1A+eKbCf6qXmBltuP8ivp3Gi07/yPq1Mfk3Ldum8cVpmk7O3+lIxbaO2mfGrP3yZCWE7bhz/eMrM0kwGp+g7HPzJxX+u/fYoeJk8kyEEDi7TZOKlMdV/Ju90tKWadkrbx39nZcl73vW35RmZn/b7MZDGgR9tQk6rykzRvE10m40bvLuMDCVjzh9CnIPMQBzzdG5B9wouuR7J5qstOKv9LcQ/YNi2eC06OZHfFggRUPK6g1+wJObERnF3I5jbo8IU9bOKWk4D8oHdnrJB6tGWXprBDJ4b+rZlOA77lohYmCClvXDlk/iw7850ZhO8qYxvPuHNhM087Hs9h1chlCn+CtAh0mHw05sBqq6QMzqz24n7rimUK79xK86kB20v8YH6pHVtwYSH3QPDcIq0wZwbCWhZf6wGwTdQVmuMu/HLLpaqo3opMpTJdnlSxuB987kFwPAsmU/YTd5Xh45Aan/0wj2c8vkmHVeNXzhUzpKXDZNJQzoDtOgFyC7g5SPDTjgOz3TkqoUWRVLJLGoLHptRsh5Hq8SxOzKEJLnEJxuTJUBKwB+SAy7mC/jukdBV232yD08kxLDAE4s5F4VN4hMBKlOlLlDcqZkxSbxLWB1lJRi45Sk9CDwR8/MewpSsANjYZ3teE9g4IHc8BNMgduz9/kn2i+oZqlzO1651Lx6DDJJtyY9ajUyI2h8It/vLBj56IyIPggRRoUoOZ9+tDVjdOTOl5+nV1Ds+1CGzBEYuTRnEP+D7MbcvynbZt49Lq98xUQpp+tC2rJxH6Z3dXmVYcij0aEwI3QnZcESLsXNy68KI8vLzvMfZ7I7gd06GzNt1F9PcYfYigN4mtXxEeKIXgMcSaQvItpdCqZ9oQ4joYWlyr7jCeozjTzw4H/GXlt4blC1T4lFtVA1V0r5Vp3eFGG7Y/JeNdJptHPkJOfp5sgxV/GsIcgU7xgLYJmLND9/0eA0zW0Pvv/Esu57g9ft+QunkzezYws4aRlO/d0U7UGwOvuGQPSgK97hGHYrZ65y+Er+c3ln/JKcuZZWm6Y3lZJlG38MInijlvroy6lqKgxPjtky3v7dtpORWJOeBMxJN/bJFKbgTD2Q4COnEJC501iX/gGUcREwrlrLS9ZADWL/b8upK0O0gP0ASbreFcUWPJLEuPtrzHlaKY6GfLW+9jUtu21WXyNGqXWy/OSBL5gathmoxYPbDpF9o3Rl8jZn8SOkzSiegOt/yAIBEDngRbDzsNRLFP3KZJi44F/KEFFl3rBgcZnlGxtgtgozqeCDMtbSm0xkY57n4K6t+sFDuYA3IWZvuQIYc0bHkwFyph+YaXltJyCUELNahMB+TStNxlMsEa+K6yqIfJDCSyzvYThg4awU18Ma7hWGfD3gxFWyK+TUV3jr0KdYlxkqE4QHfBgcmzP1q4wSKgrJm+YbIG21VqGWlE/LB2XSB+5UubQpkdiii4ZdG5xJT6C8xWaobllq+1ZjpT87NqW51J9lcjPbvKtJMmr0JKnGtgxmLRNN/YCttHlVQVc7bjd5mk3XZDb/iGykSX2psrqhLb/BWRQ8plFNbIJyzD5LW+ehEppwsTfxprhLDRgV34wC1a8NuTDpMEuIG/qNqkLLHwoKu+cDATJCScWX6G8IdWlagwO9I2TuAEuig9pmxSUKYrcPiuMvhtJmvYrhXCrrIfGjbRhUcPk5g2OE7IDGSwALljLgdGAvUco7aU9rY7/AoHqT4NLqPfo4dJjy9AUzMuGDgj3nGKzBvlE+GZXAYBicUfY2YXchRpFNCYgAc7+3TWMz/PpCvwTLoCz6Qr8Ey6As+kK/BMugLPpCvwTLoCz6Qr8Ey6As+kK/BMugLPpCvwTLoCz6Qr8Ey6As+kK/BMugLPpCvwTLoCz6Qr8Ey6AuLhCv4Hs5tsqGFjoX8AAAAASUVORK5CYII=)

**Figura 1 – Regra para numeração das versões**

O número inicial do build é **0.0.0**. Quando cada release interno for lançado, o segundo dígito deve ser incrementado. Desse modo, o primeiro release interno é nomeado **0.1.0**. Quando um build \(que não constitua um release interno\) for gerado, deve-se incrementar o terceiro dígito. Desse modo, o primeiro build lançado depois do primeiro release interno é nomeado **0.1.1**. O segundo release interno será **0.2.0**. Quando for lançado o primeiro GoldenRelease, deve-se incrementar o primeiro dígito e zerar os demais dígitos, o que no caso resulta na versão de número **1.0.0**.

### 2.2.5 Procedimentos para Integração Contínua

Essa seção define, essencialmente, como se dará o processo de construção de builds no projeto. Um build é uma versão operacional da aplicação que demonstra um subconjunto dos requisitos da aplicação final a ser desenvolvida, não constituindo necessariamente um release interno. Costuma-se dizer que a geração de builds atua como um medidor do batimento cardíaco do projeto.

Será utilizado no projeto o conceito de builds periódicos, onde a demanda de builds será definida, pela necessidade da realização de testes de unidade durante o desenvolvimento.

Após a geração do build, deve-se automaticamente verificar os erros de compilação e se todos os itens especificados no documento de build foram incluídos corretamente.

A princípio todos participantes do projeto podem realizar as operações \(check-in, check-out, update, merge, lock, unlock e tag\) sobre os itens de configuração.

### 2.2.6 Organização e Responsabilidades

| **Nome** | **Responsabilidades** |
| :--- | :--- |
| Rafael Gaudêncio | Elaboração, revisão e aprovação deste plano de gerenciamento de projeto |

### 2.2.7 Atividades e Cronograma Macro

| **Atividade** | **Responsabilidade** | **Data Término** |
| :--- | :--- | :--- |
| Geração do Build 0.0.1 |   | 23/04/2017 |
| Geração do Build 0.0.2 |   | 27/04/2017 |
| Geração de Builds a se determinar na Fase de estabilização |   | 23/03/2017 a31/03/2017 |

  


