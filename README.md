# Music-Generator-using-Markov-Chaine
# Project Overview

This project is an **academic assignment** developed as part of the course **Stochastic Processes (Processus Stochastiques)**. It explores how Markov Chains can be used to model and generate music sequences.

The system analyzes sequences of musical notes from a dataset and learns the probability of transitions between notes. Using this stochastic model, it generates new musical sequences that preserve the statistical structure of the original data.

The goal of this project is to understand and apply probabilistic models in a creative context such as music generation.

---

# Features

* Construction of a Markov transition matrix from musical note sequences
* Probabilistic generation of new note sequences
* Simulation of music creation using stochastic processes
* Visualization of transition probabilities
* Optional audio synthesis of generated sequences

---

# Methodology

1. Extract musical note sequences from the dataset
2. Compute transition probabilities between notes
3. Build a Markov Chain model
4. Generate new sequences by sampling from the probability distribution
5. (Optional) Convert generated notes into audio output

---

#  Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib

---

# Example Output

Example of a generated sequence:

```
C → E → G → A → F → C → D
```

These sequences are not directly taken from the dataset but generated based on learned stochastic transitions.

---

# Future Improvements

* Use higher-order Markov Chains
* Improve musical coherence with deep learning models
* Add rhythm and timing modeling
* Integrate MIDI input/output support
* Build an interactive web interface

---

