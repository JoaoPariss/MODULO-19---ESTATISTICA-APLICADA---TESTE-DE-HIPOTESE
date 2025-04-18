# MODULO-19---ESTATISTICA-APLICADA---TESTE-DE-HIPOTESE
Esta atividade tem como objetivo comparar o desempenho de duas estratégias de ensino (Estratégia A e Estratégia B) utilizando um **teste Z unilateral à direita**.

---

## 1. 🧪 Definição do Tipo de Teste

- **Hipótese nula (H0):** as médias das duas estratégias são iguais.  
- **Hipótese alternativa (H1):** a média da Estratégia B é **maior** que a da A.  

✅ **Tipo de teste:** **Unilateral à direita**

---

## 2. 📊 Cálculo das Médias e Variâncias

- **Média A:** `71.41`  
- **Média B:** `74.75`  
- **Variância A:** `129.27`  
- **Variância B:** `110.47`  

Amostras geradas com distribuição normal e tamanho `n = 5`.

---

## 3. 🧮 Estatística Z e p-valor

### Cálculo:

Foi utilizada a fórmula do teste Z para duas médias com variâncias conhecidas e amostras independentes:

z = (media_B - media_A) / ((variancia_A/n + variancia_B/n) ** 0.5)
p = 1 - stats.norm.cdf(z)  # Teste unilateral à direita

## 4. 📉 Gráfico da Distribuição

---

Um gráfico da **distribuição normal padrão** foi gerado para representar visualmente o teste Z.

### Elementos do gráfico:

- 📈 **Curva normal padrão** com média 0 e desvio padrão 1.
- 🔴 **Linha pontilhada** indicando o valor observado da estatística Z.
- ⚠️ **Área crítica** destacada na cauda direita (teste unilateral à direita), representando a região onde rejeitaríamos H0.

### Interpretação visual:

- A linha da estatística Z **ficou fora da área crítica**, ou seja, **não há evidência suficiente para rejeitar a hipótese nula**.
- O gráfico reforça a decisão tomada com base no p-valor.
