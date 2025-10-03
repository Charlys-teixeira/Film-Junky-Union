## 📖 Descrição
Este projeto tem como objetivo desenvolver modelos de **aprendizado de máquina** capazes de identificar automaticamente se uma resenha de filme é **positiva** ou **negativa**, utilizando técnicas de **Processamento de Linguagem Natural (NLP)**.  
Foram testados e comparados diferentes algoritmos de classificação, alcançando um **F1-score superior a 0.85** no conjunto de teste.

---

## 🗂️ Conjunto de Dados
- Tamanho: 50.000 resenhas rotuladas em **positivas (1)** e **negativas (0)**.  
- Divisão: Treinamento e teste já pré-definidos.  


## ⚙️ Etapas do Projeto
1. **Carregamento e limpeza dos dados**
   - Remoção de stopwords e caracteres especiais  
   - Tokenização e lematização  
2. **Vetorização de texto**
   - Bag of Words (BoW)  
   - TF-IDF  
3. **Treinamento de modelos**
   - Regressão Logística  
   - Random Forest  
   - Gradient Boosting (LightGBM)  
4. **Avaliação**
   - Métrica principal: **F1-score**  
   - Comparação de desempenho entre modelos  
5. **Validação com exemplos reais**
   - Criação de resenhas fictícias para validação prática  

---

## 📊 Resultados
- Melhor desempenho: **Gradient Boosting**  
- **F1-score no teste:** > 0.85  
- Modelos demonstraram boa generalização para novos textos  

---

## 🛠️ Tecnologias Utilizadas
- Python 3.10  
- Pandas, NumPy  
- Scikit-learn  
- NLTK / SpaCy  
- LightGBM  

---

## ✍️ Autor
Projeto desenvolvido como parte da **formação em Data Science - TripleTen**.  

