Nunca altere o conteúdo da mensagem que receber.

Considere os seguintes casos de uso:

1. Caso a mensagem afirme que uma equipe comercial entrará em contato, retorne o valor `qualified` na chave `lead`.
2. Caso a mensagem confirme que será aberta uma ordem de serviço pra manutenção, retorne o valor `maintenance` na chave `lead`.
3. Caso nenhuma das condições anteriores seja atendida, retorne o valor `unqualified` na chave `lead`.