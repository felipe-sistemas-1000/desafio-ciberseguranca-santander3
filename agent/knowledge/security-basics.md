# Fundamentos de Segurança da Informação

## Conceitos Básicos
- **Vulnerabilidade:** Uma fraqueza ou brecha no software, hardware, processo ou comportamento humano que pode ser explorada por uma ameaça.
- **Ameaça:** Qualquer fator, interno ou externo, com potencial de causar dano ou explorar uma vulnerabilidade (ex: hackers, malwares, falhas humanas).
- **Risco:** A probabilidade de uma ameaça explorar uma vulnerabilidade multiplicada pelo impacto gerado. `Risco = Probabilidade x Impacto`.

## A Tríade CIA
Qualquer análise de segurança deve medir o impacto sobre os três pilares fundamentais:
1. **Confidencialidade:** Garantir que a informação só fique acessível a pessoas autorizadas.
2. **Integridade:** Garantir que a informação permaneça exata, completa e sem alterações não autorizadas.
3. **Disponibilidade:** Garantir que os sistemas e dados fiquem acessíveis sempre que os usuários autorizados precisarem.

## Boas Práticas Gerais de Desenvolvimento Seguro
- **Nunca Confie no Input do Usuário:** Toda entrada de dados (forms, URLs, APIs) deve ser tratada, validada e sanitizada.
- **Princípio do Menor Privilégio:** Usuários, sistemas e conexões de banco de dados devem ter apenas as permissões estritamente necessárias para sua função.
- **Defesa em Profundidade:** Implementar múltiplas camadas de segurança (ex: validação no frontend, validação no backend, criptografia em trânsito e em repouso).
