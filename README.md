# Please use the following link for a readable rendered html

http://htmlpreview.github.io/?https://github.com/ThomasRoscher/Coursera_ds_specialization_captstone_R/blob/master/cap_report.html

# Corsera_ds_specialization_captstone

This is my solution for the capstone project of the Coursera specialization "Data Science". Natural Language Processing (NLP) which is a field that covers computer understanding and manipulation of human language offers possibilities to build models that predict next words pretty accurately. For this project I buildt a N-gram based algorithm that predicts the next word for an input word/sentence. The main challenge here was to code the algorithm so that it is accurate but also quick and small enough for real time execution on a simple web application. Moreover, since there is no pre-build R function the algorithm was build from scratch. The final model uses about 2.5 mio static N-grams, requires about 40 Mbyte, needs roughly 0.2 seconds to calculate the three most likely next words, and has an accuracy of 0.24 on 10000 randomly selected test sentences. Note, that the professional service SwiftKey get's about 0.3.
