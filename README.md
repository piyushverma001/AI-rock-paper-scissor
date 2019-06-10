# AI-rock-paper-scissor
It is an AI based rock paper scissor game which reads your hand gestures and also predicts your future moves to win the game.

For hand posture recognition, A customised background subtractor is used and multiple shots have been taken for different postures like rock, paper, and scissor. Then a simple CNN is trained using 100 images of each category. It gives around 85% accuracy in detecting right gestures, however it can be improved by training over larger number of images. A simple algorithm is also added to predict future moves.

To play the game first install the requirements from requirements.txt

Then run the main script using python main.py
To move keep your hand in the green box and press 'p'.

