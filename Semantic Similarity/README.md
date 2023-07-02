# Watch Next Recommendation System

## Project Description

The Watch Next Recommendation System is a project that utilises word vector similarity to recommend movies based on their descriptions. The system aims to provide users with suggestions on what movie to watch next by finding the most similar movie to a given description.

## Table of Contents

- [Introduction to Semantic Similarity](#introd)
- [Project Setup](#proj)
- [Usage Instructions](#usage)
- [Example Semantic Similarity](#example)
- [Screenshots](#screen)
- [Conclusion](#conc)

<a name="introd"></a>
## Introduction to Semantic Similarity

Semantic similarity is a fundamental concept in natural language processing (NLP) that measures the likeness or resemblance between text based on their meaning. 

Semantic similarity plays a crucial role in recommendation systems and information retrieval

<a name="proj"></a>
## Project Setup

To set up the project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/ghelaseG/finalCapstone.git`
2. Navigate to the project directory: `cd your_project`
3. Install the required dependencies: `pip install spacy` and 'python -m spacy download en_core_web_md'
4. Run the Python script: `python watch_next.py`

Ensure that you have Python and pip installed on your system before proceeding with the installation.

Please note that the system relies on spaCy library with the Medium Language Module Scorer for word vector similarity calculations.

For more info about how to setup the project please use this [YouTube link](https://www.youtube.com/watch?v=q9wc7hUrW8U).

<a name="usage"></a>
## Usage Instructions

To use the Watch Next Recommendation System, follow these instructions:
1. Open the `watch_next.py` file in a Python editor.
2. Modify the `planet_hulk_description` variable with the description of the movie you have watched.
3. Run the script.
4. The system will analyse the provided description and recommend the most similar movie based on the description from the `movies.txt` file.

<a name="example"></a>
## Example Semantic Similarity

Let's consider an example:

Watched Movie: "Planet Hulk"
Description: "Will he save their world or destroy it? When the Hulk becomes too dangerous for the Earth, the Illuminati trick Hulk into a shuttle and launch him into space to a planet where the Hulk can live in peace. Unfortunately, Hulk lands on the planet Sakaar where he is sold into slavery and trained as a gladiator."

Based on this description, the system will recommend the next movie that is most similar to "Planet Hulk".

<a name="screen"></a>
## Screenshots

Create a function to return which movies a user would watch next if they have watched Planet Hulk with the description “Will he save
their world or destroy it? When the Hulk becomes too dangerous for the Earth, the Illuminati trick Hulk into a shuttle and launch him into space to a
planet where the Hulk can live in peace. Unfortunately, Hulk lands on the planet Sakaar where he is sold into slavery and trained as a gladiator.”

The function should take in the description as a parameter and return the title of the most similar movie.

![5](https://github.com/ghelaseG/finalCapstone/assets/96828940/0abb1763-534e-44a4-bf3a-88a8393b0b3b)

![6](https://github.com/ghelaseG/finalCapstone/assets/96828940/227aa38e-882e-4496-b9ea-e48b1043633a)


For more details on how the system works, refer to the code comments in the `watch_next.py` file.

<a name="conc"></a>
## Conclusion

The Watch Next Recommendation System revolutionises movie selection by leveraging word vector similarity in natural language processing. With an intuitive installation process, user-friendly interface, and impactful screenshots, this system delivers personalised movie recommendations based on previously watched films.

For more information on spaCy and its features, visit the [spaCy documentation](https://spacy.io/).
