# Writing a file

Once again we are going to be using a google colab notebook to work on file IO (input, output).

To review what we covered in the last lecture:
1. We now know the syntax to open a file
2. Since files are iterables, we can go through files using a for loop
3. We can also read files line by line using the methon `.readline()`
4. We must close the file after we are done using it

### Onto writing files!

The link to the notebook that is going to be used for this lecture is [here](https://colab.research.google.com/drive/1XNbXwX8Waq-TWuUoW7MB7YI-Jbit2k3l)

Lets imagine that we have a matrix:
```python
matrix = [[1,2,3],
          [4,5,6],
          [7,8,9]]
```
 and we want to write it to a file called `'matrix.txt'`.

 We are going to need to open the file, save the data and then close the file.  Once we have done this, we can reopen the file and see the contents.
