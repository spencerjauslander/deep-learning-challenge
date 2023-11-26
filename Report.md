For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing
    What variable(s) are the target(s) for your model?
    - Target Variable = 'IS_SUCCESSFUL'
    What variable(s) are the features for your model?
    - Feature variables is every other variable except 'IS_SUCCESSFUL'
    What variable(s) should be removed from the input data because they are neither targets nor features?
    - 'EIN' and 'NAME' are neither targets nor features

Compiling, Training, and Evaluating the Model
    How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - First attempt
            Hidden nodes: 8,5
            Layers: 2 hidden, 1 output
            Functions: 2 relu, 1 sigmoid
    - Second attempt
            Hidden nodes: 40,35,15
            Layers: 3 hidden, 1 output
            Functions: 3 relu, 1 sigmoid
    - Third attempt
            Hidden nodes: 37,27,17,7
            Layers: 4 hidden, 1 output
            Functions: 3 relu, 1 tanh, 1 sigmoid
    Were you able to achieve the target model performance?
        I wasn't able to reach 75% accuracy
    What steps did you take in your attempts to increase model performance?
        Added more layers, added a variety of different nodes in different orders, added a different function.

    Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

        Overall, the first attempt was the most accurate attempt with 73%. More time in experimentation and combinations to finally reach the 75% would be required for future testing. Possible clean up or removal of columns might also be necessary.