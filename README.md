# ROBOKALAM_ASSIGNMEN
# CHATBOT-TASK
# What Is A Chatbot?
   A chatbot also known as a chatterbot, bot, artificial agent, etc is basically software program driven by artificial intelligence which serves the purpose of making a      conversation with the user by texts or by speech. Famous examples include Siri, Alexa, etc.
 
# How Does It Work?
 We can define the chatbots into two categories, following are the two categories of chatbots:
 Rule-Based Approach – In this approach, a bot is trained according to rules. Based on this a bot can answer simple queries but sometimes fails to answer complex queries.
 Self-Learning Approach – These bots follow the machine learning approach which is rather more efficient and is further divided into two more categories.
 Retrieval-Based Models – In this approach, the bot retrieves the best response from a list of responses according to the user input.
 Generative Models – These models often come up with answers than searching from a set of answers which makes them intelligent bots as well.

# FACE-DETECTION-TASK
# I used opencv
While we used OpenCV to facilitate face recognition, OpenCV itself was not responsible for identifying faces.
In today’s tutorial, we’ll learn how we can apply deep learning and OpenCV together (with no other libraries other than scikit-learn) to:
Detect faces
Compute 128-d face embeddings to quantify a face
Train a Support Vector Machine (SVM) on top of the embeddings
Recognize faces in images and video streams
All of these tasks will be accomplished with OpenCV, enabling us to obtain a “pure” OpenCV face recognition pipeline.

# In order to build our OpenCV face recognition pipeline, we’ll be applying deep learning in two key steps:
To apply face detection, which detects the presence and location of a face in an image, but does not identify it
To extract the 128-d feature vectors (called “embeddings”) that quantify each face in an image

