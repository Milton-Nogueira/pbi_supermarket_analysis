# Análise trimestral de vendas de um supermercado no Power BI

Esta análise teve como foco extrair informações sobre o período de janeiro à março de 2019 para uma rede de supermercados com filiais em três cidades diferentes.

Procurou-se obter o perfil dos clientes da loja e dos produtos e faturamentos obtidos no período delimitado.

O **dataset** foi extraído do [Kaggle](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales).

**Dicionário de dados**:

+ Invoice id: número de identificação de vendas.

+	Branch: filiais do supermercado. Denotadas como A, B e C. 

+ City: Cidades onde se encontram as filiais. A: Yangon, B: Mandalay, C: Naypyitaw.

+ Customer type: Diferencia se o cliente possui cartão de membro ou se é um cliente comum.

+ Gender: gênero informado pelos clientes.

+	Product Line: Categorização dos itens do supermercado.

+ Unit price: Preço de cada produto em dólares.

+	Quantity: Número de produtos comprados por cliente.

+ Tax: 5% de taxa por cliente que comprou no estabelecimento.

+ Total: Preço total pago incluindo a taxa.

+ Date: Data de compra, abrangendo os meses de janeiro a março de 2019.

+ Time: Hora em que a compra foi realizada, período entre 10 da manhã e 9 da noite.

+	Payment: Tipo de pagamento usado pelo cliente.

+ COGS: Custo de aquisição dos produtos pelo mercado.

+ Gross margin percentage: Percentual de ganho bruto.

+ Gross income: Faturamento bruto.

+ Rating: Avaliação dos clientes sobre o supermercado em uma escala de 1 a 10.

**Construção do dashboard no Power BI**:

O dashboard foi dividido em duas análises, sendo a primeira a do perfil do cliente que compra na rede de supermercados.

Nesta página pode-se navegar entre os meses do período, entre as três filiais e entre os tipos de cliente (membros ou não) através dos botões à esquerda.

O relatório fornece informações sobre a quantidade de clientes, avaliação fornecida por eles, se são membros ou não, gênero especificado por eles, dias onde mais compras foram feitas, quais as linhas de produtos preferidas e os tipos de pagamento mais utilizados.



![2023-01-09 19 14 07 app powerbi com 63f33f7a540e](https://user-images.githubusercontent.com/121902546/211420914-448c5989-33fc-4fdd-bff3-8153d7e12410.png)

A segunda etapa de análise compreende o aspecto financeiro do período.

Os mesmos botões de filtro estão presentes à esquerda e pode-se obter informações sobre o horário do dia que gerou mais lucro, bem como o dia mais lucrativo do período.

Além disso observa-se qual linha e tipo de pagamento resultaram maior montante. 

Vemos também nesta página informações sobre o valor de um ticket médio do cliente, número de produtos vendidos, faturamento total da loja e o seu rendimento bruto, descontando o custo de obtenção dos produtos.


![2023-01-09 19 13 51 app powerbi com 2dfebe924601](https://user-images.githubusercontent.com/121902546/211422134-48b555ef-37c6-40d0-9830-61c5c1769bde.png)

**Insights**:

+ De um total de 1000 clientes no período, a rede A é a que teve mais compras (340).

+ Há uma divisão praticamente igual entre os que se identificam como homens e os que se identificam como mulheres, assim como para os que possuem cartão de membros e os que são clientes normais.

+ Os tipos de pagamento preferidos dos clientes ao longo do período foram carteira digital e o dinheiro, respectivamente. Entretanto, membros preferem pagar com cartão de crédito.

+ As linhas de produtos mais procuradas são, em ordem, acessórios fashion, comidas/bebidas e eletrônicos. Os membros procuram mais por comidas/bebidas, enquanto os demais procuram mais por eletrônicos e acessórios fashion.

+ O dia mais visitado da loja foi 7 de fevereiro, porém foi o mês com o menor número de clientes.

+ Janeiro apresentou uma grande procura de itens da seção viagens e esportes, provavelmente em virtude das férias de começo de ano.

+ A avaliação média dos clientes foi de 6,97. A filial com pior avaliação foi a rede B, com nota 6,65 apresentada no mês de março.

+ A melhor avaliação média é a da rede C, com pico em fevereiro com nota 7,20.

+ Em geral os membros tendem a serem mais críticos, com avaliação média 6,94, enquanto os demais clientes deram uma nota média de 7,01.

+ Cada cliente gastou em média $322,97 em cada compra.

+ Houve um total de 5510 produtos vendidos, sendo a rede A a que mais vendeu (1859). Entretanto, a rede C foi a que mais faturou ($110,57 mil).

+ O tipo de pagamento que gerou mais lucro foi dinheiro, apesar de não ter sido o método mais utilizado.

+ Janeiro teve maior faturamento ($116,29 mil) com 1965 produtos vendidos enquanto Fevereiro teve o pior ($97,22 mil) com 1654 produtos vendidos.

+ O intervalo das 14h às 15h é o que geralmente traz mais lucro com uma média de $371,43, enquanto o dia mais rentável foi 9 de março de 2019, gerando $7,5 mil.

+ Comidas/bebidas foi o segmento que gerou mais lucro, com $56 mil.

+ O faturamento total com a taxa de 5% por cliente foi um montante de $322,97 mil, com um faturamento bruto de $15,38 mil quando descontados os preços de aquisição dos produtos.

### **Para navegar pelo dashboard acesse [aqui](https://app.powerbi.com/view?r=eyJrIjoiZmIwMWU4ZjUtYWRkZi00Y2FiLTgwYTQtYjgzMjY3OWM2OWZiIiwidCI6IjJjOTUwZWUxLWY4ZWYtNDY1MS05ZmRiLTIwZjRjNjk0ZTAzYyJ9).** 
