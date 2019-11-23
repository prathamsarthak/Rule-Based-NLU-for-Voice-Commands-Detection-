# Rule-Based-NLU-for-Voice-Commands-Detection
This is a rule-based approach for Natural Language Understanding (NLU) for Voice command detection for Voice Assistants.

This is an approach for the solution of problem statement given by Samsung R&D Institute Bangalore during Hackfest 2018 at IIT(ISM) Dhanbad.

In this problem, various concepts and grammar files were given and rules for each command were given and we had to come up with an approach to detect the commands from the input sentence given by the user. For a more detailed explanation of the problem statement, refer to Samsung Problem statement1.doc and Samsung Problem statement1.doc files.

Our Approach - 
We used a binary string matching approach to detect the commands. We preprocessed all the grammar files of the various commands by making binary strings for each grammar of the commands given. We made binary strings based on which concept/placeholder is present there in the grammar of that specific command. Then, we made a binary string for the input command and matched with all the binary strings for all the commands and select that command which has the most match. Exact match is not required as we are following a probabilistic approach and trying to find that command which has the most match.

One of the problems was there with the open phrases which were somewhat solved bt was not working efficiently. Kindly refer to Samsung Problem statement2.doc for a detailed explanation of the open phrases.
