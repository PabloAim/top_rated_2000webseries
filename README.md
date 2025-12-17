# Análise do Top 2000 Séries Mais Bem Avaliadas do Mundo (TMDB - 2025)

Projeto de análise exploratória de dados com foco em insights estratégicos do mercado de séries de TV e streaming.

**Principais temas abordados:**
- Colapso de produção pós-pandemia e greves
- Ascensão de Japão e Coreia do Sul com produção nacional
- Relação entre volume de séries e qualidade percebida
- Identificação de "joias escondidas" subvalorizadas pelo algoritmo

**Tecnologias:** Python, pandas, matplotlib, seaborn, Jupyter Notebook

**Autor:** Pablo Torres  
Analista de Dados em formação avançada, com sólida base em tecnologia e especialização em inteligência de negócios.  

- Graduado em Sistemas de Informação  
- Pós-graduado em Big Data para Business Analytics e Business Intelligence  
- Atualmente no 3º semestre de Ciência de Dados e Inteligência Artificial

---

### Insight 1: Top 15 Países

Os **países dominantes** no Top 2000 são:
* **United States** com **1,065** séries.
* **Japan** com **328** séries.

Os **países na base** do Top 15 (menor representação) são:
* **Germany** com **11** séries.
* **Argentina** com **10** séries.

---

**ANÁLISE DE DISPERSÃO E DOMÍNIO:**
* **Domínio Absoluto:** A diferença entre o 1º e 2º colocado é de **737** séries, o que evidencia o claro domínio dos **United States** sobre os demais rankings.
* **Empate Técnico:** A diferença de séries entre **Germany** e **Argentina** é de apenas **1** série(s). Essa pequena margem sugere um empate técnico na parte inferior do Top 15.
* **Dispersão Total:** A dispersão total é impressionante: **United States** tem **1,055** séries a mais que **Argentina**. Essa diferença mostra a alta concentração de produção em países específicos.

---

**AÇÃO ESTRATÉGICA:** Essas séries são importantes para a **percepção de valor** do assinante, mas a estratégia deve focar em **qualidade nichada** para competir com o domínio dos **United States**.

---

### Insight 2: Top 15 Idiomas Originais

**RESUMO DE REPRESENTAÇÃO POR IDIOMA**

Os **idiomas mais dominantes** no Top 2000 são:
* **English** com **1,265** séries.
* **Japanese** com **330** séries.

---

Os **idiomas na base** do Top 15 (com menor representação) são:
* **Swedish** com **2** séries.
* **Catalan** com **2** séries.

---

**CONCLUSÃO ESTRATÉGICA:**
* **Domínio:** **English** domina com uma margem de **935** séries sobre o **Japanese**.
* **Hegemonia:** Essa diferença massiva mostra a clara hegemonia da língua inglesa no conteúdo de séries de alto ranking.
* **Oportunidade de Nicho:** O fato de outros idiomas terem pouca representação sugere uma oportunidade para plataformas que desejam se diferenciar com conteúdo de nicho e alta qualidade em outras línguas (K-Dramas, etc.).

---

### Insight 3: Gêneros mais presentes + Distribuição 5 gêneros dominantes

**RESUMO DO TOP 20 MUNDIAL (Qualidade vs. Gênero)**

**VISÕES DIRETAS:**
* Gênero absoluto: **Animation** (14 séries)
* Percentual de Animação: **14** séries → **70%** do pódio!
* Países no pódio: **4** únicos → Top 3: **United States': 11, 'Japan': 7, 'Canada': 1**
* Séries não-inglês no Top 20: **8** séries

---

**VISÃO DE MERCADO - PADRÕES DE SUCESSO E RENTABILIDADE:**
* **Domínio de Categoria:** O gênero **Animation** é o líder absoluto de presença no Top 20 mundial, aparecendo em **14** das 20 melhores produções.

* **Competitividade e Proximidade (Quadrante de Ouro):** Observamos uma distância curta entre os quatro pilares do ranking:
    * A distância entre o 1º (**Animation**) e o 2º (**Action & Adventure**) é de apenas **2** unidade(s).
    * A distância total do 1º ao 4º colocado (**Sci-Fi & Fantasy**) é de apenas **4** unidade(s).
    * Isso indica que **Animation**, **Action & Adventure**, **Drama** e **Sci-Fi & Fantasy** formam o 'quadrante de ouro' do entretenimento.
    
* **Recomendação para Produtoras:** Para empresas que buscam maximizar a **rentabilidade** e aceitação pelo público global, o investimento em produções que mesclam esses quatro gêneros dominantes parece ser o caminho mais seguro e validado pelos dados históricos do Top 2000.

---

### Insight 4: Queda de séries de alta qualidade pós-2020

* **Pico histórico**: **2020** → 173 séries no Top 2000
* **2020 - 2022**: pandemia + greves de roteiristas/atores
* **2023 - 2024**: retomada lenta (plataformas cortando orçamento
* **2025 (até 20 Novembro/2025)**: **25** séries (menor em 20+ anos)
* **Queda** de **86%** em relação ao auge de 2020

---

### Insight 5: Relação Volume vs. Qualidade Média - Quadrantes de Mercado (Top 10 Gêneros)

**RESUMO DO MERCADO: VOLUME VS. QUALIDADE (TOP 10 GÊNEROS)**

**ANÁLISE DE EXTREMOS:**
* **Volume Absoluto:** **Drama** é o líder em volume, com **1,262** séries, mas sua nota média é de **7.818**.
* **Qualidade Absoluta (Outlier):** **Animation** lidera em qualidade com **8.043** de nota média, sendo o único gênero acima de 8.0 no Top 10.

---

**QUADRANTES ESTRATÉGICOS:**

* **Alto Volume / Baixa Qualidade (Saturação):**
    * **Drama** claramente domina este quadrante, demonstrando a **relação inversa** entre volume e qualidade no Top 2000.
* **Alto Volume / Alta Qualidade (Sucesso Consolidado):**
    * **Comedy** e **Sci-Fi & Fantasy** se posicionam como gêneros de alto volume e qualidade acima da média.
* **Baixo Volume / Alta Qualidade (Oportunidade de Nicho):**
    * Gêneros como **Kids** (7.824) e **Family** (7.823) mostram qualidade elevada, apesar do baixo volume.
* **Baixo Volume / Baixa Qualidade (Evitar):**
    * **Soap** (7.753) tem a menor nota média e volume, nicho menos valorizado no Top 2000.

---

### Insight 6: Países únicos VS Coproduções

**RESUMO FINAL DOS PAÍSES E COPRODUÇÕES**

**TOP 5 PAÍSES ÚNICOS (produção 100% nacional):**  
1. **United States** → Mais de 1000 séries (Hollywood domina)  
2. **Japan** → Mais de 300 séries (animações nacionais destacam) 
3. **United Kingdom** → Mais de 130 séries  
4. **South Korea** → Pouco mais de 100 séries (K-dramas estão em alta)  
5. **Mexico** → É o último país da nossa lista e também o que tem apenas um gênero, Sci-Fi & Fanstasy  

**TOP 5 COPRODUÇÕES (normalizado e somado da esquerda para a direita):**  
1. **Canada & United States** → 23 séries (19 + 4 juntos)
2. **United Kingdom, United States** → 9 séries (6 + 3 juntos)
3. **Mexico, United States** → 6 séries  (4 + 2 juntos)
4. **Colombia, United States** → 3 séries
5. **France, United States** → 2 séries

**Visões Principais**
- **Domínio Absoluto dos EUA:** Hollywood lidera em produção própria (mais de 1000 séries), e também é o parceiro indispensável em todas as Top 5 coproduções.
- **Produção Pura (Nicho):** Países como **Japão** e **Coreia do Sul** demonstram alto volume de produção *sem* depender de parcerias externas.
- **Estratégia de Parceria:** As coproduções mostram um foco claro dos EUA em buscar parceiros do eixo **América do Norte/Reino Unido** e, secundariamente, da **América Latina** (México e Colômbia).

---

### Insight 7: Top 5 Países: Distribuição dos Gêneros de Destaque no Top 2000 

**Visões: Especialização por País e Estratégia de Conteúdo**

- **Domínio Americano:** Os EUA dominam Drama, Comedy, Sci-Fi & Fantasy e Action & Adventure.  Só o Japão vence os EUA em animação.
- **Estratégia de Nicho (Japão e Coreia):**
    - O **Japan** é o especialista em **Animation** (322 séries), confirmando a dominância de **Animation** no Top 2000.
    - A **South Korea** foca primariamente em **Drama** (100 séries), sendo o maior produtor de K-dramas únicos.

---

- **Conclusão de Mercado:** Para competir com a amplitude de Hollywood, o sucesso no Top 2000 pode ser alcançado por meio da **especialização** em um único gênero de excelência **(Japan/Animation, South Korea/Drama)**.

---

### Insight 8: Top 10 Joias Escondidas Do Top 2000 (Oportunidade de Mercado)

**Joias Escondidas - Séries Que Merecem Ser Descobertas**

* **17** séries com nota ≥ 8.4 estão no fundo do ranking de popularidade
* **Corte de Popularidade:** Todas as séries estão abaixo do **2.9** (Top 10% menos populares)
* Média de popularidade dessas séries: **2.1**
* Muitos são animes japoneses, K-dramas ou produções europeias/independentes (Confirmando o insight da Célula 13)
* **Prova definitiva:** Popularidade ≠ Qualidade

---

**Ação Estratégica:** Essas são as séries que as empresas de streaming deveriam estar empurrando no algoritmo para aumentar o valor agregado pelo assinante!

---

### Insight 9: Popularidade vs Nota média

Conclusão Final Do Projeto

* Popularidade e qualidade têm correlação positiva… mas **FRACA** (R² < 0.3)
* Existem dezenas de obras-primas com nota ≥ 8.4 que poucas pessoas conhecem
* Japão, Coreia e produções independentes dominam essas "joias escondidas"
* Hollywood domina visibilidade, mas não domina mais qualidade absoluta

---

## Gráficos Principais

### 1. Top 15 Países
![Top 15 Países](imagens/01_Top_15_países.png)

### 2. Top 15 Idiomas
![Top 15 Idiomas](imagens/02_Top_15_idiomas.png)

### 3. Top 20 Séries
![Top 20 Séries](imagens/03_Top_20_Series.png)

### 4. Gêneros mais presentes e distribuição dominante
![Gêneros mais presentes e distribuição dominante](imagens/04_Gêneros_mais_presentes_e_distribuição_dominante.png)

### 5. Queda de séries de qualidade pós-2020
![Queda de séries de qualidade](imagens/05_Queda_de_séries_de_qualidade.png)

### 6. Relação volume vs qualidade
![Relação volume vs qualidade](imagens/06_Relação_volume_vs_qualidade.png)

### 7. Países únicos vs coproduções
![Países únicos vs coproduções](imagens/07_Países_unicos_vs_coproduções.png)

### 8. Top 5 Países: Distribuição dos Gêneros de Destaque
![Distribuição dos gêneros de destaque por país](imagens/08_Top_5_Países_Distribuição_dos_Gêneros_de_Destaque.png)

### 9. Joias Escondidas do Top 2000
![Joias Escondidas](imagens/09_Joias_Escondidas_Do_Top_2000.png)

### 10. Popularidade vs qualidade
![Popularidade vs qualidade](imagens/10_Popularidade_vs_qualidade.png)

## Como rodar
```bash
git clone https://github.com/PabloAim/top_rated_2000webseries.git
cd top_rated_2000webseries
pip install pandas matplotlib seaborn jupyter
jupyter notebook
