# semana-18-aula-depuracao

## Pergunta 1 - Rastreamento Lógico

* Explique, detalhadamente, por que o uso incorreto do operador de atribuição simples (=) no lugar do operador de acumulação (+=) dentro do laço de repetição resultou na devolução apenas do processamento da última venda da lista.

R: Porque o (+=) pega o total_acumulado, soma ele mesmo mais o valor_venda e o imposto, basicamente somando cada parte em vez de substituir o valor acumulado.

## Pergunta 2 - Eficiência analítica

* Por que a técnica de utilizar um Breakpoint associada ao Step Over é estruturalmente superior e mais limpa do que espalhar comandos print() por todo o código para tentar descobrir o estado das variáveis?

R: Porque a depuração utilizando breakpoint trás mais detalhes do código, para analizar o código de maneira mais cirurgica, e também não precisa escrever prints para todo lado apenas para descobrir o problema, e depois apagar. 

## Pergunta 3 - Maturidade profissional

* Relate como a junção de um Teste Unitário (que acusou o erro de gabarito final) com o processo de Depuração (que encontrou a linha exata do erro) garante um desenvolvimento de software altamente profissional e à prova de regressões.

R: Garante porque faz o código ter o máximo de eficiência com essas ferramentas, garantindo um funcionamento correto do código e trazendo confiabilidade no seu trabalho.