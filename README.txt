# CMPS143_ass3

In this repository you can find the third assignment of the course CMPS143 Natural Language Processing at UCSC Winter 2019.

## Execution of the file:
To run the file restaurant-competition-P1.py you would need to write in the terminal:

python restaurant-competition-P1.py

Additionally, you can add the next optional arguments:
· -d data_fname: File name of the training data. It's default value is "train_examples.tsv".
· -t test_data: File name of the test data. If you don't introduce this argument,
    no test prediction will be done. It's default value is None.
· -w write_fname: File name of the output. This allows to write the predictions to a file.
· -b binning: Whether you want to bin the features or not. It's default value is True.
· -c classifier: Classifier already trained. This allows to run the program with an already
    classifier. It's default value is None.

I run the file as the following:
python restaurant-competition-P1.py -t test.txt -w restaurant-competition-model-P1-predictions.txt
