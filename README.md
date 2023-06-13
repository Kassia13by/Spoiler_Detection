# Spoiler_Detection


主題是針對PTT電影版上面的影評，利用語言學特徵進行劇透偵測
為了達到更加準確的劇透偵測成效，採取sentence-level analysis
本資料夾結構如下：
```bash
 |model_feature+tf-idf.ipynb
 |model_tf-idf.ipynb
 |pre_processing.ipynb
 |
 |─data
 |  | Chinese_stopwords.txt
 |  | features.csv
 |  | LIWC.csv
 |  | spoiler_sentence_final.csv
 | 
 |README.txt
 |Sentence Level Spoiler Detection with Linguistic Features.pdf
```
[檔案說明]

pre_processing.ipynb：前處理時使用之檔案

model_tf-idf.ipynb：baseline model所在檔案（可以直接讀入features.csv使用）

model_feature+tf-idf.ipynb：加上語言學特徵訓練之模型所在檔案（可以直接讀入features.csv使用）

data：本專案使用之資料所在資料夾

Chinese_stopwords.txt：中文停用詞字典

features.csv：包含前處理後萃取出特徵之資料

LIWC.csv：LIWC中文詞典（用於情緒分析）

spoiler_sentence_final.csv：出賣視力人工斷句後的影評跟劇透標記

Sentence Level Spoiler Detection with Linguistic Features.pdf：書面報告
