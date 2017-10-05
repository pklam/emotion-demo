# Emotion Reader Demo

> The Emotion API takes a facial expression in an image as an input, and returns the confidence across a set of emotions for each face in the image, as well as bounding box for the face, using the Face API.

Based off the [Azure Emotion API](https://azure.microsoft.com/en-us/services/cognitive-services/emotion/ "Azure Emotion API") to classify facial images into a range of emotions such as:
- anger
- contempt
- happiness
- neutral
- disgust
- fear 
- sadness
- surprise

### How to setup
- Register for a free subscription key: [here](https://azure.microsoft.com/en-us/try/cognitive-services/ "here")
- Replace the empty quotes with your key. 
    `xhrObj.setRequestHeader("Ocp-Apim-Subscription-Key","");`
	
- Replace the URL with your endpoint URL. Make sure recognize is still at the end.
`url: "https://westus.api.cognitive.microsoft.com/emotion/v1.0/recognize?",`

- Open *index.html*.

