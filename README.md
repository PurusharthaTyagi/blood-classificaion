# blood-classificaion

## Context
The diagnosis of blood-based diseases often involves identifying and characterizing patient blood samples. Automated methods to detect and classify blood cell subtypes have important medical applications.

## Custom built CNN
Model contains a sequence of five Conv blocks containing combinations of SeparableConv2D, BatchNormalization, MaxPooling and Dropout layers. The output of the final Conv block is flattened and followed by three Fully Connected (FC) layers each with its own Dropout layer. A final FC layer is added with four units and a softmax activation for multiclass classification.
