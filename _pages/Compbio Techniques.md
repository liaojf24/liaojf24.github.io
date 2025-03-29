# Some interesting technical problems
## Data Leaky problem or Sequence duplicate
In bioinformatics, we often need to remove duplicates and similar sequences in bioinformatics, when we map FASTQ reads onto whole genome. The same here is that the data used in Deep learning also very important. One problem I previously encountered was that I didn't remove similar sequences in the training dataset although I did this in the validation dataset. The negative result was that the model tended to memory the features of those most abundant fragments, and could not learn the diverse data distribution, resulting in a very low generalization and performance. This problem is called Data leaky. And I think there are some possibilities.
-
