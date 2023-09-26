# ChessAI-Deep-Learning-Chess-Move-Predictor-CNN
This repository contains a Python project that uses deep learning models to predict the best chess moves given a board position in the FEN (Forsyth-Edwards Notation) format. The project utilizes Convolutional Neural Networks (CNNs) to predict the piece type, destination square's alpha (column), and destination square's number (row) for the next move.

## Overview
The project includes the following components:
- Data preprocessing to convert FEN notation to a format suitable for deep learning.
- Three separate deep learning models for predicting piece type, alpha, and number of the destination square.
- Training and evaluation of these models using a dataset of chess game moves.
- A function to predict the best move for a given FEN board position.

## Requirements
To run this project, you'll need:
- Python 3.x
- TensorFlow and Keras
- Python Chess library (`python-chess`)

You can install the required packages using `pip` with the following command:
```
pip install chess tensorflow
```

## Usage
1. Clone the repository to your local machine.
2. Train the deep learning models by running the respective training scripts.
3. After training, use the `predict_best_move` function to predict the best move for a given FEN board position.

```python
fen_board = 'r1bqkbnr/ppp2ppp/2n5/3Bp3/4P3/5Q2/PPPP1PPP/RNB1K1NR b KQkq - 0 1'
best_move = predict_best_move(fen_board)
print("Best next move:", best_move)
```

## Model Files
The trained models (piece_model.h5, alpha_model.h5, and number_model.h5) can be made available on request at sohailanwar.es@gmail.com.

Feel free to explore and enhance this project for chess move prediction and analysis. Happy coding!
