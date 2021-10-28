## Project_Atlas_Technologies
### **Análise dos usuários - Atlas Technologies 2021**

**Autor: David Ricardo Tito Infantas**

1.Dados relevantes do comportamento da base geral:
* Se analisou a **2.027** usuários.
* Um **79%** dos usuários têm sua subscrição cancelada. 
* As três regiões com mais usuários são:
  * São Paulo com **21,5%** dos usuários 
  * Rio Grande do Sul com **12,5%** dos usuários
  * Minas Gerais com **11,2%** dos usuários

* Os três planos mais vendidos são:
  * Plano A com **33,5%** das vendas
  * Plano B com **22,2%** das vendas
  * Plano C com **20,3%** das vendas

2.Características das pessoas que cancelaram a subscrição:
* Meses de maior cancelamento: **julho, setembro e outubro** de 2021.
* As três regiões com mais subscrições canceladas são:
  * São Paulo com **336** subscrições canceladas
  * Rio Grande do Sul **198** subscrições canceladas
  * Minas Gerais **185** subscrições canceladas

* A principal razão do cancelamento é : **“Falha no pagamento”**  (62% dos usuários).

3.Sugestão:
  * **Depois de analisar os dados, se planejou que houve uma falha no sistema de pagamento da plataforma, porém os usuários não conseguiram renovar seus pagamentos e ocasionou o cancelamento da subscrição.**

4.Se elaborou um modelo preditivo que indicará se o usuário vai cancelar ou não sua subscrição, por meio de um score.

---










### **O raciocínio do projeto**

* Primeiro, comecei a fazer um conhecimento geral da tabela, considerando o tamanho, o tipo da informação por feature e dados nulos. 
* Segundo, comecei a  analisar a tabela de forma geral (EDA) fazendo análise por feature e também o cruzamento de informação. 
* Terceiro, fiz uma análise mais específica sobre o segmento dos usuários que cancelaram sua subscrição, procurando chegar num insight de valor que intenta explicar o motivo do cancelamento.
* Quarto, realizei o feature selection (Boruta) para deixar as features prontas para ingressar ao modelo predictivo.
* Quinto, fiz dois modelos preditivos (XGBoost e Random Forest) com o objetivo de predecir se o usuário vai cancelar sua subscrição ou não.
* Sexto, validei os dois modelos com três métricas (KS e ROC) e o modelo ganhador é o XGBoost tendo em consideração que o target utilizado é desbalanceado.






**Link do script: https://github.com/DavidTitoInfantas/Project_Atlas_Technologies/blob/main/Analise_Asignaturas.ipynb**

