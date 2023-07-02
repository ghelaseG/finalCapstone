# Garden Path Sentences with spaCy

## Project Description

The Garden Path Sentences with spaCy project explores the phenomenon of garden path sentences and demonstrates their analysis using the open-source natural language processing (NLP) library spaCy. Garden path sentences are sentences that initially lead readers or listeners to interpret them in a certain way, but as the sentence progresses, a different interpretation emerges, often causing temporary confusion.

The main goal of this project is to showcase how spaCy's named entity recognition (NER) capabilities can handle garden path sentences. It demonstrates the tokenisation of each sentence and the subsequent identification and categorisation of named entities. Additionally, it utilises the `spacy.explain` function to provide explanations for the entity types.

## Table of Contents

- [Introduction to Garden Path Sentences](#introd)
- [Project Setup](#proj)
- [Usage Instructions](#usage)
- [Example Garden Path Sentences](#example)
- [Screenshots](#screen)
- [Conclusion](#conc)

<a name="introd"></a>
## Introduction to Garden Path Sentences

Garden path sentences are linguistic constructions that lead readers or listeners to interpret them in a certain way initially. However, as the sentence progresses, a different interpretation emerges, often causing momentary confusion. These sentences challenge the natural language understanding abilities of both humans and NLP models.

Garden path sentences demonstrate the complexity of language comprehension and the potential pitfalls that arise from sentence structure and word choice. By studying and analysing garden path sentences, we gain insights into the challenges faced by NLP models in understanding and correctly interpreting natural language.

<a name="proj"></a>
## Project Setup

To set up the project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/ghelaseG/finalCapstone.git`
2. Navigate to the project directory: `cd your_project`
3. Install the required dependencies: `pip install spacy`
4. Run the Python script: `python garden.py`

Ensure that you have Python and pip installed on your system before proceeding with the installation.

For more info about how to setup the project please use this [YouTube link](https://www.youtube.com/watch?v=q9wc7hUrW8U).

<a name="usage"></a>
## Usage Instructions

Once you have installed and run the project, it will analyse and categorise garden path sentences using spaCy. The script tokenises each sentence and performs named entity recognition to identify and categorise named entities present in the sentences. It then prints the tokens, their grammatical categories, and the entity types identified by spaCy.

The project also utilises the `spacy.explain` function to provide explanations for the entity types that may not be familiar. This feature allows users to understand the context and meaning of the identified entities within the sentences.

<a name="example"></a>
## Example Garden Path Sentences

Here are a few example garden path sentences that the project analyses:

1. "Hospitals Sued by 7 Foot Doctors."
2. "They painted the wall with cracks."
3. "Red Tape Holds up New Bridge."
4. "The old dog the footsteps of the young."
5. "Ricky knew the answer to the question was yes, but wouldn't speak the word out loud."
6. "Mary gave the child a Band-Aid."
7. "That Jill is never here hurts."
8. "The cotton clothing is made of grows in Mississippi."

By running the project, you can observe how spaCy categorises each token and identifies the named entities present in the garden path sentences.

<a name="screen"></a>
## Screenshots

Find at least 2 garden path sentences from the web or think up your own, and store the sentences you have identified or created in a list called
gardenpathSentences.

![1](https://github.com/ghelaseG/finalCapstone/assets/96828940/c2c6867c-2cb5-445c-9bba-8c287e84c77a)

Tokenise each sentence in the list and perform named entity recognition.

![2](https://github.com/ghelaseG/finalCapstone/assets/96828940/80e8ea8a-afad-4149-ad9d-2e10e3e210ad)

Examine how spaCy has categorised each sentence. Then, use spacy.explain to look up and print the meaning of entities that you don’t understand. For example: print(spacy.explain("FAC")).

![3](https://github.com/ghelaseG/finalCapstone/assets/96828940/d2679cd1-2a28-413d-b0e1-2ac06a71065c)

Write a comment about two entities that you looked up. For each entity answer the following questions:

  - What was the entity and its explanation that you looked up?
  - Did the entity make sense in terms of the word associated with it?

![4](https://github.com/ghelaseG/finalCapstone/assets/96828940/a0f74e24-af6e-43b5-b4c1-237fcc7f4bb7)

<a name="conc"></a>
## Conclusion

The Garden Path Sentences with spaCy project serves as an educational example to explore the complexities of language processing and the challenges faced in natural language understanding. By analysing garden path sentences and leveraging spaCy's NLP capabilities, we gain insights into how NLP models handle sentence tokenisation, named entity recognition, and entity categorisation.

For more information on spaCy and its features, visit the [spaCy documentation](https://spacy.io/).
