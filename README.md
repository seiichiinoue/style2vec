# Style2Vec

this script is copy from [this repo](https://github.com/jqk09a/style-sensitive-word-vectors/).


## Usage

Preparation:

```
$ g++ style2vec.cpp -o style2vec -lm -pthread -O3 -march=native -Wall -Wextra -funroll-loops -Wno-unused-result
```

To learn:

```
$ ./style2vec -train data.txt -output vec.bin
```
- `data.txt` requires being a text file and being formatted that 1 line has 1 utterance (space-separated tokens).


## References

- [Akama et al. (2018) Learning Style-sensitive Word Vector via Unsupervised-manner](https://www.jstage.jst.go.jp/article/pjsai/JSAI2018/0/JSAI2018_1N203/_article/-char/ja/)
