# NLU Assignment 2 

Divide the Gutenberg corpus into train, dev, and test. Let the training split be D2-Train. Implement and build the best LM in the following setting and evaluate.

## Task 1

Build the best token level LSTM-based language model for the setting above.


## Task 2

Build the best character level LSTM-based language model for the setting above.

```
Give examples
```

### Token Level LSTM
The code files are as follows:

(A) generate_sentece_word.py : used to generate sentences for Token level model

(B) word_tf_lstm.py          : preprocessing for the token level model

(C) word_lstm_model.py       : defines token level model created using tensorflow

```
my praetors practice.sir simply practise themonstrous advantage.you adownright aery-light me.susan me.sir
that spanned affected thoughtfulness obominable agony serapis
```

### Character Level LSTM
The code files are as follows:

(A) generate_sentece_char.py : used to generate sentences for character level model

(B) char_tf_lstm.py          : preprocessing for the character level model

(C) char_lstm_model.py       : defines character level model created using tensorflow

```
the all mrs musgroves be the sun, i shall be made no signs,i may see what best does

then he always said that i loved him to see by the first man of proper

the fortyyears old god of israel lived into a zidian11 now the princes of the rivers shall be so that one of all the words of my people. @111 and the great continually down by the house of the lord unto the assessions of the border with the waters may not see him and they shall be as a burnt offerings they shall they be set on the south of zeban, and the children of israel 1112 and the lord said, i may do in a strangerand he made him in the land of judah, and jerusalem with me with the son of shepherds, and god in my words.
```

The model used for generating sentences is the character level LSTM model
