# Modulo-1-MTS5

# Flash Cards — Técnicas de Teste de Software

## Testing x Checking

- 1. O que é Testing?
    
    **Resposta:** Processo de exploração e experimentação para aprender sobre o produto, descobrir limitações, problemas inesperados e obter informações.
    
- 2. O que é Checking?
    
    **Resposta:** Atividade de confirmação ou verificação quando já acreditamos que algo é verdadeiro.
    
- 3. Testing x Checking?
    
    **Resposta:** **Testing explora e aprende; Checking verifica e confirma.**
    
- 4. Como James Bach caracteriza Testing?
    
    **Resposta:** Uma abordagem que combina testes exploratórios, investigação e descoberta rápida de defeitos, especialmente quando requisitos são incompletos ou mudam rapidamente.
    
- 5. Como James Bach caracteriza Checking?
    
    **Resposta:** Atividade mais mecânica e repetitiva, baseada em verificações previamente definidas.
    

## Testes Ad Hoc

- 6. O que são testes Ad Hoc?
    
    **Resposta:** Testes informais e não estruturados, realizados sem planos ou casos de teste previamente definidos.
    
- 7. Em que os testes Ad Hoc se baseiam?
    
    **Resposta:** Principalmente na experiência, conhecimento e intuição do testador.
    
- 8. Vantagem dos testes Ad Hoc?
    
    **Resposta:** Permitem investigar rapidamente situações que testes formais podem não cobrir.
    
- 9. Desvantagem dos testes Ad Hoc?
    
    **Resposta:** Podem apresentar cobertura inconsistente e dificultar a reprodução de defeitos por falta de documentação.
    
- 10. Como memorizar Ad Hoc?
    
    **Resposta:** **Freestyle:** explorar livremente usando conhecimento e experiência.
    

## Testes exploratórios estruturados / SBTM

- 11. O que é SBTM?
    
    **Resposta:** **Session-Based Test Management**, ou Gerenciamento de Testes Baseado em Sessão.
    
- 12. Ideia central do teste exploratório estruturado?
    
    **Resposta:** Explorar o software de maneira livre, mas dentro de uma estrutura definida, principalmente em relação ao tempo e objetivo.
    
- 13. Quais são os elementos básicos de uma sessão exploratória?
    
    **Resposta:** **Explorar algo + com recursos + para descobrir informação.**
    
- 14. Diferença entre Ad Hoc e exploratório estruturado?
    
    **Resposta:** Ad Hoc é mais livre e informal; o exploratório estruturado mantém a exploração, mas adiciona **objetivo, técnica, tempo e documentação**.
    

## Partição de Equivalência

- 15. O que é Partição de Equivalência?
    
    **Resposta:** Técnica de caixa-preta que divide entradas em grupos de valores que devem apresentar comportamento semelhante.
    
- 16. Por que usar Partição de Equivalência?
    
    **Resposta:** Para reduzir a quantidade de testes necessários sem precisar testar todos os valores possíveis.
    
- 17. O que é uma partição válida?
    
    **Resposta:** Conjunto de valores que o sistema deve aceitar.
    
- 18. O que é uma partição inválida?
    
    **Resposta:** Conjunto de valores que o sistema deve rejeitar.
    
- 19. Exemplo: transferência deve ser ≥ R$10. Quais as partições?
    
    **Resposta:** **Válida:** ≥ R$10. **Inválida:** < R$10.
    

## Análise de Valor Limite

- 20. O que é Análise de Valor Limite?
    
    **Resposta:** Técnica que concentra os testes nos valores próximos aos limites definidos por uma regra.
    
- 21. Por que testar valores limites?
    
    **Resposta:** Porque erros frequentemente aparecem nas condições de fronteira.
    
- 22. Quais valores são normalmente testados?
    
    **Resposta:** **Abaixo do limite + exatamente no limite + acima do limite.**
    
- 23. Se o limite é R$10, quais valores testar?
    
    **Resposta:** **R$9,99 → R$10,00 → R$10,01.**
    
- 24. Partição de Equivalência x Valor Limite?
    
    **Resposta:** Partição busca **classes de comportamento**; Valor Limite busca **fronteiras entre essas classes**.
    

## Tabela de Decisão

- 25. Quando usar uma Tabela de Decisão?
    
    **Resposta:** Quando existem múltiplas condições de entrada que se relacionam e podem produzir diferentes resultados.
    
- 26. O que a Tabela de Decisão ajuda a garantir?
    
    **Resposta:** Que as diferentes combinações relevantes de condições sejam consideradas nos testes.
    
- 27. Qual é a principal vantagem?
    
    **Resposta:** Organizar combinações de condições e seus respectivos resultados esperados.
    
- 28. Como memorizar Tabela de Decisão?
    
    **Resposta:** **Se isso + isso acontecer, o que o sistema deve fazer?**
    

## Cobertura de Sentença e Decisão

- 29. O que é Cobertura de Sentença?
    
    **Resposta:** Mede a porcentagem de instruções executáveis do código que foram executadas pelos testes.
    
- 30. O que é Cobertura de Decisão?
    
    **Resposta:** Verifica se as diferentes decisões ou ramificações do código foram exercitadas pelos testes.
    
- 31. Diferença entre sentença e decisão?
    
    **Resposta:** **Sentença:** o código foi executado? **Decisão:** os diferentes resultados das condições foram exercitados?
    

## Gherkin / BDD

- 32. Para que serve o Gherkin?
    
    **Resposta:** Para descrever comportamentos e cenários de teste de forma estruturada e compreensível.
    
- 33. Quais são as principais palavras-chave?
    
    **Resposta:** **Dado (Given), Quando (When), Então (Then)** e **E (And)**.
    
- 34. O que representa o Dado?
    
    **Resposta:** O contexto ou pré-condições necessárias para o teste.
    
- 35. O que representa o Quando?
    
    **Resposta:** A ação executada pelo usuário ou sistema.
    
- 36. O que representa o Então?
    
    **Resposta:** O resultado esperado após a ação.
    
- 37. Estrutura mental do Gherkin?
    
    **Resposta:** **Dado o contexto → Quando faço algo → Então espero determinado resultado.**
    

## ISO 29119-3

- 38. O que é a ISO 29119-3?
    
    **Resposta:** Norma relacionada à documentação de testes de software, incluindo modelos e exemplos para casos de teste.
    
- 39. Qual o objetivo de documentar casos de teste?
    
    **Resposta:** Descrever instruções e comportamentos esperados para tornar os testes mais claros, consistentes e rastreáveis.
    

## ⚡ Revisão rápida — 10 conceitos essenciais

- **Testing x Checking:** explorar x verificar.
- **Ad Hoc:** teste livre, informal e baseado na experiência.
- **Exploratório estruturado:** exploração com objetivo, tempo e estrutura.
- **SBTM:** Session-Based Test Management.
- **Partição de Equivalência:** divide entradas em classes de comportamento.
- **Valor Limite:** testa valores próximos às fronteiras.
- **Três pontos:** antes + limite + depois.
- **Tabela de Decisão:** testa combinações de condições.
- **Cobertura de Sentença:** verifica instruções executadas.
- **Cobertura de Decisão:** verifica ramificações/decisões exercitadas.

📘 Módulo 3 — QA no Ágil
