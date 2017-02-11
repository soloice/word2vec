# word2vec
Fixed off-by-one error in the tensorflow word2vec tutorial.
The fix is really simple: see line 115-116.

Roughly speaking, in the original tensorflow tutorial, words in the end of a batch will be skipped. Check [issue 6860](https://github.com/tensorflow/tensorflow/issues/6860) for details.
