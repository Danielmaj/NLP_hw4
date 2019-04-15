# NLP_hw4
Class exercise for Natural Language processing course from university of Tartu.

To train execute the comand:

allennlp train name_classifier.json -s ./output --include-package my_library.


The results should look like this (there is not validation Dataset as it was in the original example):

Metrics: {
  "training_duration": "00:00:01",
  "training_start_epoch": 0,
  "training_epochs": 29,
  "epoch": 29,
  "training_accuracy": 1.0,
  "training_loss": 0.6727902293205261,
  "validation_accuracy": 0.0,
  "validation_loss": 4.690981864929199,
  "best_epoch": 0,
  "best_validation_accuracy": 0.0,
  "best_validation_loss": 2.8830056190490723
}
