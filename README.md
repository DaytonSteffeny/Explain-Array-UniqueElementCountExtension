# Challenge Explain Array Unique Element Count Extension

## Project Overview:
Sorting Arrays and Comparing the Elements- We first needed to sort these element in the array is very important when doing this challenge in order to become very efficient. After the arrays are sorted into different elements, we then compare them to make sure the values are in the same orientation as the current element, we then would compare and make sure the number the current element was unique. I was not able to successfully complete this challenge, but after looking over the documentation that Professor Musser provided for us the solution was more clear.

## Sorting Arrays
The sorting of the arrays is done by using the ***let sorted =self.sorted(by: <)***. The function will sort the values from least to greatest and works with Ints and Strings.

## Comparing the Elements
The comparing the elements array ways done with using different types of methods as a tuple. You could use a struct as well, but using a tuple will enable you to store both of the elements from before and create a current value. The function ***let result = sorted.reduce(start)*** is the tuple start. The reduce in this function reuturns the current element and the sorted is called from above function. The first comparison function will compare the first element with the nil. The start is to ***(.none, 0)*** and it will start with the element that is assigned to ***nil*** . The two called functions involving ***previousResult*** and ***currentElement*** is to store the variables as we are comparing them in the code. The line ***var uniqueCount = previousResult.1*** is setting every previous element in the array to the assigned count variable. We use a ***uniqueCount += 1*** to go up by one in the counting and then we return the ***currentElement*** and the ***uniqueCount***, then returning result the the end.
