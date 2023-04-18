## Desvio Condicional Simples

<p>
    “Uma estrutura de seleção permite a escolha de um grupo de ações (bloco) a ser executado quando determinadas 
    condições, representadas por expressões lógicas ou relacionais, são ou não satisfeita.”
    ```
    se <expressão-lógica> então:
    <sequência-de-comandos>
    fim_se
    ```
</p>

<p>
    As ações são executadas de cima para baixo e da esquerda para a direita;<br>
    ● Geralmente, o ponto-e-vírgula <b>(;)</b> finaliza uma linha de execução de uma ação;
</p>


>Somando a idade com + 1
``` python
idade = int(input("Digite a sua idade: "))
nova_idade = idade + 1
print(nova_idade)
```