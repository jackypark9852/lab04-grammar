# lab04-grammars
Let's practice using grammars! For this lab, please pull up the L-system node in Houdini.

## 1. Wheat grammar puzzle
Look at these iterations (n = 1, 2, 3) of a one-rule grammar. Using the built in symbols in Houdini, design a grammar that produces this output. Take a screenshot of your rules.\
<img width="200" alt="square1" src="https://user-images.githubusercontent.com/1758825/193949661-a3a0e1f7-7d68-4b9e-8384-d9991e1e9fd2.png">
<img width="200" alt="square2" src="https://user-images.githubusercontent.com/1758825/193949853-cf2306b3-3537-4c24-91b5-0a3083bc87c0.png">
<img width="200" alt="square3" src="https://user-images.githubusercontent.com/1758825/193949859-5e432b4b-f18d-48b5-a9e9-8d7dba255955.png">

```
Axiom: X
Rule: X=XX[+XX]X[+XX]XX+
```

## 2. Square grammar puzzle
How about this one? Take a screenshot of your rules.\
<img width="200" alt="square1" src="https://user-images.githubusercontent.com/1758825/193949895-87cdfb43-da7c-4867-ab1b-107e1ba9d2a7.png">
<img width="200" alt="square2" src="https://user-images.githubusercontent.com/1758825/193949904-a9cdfe0f-319e-4ca8-9935-dd338217a7cf.png">
<img width="200" alt="square3" src="https://user-images.githubusercontent.com/1758825/193949910-928e5993-ce26-4681-80f8-ffeb54be4dcf.png">

```
Axion: -X
Rule: X=X+X-X-X+X
```
## 3. Custom plant
Choose a plant in the world. Working off a reference, design a grammar that mimics the structure of that plant. Unlike our simple puzzles, please use multiple rules for greater complexity. Think carefully about the structure of your grammar! EXPLAIN the structure of your plant in the README. What are the components? What do each of the rules do? Be sure to also include images of a few iterations of your output plant. 
<img width="200" height="381" alt="image" src="https://github.com/user-attachments/assets/e8b3ba4e-71eb-49ca-938a-442433e8ccd0" />
<img width="200" height="380" alt="image" src="https://github.com/user-attachments/assets/c6c8d561-9300-4156-b44a-50a0a5dfbbf7" />
<img width="200" height="384" alt="image" src="https://github.com/user-attachments/assets/4e40abf4-be46-48d9-9c79-2b2e5a4c0c25" />
```
Axiom: X
Rule 1: X=-C0D[++++C1F---F---F]C0D[---------C1F+F+F]C0DDDDDDDDDDX
Rule 2: F=[++++DDDDDDDD][-----DDDDDDDD]DDF
```
## Submission
- Create a pull request against this repository
- In your readme, list your solutions and format your README nicely
- Profit
