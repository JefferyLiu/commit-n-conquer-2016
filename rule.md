> rule.md
> authored by [@cuter44](https://github.com/cuter44)
> timestamp 1454861631000

## 玩法

就是简单地提交一个 commit, 以提交产生的 SHA1ID 决胜负, 最小者胜出.  
纯粹(不)是赌人品的游戏!!  

## 基本步骤

...不过为了玩起来有点意义以及规范性, 以下是追加说明

1. 编辑 README.md, $('#白板').append(随便写点什么比如明年我要在935刷一百个项目帮老邝赚几百万或者捉大家今年六六六六之类).  
   > 最佳实践肯定是刷老邝鞋啦!  

2. 提交你的更改, commit msg 才是关键:  
   第一行(summary), 请填写收钱的id: 比如 `wxpay://617443801` 或者 `alipay://cuter44@qq.com`, 你们这么聪明一定能看懂这个 scheme 的.   
   第二行为空行, git 固有规定.  
   第三行(detail)开始, 随便写. 不过了解[散列算法](https://en.wikipedia.org/wiki/Sha1)的童鞋肯定知道这才是胜负的关键吧hhhhh  

3. 提交后自动计算的 SHA1ID 就是参赛的奖券了~

## 奖项设置

* 按 [Big-Endian](https://en.wikipedia.org/wiki/SHA-1) 对所有 commit 进行排序. 按自然对数的展开多项式(f(n)=(1/n!), n=1→+∞)评选奖金. Rank#1 的奖金是 100 CNY, Rank#2: 50 CNY, Rank#3: 16.67 CNY, 如此类推.  
* 依照提交内容质量由老邝评选 金邝奖 一名, 奖金是 66.66 CNY. 

## 提示

* 截止时间为 开学后一周内, 具体时刻看副主任心情.  
* 总 Contributors 达到 16 人这个活动方为有效.  
* 多次提交以收款id进行排重, 仅计算最高奖金, 不累计.  
* 仅 master 分支的 commit 为有效参与, 且 **排除 merge commit**.  
* 战斗规则是 Free-Fight, 也就是说: 暴力尝试/强制推送复写对手的提交/使用git的底层指令伪造SHA1ID/租用天河一号运算必胜解 等手段都是合法的, 只要不会被 Github 官方封号的行为都予以认可. (大概就是中忍选拔考试的笔试的样子嗯  
* 新的一年也来一起愉快地玩耍吧!!  