# Miniguia de Estudos: IA para Tomada de Decisão (Fuzzy & Machine Learning)🎯 Contexto e Objetivos
Este repositório contém o resultado de um desafio de aprendizagem ativa utilizando o NotebookLM. O objetivo foi explorar como a Inteligência Artificial, especificamente a Lógica Fuzzy e o Aprendizado de Máquina, pode ser aplicada em cenários financeiros e de análise de risco, transformando dados qualitativos e imprecisos em decisões quantificáveis.

## 📚 Curadoria de Fontes 
### Para a construção deste caderno, foram utilizadas as seguintes fontes abertas e materiais acadêmicos:
#### Aula 05 - IA: Lógica Fuzzy (Prof. Relton Alves da Silva).
#### Aula 06 - IA: Aprendizado de Máquina (Prof. Relton Alves da Silva).
#### Aula 08 - IA: Redes Neurais (Prof. Relton Alves da Silva).
#### Material Complementar: Lógica Fuzzy (Adailton de Jesus Cerqueira Junior).

## 🧠 Engenharia de Prompts e "Cicatrizes"
### Durante o desenvolvimento, testei variações de prompts para extrair o raciocínio lógico da IA sobre os documentos:
#### Prompt Estratégico: "Baseado na Aula 05, como a lógica fuzzy ajudaria a dar um score de crédito para alguém que ganha 'médio'?"
#### Cicatrizes (Troubleshooting): O desafio inicial foi garantir que a IA não utilizasse conhecimento genérico de internet, mas sim as fórmulas de Fuzzificação e Defuzzificação presentes nos slides. Ajustei o prompt para pedir especificamente a explicação técnica do processo de Centróide.

## 📖 Miniguia de Estudo (Entrega Final)
### Resumo Estruturado: 
### O Processo Fuzzy em FinançasDiferente da lógica clássica (binária), a lógica fuzzy permite lidar com o "meio-termo". Para dar um score de crédito, o sistema segue três etapas:
#### Fuzzificação: Transforma um valor exato (ex: Salário de R$ 5.000) em um grau de pertinência (ex: 75% "Médio" e 25% "Inadequado").Inferência: Aplica regras lógicas como "SE o dinheiro é Médio E o número de dependentes é Alto, ENTÃO o risco é Normal".
#### Defuzzificação: Consolida as áreas de influência das regras e calcula, através do método do Centróide, um valor numérico final para o score.📝 Glossário de ConceitosAprendizado de Máquina: Processo pelo qual um sistema melhora sua performance através da experiência.
#### Variável Linguística: Termos imprecisos que representam conceitos (ex: "frio", "caro", "médio").
#### Redes Neurais: Processadores paralelos que armazenam conhecimento experimental, sendo altamente tolerantes a falhas.Overfitting: Quando o modelo "decora" os dados de treino e falha ao receber novos dados (problema de generalização).

## 🚀 Prompts Reutilizáveis
#### "Explique o 'Dilema de Occam' na Inteligência Artificial e como ele afeta a escolha entre modelos simples e complexos." 
#### "Descreva o Princípio de Bonferroni e o risco de encontrar padrões sem sentido em grandes bases de dados." 
