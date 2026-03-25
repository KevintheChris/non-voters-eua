# 🇺🇸 O que é considerado "ser americano" para o eleitor dos EUA?

## 📊 Descrição do Projeto
Este projeto de análise de dados explora as perceções dos cidadãos dos Estados Unidos sobre o que significa ser um "bom americano". Utilizando dados de pesquisas de opinião, o objetivo é entender como diferentes atitudes sociopolíticas (como votar, protestar, exibir a bandeira ou apoiar o exército) são valorizadas por diferentes perfis demográficos e eleitorais (frequentes, esporádicos e não-eleitores).

## 🎯 Objetivos da Análise
O projeto está dividido em quatro partes principais para responder às seguintes questões:
1. **O Público da Pesquisa:** Qual é o perfil demográfico da amostra (idade, género, raça, educação e renda)? Existe correlação entre educação e poder aquisitivo?
2. **Ser um Bom Americano:** Estudar mais implica maior responsabilidade de voto? O que é mais importante para as minorias não-brancas? Qual geração demonstra maior nível de tolerância?
3. **Escolhas Partidárias:** Qual partido atrai o público mais jovem e qual atrai mais mulheres? Existe correlação entre a idade e a frequência de ida às urnas?
4. **Estratégias Eleitorais:** Qual é o "eleitor adormecido" (perfil demográfico) que a equipa de marketing do Partido Republicano deve focar para atrair mais votos?

## 🛠️ Tecnologias Utilizadas
* **Python:** Linguagem base da análise.
* **Pandas:** Limpeza, manipulação e cruzamento de dados (tabelas de frequência e contingência).
* **Matplotlib & Seaborn:** Visualização de dados (Countplots, Boxplots, Swarmplots, Gráficos de Barras Agrupadas).
* **Google Colab:** Ambiente de desenvolvimento (Jupyter Notebook).

## 📖 Dicionário de Dados
Abaixo estão as principais variáveis utilizadas neste estudo, derivadas da base de dados original da pesquisa:

| Variável | Descrição |
| :--- | :--- |
| `ppage` | Idade do respondente. |
| `gender` | Género do respondente (Male, Female). |
| `race` | Etnia/Raça do respondente (White, Black, Hispanic, Other/Mixed). |
| `educ` | Nível educacional atingido (High school or less, Some college, College). |
| `income_cat` | Faixa salarial/poder aquisitivo anual do agregado familiar. |
| `voter_category` | Propensão de voto nas eleições (always, sporadic, rarely/never). |
| `Q2_1` | Nível de importância atribuída a "Votar em eleições" (1 = Muito importante a 4 = Nada importante). |
| `Q2_4` | Nível de importância atribuída a "Exibir a bandeira americana" (Escala de 1 a 4). |
| `Q2_7` | Nível de importância atribuída a "Apoiar os militares" (Escala de 1 a 4). |
| `Q2_8` | Nível de importância atribuída a "Respeitar as opiniões de quem discorda de si" (Escala de 1 a 4). |
| `Q30` | Escolha partidária principal (1 = Republicano, 2 = Democrata, 3 = Independente, 4 = Outro, 5 = Sem preferência). |
| `Q33` | Para quem não tem partido: com qual partido se sente mais próximo/alinhado. |

## 🚀 Como executar este projeto
1. Faz o clone deste repositório.
2. Abre o ficheiro `Eleitores_EUA.ipynb` no teu Google Colab ou Jupyter Notebook local.
3. Certifica-te de que tens as bibliotecas `pandas`, `matplotlib` e `seaborn` instaladas.
4. Executa as células sequencialmente. O dataset é carregado automaticamente via link no código.
