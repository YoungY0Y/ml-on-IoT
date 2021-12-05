### To run:
  * run blewithmic.ino sketch on arduino ide
  * run app.py with "Training" mode on
  * communicate with the microphone on Nano 33 BLE for training data
    * our training model used "YES" and "NO", but all simple words works
  * run classifier.py to train the svm model 
  * run app.py with "Testing" mode on

We achieved a 75% accurate model in cross-validation, and the latency for model
inference on average is ~0.5ms, while the total model latency from detecting voice
to Nano BLE receiving inference result on average is ~15ms.
