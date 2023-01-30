# voxsrc_custom
Speaker Verification Task

제공된 100명의 음성 파일을 학습, 전혀 다른 화자의 음성(test data)이 주어졌을 때 target과 동일 화자인지 구별할 수 있도록 모델을 학습한다.

[제공 데이터셋 (100명) 2.42GB](https://drive.google.com/file/d/1IWLUR3HxF0YO_O6PIJhm0KzcfHjElx-M/view?usp=sharing)

[preprocess label (txt file) 2.9MB](https://drive.google.com/file/d/1O4C36yIa21vjhxntyjPTP5_GEXMOA1nK/view?usp=sharing)

---
* Label txt explanation

```shell
0 id10003/na8-QEFmj44/00002.wav id10519/oUHGKXT4Aew/00026.wav
1 id10003/na8-QEFmj44/00002.wav id10003/bDxy7bnj_bc/00005.wav
# 라벨 source target으로 정렬
# source와 target이 같은 speaker면 1, 다른 speaker일 경우 0
```

Reference

http://mm.kaist.ac.kr/datasets/voxceleb/voxsrc/competition2022.html
