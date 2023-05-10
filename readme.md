Traffic Counter Analytics using YOLOv8, that counts vehicles passing in video feeds with 90% of accuracy.
It uses deep sort technique to determine and analyise the vehicles in the video and finds the approaching and leaving vehicles based on a certain checkpoint the has been implemented.
This project can be further enhanced to check for a U-Turn be marking each of the vehicle with a particular ID if the number plate of the vehicle can be analyised

Run the following commands in the terminal to see the output on the input video
**pip install -r requirements.txt
python main.py

test.mp4 is the input video on which the algorith is playing, the video can be changed to any other video in the same path to perform the same action on it
