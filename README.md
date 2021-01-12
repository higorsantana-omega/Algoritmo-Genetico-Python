# Algoritmo Genético Python
 
Um algoritmo genético (AG) é uma técnica para achar soluções aproximadas de problemas em otimização e busca. Assim sendo, um algoritmo extremamente simples e eficiente.

## Componentes Principais
*Indivíduo*
- Indivíduos representam as soluções
- O cromossomo representa uma solução
- O indivíduo pode ser o próprio cromossomo na maneira mais simples possível, ou pode conter o cromossomo como atributo

*Seleção*
- Operadores genéticos são utilizados em indivíduos selecionados dentro da população
- Indivíduos mais aptos serão selecionados mais frequentemente que os menos aptos
- Deve-se simular o mecanismo de seleção natural que atua sobre as espécies biológicas
- Privilegiar indivíduos com função de avaliação alta, sem desprezar completamente com função baixa

*Reprodução*
- Combina pedaços do cromossomo de dois genitores gerando filhos mais aptos e consequentemente com o passar das gerações a população tende a evoluir
- Representa a reprodução assexuada