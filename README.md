# Project 5 - Word Scramble

Days 27-29 of 100 Days Of Swift

https://www.hackingwithswift.com/100

## Topics

Day 27: Capture lists, reading from disk: contentsOfFile, and UIAlertController.

Day 28: UITextChecker, inserting table view rows with animation, indexPath, and lowercased().

## Challenges

Day 29:

1. Disallow answers that are shorter than three letters or are just our start word. For the three-letter check, the easiest thing to do is put a check into isReal() that returns false if the word length is under three letters. For the second part, just compare the start word against their input word and return false if they are the same.
2. Refactor all the else statements we just added so that they call a new method called showErrorMessage(). This should accept an error message and a title, and do all the UIAlertController work from there.
3. Add a left bar button item that calls startGame(), so users can restart with a new word whenever they want to.

Bonus: Once you’ve done those three, there’s a really subtle bug in our game and I’d like you to try finding and fixing it.

To trigger the bug, look for a three-letter word in your starting word, and enter it with an uppercase letter. Once it appears in the table, try entering it again all lowercase – you’ll see it gets entered.

## Screenshots

<img src="https://github.com/vogtmano/Project-5/assets/92689831/2f289014-4e56-49c0-a94f-1d49ec94140b" width=300 height=520>

<img src="https://github.com/vogtmano/Project-5/assets/92689831/67e26213-1ab0-425c-b4bc-ea2e243e06b9" width=300 height=520>

<img src="https://github.com/vogtmano/Project-5/assets/92689831/33f6acc0-65a8-486b-8841-746d2c840613" width=300 height=520>

<img src="https://github.com/vogtmano/Project-5/assets/92689831/16b64905-53c3-4985-bc05-1d3203e869db" width=300 height=520>

<img src="https://github.com/vogtmano/Project-5/assets/92689831/1d54c887-81e9-4b23-a92c-af58751c5743" width=300 height=520>

<img src="https://github.com/vogtmano/Project-5/assets/92689831/93dda4ff-3f0b-4726-bdc6-f71646373e58" width=300 height=520>
