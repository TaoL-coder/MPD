*MPD is a tool for finding complex paired sequences of structural RNA.* 


# 如何预测你的motif假节


## 直接输入标准的sto文件
* 将得到形成结构的序列与两侧单链序列的配对结果


## 在sto文件中添加#MPD
* 依据你设定标签的位置，改变选定预测的序列，并且输出配对峰。
  * 比如在输入框中输入 /demo/demo-i-HDV-7p.sto 文件中的所有字符，
  将预测#MPD行中由<...> <.....>所选定的区域。配对峰表示，此区域的碱基发生配对的概率。
  > #=MPD             .........<..........>.............................................................................<...............>  



## 参数的含义
* Number of sequences paired： 最小的配对个数，大于此个数的配对都将输出
* MSA motif： 输出多序列的结构文件
* Skeleton：输出结构的骨架
* Molecular evolutionary tree： 依据你输入的sto多序列文件，构建系统进化树
* R-scape predict new structure： 使用R-scape预测出新的motif结构



## 其他
We will release the source code soon.
