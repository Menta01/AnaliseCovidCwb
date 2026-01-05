# 📊 Análise Covid-19 em Curitiba (AnaliseCovidCwb)

Este projeto tem como objetivo realizar uma **análise dos casos de Covid-19 no município de Curitiba**, buscando compreender:

- Os **bairros mais afetados**
- A **tendência dos casos ao longo do tempo**
- A **distribuição dos casos e óbitos por sexo e faixa etária**

> ⚠️ **Importante:**  
> Para a execução correta da análise, é necessário baixar os seguintes arquivos:
> - `DIVISA_DE_BAIRROS_SIRGAS.zip`
> - `2025-11-06_Casos_Covid_19_-_Base_de_Dados`

---

## 1️⃣ Tendência de Casos com Média Móvel

Neste gráfico, utilizamos um **gráfico de linhas** em conjunto com a **média móvel** para facilitar a visualização da tendência dos casos ao longo do tempo.

- 🔵 **Linha Azul:** Casos reais
- 🔴 **Linha Vermelha:** Média móvel

Essa abordagem ajuda a reduzir oscilações pontuais e evidenciar o comportamento geral da pandemia.

<img width="1444" height="489" alt="image" src="https://github.com/user-attachments/assets/d5da7353-00c1-4991-bf70-cae46ec0563d" />

---

## 2️⃣ Distribuição de Casos por Sexo

O gráfico de pizza apresenta a **distribuição dos casos por sexo**.  
É possível observar que o **sexo feminino** foi o mais afetado em número de casos, indicando um grupo que merece maior atenção em análises epidemiológicas.

<img width="501" height="343" alt="image" src="https://github.com/user-attachments/assets/37900271-7966-48d4-8ae7-77a5bddf1c58" />

---

## 3️⃣ Casos por Faixa Etária e Sexo

Neste gráfico de **linhas agrupadas**, os dados são segmentados por **faixa etária** e **sexo**, permitindo identificar:

- As faixas etárias mais impactadas
- Diferenças de incidência entre homens e mulheres

Essa visualização auxilia na compreensão do impacto da Covid-19 em diferentes grupos populacionais.

<img width="1179" height="521" alt="image" src="https://github.com/user-attachments/assets/8400467d-646b-45b2-b26a-eb4bcf829ce0" />

---

## 4️⃣ Letalidade por Mês

O gráfico de letalidade por mês apresenta no eixo inferior o **ano/mês**, enquanto as linhas representam a **quantidade de óbitos** registrados.

Esse gráfico facilita a identificação de períodos críticos da pandemia, evidenciando picos de mortalidade ao longo do tempo.

<img width="1222" height="532" alt="image" src="https://github.com/user-attachments/assets/465a4da9-24a7-4939-99bb-4fa990130d5b" />

---

## 5️⃣ Letalidade por Sexo

Semelhante ao gráfico anterior, porém segmentado por **sexo**, esta visualização permite analisar diferenças na letalidade entre homens e mulheres ao longo do tempo.

<img width="1471" height="544" alt="image" src="https://github.com/user-attachments/assets/51f17bf4-9581-4f8e-adc1-74a0db104086" />

---

## 6️⃣ Histograma – Casos por Idade e Sexo

O histograma permite entender a **distribuição dos casos por idade**, segmentados por sexo, facilitando a identificação dos grupos etários mais afetados ao contrair Covid-19.

<img width="1040" height="501" alt="image" src="https://github.com/user-attachments/assets/03ce2814-2cd8-4fb2-bf68-08833fe1d241" />

---

## 7️⃣ Bairros Mais Afetados

Este gráfico apresenta os **bairros com maior número de casos de Covid-19**, permitindo identificar regiões com maior concentração da doença.

<img width="1266" height="540" alt="image" src="https://github.com/user-attachments/assets/8a1b80f2-7790-495a-a7a3-6b90e5d144fa" />

---

## 8️⃣ Mapa de Calor – Casos por Bairro

De forma semelhante ao gráfico anterior, porém utilizando **GeoPandas** e um **mapa de calor**, esta visualização proporciona uma interpretação espacial mais intuitiva da distribuição dos casos, facilitando a análise geográfica dos bairros mais afetados.

<img width="614" height="478" alt="image" src="https://github.com/user-attachments/assets/7092970c-0c8a-4804-a3c5-09b3025d9520" />
