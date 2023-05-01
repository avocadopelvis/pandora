# PANDORA - THERAPEUTIC AI ASSISTANT
Classic therapy scenes in Hollywood films show a distraught client reclining on a colourful Victorian sofa and recounting their troubles. The psychotherapist ponders in a leather chair, while the client’s concerns are revealed to be tied to some early experiences. Most therapy in the real world hasn’t looked like this in ages. However, these scenes get one thing right: the therapist in the room is **human**. <br>

Today, as the need for mental health services continues to surpass availability, people in distress can reach out online to mental health “chatbots.” In some instances, the responses are based on artificial intelligence (AI). In others, there’s a human element.

But the question remains: Is it possible to automate the expertise needed to become an effective therapist, using sophisticated algorithms and programming, when humans spend a lifetime trying to master these skills?

# CHATBOTS
Chatbots are systems that can carry on extended conversations with the goal of mimicking the unstructured conversations or ‘chats’ characteristic of informal human-human interaction.

![eliza](https://user-images.githubusercontent.com/92647313/161245945-2314570e-6c7a-4ab2-98aa-98129529c669.png) <br>
Starting from the very first system, **ELIZA**, chatbots have also been used for practical purposes like testing theories of psychological counseling. ELIZA was designed to simulate a Rogerian psychologist, based on a branch of clinical psychology whose methods involve drawing the patient out by reflecting the patient's statements back at them.

# PANDORA
**Pandora** is a conversational agent designed to mimic a psychotherapist in order to provide emotional support to people with anxiety & depression.
At its core, Pandora is a chatbot trained on a text dataset using Deep Learning and Natural Language Processing techniques. 

Pandora can provide general advice regarding anxiety and depression, answer questions related to mental health and make daily conversations. Pandora is obviously not a licensed physician, and it does not make diagnoses or write prescriptions. Pandora offers help and support rather than treatment. Pandora is not equipped to deal with real mental health crises either. When it senses someone is in trouble, it suggests they seek help in the real world and provides text and hotline resources. Pandora doesn’t seek to remove the human element in therapy either but is rather a “gateway therapy,” to give people a good first experience, and even help them realise when they need a more intense form of intervention.

# HOW TO RUN THIS REPOSITORY?
First, clone this repository. 
Create a virtual environment using:
```
python -m venv <environment name>
```
Activate the virtual environment and then install the necessary libraries using:
```
pip install -r requirements.txt
```
Train the model using:
```
python model.py
```
Now run Pandora using:
```
python chat.py
```

You can modify Pandora by inserting your own text in the `intents.json` file.

# A CONVERSATION WITH PANDORA
![sample-chat](https://user-images.githubusercontent.com/92647313/161245842-93846e15-1fb7-4a5f-b863-83588858fddf.png)

# DATASET
https://www.kaggle.com/datasets/elvis23/mental-health-conversational-data

# FUTURE WORK
- [ ] Fine-tune using GPT-3.
 


