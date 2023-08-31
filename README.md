# deep-learning-challenge

Overview:
The non-profit Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. The pupose of the analysis is to create a neural netowkr to predict whether applicants will be succesful if they are funded by Alphabet Soup.

Preprocessing:
Target Variable: “IS_SUCCESSFUL’.
Features: APPLICATION_TYPE	AFFILIATION, CLASSIFICATION, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, USE_CASE
Removed Variables: NAME, EIN

Model:
2 hidden layers with activation relu, 100 and 40.
Outer layer activation was sigmoid.
Accuracy: 73%
![Screenshot 2023-08-31 at 1 10 36 PM](https://github.com/ollayyy/deep-learning-challenge/assets/124837569/21e3c9f6-6aae-4e9d-9842-d25e8e1d14d7)

Summary:
In the optimization file I tried different amounts of layers, activation functions, dropping columns and also adjusting the bins. All tests stayed around 72% with the highest being 73%. I couldn’t achieve the target performance.

![Screenshot 2023-08-31 at 1 09 47 PM](https://github.com/ollayyy/deep-learning-challenge/assets/124837569/35c4162a-a8fa-4bf8-849e-2c8c83b1f886)
