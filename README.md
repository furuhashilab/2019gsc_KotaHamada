# 2019gsc_KotaHamada
浜田皐太2019年度ゼミ論用レポジトリ
ゼミ卒論https://docs.google.com/document/d/1NWQJAQSmqOeuI7MpwGGbHMJxqg6zwUwLxdr8Q3jZ-O8/edit



クロントイ・スラム地域の空間情報共有

# 概要
東南アジア最大級のクロントイ・スラムに現地調査まで行き研究した内容について説明する。研究課　題は以下の二点。
　・日本では馴染みのないスラムを調査することにより、スラムの実態を知りそこに住む人々の生活を知る。
　・現地調査で見えてきたタイ社会の課題を把握しクロントイ・スラムの人々の生活の質
     （Quality Of Life、以下QOL）をあげる施策を探求する。
　彼らの取り巻く限られた環境下でいかにQOLを向上させるかが重要になってくる。そのために重要となってくるのは空間情報の共有である。スラムの人々に現地支援財団や薬局、学校、商店などの位置をスラムの地図とともにすべての情報を一つの地図で共有できればいざ緊急のことがあった場合どこにいくべきかわかるので対応速度が早まる。
　今回のクロントイ・スラム地図アプリ作成目的はクロントイ・スラムに住む人々がより便利な生活を送れるようにクロントイ・スラム周辺の支援団体や病院などの施設を一目で見れるようにしQOL向上を目指すものである。Google Map などの地図アプリは網羅性には優れているが地域特化型となると不十分な部分があり今回作成する地図アプリでその不完全さを解消できることを目指している。


## Introduction:
タイへ留学をしていた際、以前から勉強していたスラムのことをさらに学ぶため現地調査をすることになった。東南アジア最大級のスラム、クロントイ・スラムの現地調査へ行くため現地で支援活動を行なっているシーカアジア財団に協力をしてもらいクロントイ・スラムへ足を運ぶことになった。
現地調査ではスラムの人々のリアルな生活を学ぶことができたと同時に面白い発見があった。彼らは貧困層にも関わらずほとんどの人がスマートフォンを所持しており現代の情報社会の流れにうまく乗っていた。もちろんiPhoneではなくHUAWEIやOPPOなどの比較的低価格なものではあったが常に情報は受け取れる環境であった。
スラム全体の状況としては小さい住宅が入り組んでおり人が一人通れる通路以外は壁に囲まれており、現地の人でないと確実に迷ってしまうものであった。彼らが急病になり救急隊をよんだ際、救急隊は急病人のところへ正確にたどり着くことができるのか甚だ疑問であった。そのでスラムの人々のスマホ社会を生かし地図アプリを作成してみたいを考えた。具体的には緊急時や急病時に地図アプリで自分の場所をGPSで知らせ救急隊がスムーズに急病者の元へたどりつけるというものである。加えてスラム内の学校や商店そしてスラム支援財団の場所も一目でわかるようにしスラムの人々がより便利な生活を送ることができるような地図アプリにしていく。
## Methods:
Glideというアプリ作成ソフトウェアを使用しクロントイ・スラムの支援財団や周辺のコンビニ、病院などを全て一目で見ることができるアプリを作成した。



## Results:
Google map等の地図アプリは網羅性には優れているが地域特化型となると不十分な部分があり、優れているとは言えなかった。クロントイ・スラムに特化した地図アプリがなかったため取り組んでみたところ、彼らに必要な情報だけを掲載できるため利便性が高いという結果を得られることができた。
## Discussion:
今回作成したアプリは作成者の私だけでなく全ての人が編集可能にしているためクロントイ・スラムと人々が追加したい情報や内容をスマートフォンで簡単に操作することができるので今後の汎用性も優れていると感じた。

## Conclusion:
地図を作成する上で建物の住所を打ち込んだ際、Mapbox上の地図には正しく住所が反映されずタイ国外のピンが立てられるのがほとんどであった。このようなことは他のユーザーでも起こっておりGlideの問題かMapboxの問題かは判断できかねるが今度実際に実証した際大きな課題点であると考えている。
## Reference/参考文献:
卒業論文本文中に記載。

## Acknowledgements/謝辞:
本研究を進めるにあたりシーカアジア財団、青山学院大学古橋大地教授をはじめ多くの方々より多大な助言を賜りました。厚く感謝を申し上げます。



# はじめに

現在タイの経済成長は凄まじい。2018年の経済成長率は4.1％にもなり東南アジアの中で世界に注目されている国の一つである（外務省　2019）。バンコク中心街へ行けば高層ビルの建設ラッシュで都市鉄道のBTSやMRTも駅数を増やし利便性を高めている。しかしながら経済成長と同時に貧富の差も大きくなっている。富裕層上位1%の資産が、国全体の資産に占める割合が2018年には66.9%で世界一位となってしまった（CREDIT SUISSE 2018）。経済成長のおかげで富裕層の割合が増えインフラも税収によって都市部は整理されたがその分、貧困層は増え低賃金労働を余儀なくされまともな住居空間が確保できずスラムも拡大しているのである。タイの平均時給も業種によって異なるがアルバイトで言えば平均時給が男性は100バーツ（日本円で約350円）、女性は87バーツ（日本円で約304円）であった（JETRO 2018）。まともな教育を受けていない人々はこのような仕事につき低所得で働くのであるが、この時給では到底子供を大学へ通わせることができず、その子供もまともな職につけず負のループになっていく。低所得家庭の子供は安定した家庭に比べ大学進学の機会が１９倍も低下するとも言われているように高度な教育には資金が必要不可欠なのは明白である。低賃金労働の中では住居空間の確保が難しくスラムに定住する人が後を絶たない。バンコクにスラムは2000箇所以上もあり人口は約210万人である（シーカアジア財団　2019）。これはバンコクの人口のおおよそ4分の１にもなる。

# クロントイ・スラムとは
  
## ・クロントイスラムのこれまで 
  
　クロントイ・スラムは約80,000人が住む、バンコク最大のスラムである。バンコクの玄関港であったクロントイ港へ仕事を求めて多くの人々が集まり、スラムを形成し、最初は数十世帯であったのが徐々に増えていき、1991年には世帯数が6,000以上に及んだ。 クロント・イスラムのある場所は元々河口洲の湿地帯で、塩分を多く含んだ土地は農作物を育てることも出来ず、人は殆ど住んでいなかった。そこに地方からやってきた人々は廃材を使って家を建て、下水道設備も整備された道路もなく、家々から出た汚水の上に渡した板の上を子どもたちが走り回っていた。そして雨期になって降水量が増えると床下の汚水は家の中まで浸水するといった状況で、衛生状態はひどいものだった。また次第に増えて行った家々は密接して建てられ、子どもたちが遊べるような広場も無ければ学校もなく、さらには私有地や政府機関の土地に不法占領しているため、何度も立ち退きを要求され、一つ所に落ち着くことは決して出来なかった。そして、そういった生活環境面だけではなく、スラムの人々は一般の人々が受けられる公共サービスを全く受けられない状態にもあった。例えば、出生証明書が無いために十分に教育をうけられず、適当な職業に就くことも不可能だった。 これら様々な問題は複雑に絡み合い、悪循環の繰り返しによりますます深刻なものとなって行く。そして住民達は日々単純労働に従事する以外には他の世界のことを知る由もなく、世間の人々もクロントイスラムに関心を寄せることはない。 
  
## ・現在のクロントイスラム 

　住民達が結束し、政府にも直接意見を言えるようになったことで、様々な改善がされてくる。家々の間の路地はコンクリートで埋められ、水道や電気など のライフラインも整備された。しかし、現在でもスラムが抱える問題は山積みだ。生活環境面では電気や上水道などの公共設備が整ってきたものの（およそ電気70% ・上水道90％）、湿地の上に家を建てている地域では下水設備は整っておらず、下水をそのまま床下に流すなどしている。そうした家はクロントイスラムの中におよそ40％ある。また立ち退き問題も解消されていない。一時は港湾局と住民側との中期的な土地共有がなされたが、その期限も切れ、現在は いつ立ち退きを強要させるか分からない状態だ。これでは住民は決して安心して暮らすことは出来ない。  （Duang Prateep Foundation, 2018)


# クロント・イスラム現地調査で見えてきたもの

## ・調査内容
　東南アジア最大級のクロントイ・スラムに現地調査まで行き研究した内容について説明する。研究課　題は以下の二点。
　・日本では馴染みのないスラムを調査することにより、スラムの実態を知りそこに住む人々の生活を知る。
　・現地調査で見えてきたタイ社会の課題を把握しクロントイ・スラムの人々の生活の質
     （Quality Of Life、以下QOL）をあげる施策を探求する。
　日本にはスラムというものがなくネットや授業で間接的に学ぶことしたできなかったので
スラムへ行き彼らの生活や仕事を直接見てみたいという好奇心がこの調査の最初であった。現地調査で現地財団やスラムの人々と接した中でタイ社会の課題が浮き彫りになりこの状況を良くするにはどうしたら良いのかというのが２つ目の研究内容の大きな動機である。読者に誤解がないようあらかじめ説明しておくが私は決してクロントイ・スラムをなくしスラムの人々をスラムから脱却させるなどとは考えてはいない。そのような考えは不可能でありただの理想論に過ぎないと考えているためだ。理由としては以下通り。
まず1人の大学生が考えついた案でスラムがなくなったらすでにスラムはなくなっているはずである。そして一時的にスラムをなくしてもまた別のところに再形成されるだけである。更に言えばそのような大掛かりな話は１個人でできる話ではない。そもそのタイ政府は富裕層しか見ていないくスラムの人々に対して動いていないため、タイ政府をあてにできないところがある。
　このような背景があるため私の調査内容の目標はスラムの人々がより快適な生活をするために彼らのQOLをあげるところにある。

## ・クロントイ・スラム現地調査

まずはじめにクロントイ・スラムへ調査へ行くために現地で支援活動を行なっているシーカアジア財団とコンタクトをとりクロントイ・スラム全体の説明と現地ツアーを組んでもらった。クロントイ・スラムはバンコクの中心地スクンビットから徒歩圏内のところにある。スラムから見えるスクンビット地区の高層ビルが貧富の格差を物語っていた。彼らの主な職は港での仕事、タクシー運転手、建設業などである。建設業などの人々がやりたくないきつい仕事がスラムの人々に回ってくるのである。スラムは人手が多く低賃金で雇えるため重宝されたのだ。つまり、近年のタイの経済成長はやりたくもない仕事を低賃金ながら必死でやってきたスラムの人々の貢献でもあるのは紛れも無い事実である。
実際にクロントイ・スラムに入ってみた。入って早々スラムの人々のごみ収集所がありかなりの匂いがあった。乾季だったからまだ良かったものの雨季になるとさらにその匂いは増すようだ。あたりを流れている小川もかなり水質状態が悪く匂いもあった。スラムの人々の住居空間は屋根が錆びついたトタン板で、玄関というものはなく外から家の中が丸見えという状態であった。中を少し覗かしてもらうと大きな液晶テレビがある家が多く立派な冷蔵庫も設置されていた。確かに家自体も狭く家同士の間隔も狭いため密集的なコミュニティでいかにもスラムという感じではあったが、家の中は綺麗に保たれており住居環境は整っているような印象を抱いた。現地調査の前までは貧困層の人々は衛生状態悪い環境下で生活していると思っていたが実際に見ると住居空間は小さいものの一般の人々となんら変わらない生活をしているように見えた。スラム内にタイの街中と同様、屋台や商店がありスラムの子供達のために学校まである。スラムが一つのコミュニティとして完結しており自分が考えていた危険なイメージは全くと言っていいほど見受けられなかった。スラム内を回っている際、当然たくさんのスラムの人々と顔をあわせることになる。どこからきたかもわからない他所者に対して彼らは嫌悪感を示すと思っていたが、彼らは我々に対して笑顔で接してくれたのである。もっと嫌な反応をされると思っていたので意外であった。

## ・浮き彫りになったタイ社会の課題

　一度素朴な疑問に戻って見ると、なぜスラムが依然としてなくならないのかというところに至る。スラムの人々は国有地に違法占拠しているため住んでいるのは自分たちの土地ではない。つまり国がいつ彼らに立ち退きを強要するかわからないのである。実際に2020年にスラム地域の再開発の工事が予定されているのである。では立ち退きがされたらスラムの人々はどうなってしまうのであろうか。国は基本的に三つ、支援の選択肢を示している。一つ目は郊外にあるコンドミニアムの提供。二つ目は田舎の土地で家を建てる。三つ目は政府からお金をもらい自分たちでなんとかする。しかしこれには大きな問題点がある。この条件に当てはまるのは住民票がある人々のみであるという点だ。多くのスラムの人々は住民票を持っているが持っていない人々も決して少なくない。住民票を持っていない人々は途方に暮れることになる。さらに重要な点は、郊外の生活ということでスラムの人々は今の仕事を捨てなければいけないのである。都心部だからこそ港での建設業の仕事や、タクシー運転手などの職で生活できるにも関わらず、移住した場合の郊外では職の保証はないのだ。このような問題ではスラムに人々も今の暮らしを捨てて移住しようという話にはもちろんならなく、依然としてスラムが拡大し続けているのである。
 
## ・クロントイ・スラムの人々のQOL向上のために

  彼らの取り巻く限られた環境下でいかにQOLを向上させるかが重要になってくる。そのために重要となってくるのは空間情報の共有である。スラムの人々に現地支援財団や薬局、学校、商店などの位置をスラムの地図とともにすべての情報を一つの地図で共有できればいざ緊急のことがあった場合どこにいくべきかわかるので対応速度が早まる。この地図を作ることで現地の人はもちろん、外部の支援団体がクロントイ・スラムに入った際も大いに役立つに違いない。例えばスラムの入り組んだ環境で一人のスラムの人が急病で倒れた際、自分の位置情報をその地図アプリに知らせることで救急隊も目印がないスラムの中で早く患者の元へ向かうことが出来るのである。

# クロントイ・スラム地図アプリ作成

　今回アプリ制作において使用したソフトはGlideである。Google Spread Sheetに建物などの載せたいデータを記入しそれをGlideが勝手に最適なアプリケーションを作成してくれるのである。アプリケーション作成初心者でも容易に使用することができると考えている。
　今回のクロントイ・スラム地図アプリ作成目的はクロントイ・スラムに住む人々がより便利な生活を送れるようにクロントイ・スラム周辺の支援団体や病院などの施設を一目で見れるようにしQOL向上を目指すものである。Google Map などの地図アプリは網羅性には優れているが地域特化型となると不十分な部分があり今回作成する地図アプリでその不完全さを解消できることを目指している。


## ・作成過程

まずはじめにGoogle Spread Sheet上に建物名、カテゴリー、住所、写真、その建物のURLなどの必要な情報を記入しテイク。ここで重要になってくるのが写真である。Google Spread Sheet上に載せる際は写真をPermanent linkとしないといけない。しかしながら全ての写真をPermanent link化するのはかなり面倒な作業になってくるのでここでもGlideを使っていく。

![IRQi4BOe0zhvFmmn3Prij_gfu1ijw1TcCwgqWpljmGWLZSAwBOpr0rpMvctf1sRcTT78FE5rAXEdmNlzPxkxLmZxy8xANIkbMknTLoA0wUkD75b-UswXNj1rx4tKADvdUdRdpf25](https://user-images.githubusercontent.com/30167629/72706414-53cdef80-3ba1-11ea-886a-b04a46be78f3.png)


Componentの右上にあるプラスボタンを押しImage Pickerを追加する。そこに挿入したい写真をアップロードすることでGlideが勝手にその画像をPermanent link化してくれるため写真挿入の作業効率が飛躍的に向上する。

Google Spread Sheetに全てのデータをいれ、Glideに反映させる。

 <img src="https://user-images.githubusercontent.com/30167629/72707561-0a32d400-3ba4-11ea-954e-1fe46ce3869a.PNG" width="280" >  <img src="https://user-images.githubusercontent.com/30167629/72707623-34849180-3ba4-11ea-8f15-6c9b692cd9f0.PNG" width="280" >  <img src="https://user-images.githubusercontent.com/30167629/72707667-4c5c1580-3ba4-11ea-8678-ee4d88c8a52e.PNG" width="280" >

　このように全ての建物が表示されるのが左上の画像である。Permanent linkで挿入した画像もアイコンとして表示されクロントイ・スラム周辺の建物概要を瞬時に見ることができる。またカテゴリーごとに分けたことによって真ん中上の写真でโรงพยาบาล （Hospital）のように病院だけのタブを作ることができ全体のリストから探すことなく病院を見つける際は病院タブへいきそこから探している病院を見つけることができる。Glideにはチャット機能もあり住民同士の安否確認もできるのである。何かお互い困ったことがあるがラインなどの連絡手段を持っていなかった場合Glideのチャットはオープンスペースなので誰でも発言でき連絡を取ることができるのである。

 <img src="https://user-images.githubusercontent.com/30167629/72707904-e0c67800-3ba4-11ea-9291-ffe084492cd8.jpg" width="100" > 
 最終的に完成したらQRコードが作られるのでそれを読み取りホーム画面に追加とすればアプリケーションとしてスマートフォン上に表示できる。　
クロントイ・スラムに現地調査に行ってみてわかったことは貧困層の彼らでさえほとんどの人がスマートフォンを所持していた。つまり紙媒体や掲示板を利用するよりアプリケーションを用いるほうが彼らにとっても利便性が高く利用しやすいと推測できる。


## ・Glideを使ってみてわかったメリット

　Glideは誰でも編集することができるのでクロントイ・スラムの人々が載せたい情報を彼らの手で新たにパソコンではなくスマートフォンを使って入れることができる点である。現地に住んでいる彼らの方がもちろん土地に詳しいので便利な情報をさらに入れ、よりアプリの汎用性が高まる点は大きなメリットであると考える。さらにGlide上に情報を載せるとGoogle Spread Sheet上に勝手に反映される点も大きなメリットであると考える。全てをGoogle Spread Sheetで作るのは見えづらい部分もあり大変であるがGlideから行いそれがGoogle Spread Sheetに反映されるのはクロントイ・スラムの人々にとってもGlideのみ理解すればいいので機械に強くない人も利用しやすいのではないか。

 <img src="https://user-images.githubusercontent.com/30167629/72708020-22efb980-3ba5-11ea-8129-8d24b2d6682c.PNG" width="250" >

## ・Glideを使ってみてわかったデメリット

　GlideのなかでMapboxを使用することができ建物の住所をGoogle Spread Sheetに打ち込みMapを選択するとMapbox上に建物の位置が表示されるが、その場所が正しくない場所にピン留されていて機能はしているもののMapを利用するに値しない結果となった。クロントイ・スラム周辺の建物しか載せていないにも関わらず上図のようにピンが世界中に及んでいる。住所入力はタイ語ではなく英語を使用しているにも関わらず、まともに認識しないのである。これは他のGlideユーザーでも起こっておりGlideの問題かMapboxの問題かは不明だがGlideのMap機能を使う上で大きなデメリットであると感じた。

## ・このアプリのプロモーション方法として紹介動画を作ってみた！！
　
   このアプリを広げるプロモーションとして動画が一番分かりやすいのでいかにこのアプリが汎用性が高く使いやすいかということを紹介することにした。
   
   https://www.youtube.com/watch?v=XTOW1joAIRY&feature=emb_title
   

# まとめ

　タイには多くの日系企業が進出していることからわかるように経済的に発展しビジネスチャンスが多くある国である。しかしその一方で現地調査からもわかったようにこの経済発展の波に取り残された人々がいるのもまた現在のタイの姿である。タイ経済全体が安定し上向きになるまでは彼らの生活は変わることがないだろう。いつスラムが消え貧富の差がなくなるのかはわからない。しかしこの環境の中で彼らは生活を営み必死に生き抜いていたのである。
　今回作成したGlideによるクロントイ・スラム地図アプリはまだまだ課題点も多く情報掲載も不十分であると考える。よりMapbox上のピンが正確になって行くことはもちろん、クロントイ・スラムの人々が自身のスマートフォンで必要な建物などを入力してより汎用性の高いものにしていく必要があるとともにこのアプリ自体をプロモーションしていく方法も重要であり今後の課題だと考える。今回作成したクロントイ・スラム地図アプリで彼らの生活が少しでもよくなればと願っている。




# Reference

https://docs.google.com/spreadsheets/d/1rlS4Iu7afSExfyOPpoi_1djSAyc8Hst4zIU7dUc68Iw/edit#gid=0
