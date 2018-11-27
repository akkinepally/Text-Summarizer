# Text-Summarizer

<h3>Steps:<br>
step 1:Fetch the article from web.</br>
step 2:Parse the data using lxml to remove all the html tags. </br>
step 3:Tokenize the paragraph to sentences.</br>
step 4:Preprocess the sentences.</br>
step 5:Create a histogram to get the count of each word. </br>
step 6:Create a weighted histogram by dividing each one of them with the max count, then we would get weight corresponding to each word.</br>
step 7:Now we have to calculate the weighted sum of all the sentences taking the weights of all the words in a particular sentence by adding the weights of the words.</br>
step 8:Choose the sentences with the highest score and that will give u the summary of the complete wikipedia document. </br><h3>
