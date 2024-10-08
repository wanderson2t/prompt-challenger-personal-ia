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

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto





### Assistente de Personal Trainer - Gerador de Treino Ideal

#### 1. Identificação do Biotipo Corporal
**Por favor, identifique seu biotipo corporal consultando a seção de biotipos:**

{{  Seu tipo de corpo

1 - Treinos de força e resistência — biotipo ectomorfo
Os exercícios físicos focados no aumento da massa muscular requerem força, por isso, estão associados ao levantamento de peso. A musculação é o exercício de força mais praticado atualmente e é a solução ideal para quem está em busca de hipertrofia.

Essa é a solução mais indicada para o grupo dos ectomorfos, uma vez que essas pessoas têm dificuldade em aumentar a massa corporal. O treino não deve ser excessivo, para não favorecer a queima de gordura. Veja outras dicas para esse perfil:

é importante focar em pegar mais peso e fazer menos repetições;
o intervalo de descanso entre cada treino é extremamente importante para não sobrecarregar os músculos e deve ser maior nesse caso;
outro ponto importante é que as pessoas pertencentes a este grupo devem evitar exercícios cardiorrespiratórios, já que eles favorecem a queima de gordura e perda de peso.
Os ectomorfos também têm um desempenho muito bom em exercícios que necessitam de resistência, com perfil mais atlético ou maratonista. Não é à toa que existem tanto atletas que pertencem a esse grupo.

2 - Combinação entre força e cardio — biotipo endomorfo
As pessoas do grupo dos endomorfos precisam perder peso, enquanto fortalecem a musculatura. Por isso, o ideal é que haja a junção de atividades cardiorrespiratórias com o levantamento de peso.

É importante colocar intensidade no levantamento de peso, para acelerar o metabolismo, no entanto, evite o excesso de peso associado a poucas repetições. É importante movimentar todas as partes do corpo, por isso, sempre reserve um tempo para a dança, corrida ou HIT.

Como os endomorfos tendem a ser mais pesados, é importante escolher exercícios de baixo impacto, para não forçar as articulações.

3 - Variação de exercícios físicos — biotipo mesomorfo
A variação de exercícios físicos é a melhor solução para o grupo dos mesomorfos, já que essas pessoas podem queimar gordura e ganhar massa muscular com facilidade. Quem se enquadra nessa realidade tem mais liberdade para escolher os tipos de exercícios físicos que deseja praticar.

É possível optar pelo levantamento de peso — seja ele leve, moderado ou pesado — pelo trabalho com o peso do próprio corpo e também com os exercícios cardiorrespiratórios. Em geral, é possível manter uma rotina com foco e força e uma pequena variação de cardio, mas isso vai depender dos seus objetivos.

Esse também é o biotipo adequado de quem aprecia o fisiculturismo, já que os mesomorfos alcançam uma boa explosão muscular.

}}

opções:

- Ectomorfo
- Mesomorfo
- Endomorfo

**Resposta: ** [mesomorfo]


#### 2. Determinação da Frequência de Treino
**Quantos dias por semana você pode treinar?**
- 3 dias
- 4 dias
- 5 dias
- 6 dias

**Resposta:** [5]

#### 3. Seleção do Tipo de Exercício
**Qual tipo de exercício você prefere realizar e que se encaixa melhor nos seus objetivos?**
- Musculação
- Cardio
- HIIT
- Yoga
- Outro (especifique)

**Resposta:** [musculação]

#### 4. Geração do Plano de Treino Personalizado
**Por favor, insira suas preferências e objetivos (ex: perda de peso, ganho de massa muscular, melhora da flexibilidade, etc.):**

**Resposta:** [ganho de massa muscular]

#### 5. Possui restrição a exercícios físicos? se sim qual?
**Resposta:** [sim, saudades da morena]

#### 6. indique alimentos que me ajudará na evolução dos treinos 

---




com base nessas informações gere um plano de treino personalizado. use a explicação do tipo de corpo antes de informar o plano de treino e uma breve recomendação para consultar um medico ou profissional de musculação.
