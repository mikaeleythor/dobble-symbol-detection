# Dobble Symbol Detection

This project aims to train the Yolov8 model to detect unlearned symbols in Dobble
cards. Classifying the symbols is not within the scope of this project, but
determining the existence and location of all symbols is.

## Use Cases

The aim of this project is to be able to locate symbols in Dobble cards on an
image, such that the symbols can be extracted and passed to a Siameze Network
which determines which, if any, symbols are matching.

## Method

Train the Yolov8 model on multiple datasets, perhaps utilizing transfer
learning, such that the model can detect unlearned in Dobble cards.
