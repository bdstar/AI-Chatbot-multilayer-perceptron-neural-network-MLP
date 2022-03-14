# AI-Chatbot-multilayer-perceptron-neural-network-MLP
Note: This project copied from original project https://github.com/NeuralNine/neuralintents and customized according to chatbot for SAP landscapes, however here we need to work with SAP FIORI UI team to integrate and call webservice which deployed in these python programs on secured database.

Arificial Intelligent Chatbot Using Neural Networks and Natural Language Processing

Steps to follow:

1. Run the program training.py
2. The program will 500 epochs and creates chatbot_model.h5, labels.pkl and words.pkl files.  The sample files attached.

Epoch 1/500
10/10 [==============================] - 0s 2ms/step - loss: 2.4801 - accuracy: 0.0423
Epoch 2/500
10/10 [==============================] - 0s 723us/step - loss: 2.3048 - accuracy: 0.2163
Epoch 3/500
10/10 [==============================] - 0s 0s/step - loss: 2.2063 - accuracy: 0.2503
Epoch 4/500
10/10 [==============================] - 0s 2ms/step - loss: 2.0829 - accuracy: 0.3555
.....................................................................................
10/10 [==============================] - 0s 0s/step - loss: 0.0471 - accuracy: 0.9586 
Epoch 498/500
10/10 [==============================] - 0s 2ms/step - loss: 0.0372 - accuracy: 0.9722
Epoch 499/500
10/10 [==============================] - 0s 0s/step - loss: 0.0887 - accuracy: 0.9595
Epoch 500/500
10/10 [==============================] - 0s 2ms/step - loss: 0.0592 - accuracy: 0.9393
Done

3. Run the program chatbot.py
4. Start chat with AI Chatbot
5. Below few chats with AI Chatbot

Bot: Hi! How can I help you

User: hi

Bot: Hi there, how can I help you?

User: how are you

Bot: Hi! I am good, how about you?

User: I am good

Bot: What can I do for you?

User: I want to query an order

Bot: Please provide order number.

User: 123456789

Bot: The Order is ready to deliver on 3rd June 2021.
