## L1-7 吃鱼还是吃肉
fish.JPG 肉.JPG

国家给出了 8 岁男宝宝的标准身高为 130 厘米、标准体重为 27 公斤；8 岁女宝宝的标准身高为 129 厘米、标准体重为 25 公斤。

现在你要根据小宝宝的身高体重，给出补充营养的建议。

## 输入格式：
输入在第一行给出一个不超过 10 的正整数 N，随后 N 行，每行给出一位宝宝的身体数据：

>性别 身高 体重

      
    
其中 `性别` 是 1 表示男生，0 表示女生。 `身高` 和 `体重` 都是不超过 200 的正整数。

## 输出格式：
对于每一位宝宝，在一行中给出你的建议：

如果太矮了，输出：duo chi yu!（多吃鱼）；
如果太瘦了，输出：duo chi rou!（多吃肉）；
如果正标准，输出：wan mei!（完美）；
如果太高了，输出：ni li hai!（你厉害）；
如果太胖了，输出：shao chi rou!（少吃肉）。
先评价身高，再评价体重。两句话之间要有 1 个空格。

## 输入样例：
>4  
0 130 23  
1 129 27  
1 130 30  
0 128 27

      
    
## 输出样例：
>ni li hai! duo chi rou!  
duo chi yu! wan mei!  
wan mei! shao chi rou!  
duo chi yu! shao chi rou!