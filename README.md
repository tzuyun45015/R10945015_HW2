# ML_HW2
Run R10945015_HW2.ipynb and will generate models. The final predictions are save in prediction.csv.

For model structure, I use GRU as Recurrent Neural Network with dropout = 0.5 and bidirectional and 6 layers. Then put the output of the GRU model into linear model with dropout = 0.5 and batchnorm. As for parameters, I set concat_nframe as 45, training ratio 0.9, batch_size = 512, num_epoch = 10.
