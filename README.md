# learning-nlp-semantic-similarity
Library to accompany my Medium post about learning to implement NLP, specifically semantic similarity. 

## Setup ##

If you're using an Apple Silicon Mac, there are a few pre-requisites needed to run the huggingface libraries - Rust and cmake. I'm using Pyenv for this projects environment.

Install Rust, which is required for the NLP model (https://github.com/huggingface/transformers/issues/2831#issuecomment-600141935)

    curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

Use Homebrew to install cmake.

    brew install cmake

Restart your terminal.

Install Python:

    pyenv install 3.11.1

Create a new pyenv environment:

    pyenv virtualenv 3.11.1 learning_nlp

Activate the new environment:

    pyenv activate learning_nlp

Install the required modules:

    pip install -r requirements.txt