## Credit:
Base model from Mediapipe & Kazuhito Takahashi

## This is to translate hand gesture into: 
- Common phrase <br>
- Alphabet by using standard American Sign Language <br>

## Add training data:
1) Press <k> to enter logging mode
2) Position hand with respect to the target translation
3) Press the key that correspond to the translation index (starting from 0)

Note that for translation with index above 9, alphabet 'a' to 'z' will represent translation 11 to 37

## Add translation:
1) Open "keypoint_classifier_label.csv"
2) Add new translation on a new line (one line per translation)

## Train:
Run "model_train.py"

##
Last edit: June 13, 2025
