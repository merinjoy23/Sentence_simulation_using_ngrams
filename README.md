## Sentence_simulation_using_ngrams

### Introduction :

Authors : Merin Joy and Sai Nikitha

Date : October 4th 2018

The following code generates given number of sentences based on the ngram model taking text files as input.

### Instructions to run :

* Step 1: Run the following code in command line.
* Step 2: Give the file name, n, m, text files as ngram.py 3 10 AnnaKarenina1.txt AnnaKarenina2.txt CrimeandPunishment.txt.
* Step 3: The program will then generate sentences using the ngrams, no.of sentences provided.

### Sample Output

(base) C:\Users\Merin\Desktop\AIT690>python Merin.py 3 10 AnnaKarenina1.txt AnnaKarenina2.txt CrimeandPunishment.txt

Sentence 1:
>he almost smiled at himself inhis anger ....

Sentence 2:
>strange to him that there are no barriers and it’ s prison again.marfa petrovna had not uttered a sudden he stood againstthe wall, ticking away hurriedly, with a defiant and offended face.silence lasted for twominutes.

Sentence 3:
>perhaps, too, and was beingredecorated at his insinuations, hegradually began being in the corner, probably will not refuse this time ....

Sentence 4:
>of course that’ s album, and i knew your secret.

Sentence 5:
>he promised to marry her daughter, a neighbour,’ says he.

Sentence 6:
>well, i am afraid of it, because i canreason that i am very ill, the fact was very heedless ... ” “ but why did they get there.

Sentence 7:
>she looked at himdifferently ; he attached himself to be a very great deal, if you have, but i might ( with luck ) hope to get round you, ” said raskolnikov who, directly they are really provided for and praises—i hate that good nature, which excited a sarcastic smile in andreysemyonovitch lebeziatnikov, and ... and do you want the money the daybefore.

Sentence 8:
>iwill put those two stuck-updraggletails ” if they were particularly irksometo him.

Sentence 9:
>and why on the staircase, he got into the doorway, notknowing what she was a certain and definite ; a firm purpose in hismind.

Sentence 10:
>he stopped short, kindly examineme or let me know it all.

### Algorithm:

* Step1: Start
* Step2: Combining the input text files and converting them to lower case.
* Step3: Generating sentence and word tokens and adding start, end tags 
* Step4: Generating ngram sentences
    * Step4.1: Calculating frequency and probability
    * Step4.2: Predicting the next word
    * Step4.3: Display the sentences
* Step5: End
