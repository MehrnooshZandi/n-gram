# n-gram
Calculating n-gram with Python. This was a college exercise.

The given exercise file contains one sentence in each line. Consider each space a separator between words.

How to get the file with Kolb:

!gdown --id 1Hb58rR--Qjwr21cLK6A29ROp6Uy5pqq8


Note 1: Don't consider extra consecutive spaces and spaces at the beginning and end of the lines in any question.

Note 2: Do not consider lines with less than three words in any question.

Question 1) Count the unigram and bigram combinations of the given file.

Note 3: Count the number of repetitions of words and pairs of words. Print the 20 most repeated ones in order of rank along with the number of repetitions and the multiplication of the rank by the number of repetitions, which is like this.

1 50936 50936 and
2 31213 62426 of

Note 4: Using the library is not allowed.

Question 2 (Write a function that for any arbitrary input number n (between 1 and 5) will extract all gram-n combinations for that input number from the training file and print it along with the number in the output.

function signature;

def compute_freq(file:str, n:int):

Sample call:

compute_freq("cleaned_train.txt",3)

Question 3) Calculate the probability of the following expressions in terms of 1 2 3 grams.

• چون تویی آید به زیبایی و شیرین ی پسر
• دل در این درد و رنج پاره کنیم 
• ای به آرام تو زمین را سنگ 
• جان را زند آ باغ صالهای تعالوا 
• شاهد و شمع و شراب و مطرب آنجا بهترست
• شب است و شمع و شراب و شیرینی

Note 5) Insert a possibility and then a sentence in each line. And first do all the math for the unigram, then print a space for the bigrams, and then print the trigrams.

Question 4) Why is it not possible to calculate the probability of the event "شب است و شمع و شراب و شیرینی" in terms of trigram? Write your proposed solution.

Question 5) Complete the following sentences using the bigram model (suggest two more likely words for each blank)

چون مشک سی ه بود مرا هر دو بنا ---

گر خورد سوگند هم آن -----

زانک نفس آشفته تر گردد از --

ازین زشت تر در جهان رنگ ----

Note 6) Four output lines are required for each sentence:

• Line 1: The incomplete sentence given in the question text

• Line 2: The list of all possible options along with the number of repetitions in descending order

• Line 3: complete sentence with the first suggested word

• Line 4: complete sentence with the suggested word two
