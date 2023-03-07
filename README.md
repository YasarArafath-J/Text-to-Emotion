Text To Emotion:

Discover the emotions in textual messages automatically using NLP.
Human beings can easily perceive emotions from texts and experience them naturally. Text to Emotion API lets you find the appropriate emotions embedded in the text data automatically using a few lines of code and a simple API.

How it works:

Text to Emotion API uses complex NLP algorithms to mine underlying emotions from a given text. Basically, the flow is as follows:

• Remove the unwanted textual part from the message.
• Perform the natural language processing techniques.
• Bring out the well-pre-processed text from the text pre-processing.
• Find the appropriate words that express emotions or feelings.
• Check the emotion category of each word.
• Store the count of emotions relevant to the words found.
The output of the endpoint is a JSON dictionary with keys as emotion categories (happy, surprise, angry, sad, fear) and values as emotion scores. The score is a value between 0.00 to 1.00. The higher the value, the more likely our text is to express that emotion.

Typical Use cases:

The API is mostly useful for the following industrial use cases:
• Customer Engagement: The signals that will be provided by the text-to-emotion API can help customer services teams to understand and interact with their clients more appropriately. It helps to speed up the process of understanding customer needs and complaints.
• Customer support with chatbots: Customer support with chatbots: Chatbots help companies to provide 24-hour support to their users. By enabling emotion detection, chatbots will be able to provide more human-like interaction which will help to increase customer satisfaction.
• Social Media Monitoring: Keeping a close eye on social media posts will help brands to take action before small problems happen to be a crisis.

Dependencies :

• In order to use this feature, first thing We must create an API Layer account to get an API Key. (Refer to this: https://apilayer.com/marketplace/text_to_emotion-api)
• Mendix Modular Version 8.18.23 or above.

How to configure:

• Create an account on the API Layer (https://apilayer.com/ ) and search the Text to emotion API on the given search bar and subscribe to the Text to emotion API from the API Layer marketplace (Refer to this: https://apilayer.com/marketplace/text_to_emotion-api)
• Collect the API Key for your API Layer account!
• Add the API Key value to the constant API Key from the module.
• Use Review to emotion snippet with preferred page and add it into the Navigation.
