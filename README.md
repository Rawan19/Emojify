# Emojify!
This project is a part of Coursera's course: Sequence Models.

(I have already included in the coursera_sequence_models repo, but I loved this project so much that I wanted to include it in a seperate repo)

In this assignment, I used word vector representations to build two versions of an Emojifier:

   1 - A baseline model (Emojifier-V1) using word embeddings.
   
   2 - A more sophisticated model (Emojifier-V2) that further incorporates an LSTM.
   
   The model which inputs a sentence (such as "Let's go see the baseball game tonight!") and finds the most appropriate emoji to be used with this sentence (⚾️).

## Have you ever wanted to make your text messages more expressive? Your emojifier app will help you do that. 
So rather than writing:

  "Congratulations on the promotion! Let's get coffee and talk. Love you! "

The emojifier can automatically turn this into:

   "Congratulations on the promotion! 👍 Let's get coffee and talk. ☕️ Love you! ❤️"

 
## Using word vectors to improve emoji lookups

   In many emoji interfaces, you need to remember that ❤️ is the "heart" symbol rather than the "love" symbol.
    
   In other words, you'll have to remember to type "heart" to find the desired emoji, and typing "love" won't bring up that symbol.
      
   We can make a more flexible emoji interface by using word vectors!
    
   When using word vectors, you'll see that even if your training set explicitly relates only a few words to a particular emoji, your algorithm will be able to generalize and associate additional words in the test set to the same emoji.
    
   This works even if those additional words don't even appear in the training set.
        
   This allows you to build an accurate classifier mapping from sentences to emojis, even using a small training set.


