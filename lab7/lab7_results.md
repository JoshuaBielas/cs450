# Names: Josh Bielas and Josh Garbi
# Lab: lab7 (RAG for Code with UniXcoder)
# Date: 12/3/2025

---

## 2.2.1
The UniXcoder discrimination is a lot bigger than the generic discrimination. This means that UniXcoder is considerably better at determining how different the code segments are. 

## 2.3.1
It handles functionally similar code with different variable names very well. It still recognizes it as very similar. Multiplying numbers is pretty high even though its logic is a bit different.

## 2.3.2
It handles it very well. It recognizes it as the most similar to the original case. It has the highest score.

## 2.4.1
As more changes happen, the scores decrease more. It looks at syntax changes more than logic changes. Changing just the cosmetics drops the score more than changing the logic by changing operators. 

## 2.4.2
Cosmetic changes affect the score a lot more than changing one or a few operators. Adding a comment dropped the score more than changing 1 or 2 operators. Chaning variable names changed the score more than any of the other cases.