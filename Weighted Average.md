# Weighted Average 加权平均数
  
Consider a basket of fruits. By count, 20% are Fruit A, 30% are Fruit B, and 50% are Fruit C. Fruits A, B, and C have different weights. Fruit A weighs 100g each, Fruit B weighs 150g each, and Fruit C weighs 50g each. What is the average weight of a fruit in the basket?
  
| Fruit | Percentage by Count | Unit Weight |
|-------|---------------------|-------------|
| A     | 20%                 | 100g        |
| B     | 30%                 | 150g        |
| C     | 50%                 | 50g         |

$$
\text{Weighted Average} = \sum_{i=1}^{n} (\text{Percentage}_i \times \text{Unit Weight}_i)
$$
  
# Method 1
  
We can divide the total weight by the total count.  
The total weight is:  
Divide the total weight by count .  
Therefore, the average weight is 90g.  
Notice that is cancelled out eventually. We do not need to include it at the beginning. This is actually a common way to compute weighted average.  
（N 省略）
      
# Method 2
We pick a fruit as the reference and look at the differences of each fruit to the reference.  
Let us use Fruit A's weight as the reference.  
The methods are essentially the same. We can consider the reference in Eq. 1.1 is 0. Eq. 2.1 can also be obtained from Eq. 1.1 as follows.
  
$$
R{\text{weight}} + \text{percentageA} \times ( \text{weightA} - R_{\text{weight}} ) + \text{percentageB} \times ( \text{weightB} - R{\text{weight}} ) + \text{percentageC} \times ( \text{weightC} - R{\text{weight}} )
$$
  
（参考值）
  
# Reference  
https://zhijieshi.github.io/cse3666/ 
