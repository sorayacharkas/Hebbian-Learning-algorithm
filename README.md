# Hebbian learning: letter recognition

A Hebbian network that tries to recognise 7 letters (A, X, O, E, Z, T, L) drawn on a 5×7 grid, with clean and noisy test patterns.

What I found:

| Encoding | Accuracy on noisy letters |
|---|---|
| Binary input/output | ~5% |
| Binary input, bipolar output | ~36% |
| Bipolar input and output | ~64% |

Letters that are close to orthogonal (like T and L) are recognised best; similar ones (E vs. A) get mixed up. That limitation is why I tried a [perceptron](https://github.com/sorayacharkas/perceptron_character_recognition) next.

`hebbian_learning.ipynb` (NumPy). Artificial Neural Networks course, Sharif University of Technology.
