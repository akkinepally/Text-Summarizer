# Text-Summarizer

Steps:
step 1:fetch the article from web.
step 2:parse the data using lxml to remove all the html tags. 
step 3:Tokenize the paragraph to sentences.
step 4:Preprocess the sentences
step 5:Create a histogram to get the count of each word
step6: create a weighted histogram by dividing each one of them with the max count, then we would get weight corresponding to each word.
step7:Now we have to calculate the weighted sum of all the sentences taking the weights of all the words in a particular sentence by adding the weights of the words.
step 8:Choose the sentences with the highest score and that will give u the summary of the complete wikipedia document
