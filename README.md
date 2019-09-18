# Publications

This repository contains my publications.

## A Reciprocal Recommender System for Joint Event Visits 

**Master's thesis, graded 1.0/1.0**

**Abstract:** Event recommenders present users with events they find interesting. These events can become more interesting for users depending on who will join them in the visit of the event. Thus, social matching features could improve the accuracy of event recommenders. This thesis investigates whether this prospect is true.
We extended a pre-existing event recommender (“Eventguide”) with social matching features. For this purpose, we enhanced the recommender’s algorithm with three stages: first, by considering demographic information; second, by finding similar users; third, by adapting a reciprocal algorithm that computes reciprocal matches (“RECON”).
Our evaluation with 20 participants showed that they did not find social matching to be significantly beneficial. The main reason for this is that participants were not actively interested in getting to know other people. Thus, our study raised further research questions, for example, whether people who are actively interested in getting to know other people find social matching features in event recommenders interesting. If so, one should also research what the ratio of these people to the total potential user base is.

## Gesture control with the Apple Watch Series 3

**Inter-disciplinary project (IDP) report, graded 1.0/1.0**

**Abstract:** The research and development of robust systems for gesture recognition and control is expensive. Another problem is that companies often struggle to find good use cases for gesture control in their existing products. In conclusion, a cheap and yet effective way of evaluating such potential business ideas is crucial for R&D.
The purpose of this IDP report is to evaluate to which extent the Apple Watch Series 3 can be used in prototyping ideas for gesture control.
We first select a use case from the automotive industry. The goal is for a user that is driving a car to accept or deny an incoming call with gesture control.
Afterwards, we develop a working prototype. For this purpose, we implement a way to record the raw sensor data of a gesture. A set of 734 gesture recordings is then created and this set is used to train a machine learning model.
Additionally, we evaluate this prototype in an empirical case study. In this study 500 random gesture attempts are recorded and evaluated. The total False Rejection Rate (FRR) is 12.6%. The FRR without NoGesture where gestures that were not recognized do not count is 2.2%. Furthermore, we observe a learning effect. The FRR for the RightSwipe gesture improves from 63.6% to 10.0% between the first 100 attempts and the last 100 attempts.
Finally, we rate how easy the integration of our prototype into an existing app is. On a subjective rating scale we rate this a full 10 out of 10.
In conclusion, we present a gesture recognition library that is reasonably accurate and that can be easily integrated into existing apps. We suggest that the Apple Watch can be used by companies to quickly and cheaply prototype their gesture recognition and control ideas.

## Automatic Detection of Ambiguity in Requirements

**Seminar report, graded 1.0/1.0**

**Abstract:** The quality of a software system is tightly coupled to the quality of its requirements. One important criterion for high quality requirements is unambiguity.
The purpose of this report is to evaluate to which extent (attachment) ambiguity in software requirements specifications can be automatically detected by comparing the output of different dependency parsers.
We first implement a natural language processing pipeline so that a single require- ment can be processed by different dependency parsers. We start by using the NLP4J framework for linguistic pre-processing tasks, such as sentence splitting, tokeniza- tion, and part-of-speech tagging. We then select and implement three dependency parsers: NLP4J parser, MaltParser, and MSTParser. The result is that three outputs are produced from one requirement.
Afterwards we evaluate the implemented prototype in a case study using the KeePass study object. We first evaluate to which extent inconsistiencies between the three parsers occur. For this we focus on prepositions which are the cause of attachment ambiguity and we measure the Unlabeled Attachment Score. The result, i.e. the percentage of consistently parsed prepositions, ranges from 69.64% to 76.89%.
Finally we evaluate the remaining roughly 25% to 30% of recognized prepositions that are not consistent between parsers. Out of the first 25 such occurrences, 21 were due to erroneous parsing, but four were due to ambiguity.
In conclusion we find that (attachment) ambiguity can be detected by comparing the output of dependency parsers. We suggest that similarly to how spell-checking tools work, this approach can help in implementing “ambiguity-checking” tools. While a human would still have to evaluate whether ambiguities exist or not, such a tool would still be of aid for requirements writers.
