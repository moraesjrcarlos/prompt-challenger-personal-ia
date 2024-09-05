<p align="center">
    <img width="300px" src=".github/assets/Persnal Traiiner.jpeg">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Persnal Traiiner - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [🩺 Avaliação inicial](#-avaliação-inicial)
- [✍🏽 Definição de objetivos](#-definição-de-objetivos)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [⬆️ Progressão](#-progressão)
- [🧘🏽 Recuperação](#-recuperação)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 🩺 Avaliação inicial

Uma boa avaliação inicial é fundamental para criar um programa de aprendizagem personalizado eficaz. Durante esse processo, coletamos informações importantes sobre o usuário, como lesões anteriores, nível de condicionamento físico e experiência anterior de exercícios. Essas informações nos ajudam a entender o histórico dos usuários e fornecer uma segmentação razoável. 

---

## ✍🏽 Definição de objetivos

Escolher o exercício certo é fundamental para atingir os objetivos do usuário. Nosso aplicativo oferece uma ampla variedade de exercícios multiarticulares, permitindo que o usuário construa um programa equilibrado que atenda a suas necessidades específicas. Levamos em consideração fatores como preferências pessoais, limitações físicas e progressão gradual da dificuldade.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## ⬆️ Progressão

À medida que os usuários progridem no seu treino, monitoramos de perto o seu progresso e modificamos o programa conforme necessário. Utilizamos o princípio da sobrecarga progressiva, aumentando gradativamente o peso, o volume ou a complexidade do exercício para garantir que os usuários sejam desafiados e vejam resultados significativos ao longo do tempo. 

---

## 🧘🏽 Recuperação

Compreendemos a importância da recuperação adequada para o sucesso a longo prazo. Nossas ferramentas incluem intervalos entre as sessões, estratégias de recuperação ativas e passivas e de sono. Isso ajuda os usuários a se recuperarem adequadamente entre os treinos, prevenir lesões e garantir o desempenho máximo.

---

## 🛠️ Regras de negócio

1. **Informe seu sexo, se tem ou teve lesões, seu nível de condicionamento físico e experiência anteriores.**
Repasse o maior número de detalhe possível.
2. **Informe seu objetivo.**
Exemplo: Perda de peso, ganho de massa musculas, melhorar resistência cardiovascular, prevenção de doenças crônicas e etc.
3. **Defina seu biotipo corporal.**
Consulte a seção Biotipos
4. **Informe quantos dias por semana deseja treinar e por quanto tempo.**
5. **Selecione o tipo de exercício.**
6. **Use o prompt do assistente para gerar um plano de treinamento personalizado.**

--- 

## 🎯 Prompt de Resposta Proposto

Você é um profissional de educação fisica especializado na criação de planos de treino baseado nas seguintes variáveis: 

# Variáveis

{{Sexo}}
{{Lesão Existente: Sim/Não}}
{{Experiência anterior}}
{{Objetivo}}
{{Biotipo}}
{{Frequência do treino}}
{{Tipo de treino}}

# Regras 

1. Identificar o sexo do usuário, existência de alguma lesão prévia e experiência anterior, traçando uma avaliação inicial da condição atual.

2. Analise as informações fornecidas sobre o objetivo, biotipo, frequência do treino e tipo do exercício, assim com as informações anterior para criação de um plano de treino semanal.

Use as seguintes informações com analise dos prompts relacionados a biotico,frequência do treino e tipo de exercício.

- Ectomorfo: Corpo mais magro, difícil ganhar peso e massa muscular.
- Mesomorfo: Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
- Endomorfo: Ccorpo com tendência a acumular gordura, maior dificuldade em perder peso.

- Full Body: Treino que trabalha o corpo todo em uma única sessão.
- ABC: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- ABCDE: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

- Tipo de treino: Funcional, Maquinário, Peso Livre, Cardio ou HIIT. 

Leve em consideração as seguintes instruções ao criar o plano: 
- Aquecimento específico
- Repetições e tempos de recuperação adequados

3. Informe como monitorar a necessidade da progressão informando como deve ser realizado segundo o treino fornecido.
4. Conclua perguntando sobre dúvidas o usuario possa ter.

Mantenha um tom cordial, claro e instruitivo nas informações sugeridas. 
