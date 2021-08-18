## AI502 HW#1

In Implementing models part,
- Use l_lambda value 0.01 for L2 regularization, and use l_lambda value 1e-5 for L1 regularization.
- Specify the model by uncommenting the line of the model: MLP, MLP with Dropout, VGG16 or ResNet18.
- Specify the optimizer by uncommenting the line of the optimizer: Momentum, Momentum with L2 regularization, AdaGrad or Adam.

In Training part,
- train_loss, train_acc, valid_acc, l1_norms and l2_norms are to store the results for each epoch and used in Visualization part.
- To use L1 regularization, uncomment the line below ### L1 regularization.

In Visualization part,
- Plot training loss, L1 norm, L2 norm, training accuracy and validation accuracy.

In MLP.py,
- Revised some part to add Dropout functionality.