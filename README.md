# Korean Sound Symbolic Word List - 표준국어대사전 편찬용 의성의태어 목록

The data in this repository references the data from[<표준국어대사전 편찬용 의성의태어 목록>](https://www.korean.go.kr/front/etcData/etcDataView.do?mn_id=208&etc_seq=17&pageIndex=1) as a resource.

We created a list of words ranging from 1 to 4 characters, classified by morphological templates, excluding unnecessary words in [text_processing.ipynb](text_processing.ipynb).

The data is as follows:
- [data/raw_text.txt](data/raw_text.txt): A raw text fetched from National Institute of Korean Language.
- [data/words.txt](data/words.txt): All words included in list.
- [data/pruned_words_by_template.json](data/pruned_words_by_template.json): Pruned words list (ranging from 1 to 4 characters) obtained by excluding verbs and adverbs, classified by morphological templates.
