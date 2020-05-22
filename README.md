# News Summarizator
The final project for Stepic course Huawei Natural Language Processing.

## Project previous description
a) What is the problem you are trying to solve? Why it is important?

At first our team have two ideas for course project for the same dataset.
The prior task is trying to generate news header by it text, where original header can be used as target and original text used as train data.
Success solution can be used for "shortization" long texts whithout loosing general line of story. For example application that make analogue of Cloud_Of_Words, where words selected not by its frequency's, but by importances aka weights in final sequence. It looks much more relevant, and do not require stop_words vocabulary.
Meanwhile its a complex task, and we have B-plan: classificate news texts, where original news section can be used as target and original text used as train data. For a newbies it looks much more easy.

b) What are the existing solutions for this problem? If the problem is new, describe the solutions of the most relevant problems to yours.

At the fist is solution by Gavrilov, D., Kalaidin, P., Malykh, V.: Self-Attentive Model for Headline Generation.
The second is VKcom competition 2019 "Headline generation track". We expect to find some good baseline ideas here.
And the final is Ilya Gusev model https://github.com/IlyaGusev/summarus

c) What is the data you will be working with? Is it an already released dataset? If so, please provide a description and a link to it. If it is a new one, please describe your methodology to collect the dataset.

We would use self collected dataset of texts from website of Rossiyskaya Gazeta or/and from sport newsportal Championat.
Licens agreements permits collecting, copying and saving data from this sites for personal non-commersial uses by Russian citizens.
Metodology to collect the dataset is self-designed parser through C# and AngleSharp library. Raw HTML -> JSON dataset.

d) What is your team? If there is more than one person, please provide provision responsibilities for all people.

Kotyukov Alexander (github @kotyukov): design parser, dataset collecting, summarization model
German Abramov (github @germanjke): dataset cleaning, summarization model

e) How are you going to solve the described problem? What are the differences from the baselines you are comparing with. Please do include a link to a repository where you are going to keep solution's code and data in case you are collecting  the dataset.

Methodological ideas have not been chosen yet.