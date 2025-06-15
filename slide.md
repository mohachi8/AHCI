---
marp: true
paginate: true
math: true
---
<script src="https://cdn.tailwindcss.com/3.0.16"></script>
<script>tailwind.config = { corePlugins: { preflight: false } }</script>



# 人はどのように作業をするか
## -行為の七段階理論-

---

## 回想

<div class = "flex justify-center justify-between mx-[80px] text-2xl">
  <div>
    <div>１．発表者が使ったことない映写機に</div>
    <div class="pl-[50px]">フィルムを通そうとしている</div>
    <img src="./img/Slide1.png" class="w-[150px] translate-x-[130px] mt-3" />

  </div>

  <div>
    <div>２．手助けがきて、議論が起こる  </div>
    <img src="./img/Slide2.png" class="w-[150px] translate-x-[130px] mt-10" />
  </div>
  
</div>

<div class = "flex justify-center justify-between mx-[80px] text-2xl mt-5">
  <div>
    <div>３．会議の責任者が登場し、</div>
    <div class="pl-[50px]">聴衆たちに助けを求める </div>
    <img src="./img/Slide3.png" class="w-[150px] translate-x-[130px] mt-3" />
  </div>

  <div class = "pr-[164px]">
    <div>４．技術者が解決</div>
    <img src="./img/Slide4.png" class="w-[150px] translate-x-[100px] mt-10" />
  </div>
</div>

<!-- 図にしたい .このままだとわかりにくい-->
---

## Q. 映写機にフィルムを通すのが難しいは？ 
- 人が何かをするときに何が起きているかを知る<br>**行為の構造**の検討が必要
<!-- 
なぜフィルムを通すのが困難だか、皆さん説明できますか？
ここでは、行為の構造というものにのっとって検討していきましょう
 -->
---

## 行為の構造
### 行為＝<span style="color: red; ">実行</span>+<span style="color: green; ">評価</span>

<div class="grid grid-cols-2">
  <div class="grid-item">
    <ul>
      <li>実行＝何かをすること</li>
      <li>評価＝チェックすること</li>
    </ul>
  </div>
  <div class="grid-item">
  <img src="./img/action_process1.drawio.svg" class="w-[500px]" />
  </div>
</div>

### ゴール＝起こって欲しいこと
### <span style="color: red; ">実行</span>=外界に対して行ったこと
### <span style="color: green; ">評価</span>＝外界に実際に起きたこととゴールとの比較
<!-- 
まず、行為は2つのことに分類されます。実行と評価です。
実行する前に、行為をするものはゴール、つまり何をしたいかを策定します。それを達成するために外界に何かしらの働きかけを行います。その外界への働きかけを実行といいます。
実行した後は、それが目標のゴールと得られたものが合致しているかどうかを「評価します」
 -->

---
## 実行（ゴール→外界）の変換過程①
### ゴールは明確なものか？
$$\begin{pmatrix}
何か食べよう\\
身支度でもするか
\end{pmatrix}←はっきり記述されないゴール$$
$$このままでは行為につながらない...!$$
### <span style="font-size: 2rem; display: inline-block; text-align: center; width: 100%;">行為につなげるためにゴールを特定する、<b style="font-size: 3rem; color: red; display: inline-block; text-align: center; width: 100%;">意図</b>に表現を変換</span>

<!-- 

 -->
---
## 実行（ゴール→外界）の変換過程②
### 意図を持った者は体を動かす
 - 具体的行為＝「ゴールと意図」と「身体動作」を結びつける
  - - 行為の詳細化
  - - - 何の行為をするか特定
  - - 行為の実行
  - - - 実際に行為をする 

<!-- 

 -->

 --- 
 # 実行（ゴール→外界）の変換まとめ
 <div align="center">
 <img src="./img/action_process3.png" >
</div>
<!-- 
実行は3つのフェーズ
 -->

---
 # 評価（外界→ゴール）の変換まとめ
 <div align="center">
 <img src="./img/action_process4.png" >
</div>
<!-- 
評価は3つのフェーズ
 -->

---
## 行為の7段階についてまとめると
<div class="flex justify-center items-center  ml-[10px]  mt-[1px] top-0">

| カテゴリ | 段階名 | 
| :------- | :----- |
| **ゴール** | 1. ゴールの形成 |  
| **実行過程**| 2. 意図の形成 
|  **実行過程**|3. 行為の詳細化 
|  **評価過程**| 4. 外界の状況の知覚 |
|  **評価過程**| 5. 外界の状況の解釈 |  
|  **評価過程**| 6. 結果の評価|  
</div>


---

# 実行と評価におけるへだたり

---

## へだたり（gulf）
- 心の中にある意図・解釈・実際の行為・状況の間の距離
- 心の中の状態と外界の状態の間を切り離している
- 人が頭の中に作り上げる心理的な表現と外界の物理的な構成要素・状態の間存在する距離の一つの側面を反映

<br>

- **へだたりがあること　→　ユーザにとっての重大な困難**

---

## 実行におけるへだたり（gulf of execution）

- ユーザの意図とそのシステムで許される行為の差異
- ユーザが意図した通りの行為をどれだけ直感的に行えるかがこのへだたりの大きさの一つの尺度となる

---
## 実行におけるへだたりの例（映写機）

- 「映写機を準備してフィルムを上映する」という意図を達成するためにどんな行為をしなければならないかがまったく明らかでなかった
- 一方、フィルムを自動巻き付けする映写機やVTR（カセットを機械に押し込むだけ再生可能）は**へだたりに橋をかけている**といえる
<img src="./img/gulf_of_exe_ex.svg" class="w-[600px]" />

---

## 評価におけるへだたり

- ユーザがシステムの物理的な状態を解釈したり、自分の予期や意図がどの程度よく満たされているかを判断する際にどのくらい努力をしなければならないか
- そのシステムはそのままの形で知覚可能で解釈可能か

---

## 評価におけるへだたりの例（映写機）

- フィルムが映写機の中に挿入されているとき、本当に正しく巻き取られているかを判断するのが困難
- VTRの場合はカセットがちゃんと入っていない場合は、機械に収まらず、飛び出す
→うまくいかなかったことがわかる

---

## デザインの手助けとしての行為の七段階理論

- デザインの貴重な手助けとなる
- ↓
- 評価と実行における隔たりに橋を架けることができているかどうかを確認するためのチェックリストとして利用可能
