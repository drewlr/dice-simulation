# dice-simulation
Small repo using python and Jupyter to calculate some dice probabilities. 

My use case is to work out suitable dice mechanics for a board game.

**What it does**

- It can estimate probability that rolling N dice simultaneously, you get:
  - at least X dice >= (or just >) than a given Threshold
  - sum of X dice >= (or just >) than a given Threshold
  
- Ability to add additional win and loss conditions, under the shape of repeated numbers. E.g. if you roll at least two 1s, you lose automatically. Or if you roll three 4s, you win automatically

- Dice can be customized in terms of n of faces, but also in terms of specific values (e.g. you could have a d6 with values [1,2,3,6,6,6])

**Example results for a d8 (die with 8 faces)**
![prob_d8](https://user-images.githubusercontent.com/8734331/183640515-e2a48ea4-4588-494e-b0d6-af5f826366d9.png)
