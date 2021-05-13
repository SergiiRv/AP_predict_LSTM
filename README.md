# AP_predict_LSTM
Real Neuron Upcoming Activity Prediction based on LSTM seq2sec model

## Why do this? The Rationelle!
Sometimes in Neuroscience and related kind of research and development, it could be important   
to have a prediction of the upcoming Action Potentialin in the real neuron probed with any electrophysiological setup
There is a mounting number of papers demonstrating that real neurons in our brain have an intrinsic mechanism of AP anticipation 
based on the previous short or long time resting potential fluctuations.
For example:
* [How can single sensory neurons predict behaviour?](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4683594/) 
* [Neurons learn by predicting future activity](https://www.biorxiv.org/content/10.1101/2020.09.25.314211v2.full)

Thus, it could be useful to analytically or computationally predict the upcoming AP in a real "wet" neuron of interest in order to undertake the active type or electrophysiological experiments or develop a neuromodulating tool.

# AP_predict_LSTM
Real Neuron Upcoming Activity Prediction based on LSTM seq2sec model
## Data used
![HillelPresentation_simple](https://user-images.githubusercontent.com/8824649/118050611-476a3900-b388-11eb-8412-1a655a4d9e24.jpg)
## Result by using simple LSTM
![HillelPresentation_simple2](https://user-images.githubusercontent.com/8824649/118050614-489b6600-b388-11eb-8536-473fbe0ed2e0.jpg)
## Result of using AutoEncoder+LSTM
![HillelPresentation_simple3](https://user-images.githubusercontent.com/8824649/118050616-4933fc80-b388-11eb-9d90-4fbe7949e561.jpg)

## Metrics results
TEST RESULTS
{'Test_EV_epoch': 0.7756353616714478,
 'test_EV_batch': 0.7840792536735535,
 'test_loss_batch': 0.00021588130039162934}

