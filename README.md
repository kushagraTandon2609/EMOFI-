# EMOFI
emotion detection song recommendation system

This project develops a song recommendation system that leverages emotion detection to suggest music tailored to the user's current emotional state. By analyzing text input (like lyrics or user moods) and identifying emotions, the system recommends songs that resonate with the detected feelings.
CMD run - streamlit run music.py

##Make sure to have python 3.10 installed in your system.

## Features
- Collects emotion data
- Trains a machine learning model
- Runs inference to detect emotions
- Recommends music based on emotion

## Project Structure
- `data_collection.py`: Collects emotion data
- `data_training.py`: Trains the emotion recognition model
- `inference.py`: Runs emotion inference
- `music.py`: Recommends music based on detected emotion
- `model.h5`: Trained model file
- `*.npy`: Numpy data files for emotions
- `requirements.txt`: Python dependencies

## Setup
1. **Clone the repository**
	 ```
	 https://github.com/kushagraTandon2609/EMOFI-.git
	 cd EMOFI-
	 ```
2. **Create and activate a virtual environment**
	 ```
	 python -m venv venv
	 venv\Scripts\activate
	 ```
3. **Install dependencies**
	 ```
	 pip install -r requirements.txt
	 ```

## Usage
- **Collect Data:**
	```
	python data_collection.py
	```
- **Train Model:**
	```
	python data_training.py
	```
- **Run Inference:**
	```
	python inference.py
	```
- **Recommend Music:**
	```
	python music.py
	```
	or
	streamlit run music.py

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
