##  How to prepare data for training model :
```
--data.
---coin_banknote.
-------Annotations: all .xml files.
-------Images: all .jpg files.
-------ImageSets: .txt file, includes: train.txt, test.txt, val.txt (Use train_test_val.py).
```
train.txt, test.txt, val.txt include file name without extension
`coin5_reverse_041`

** Use `train_test_val.py` to create train.txt, test.txt, val.txt for training model