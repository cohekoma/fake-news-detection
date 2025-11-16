# Fake News Detection (FND)
Digital era has given us lots of great things but also many terrible things and fake news is one of those terrible things. While researching for an idea to build a side project, I stumbled upon the idea of working on a project that helps detect fake news using Python and Machine Learning and so that's how this project was borned.

## Project Overview
Initiallly, FND aims to provide an API that interacts with a self-trained model to detect and classify whether a news article is: fake, uncertain (potentially fake/potentially real), real. Beside news detection and classification, FND will provide details on why this news article is fake (or real) based on certain points and give suggestion on whether users should trust this news or not.

## Development
- Pull the source.
- `cd src`.
- Use `venv` with `python3 -m venv venv`.
- Install deps with `pip3 install`.
- Activate with `source venv/bin/activate` (if you're on MacOS, for Win then `venv/Scripts/activate`).

## Credit
The idea of the project is not new. I just reuse the idea and add my own takes on to the idea so here's the list of resources that I have been using to build the project (the list will still be updated until there's no more):
- [Development of Fake News Model Using Machine
Learning through Natural Language Processing by Sajjad Ahmed, Knut Hinkelmann, Flavio Corradini](https://arxiv.org/pdf/2201.07489).
- [Detecting Fake News with Python and Machine Learning
 by DataFlair](https://data-flair.training/blogs/advanced-python-project-detecting-fake-news/).