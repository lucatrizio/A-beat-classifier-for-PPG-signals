This project was developed as part of the Applied AI in Biomedicine course at Politecnico di Milano.

The goal is to classify each beat in PPG (Photoplethysmography) signals as Normal (N), Supraventricular (S), or Ventricular (V). The system provides two levels of classification:

Binary classification: N vs. non-N

Multiclass classification: N / S / V annotations for each detected systolic peak position

The project includes:

Data extraction and exploration

Preprocessing pipelines for PPG signals

Development and evaluation of neural network models tailored to improve detection accuracy, with a particular focus on the challenging S and V cases

Confidence estimation for each classification decision

Custom evaluation metrics to better assess and optimize the performance on minority classes
