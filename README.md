# Purpose
Given a container of objects, fill in a dictionary with those objects in the container.
This is useful when you want to dynamically generate a list of objects.


# Requirements
Requires [BOLT for Unity](https://assetstore.unity.com/packages/tools/visual-scripting/bolt-163802)
Tested on Unity 2019.3.1f1

# Demo Scene
The package includes a demo scene as seen below:
![Demo Scene](./SS_Dynamic_Dictionary_FilledIn.png?raw=true "Demo Scene")

In the demo scene you will see how the list of game objects is converted into a dictionary that you can use in your code.

Note: The included asset's demo scene has some warnings about missing scripts when I tested it on a fresh project. They do not stop it from running and I am not sure why this occurs yet (for example, canvas is missing the scaler). 

# Super Unit


![Super Unit](./SS_SuperUnit_FillInDictionary_WithObjects.png?raw=true "Super Unit")

The above image is of the Super Unit. It takes in a key format and the container that has the objects to put into a dictionary. Out, you get the counter of items and also the dictionary.

The format of the key can be any string. In order to help, you can include %Iterator% and it will create numbered keys. For example, User%Iterator% will create a dictionary with User1, User2, and User3 as the keys if 3 game objects exists under the parent game object you are using.



# Bring Into Project (How to use)
Import the unityasset like you would any asset. From there, use the super unit (JerryBOLT_V1_Utility_SUPERUNIT_FillDictionaryWithGameObjects_V0002) included in your BOLT Graphs.

