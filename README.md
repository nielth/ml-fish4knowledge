Download dataset from source and extract the files. Too big for github
```
Dataset source (Fish4Knowledge): https://homepages.inf.ed.ac.uk/rbf/Fish4Knowledge/GROUNDTRUTH/RECOG/Archive/fishRecognition_GT.tar
https://uia.brage.unit.no/uia-xmlui/bitstream/handle/11250/2991805/Article.pdf?sequence=4&isAllowed=y
```
```sh
wget -O - https://homepages.inf.ed.ac.uk/rbf/Fish4Knowledge/GROUNDTRUTH/RECOG/Archive/fishRecognition_GT.tar | tar -xvf - --strip-components=1 -C ./Fish4Knowledge/fish_image fish_image
```
