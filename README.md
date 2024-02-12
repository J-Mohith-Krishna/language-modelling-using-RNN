# language-modelling-using-RNN
## Description-
The script trains a character-level RNN model using PyTorch to generate names associated with different nationalities. It preprocesses data, defines the model architecture, trains the model, and samples new names. Training progress is visualized.
## Explanation-
  -Importing necessary packages: Essential libraries such as PyTorch, as well as utilities for file handling and Unicode manipulation, are imported.

  -Defining data preprocessing functions: Functions for reading and processing text files containing names and their corresponding nationalities are defined.

  -Building the RNN model: The RNN class is defined, which initializes the model architecture and includes the forward propagation method.

  -Training the RNN: Functions for training the RNN model using randomly sampled training examples are provided.

  -Monitoring training progress: Functions for tracking and printing training loss during the training process are implemented.

  -Generating name samples: Functions for generating names based on a given nationality and starting letters are defined.

  -Executing the script: Finally, the script is executed by generating name samples for various nationalities using different starting letters.
