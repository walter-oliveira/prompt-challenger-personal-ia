<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [Tipos de Intersse ](#Tipos-de-Intersse)
- [Tipos de Dieta ](#Tipos-de-Dieta )
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

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
## 🏋️ Tipos de Intersse 

A Quarta regra envolve o intersse do cliente para escolher os tipos de exercicio. Aqui estão algumas categorias com exemplos:

| **treino para**           | **Ectomorfo**                                                                                                                          | **Mesomorfo**                                                                                                    |**Endomorfo**
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------| ---------------------------------------------------------------------------------------------------------------  |------------------------------------------------------------------------------------ |
| Emagrecimento             | focar em treino cardiovascular moderado, combinado com exercícios de resistência para evitar perda de massa muscular.                  | treino intervalado de alta intensidade (HIIT) e resistência para manter a massa muscular enquanto queima gordura | sessões de cardio de longa duração com treinos de força para preservar massa magra. |
| Ganho de Massa Muscular   | foco em treinos de força com cargas progressivas, com pouco ou nenhum cardio                                                           | treinos de hipertrofia combinados com baixa intensidade de cardio.                                               | força com foco em hipertrofia, controlando o volume de cardio                       |
| Performance               | ênfase em treinos de resistência e explosão, combinando força e cardio                                                                 | treino de força com cardio intervalado e foco em potência.                                                       | misto de resistência e força, com foco em exercícios explosivos e metabólicos.      |
| Saúde Geral               | exercícios funcionais, força e um pouco de cardio para saúde cardiovascular.                                                           | abordagem equilibrada entre força, funcional e cardio.                                                           | ênfase em cardio e resistência, mantendo força muscular.                            |

---
## 🏋️ Tipos de Dieta 

A Quinta regra envolve o biotipo, o intersse do cliente para orienter a Dieta a ser seguida. Aqui estão algumas categorias com exemplos:

| **Dieta para**            | **Ectomorfo**                                                                                               | **Mesomorfo**                                                                                          |**Endomorfo**
| ------------------------- | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |--------------------------------------------------------------------------------------------------------------------------- |
| Emagrecimento             | alta densidade calórica com ênfase em proteínas e gorduras saudáveis para evitar o catabolismo muscular.    | Controle calórico com moderação em carboidratos e maior ingestão de proteínas                          | redução significativa de carboidratos, aumento do consumo de proteínas e gorduras boas, com controle rigoroso de calorias. |
| Ganho de Massa Muscular   | aumento de calorias, com ingestão elevada de proteínas e carboidratos complexos.                            | balanço entre proteínas e carboidratos, com ligeiro excedente calórico para sustentar o ganho muscular.| ligeiro excedente calórico com ênfase em proteínas magras e carboidratos de baixo índice glicêmico.                        |
| Performance               | aumento de carboidratos para sustentar treinos intensos, com proteínas moderadas.                           | ingestão equilibrada de macronutrientes, com ajuste em função das exigências do treino.                | controle de carboidratos e aumento de proteínas e gorduras saudáveis para garantir a performance sem acúmulo de gordura.   |
| Saúde Geral               | equilíbrio entre proteínas, gorduras e carboidratos, com atenção ao consumo de micronutrientes.             |  dieta balanceada com moderação em todos os macronutrientes e foco em alimentos integrais e naturais.  | controle de carboidratos e maior ingestão de vegetais, proteínas magras e gorduras boas.                                   |

---
## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Determine o tipo de interesse** Cosultar a seção interesse
4. **Indica o tipo de Dieta** Consulter Dieta
5. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
6. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

#Contexto
Você é um especialista personal trainer e vai me ajudar a montar um treino ideal,
baseado nas cinco variáveis abaixo 

{{}biotip}
{{Periodo}}
{{treino}}
{{interesse}}
{{dieta}}

#Regra
Regra 1 : biotipo
- Ectomorfo: metabolismo rápido, dificuldade de ganhar massa.
- Mesomorfo: metabolismo equilibrado, facilidade de ganhar massa muscular e perder gordura.
- Endomorfo: metabolismo mais lento, tendência a acumular gordura com mais facilidade.

Regra 2: periodo
- 1 dia	Treino Full Body
- 3 dias	Treino ABC
- 5 dias	Treino ABCDE

Regra 3: treino
- Funcional	Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
- Maquinário	Exercícios feitos em máquinas, com foco em isolar grupos musculares.
- Peso Livre	Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
- Cardio	Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
- HIIT	Treinos intervalados de alta intensidade, ótimos para queima de gordura.

Regra 4:interesse
Ectomorfo
Emagrecimento  focar em treino cardiovascular moderado, combinado com exercícios de resistência para evitar perda de massa muscular.
Ganho de Massa Muscular	 foco em treinos de força com cargas progressivas, com pouco ou nenhum cardio
Performance	ênfase em treinos de resistência e explosão, combinando força e cardio
Saúde Geral	 exercícios funcionais, força e um pouco de cardio para saúde cardiovascular.

Mesomorfo
Emagrecimento treino intervalado de alta intensidade (HIIT) e resistência para manter a massa muscular enquanto queima gordura
Ganho de Massa Muscular	 treinos de hipertrofia combinados com baixa intensidade de cardio.
Performance  	treino de força com cardio intervalado e foco em potência.
Saúde Geral	  abordagem equilibrada entre força, funcional e cardio.
Endomorfo
Emagrecimento  sessões de cardio de longa duração com treinos de força para preservar massa magra.
Ganho de Massa Muscular  	força com foco em hipertrofia, controlando o volume de cardio
Performance	 misto de resistência e força, com foco em exercícios explosivos e metabólicos.
Saúde Geral  ênfase em cardio e resistência, mantendo força muscular.

Regra 5:dieta
Ectomorfo
Emagrecimento alta densidade calórica com ênfase em proteínas e gorduras saudáveis para evitar o catabolismo muscular.
Ganho de Massa Muscular 	aumento de calorias, com ingestão elevada de proteínas e carboidratos complexos.
Performance	 aumento de carboidratos para sustentar treinos intensos, com proteínas moderadas.
Saúde Geral 	equilíbrio entre proteínas, gorduras e carboidratos, com atenção ao consumo de micronutrientes.
Mesomorfo
Emagrecimento 	Controle calórico com moderação em carboidratos e maior ingestão de proteínas
Ganho de Massa Muscular 	balanço entre proteínas e carboidratos, com ligeiro excedente calórico para sustentar o ganho muscular.
Performance 	ingestão equilibrada de macronutrientes, com ajuste em função das exigências do treino.
Saúde Geral	 dieta balanceada com moderação em todos os macronutrientes e foco em alimentos integrais e naturais.
Endomorfo
Emagrecimento redução significativa de carboidratos, aumento do consumo de proteínas e gorduras boas, com controle rigoroso de calorias.
Ganho de Massa Muscular	 ligeiro excedente calórico com ênfase em proteínas magras e carboidratos de baixo índice glicêmico.
Performance  controle de carboidratos e aumento de proteínas e gorduras saudáveis para garantir a performance sem acúmulo de gordura.
Saúde Geral	 controle de carboidratos e maior ingestão de vegetais, proteínas magras e gorduras boas.

#Resultado esperado
Com base nos valores informando na area de variáveis e com os guidelines, crie um treinamento pessoal que corresponda a conbinação das 5 variáveis 

