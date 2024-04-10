1.
(LHS) = (A ↑ A) ↓ (B ↑ B)
(LHS) = (¬(A ∧ A)) ↓ (B ↑ B)
(LHS) = (¬A) ↓ (B ↑ B)
(LHS) = (¬A) ↓ (¬(B ∧ B))
(LHS) = (¬A) ↓ (¬B)

(RHS) = (A ↓ A) ↑ (B ↓ B)
(RHS) = (¬(A ∨ A)) ↑ (B ↓ B)
(RHS) = (¬A) ↑ (B ↓ B)
(RHS) = (¬A) ↑ (¬(B ∨ B))
(RHS) = (¬A) ↑ (¬B)
(LHS) = (¬A) ↓ (¬B)
(RHS) = (¬A) ↑ (¬B)
(A ↑ A) ↓ (B ↑ B) is equivalent to (A ↓ A) ↑ (B ↓ B),

2. 
(A↑A)↑(((A↑B)↑(A↑B))↑((A↑B)↑(A↑B)))
(A↑B)↑(A↑B)
(A↑B)↑(A↑B) = (A↑A)
(A↑A)↑(((A↑B)↑(A↑B))↑((A↑B)↑(A↑B))) = (A↑A)↑((A↑A)↑((A↑B)↑(A↑B)))
(A↑A)↑((A↑A)↑((A↑B)↑(A↑B))) = (A↑A)↑A
(A↑A)↑A = A
(A↑A)↑(((A↑B)↑(A↑B))↑((A↑B)↑(A↑B))) simplifies to A.

3. 
(A+B)(A+AB) + AB(A+B)
(A+B)(A+AB) + AB(A+B) = (A+B)(A+AB) + AB(A+A)
(A+B)(A+AB) + AB(A+A) = A(A+AB) + B(A+AB) + ABA + AAB
A(A+AB) = A^2 + A^2B = A + A^2B
B(A+AB) = AB + A^2B^2 = AB + A^2B
ABA = A^2B
AAB = A^2B
(A+B)(A+AB) + AB(A+A) = A + A^2B + AB + A^2B + A^2B + A^2B
(A+B)(A+AB) + AB(A+A) = A + A^2B + AB + A^2B + A^2B + A^2B = A + A^2B + AB + 3A^2B
A + A^2B + AB + 3A^2B = A + AB + 4A^2B
A + AB + 4A^2B = C + CD + 4C^2D
C + CD + 4C^2D = C¯ + D
Therefore, if (B⇒A) is true, then (A+B)(A+AB) + AB(A+B) simplifies to C¯ + D.

4. --
Idempotence
Venn Diagram for OR

![image](https://github.com/MalykaMabom205/IDS2024S/assets/91574091/ed14a05a-d8cb-4c90-8d1b-3abc10dac12f)    

 Venn diagram for AND
 
 ![image](https://github.com/MalykaMabom205/IDS2024S/assets/91574091/fcb91234-16d5-4876-94d2-603406a919c3)     

Commutativity:
Venn diagram for OR (⋁) operation:

![image](https://github.com/MalykaMabom205/IDS2024S/assets/91574091/003fdaa1-2c72-4d97-8a31-81f893186a42)        

Venn diagram for AND (⋀) operation:

![image](https://github.com/MalykaMabom205/IDS2024S/assets/91574091/35a1e1d3-99c9-4c90-ae81-44230acab2ee)         

Associativity:

Venn diagram for OR (⋁) operation:

![image](https://github.com/MalykaMabom205/IDS2024S/assets/91574091/6501f567-ce53-4ded-9be2-ad3a136a0107)     

Venn diagram for AND (⋀) operation: 

![image](https://github.com/MalykaMabom205/IDS2024S/assets/91574091/f154957d-4e2e-44d9-b8c1-b41f0bb10885)        

Distributivity:
Venn diagram for distributivity:

![image](https://github.com/MalykaMabom205/IDS2024S/assets/91574091/63fdf2e5-b618-4140-9307-aafc6030d1a6)     

Duality: 
A
       _____
      |     |
      |  ∪  |
      |_____|
         A

A
       _____
      |     |
      |  ∩  |
      |_____|
         A         

5:

Idempotence:
Truth table for OR (⋁) operation:

| A | A ⋁ A |
|---|-------|
| 0 |   0   |
| 1 |   1   |


Truth table for AND (⋀) operation:
| A | A ⋀ A |
|---|-------|
| 0 |   0   |
| 1 |   1   |

Commutativity:

Truth table for OR (⋁) operation:
| A | B | A ⋁ B | B ⋁ A |
|---|---|-------|-------|
| 0 | 0 |   0   |   0   |
| 0 | 1 |   1   |   1   |
| 1 | 0 |   1   |   1   |
| 1 | 1 |   1   |   1   |

Truth table for AND (⋀) operation:
| A | B | A ⋀ B | B ⋀ A |
|---|---|-------|-------|
| 0 | 0 |   0   |   0   |
| 0 | 1 |   0   |   0   |
| 1 | 0 |   0   |   0   |
| 1 | 1 |   1   |   1   |

Associativity:

Truth table for OR (⋁) operation:

| A | B | C | (A ⋁ B) ⋁ C | A ⋁ (B ⋁ C) |
|---|---|---|-------------|-------------|
| 0 | 0 | 0 |      0      |      0      |
| 0 | 0 | 1 |      1      |      1      |
| 0 | 1 | 0 |      1      |      1      |
| 0 | 1 | 1 |      1      |      1      |
| 1 | 0 | 0 |      1      |      1      |
| 1 | 0 | 1 |      1      |      1      |
| 1 | 1 | 0 |      1      |      1      |
| 1 | 1 | 1 |      1      |      1      |


Truth table for AND (⋀) operation:

| A | B | C | (A ⋀ B) ⋀ C | A ⋀ (B ⋀ C) |
|---|---|---|-------------|-------------|
| 0 | 0 | 0 |      0      |      0      |
| 0 | 0 | 1 |      0      |      0      |
| 0 | 1 | 0 |      0      |      0      |
| 0 | 1 | 1 |      0      |      0      |
| 1 | 0 | 0 |      0      |      0      |
| 1 | 0 | 1 |      0      |      0      |
| 1 | 1 | 0 |      0      |      0      |
| 1 | 1 | 1 |      1      |      1      |

Distributivity:
| A | B | C | A ⋀ (B ⋁ C) | (A ⋀ B) ⋁ (A ⋀ C) |
|---|---|---|-------------|------------------|
| 0 | 0 | 0 |      0      |        0         |
| 0 | 0 | 1 |      0      |        0         |
| 0 | 1 | 0 |      0      |        0         |
| 0 | 1 | 1 |      0      |        0         |
| 1 | 0 | 0 |      0      |        0         |
| 1 | 0 | 1 |      1      |        1         |
| 1 | 1 | 0 |      1      |        1         |
| 1 | 1 | 1 |      1      |        1         |

Duality:

Truth table for original expression:

| A | B | C | A ⋁ (B ⋀ C) |
|---|---|---|-------------|
| 0 | 0 | 0 |      0      |
| 0 | 0 | 1 |      0      |
| 0 | 1 | 0 |      0      |
| 0 | 1 | 1 |      0      |
| 1 | 0 | 0 |      1      |
| 1 | 0 | 1 |      1      |
| 1 | 1 | 0 |      1      |
| 1 | 1 | 1 |      1      |

Truth table for dual expression:
| A | B | C | A ⋀ (B ⋁ C) |
|---|---|---|-------------|
| 0 | 0 | 0 |      0      |
| 0 | 0 | 1 |      0      |
| 0 | 1 | 0 |      0      |
| 0 | 1 | 1 |      0      |
| 1 | 0 | 0 |      1      |
| 1 | 0 | 1 |      1      |
| 1 | 1 | 0 |      1      |
| 1 | 1 | 1 |      1      |
       
   
6. --
"B|C' > B|C"   
![image](https://github.com/MalykaMabom205/IDS2024S/assets/91574091/87334094-ee0b-4c7a-84f5-1157a63e85cd)     
"A|BC' = A|BC
![image](https://github.com/MalykaMabom205/IDS2024S/assets/91574091/a55b738a-a514-4807-9d48-aa77a29e656d)      
"B|C' > B|C" and "A|BC' = A|BC"
![image](https://github.com/MalykaMabom205/IDS2024S/assets/91574091/2c5f487a-95c9-4352-bb93-a86c1b46eb06)      
"AB|C'" and "AB|C."
![image](https://github.com/MalykaMabom205/IDS2024S/assets/91574091/7927707d-c73f-4f99-8ee7-e5dde183c149)       

7.
The three fundamental desiderata of Probability Theory are:
Sample Space: Probability theory requires the definition of a sample space, which represents the set of all possible outcomes or events of interest in a given situation. The sample space provides a framework for identifying and describing the possible outcomes that we want to assign probabilities to.

Events: In probability theory, events are subsets of the sample space. An event represents a specific collection or combination of outcomes from the sample space. Events can range from simple, single outcomes to complex combinations of outcomes. Probability theory deals with assigning probabilities to events and understanding their likelihood of occurrence.

Probability Measure: Probability theory employs a probability measure, which assigns a numerical value to each event in the sample space. The probability measure represents the likelihood or chance of an event occurring. It satisfies certain axioms, such as being non-negative, summing to one over the entire sample space, and exhibiting additive or sigma-additive properties. The probability measure allows us to quantify uncertainty and make probabilistic predictions or decisions based on the assigned probabilities.


























   
