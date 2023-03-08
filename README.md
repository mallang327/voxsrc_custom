# voxsrc_custom
Speaker Verification Task

제공된 100명의 음성 파일을 학습, 전혀 다른 화자의 음성(test data)이 주어졌을 때 target과 동일 화자인지 구별할 수 있도록 모델을 학습한다.

[1] Voxceleb1 발췌

[(링크 변경!) 제공 데이터셋 (100명) / 2.42GB / 12,290 audio files](https://drive.google.com/file/d/1QGZKLTM_ajwVh9ZLi_5dSt8IQTGEoNjT/view?usp=sharing)

[링크 변경 preprocess label (txt file) 2.9MB](https://drive.google.com/file/d/1jw_XZdtqIAcPvM5gFVoOuHlSzWL8-c4a/view?usp=sharing)

[2] Voxceleb2 발췌

[(링크 변경!) 제공 데이터셋 (50명) / 3.76GB / 32,040 audio files](https://drive.google.com/file/d/1p9Cyq38is-ymqSEeFJF1VgREa81rpsAJ/view?usp=sharing)

[링크 변경 preprocess label (txt file) 3.8MB](https://drive.google.com/file/d/1RgYrPYnd6Uv9DuGw4YKdArpe41xRBg7w/view?usp=sharing)

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
