# Web-based-app-for-Abstractive-Text-Summarization
Text summarization is the problem of reducing the number of sentences and words of a document without changing its meaning.. There are different
techniques to extract information from raw text data and use it for a
summarization model, overall they can be categorized as Extractive and
Abstractive.
# Our Model-Sequence to Sequence (often abbreviated to seq2seq) models is a
special class of Recurrent Neural Network architectures that we
typically use (but not restricted) to solve complex Language
problems like Machine Translation, Question Answering, creating
Chatbots, Text Summarization, etc..
The most common architecture used to build Seq2Seq models is EncoderDecoder architecture.
Workflow:
Input:Abstract->Model->Output:Research Highlights

# Procedure:
1)Starting with some Data Analysis which is needed for the
next Feature Engineering.
2)Next we can have a look at the length distribution by
counting the words
3)After that, we have all we need to proceed with Feature
Engineering. The feature matrix is created by transforming the
preprocessed corpus into a list of sequences using
TensorFlow/Keras
4)Next we take care of the summaries. Before applying the
same feature engineering strategy we need to add two special
tokens inside each summary that determine the beginning and
end of the text.
5)Then we build the encoder-decoder model and apply a
Seq2Seq algorithm to get the summary.


# Author- Soumyo Nath Tripathy
# Co-Author- Anushka Mitra
