# Text Generation with Project Gutenberg

## Source
My dataset is based on book from Gutenberg library. Link to book: `https://www.gutenberg.org/ebooks/16653`. It book about title "Mythos of Babilonia and Assyria". Dataset created by transform characters array to boolean array. Characters array comes from text. Bolean array is suitable to use with neural network. Data divided by X dataset and Y dataset. X is current character and Y following character.

### Creating dataset


## Neural Network
After search process I found out that recurrent neural network is suitable to generate text. Recurrent neural network rely on processing on while data from previous epochs. It is available by ability to store previous inputs data.

