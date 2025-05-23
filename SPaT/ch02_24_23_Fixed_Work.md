# 枠を決めて作業

 Original:[Fixed Work](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/fixed-work)

{:style="text-align:center;"}
![ch02_24_23_Fixed_Work1](Images/ch02_24_23_Fixed_Work1.png)<br>
メカニックは、レーシングカーのエンジンを調整する時間を、レースの完走タイムの予測とは別に計算する。レースのタイムは短縮され続けるのに対して、エンジンの調整は繰り返される作業である。

...あなたは製品を提供するために完成させなければいけない作業を整理しており、​​[プロダクトオーナー](ch02_11_11_Product_Owner.md)​は、要求と​[Product Backlog](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/product-backlog)​の準備のために、チームに協力してもらう方法を探しています。

スクラムは時間を2つに分けます。分析とビジネスのための連続したタイムラインと、生産のための[Sprint](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/sprint)の周期的なタイムラインです。分析やイノベーションにかかる時間は見積もり不可能で、時として長期間かかることもあります。そのような瞬間は、スティーブ・ジョンソンが『Where Good Ideas Come From』[Joh11]で「ゆっくりとした閃き」と呼ぶプロセスの中で、前触れもなく生じるからです。

{:style="text-align:center;"}
＊　　＊　　＊

**[プロダクトオーナー](ch02_11_11_Product_Owner.md)がリリース計画のためにチームのベロシティ（[Notes on Velocity](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/notes-on-velocity)を参照）を使用する場合、すべての作業を計測対象にする必要がありますが、開発作業すべてを時間で区切ることはできません。**例えば、チームは​、[リファインメントされたプロダクトバックログ](ch03_30_64_Refined_Product_Backlog.md)​が完璧に出来上がり、どの​[プロダクトバックログアイテム](ch03_21_55_Product_Backlog_Item.md)​もReady（[Definition of Ready](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/product-backlog/definition-of-ready)​を参照）であると宣言できる瞬間に至ることはありません。​[開発チーム](ch02_14_14_Development_Team.md)​の見積もりには含まれない、定常的で定期的な作業は常にあります。

{:style="text-align:center;"}
![ch02_24_23_Fixed_Work2](Images/ch02_24_23_Fixed_Work2.png)<br>
Sprint time box: スプリントのタイムボックス<br>Planning: プランニング<br>Reviews: レビュー<br>Research: 調査<br>Development: 開発<br>Done: 完成

[Product Backlog](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/product-backlog)は、プロダクト開発作業の予算策定をするための主要なツールです。[プロダクトオーナー](ch02_11_11_Product_Owner.md)は、[プロダクトバックログアイテム](ch03_21_55_Product_Backlog_Item.md)（PBIs）を、開発の見積もりと予想される価値を考慮して、並べます。チームは​ ​[スプリントゴール](ch03_38_71_Sprint_Goal.md)を確約し、[開発チーム](ch02_14_14_Development_Team.md)は自分たちの見積もりに自信を持っています。その作業には時間がかかります。[開発チーム](ch02_14_14_Development_Team.md)のメンバーは、すべての作業を​[Production Episode](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/production-episode)​の範囲内に収める責任があります。

通常、[開発チーム](ch02_14_14_Development_Team.md)のメンバーは、自らのスキルセット、経験、担当分野に関連する開発タスクだけを予測できます。それは通常、プロダクトの構築に関連するものです。他の作業は、開発者が見積もるのが難しい、あるいは不可能なこともあります。例えば、開発の実現性、コスト、トレードオフを評価するための終わりのない調査を必要とする分析タスクがあります。分析は通常、[プロダクトオーナー](ch02_11_11_Product_Owner.md)の仕事ですが、そのような分析には、[開発チーム](ch02_14_14_Development_Team.md)からの情報や作業が必要となることがよくあります。このような調査を固定期間で試みることはできますが、そうすると調査期間の延長を繰り返す可能性があります。そして、調査からは洞察が得られますが、[Production Episode](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/production-episode)中に行われた作業から期待されるような​[定期的なプロダクトインクリメント](ch03_52_85_Regular_Product_Increment.md)​をあまり生み出さないことが多いです。これは、そのような作業を[Sprint](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/sprint)内で行うこと、および[Product Backlog](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/product-backlog)でそれを予算化することに疑問を投げかけます。それがプロダクトを生産していない場合、それは何らかの無駄かもしれません。

もし​[プロダクトオーナーチーム](ch02_12_12_Product_Owner_Team.md)​だけで調査できるならば、問題にはならないでしょう。なぜなら、[プロダクトオーナー](ch02_11_11_Product_Owner.md)は自らの時間を管理することができるからです。しかし、実際には、[プロダクトオーナー](ch02_11_11_Product_Owner.md)はビジネススキルセットが強力である一方、調査をサポートするには、作成物を実際に構築するスキルセットが弱いことがよくあります。それにもかかわらず、テクノロジーや生産に関する問題は、ビジネスリスクの主要な要素としてしばしば浮上し、そのような問題は、[プロダクトオーナー](ch02_11_11_Product_Owner.md)の権限範囲内にあります。

[Product Backlog](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/product-backlog)は、プロダクト開発という大きなカテゴリーに含まれる作業の一部しか文書化していません、ましてやチームが開発以外に費やす時間まで考慮するわけではありません。例として、​[スプリントプランニング](ch02_25_24_Sprint_Planning.md)で費やされる時間、​​[スプリントレビュー](ch02_36_35_Sprint_Review.md)​、インターバル（例えば、コーヒーを飲んだり、オフィスでのネットワーキングに費やす時間など）、​[スプリントレトロスペクティブ](ch02_37_36_Sprint_Retrospective.md)​、[リファインメントされたプロダクトバックログ](ch03_30_64_Refined_Product_Backlog.md)の維持に注力する時間などがあります。

それゆえ：

**[開発チーム](ch02_14_14_Development_Team.md)の作業を、時間を見積もるもの（つまり、プロダクトに関する作業）と、見積もることができないもの（例えば、PBIをReadyに移動する際の要件を理解する作業など）に分けます。各[Sprint](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/sprint)では、[Production Episode](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/production-episode)のタイムボックスに収まるだけの見積もりされたタスクだけを計画的に実施します。[Production Episode](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/production-episode)の枠外で、見積もりが難しい作業のための定期的なタイムボックスを設定し、タイムボックスが許す範囲でそのような作業を完了させます。**各[Sprint](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/sprint)では、​[スクラムチーム](ch02_07_7_Scrum_Team.md)​​は、見積が難しい作業（例：分析作業、ビジネス計画、レビュー活動など）を、そのために用意されたタイムボックスに収まる分だけ実施します。この見積が難しい作業を、[スプリントプランニング](ch02_25_24_Sprint_Planning.md)、[スプリントレビュー](ch02_36_35_Sprint_Review.md)、[スプリントレトロスペクティブ](ch02_37_36_Sprint_Retrospective.md)、[スクラムチーム](ch02_07_7_Scrum_Team.md)全体が[リファインメントされたプロダクトバックログ](ch03_30_64_Refined_Product_Backlog.md)を継続的に維持するためのタイムボックス、といったイベントで実施します。

{:style="text-align:center;"}
![ch02_24_23_Fixed_Work3](Images/ch02_24_23_Fixed_Work3.png)<br>
Sprint time box: スプリントのタイムボックス<br>Planning: 計画づくり<br>Reviews: レビュー<br>Research: 調査<br>Development: 開発<br>Done: 完成<br>Fixed timeboxes: 固定されたタイムボックス<br>Production episode timebox: Production Episodeのタイムボックス

チームが、一連の見積もりできないタスクの作業を現時点で完了したと感じる場合、対応するタイムボックスを無理に埋める必要はありません。例えば、チームが[スプリントプランニング](ch02_25_24_Sprint_Planning.md)をそのタイムボックスが終了する前に完了したなら、[開発チーム](ch02_14_14_Development_Team.md)はすぐに[Production Episode](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/production-episode)に移ることができます。

{:style="text-align:center;"}
＊　　＊　　＊

これで、[開発チーム](ch02_14_14_Development_Team.md)は、抜本的な革新を必要とするタスクや、さもなけば高い不確実性を伴うタスクなど、見積もりが難しいアイテムの作業を継続できます。このような作業を[Product Backlog](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/product-backlog)から取り除き、したがって[Production Episode](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/production-episode)の時間から除外することで、そうした作業を適切なペースで進めることができます。抜本的な革新やブレイクスルーを必要とするタスク、例えば[開発チーム](ch02_14_14_Development_Team.md)が[プロダクトオーナー](ch02_11_11_Product_Owner.md)をサポートするための作業などは、[Production Episode](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/production-episode)内のタイムボックスで作業をせずに、適切なペースで進行できるようになります。[リファインメントされたプロダクトバックログ](ch03_30_64_Refined_Product_Backlog.md)や[スプリントプランニング](ch02_25_24_Sprint_Planning.md)に割り当てられた時間で、このような際限のない作業を行うことにより、[Production Episode](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/production-episode)の予算への影響や、開発時間の減少を避けられます。

とはいえ、[Sprint](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/sprint)ごとの[枠を決めて作業](ch02_24_23_Fixed_Work.md)の「合計」時間、さらには[Sprint](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/sprint)内の[枠を決めて作業](ch02_24_23_Fixed_Work.md)それぞれの時間はタイムボックス化されています。例えば、チームは高性能のネットワークルーティングアルゴリズムの代替案を探求すると決定するかもしれません。そのタスク全体の工数をタイムボックスに区切ることも、その完了をスケジュールすることもできませんが、タイムボックス化したイベントとして制限することで、その作業の工数を[Sprint](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/sprint)ごとにタイムボックス化することは可能です。したがって、そのようなすべての作業はタイムボックス化した[スプリントプランニング](ch02_25_24_Sprint_Planning.md)内で行われるか、または（[Sprint](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/sprint)を越えて）進めている[Set-Based Design](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/set-based-design)​というタイムボックス化した工数に含まれる作業として行うことができます。

さらに、[プロダクトオーナー](ch02_11_11_Product_Owner.md)は、[Sprint](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/sprint)内でのPBIがプロダクトに直接貢献しない場合でも、よくまとまった（すなわち、ある程度見積もり可能な）PBIにチームが取り組むことに投資できます。[プロダクトオーナーチーム](ch02_12_12_Product_Owner_Team.md)が一部の技術的懸念（例：プロダクトのパフォーマンス分析、プロトタイプ構築）のビジネスへの影響を評価するための専門知識を持っていない場合、[プロダクトオーナー](ch02_11_11_Product_Owner.md)は、[Sprint](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/sprint)内の[Set-Based Design](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/set-based-design)の取り組みで、[開発チーム](ch02_14_14_Development_Team.md)がそうした分析作業を行うことに投資できます。このような作業は、[開発チーム](ch02_14_14_Development_Team.md)が合理的に小さい誤差範囲で見積もった作業として行うか、[プロダクトオーナー](ch02_11_11_Product_Owner.md)と[開発チーム](ch02_14_14_Development_Team.md)が予め決定されたタイムボックスで行います。例えば、[プロダクトオーナー](ch02_11_11_Product_Owner.md)がプロトタイピングツールを必要とし、それを使用してチームが何を構築するかを理解するのに役立つ[Enabling Specification](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/product-backlog/enabling-specification)​を作成できる場合、その作業を行うようにチームに指示するためにPBIを使用しても構いません。このようなツールは[Value Stream](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream)を支え、投資対効果は明らかです。

しかしながら、このような作業は、現在のプロダクトインクリメントに集中する[開発チーム](ch02_14_14_Development_Team.md)の注意を逸らすため、多くの場合ムダであることを[スクラムチーム](ch02_07_7_Scrum_Team.md)が認識するべきです。代わりに[プロダクトオーナーチーム](ch02_12_12_Product_Owner_Team.md)に分析作業を担当させることで、貴重な開発にかける時間を奪わずに済みます。先述のプロトタイプ作成ツールは、一回のコストで、継続的な投資対効果をもたらすという好例です。[プロダクトオーナー](ch02_11_11_Product_Owner.md)が[Enabling Specification](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/product-backlog/enabling-specification)の提供の代わりに、実際に分析を行うようにチームに何度も依頼する場合、それは[プロダクトオーナーチーム](ch02_12_12_Product_Owner_Team.md)の専門知識の不足を示している可能性があり、チームはそれを障害として対処するべきです。[Sprint](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/sprint)をまたいで変動するこのような作業は、[開発チーム](ch02_14_14_Development_Team.md)の作業能力の変動を直接生み出し、予測を難しくします。このような障害に対しては、[プロダクトオーナーチーム](ch02_12_12_Product_Owner_Team.md)は、スキルセットを補完するためにチームメンバーを訓練または雇用して、適切な人員の数を確保し、[Enabling Specification](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/product-backlog/enabling-specification)を開発者に一貫して提供できるようにすべきです。

代替手段として、[開発チーム](ch02_14_14_Development_Team.md)の分析への時間の貢献（ひいては他の活動）をPBIとして管理できる妥協的なアプローチも考えられます。[Set-Based Design](https://sites.google.com/a/scrumplop.org/published-patterns/value-stream/set-based-design)のデザインスプリントのようなものです。

