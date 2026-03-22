## 一、同源重组

### 1\. Mechanism for Crossing-Over→真核细胞减数分裂

* 交换：减数分裂期间发生的同源重组引起  ==同源染色体之间==  发生DNA大片段的交换
* !\[\[Pasted image 20250416213603.png|300]]!\[\[Pasted image 20250416213610.png|300]]

  * **酶Spo11** 在染色体上制造了一个双链断裂（DSB）→同源重组的起始步骤，通常发生在减数分裂过程中。
  * 断裂末端被外切酶处理后形成单链，接着**Rad51蛋白**结合到单链DNA上，形成核蛋白丝nucleoprotein filament
  * Rad51 涂层的单链 DNA 搜索结果开始寻找其互补的同源染色体链
  * 单链 DNA 侵入同源染色体的双链 DNA 中，形成一个 D 环（D-loop）
  * 迁移：如果holiday junctions继续往前走→扩大，可能会一直走到头
  * 形成holiday junctions

    * 不产生交换的Holliday交叉拆分!\[\[Pasted image 20250417145535.png|500]]
    * 产生交换的Holiday交叉拆分→降解掉一边的连接处后，另一边在三维结构上扭了一下(可以结合视频理解)!\[\[Pasted image 20250417145526.png|500]]

#### 2\. Mechanism for Double-Stranded Break Repair\[\[Chapter6 突变和突变修复]]

* 步骤：!\[\[Pasted image 20250417143136.png|400]]

  * 酶Spo11→双链切割，类似于减数分裂重组的第一步，断裂末端被外切酶降解→形成错位末端，带有悬垂的单链
  * 悬垂的单链寻找同源序列进行配对，侵入同源染色体→形成D-loop→扩展形成holiday junction
  * holiday junction可以在两个同源染色体之间移动，增加杂交区域的长度→拆分(交换或不产生交换)
* e.g.BRCA1或BRCA2的缺失→同源重组修复机制受损，使得DNA双链断裂无法有效修复→引发乳腺癌、卵巢癌等

#### 3\.  The RecBCD pathway→原核细胞中

* 组成：

  * RecB→核酸酶；RecC→识别DNA末端；RecD→解旋酶
* 过程!\[\[Pasted image 20250417143707.png|400]]

  1. 双链断裂→由RecBCD降解后单链于SSB结合→RecA入侵另一条链→Holiday过程

#### 4\. Gene Conversion #易混淆

区别于转换Transition\[\[Chapter6 突变和突变修复]]
!\[\[Pasted image 20250416214533.png|400]]

* 定义：基因转换是一种遗传物质的重组方式，指的是在细胞内同源染色体之间或者姐妹染色单体之间，发生局部的遗传物质的交换和重组的过程→其中供体的基因不变，而受体将持有供体的相同基因→经过复制后，两个子代分子将完全相同，携带同一基因的单一版本

  * 基因转换改变了群体的基因频率，而交叉互换不会导致群体基因频率的改变
* 过程：

  * 在  ==DSBR过程==  中，侵入的单链以同源染色体的DNA为模板，沿着被置换的单链 DNA 进行 DNA 合成和延伸→新的 DNA 链会按照模板链的序列进行合成 #待解决
  * 原本被侵入的单链 DNA 被逐渐置换出来，并与另一条单链 DNA 重新连接，形成重组后的染色体结构。在这个过程中，DNA 连接酶会将新合成的 DNA 链与原有的 DNA 链连接起来，完成基因转换的过程
  * 看不懂，暂且理解为不产生交换的holiday拆分
* e.g.粗糙脉孢菌（Neurospora crassa）：基因转换导致特定基因型的改变



\---

## 二、非同源重组

* Ⅰ型转座子：以DNA为模板，转录为mRNA，再反转录为cDNA，在整合酶作用下插入基因组的新位置  ==“复制-粘贴”==  
* Ⅱ型转座子：由DNA介导  ==“剪接-粘贴”==  

  * 自主型TEs
  * 非自主型TE：需要另外一个TE带着才能够跳跃，缺少转座酶（对于II类）或逆转录酶（对于I类）

#### 1\. Transposons(TE)/Ⅱ型转座子!\[\[Pasted image 20250417133612.png|300]]

^0c3da1

* 发现者：Babara

  * e.g.Ac-Ds调控系统→属于植物转座子系统

    * 元件

      * **Ac元件（Activator，激活子）** ：是一个 ==能够自主转座== 的 DNA 序列，自身编码转座酶，这种转座酶不仅能够催化自身的转座，还能激活非自主转座子 Ds 的转座。
      * **Ds元件（Dissociation，分离子）** ：是一个非自主转座子，其结构与 Ac 相似，但自身缺少完整的转座酶编码序列，因此不能自主转座，只有在 Ac 提供的转座酶存在的情况下才能发生转座。
    * 过程

      1. **Ac的转座** ：在植物细胞中，Ac元件可以在转座酶的催化下，从一个 DNA 位置跳跃到另一个位置，这个过程会导致 DNA 的切断和重新连接。

         *  ==转座酶首先识别 Ac 元件两端的反向重复序列== ，然后在这些序列处切割 DNA，并将 Ac 元件插入到新的 DNA 位置。
      2. **Ds的转座** ：当 Ac 元件存在时，其编码的转座酶也能识别 Ds 元件两端的反向重复序列，并催化 Ds 元件的转座。转座酶会切割 Ds 元件两侧的 DNA，并将其插入到新的 DNA 位置。
* 复制型转座：转座酶催化插入序列移动到基因组中的新位点中，当移动时产生一个转座子的  ==拷贝==  并将它插入新的位置，而原先的  ==转座子还留在原来的位置==  的转座。

  * 机制：!\[\[Pasted image 20250417134908.png|200]]!\[\[Pasted image 20250417134925.png|300]]

    * 转座子末端与目标位点的末端切割后相连
    * DNA合成填补缺口，转座子插入后，重组位点res site形成
* 保守型转座：转座酶催化插入序列移动到基因组中的新位点中，转座子  ==离开原来的位置==  并插入到新的位点中的转座。

  * 机制:!\[\[Pasted image 20250417135154.png|250]]!\[\[Pasted image 20250417135204.png|250]]
* functions：generate chromosomal rearrangements and relocate genes!\[\[Pasted image 20250417134255.png|400]]

  * 可以导致基因突变，产生基因组的多样性/引起某些疾病

    * FA-T型范可尼贫血
  * 可能会改变基因的启动子、增强子等，从而影响基因表达/导致基因沉默
  * 可以作为遗传标记，用于基因定位和遗传图谱的构建
  * 作为基因转移工具，用于基因治疗和基因编辑

#### 2\. 反转录转座子Retrotransposons/Ⅰ型转座子

* LTR-Retrotransposons

  * !\[\[Pasted image 20250417135443.png|400]]
  * LTR-逆转座子的  ==两端是长末端重复序列(LTR)==  ，中间包含一些基因，如逆转录酶（reverse transcriptase）和整合酶（integrase）
  * 以DNA为模板，转录为mRNA，再反转录为cDNA，在整合酶作用下插入基因组的新位置  ==“复制-粘贴”== 
* Non-LTR Retrotransposons!\[\[Pasted image 20250418163950.png|300]]

  * 含有一个/多个ORF，编码逆转录酶和其它蛋白
  * !\[\[Pasted image 20250417135456.png|400]]
  * L1逆转座子被转录成RNA，这个RNA包含了一个  ==poly(A)尾==  ，此后被导出到细胞质中
  * 被转录为ORF1和ORF2蛋白→与L1RNA组装成为核糖核蛋白颗粒RNP
  * RNA通过p40蛋白介导进入细胞核，在新的染色体位置整合截短.逆转录酶（RT）将RNA逆转录成cDNA，然后整合到宿主DNA中
  * e.g.： #课后拓展

    * **LINEs**（Long Interspersed Nuclear Elements）：能自主转座，编码逆转录酶。
    * **SINEs**（Short Interspersed Nuclear Elements）：依赖LINEs的酶完成转座，如人类的Alu元件。

#### 3\. Bacteriophage λ integration

* 裂解\[\[Chapter3 病毒Virus]]
* 溶源性
* site-specific recombination：可逆过程，噬菌体DNA可以通过整合酶的作用整合到细菌染色体中，也可以通过切除酶的作用从染色体中切除

  * attachment site of phage，噬菌体的附着位点
  * attachment site of bacterium，细菌的附着位点
  * !\[\[Pasted image 20250417141013.png|300]]

    * 整合：整合酶识别并结合到attP和attB位点，由IHF帮助整合酶完成重组过程→噬菌体DNA整合到细菌染色体
    * 切除：切除酶识别并结合到整合后的噬菌体DNA和细菌染色体的交界处→切除病毒DNA

#### 4\. 重复序列

* 串联重复Tandem repeats

  * **卫星DNA**：以相对恒定的短序列作为重复单位，首尾相接，串联形成的重复序列→主要存在于非编码区
  * 类型：

    * 大卫星DNA
    * 小卫星DNA
    * 微卫星DNA/短串联重复序列STRs→SSRs→在植物中常作为遗传标记使用
* 散在重复Dispersed repeats/转座子\[\[#^0c3da1]]

\---

1. What is gene conversion, and how does it occur?
2. How does the distance that a Holliday junction migrates during branch migration affect the characteristics of the heteroduplex joint?
3. Do you think transposons have mostly negative or positive effects on organisms? Why?
4. What are the differences between double-stranded break repair and crossing-over?

\---

* References

  * [【动画】Holliday连接分析 Holliday junction resolution《分子生物学：基因功能原理》14\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV15x411h7XW/?vd_source=cbeeb9b4a81ed17f43f1d0be32a9f270)
  * [基因转换和基因重组 - 知乎](https://zhuanlan.zhihu.com/p/386974925)
  * [转座子（TE,散在重复）特征及其对基因组影响 - 简书](https://www.jianshu.com/p/e759988cd4b5)
  * [DNA转座子和逆转录转座子的区别 - 知乎](https://zhuanlan.zhihu.com/p/608386912)
  * *Cordaux and Batzer 2009 Nat Rev Genet*

