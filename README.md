# Medical-Deep-Learning

In this exercise objective was to classify (variable-length) ECG recordings of the PhysioNet/CinC Challenge
into four rythm classes: 1.normal sinus rhythms (N), 2.atrial fibrillation (AF), 3.other rhythms (O), 4.noise
signals (∼).

Initially used pretrained 7 layer ResNet with adaptive max-pooling and then extended to 15 layer ResNnet. 
Furhter implemented 2 layered LSTM to replace adaptive max-pooling in 15 layer ResNet.
