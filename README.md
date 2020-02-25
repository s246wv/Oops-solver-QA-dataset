# Oops-solver-QA-dataset  
**介護の困りごとデータセット**  
[日本語の説明](#困りごとデータセットとは)は下にあります．  

## What is a Oops-Solver-QA-dataset  
We extracted title information from a dataset "福祉用具ヒヤリ・ハット情報", which is provided by The Association for Technical Aids, as Oops situation. "利用者の足がフットサポートから落ちてしまい，車いすに巻き込みそうになる" (English translation: A wheelchair was about to catch foot of an elderly person when his/her foot falled from foot-support of the wheelchair.) is an example of Oops situation.
We also generated triple of natural language question, corresponding computer-interpretable query to the question and the result extracted from "Example of structured manuals for elderly care," which is a procdedural knowledge base about elderly care and the detailed information is mentioned below.
This data-set Oops Solver QA dataset contains <u>Oops situation</u>, <u>natural language question</u>, <u>computer interpretable query</u>, and <u>extracted information from "Example of structured manuals for elderly care"</u>.  

## Example of structured manuals for elderly care
A structured manual is a kind of procedural manual which represents a goal and required actions to realize the goal by rectangle nodes and links among them.   
Following figure shows a legend of its graphical representation.  
<img src="https://raw.githubusercontent.com/satoshinishimura2460/Example_of_structured_manuals_for_elderly_care/master/img_readme/structure_of_actions_en.png" width="750">  
You can find the detailed information [here](https://github.com/satoshinishimura2460/Example_of_structured_manuals_for_elderly_care).
  
## Use-case scenario of the dataset
### **Evaluation of structured manuals**
<img src=".\fig\Querying_en.svg" width="750">

### **Creation procedure of the dataset**
<img src=".\fig\CreationProcedure_en.svg" width="750">

## References  
The Association for Technical Aids: 福祉用具ヒヤリ・ハット情報, http://www.techno-aids.or.jp/hiyari/  

## Citation
Please cite "Oops-solver-QA-dataset (URL)" if you utilize this dataset under the [licence](.\LICENSE.MD).
We will add publication information about this dataset here.
Nishimura, S., Oshiyama, C., Oota, Y.: Towards “Oops! solver” for elderly care: structured manuals and its evaluation, International Conference on Nursing Informatics (2020). (Submission)  

## Update plan
* Update of the contents
  * We will update the contents which contains errors.
  * We will add other 5-tuples to the dataset.
  
  
## 困りごとデータセットとは  
介護分野での困りごととして，テクノエイド協会の公開する福祉用具ヒヤリ・ハット情報からタイトル情報を抜き出した．  
その困りごとに対して，介護の構造化マニュアルの例というデータセットから情報を抽出することで解決可能なものに関して，自然言語の質問文とSPARQL言語によるクエリ文を生成した．  
本データセットは，<u>困りごと</u>，<u>困りごとを示すURL</u>，<u>質問文</u>，<u>クエリ文</u>，および<u>そのクエリにより抽出された結果情報</u>である．  
  
## 介護の構造化マニュアルの例  
  
このマニュアルは，達成したい目的に向けて必要な行為とその関係を整理し，線や四角などの図形を用いて表現した業務手順書である．  
以下に例を示す．  
<img src="https://raw.githubusercontent.com/satoshinishimura2460/Example_of_structured_manuals_for_elderly_care/master/img_readme/eat_something.png" width="750" >  
詳細は[こちら](https://github.com/satoshinishimura2460/Example_of_structured_manuals_for_elderly_care)を参照のこと．  
  
## データセット利用イメージ  
### **介護の構造化マニュアルの例の評価**  
<img src=".\fig\Querying_ja.svg" width="750">  

  
### **データセットの作成過程**  
<img src=".\fig\CreationProcedure_ja.svg" width="750">  
  
## 参考文献  
公益財団法人テクノエイド協会: 福祉用具ヒヤリ・ハット情報, http://www.techno-aids.or.jp/hiyari/  
  
## 引用の仕方  
本データセットを引用する場合は，「介護の困りごとデータセット（https://github.com/satoshinishimura2460/Oops-solver-QA-dataset/）」であることを明記してください．  
*関連する発表が採択された場合には，その文献情報を追記します．  
Nishimura, S., Oshiyama, C., Oota, Y.: Towards “Oops! solver” for elderly care: structured manuals and its evaluation, International Conference on Nursing Informatics (2020). (Submission)  
  
  
## 今後の更新予定  
* 内容の更新  
	* 必要に応じて不備のある内容を更新する．  
	* 困りごとと質問文の組を追加する．  
  
	  
