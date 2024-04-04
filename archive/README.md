# Voice Assistant Failures Dataset


This is a crowdsourced English language dataset detailing voice assistant failures that people have experienced in the wild. The dataset was then qualitatively analyzed and categorized into failure types and sources according to a taxonomy derived from [Hong et al., 2021](https://www.adamfourney.com/papers/hong_chi2021.pdf). 60 of the 199 failures in this dataset were used in the development of a survey that informed "A Mixed-Methods Approach to Understanding User Trust after Voice Assistant Failures". This dataset can be used for future survey and experimental analysis of the impact of voice assistant failures on user perceptions and behavior. More detailed analysis of the dataset and our results can be found in our paper.


## Dataset Description

This dataset consists of 199 failures sourced from 107 users during Fall 2021. Each failure outlines what the user said to the voice assistant, how the voice assistant responded, and the context for the failure, such as the user’s intention and the environment at the time. The frequency at which the failure occurs is also included. Each row of the CSV ends with demographic details about the participant as outlined below.

1. PID (integer): Participant ID
2. Failure_Type (string): The category of failure we (the research team) assigned through qualitative analysis.
3. Failure_Source (string): The source of failure we (the research team) assigned through qualitative analysis.
4. User (string): what the user has said to the voice assistant
5. Voice_Assistant (string): what the voice assistant says or does in response to the user
6. Context (string): what is happening in the environment 
when the failure occurs
7. Failure_freq (string): how often the failure type occurs (e.g. every time I use my voice assistant)
8. Survey (string): “Y” if the failure was used in our survey, blank if not
9. Age (string): age range of the participant who submitted the failure (e.g. 34-44)
10. Gender (string)
11. Native-English (string): Whether the user who submitted the failure is a native English speaker or not (Yes, No)
12. accent (string): Whether the user thinks they have an accent or not (Yes, No, Maybe)
13. adjust_speech (string): how often is speech adjusted when using a voice assistant (e.g. every time I use it)
14. repeat-speech (string): how often speech is repeated when using voice assistant (e.g. every time I use it)
15. race  (string): Race of the user who submitted the failure
16. Device (string): which type of device the voice assistant is on (e.g. mobile, smart home device)
17. Device_write_in (string): option for users to supply a custom device they use their voice assistant on
18. Frequency (string): how often the voice assistant is used
