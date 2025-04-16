student name-Pavani seelam
Student id-700756483


Stemming cuts a word to its root form, often crudely.
Lemmatization reduces a word to its base or dictionary form using context.
Example with "running":
Stemming: running → run (or sometimes runn)
Lemmatization: running → run (considering it's a verb)

Removing stop words is useful in NLP tasks like text classification or search, where common words (e.g., the, is) don’t add meaning and reduce noise.
However, it can be harmful in tasks like sentiment analysis or machine translation, where stop words (e.g., not) can affect meaning or sentiment.

NER (Named Entity Recognition) identifies and classifies entities like names, places, and dates.
POS (Part-of-Speech) tagging labels each word with its grammatical role, like noun, verb, or adjective.
Example:
In "Barack Obama was born in Hawaii."
NER: Barack Obama → PERSON, Hawaii → LOCATION
POS: Barack → NNP (proper noun), was → VBD (verb), etc.

Financial News Analysis: NER extracts company names, stock symbols, and dates to track events and trends automatically.
Search Engines: NER helps understand user queries by identifying entities (e.g., people, places) to give more accurate results.

We divide by √d to prevent very large dot-product values when the dimension d is large, which can cause softmax to produce very small gradients and slow learning. It helps stabilize training.

Self-attention lets the model weigh the importance of each word in a sentence relative to others, helping it capture context and relationships, like which words influence or depend on each other.

The main difference is:
BERT uses only the encoder and is designed for understanding tasks.
GPT uses only the decoder and is designed for generation tasks.

Using pre-trained models saves time and resources and provides better performance because they’ve already learned language patterns from large datasets. You just fine-tune them for your specific task.























