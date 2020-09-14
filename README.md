# Face and Object Recogniser
 
1. build_dataset.py is used to generate the facial data by taking pictures from the webcam
2. extract_embeddings.py is used to extract the facial embeddings in the from of 128-d vector
3. train_model.py is run to train the model with the facial data generated above with the embeddings and other inputs
4. minor.py has the main program that performs facial and object recognition
	a. pyttsx3 is used for text to speech conversion to give the voice output.
	b. a bounding rect is drawn around the recognized ROI along with the label.
	c. coco dataset is used to train the object recognition model


References: pyimagesearch.com
