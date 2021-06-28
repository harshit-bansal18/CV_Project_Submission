# CV_Project_Submission

Number Prediction From Hand Gestures


Our aim is to predict the number shown through hand gestures. For this, we trained the hand image model with CNN and used a sliding window on the input image which detects the location and finger number simultaneously . This also helps in identifying multiple hands along with the digits they represent and this was the main purpose of the sliding window . To do this type of multiple detection , we have decided a threshold for score and then we draw a box around the detected hands and also provide a list of detected numbers.
We have also included a special feature which allows the user to open their camera and capture the image and then we predict the hand and number detected by it.



Now, our model predicts the number with a very high accuracy but there is a problem, sometimes, it gives high probability even on wrong objects. 

Our model was not based on CNN at first . It was based on HOG, DOM and sliding window, but it was not even detecting the hand due to some unknown reasons. We tried tweaking the model parameters like stepsize, pixels per cell etc, but even after wasting almost one day on it , our model was not able to detect the hand so then we thought of using neural networks for higher accuracy . We were partially successful in predicting the number represented by hand gesture since even after very high accuracy on test and train datasets it kept detecting objects other than hands with a very high score. We tried perfecting this model as much as we could but no major change was seen.
At last we just submitted the final code with both the approaches with first approach fully commented.
