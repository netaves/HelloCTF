[SWPUCTF 2021 新生赛]gift_F12

F12：

![sp0_[SWPUCTF 2021 新生赛]gift_F12](https://raw.github.com/netaves/repositpry/master/helloCTF/writeup_0/images/sp0_[SWPUCTF 2021 新生赛]gift_F12.png)

得到Flag：{We1c0me_t0_WLLMCTF_Th1s_1s_th3_G1ft}



[SWPUCTF 2021 新生赛]re1

使用IDA打开.exe文件，F5进入伪代码视图：

![sp0_[SWPUCTF 2021 新生赛]re1](https://raw.github.com/netaves/repositpry/master/helloCTF/writeup_0/images/sp0_[SWPUCTF 2021 新生赛]re1.png)

第一个for循环功能是将Str1中值为101的元素重赋值为51，查ASCII码表，即将e重赋值为3，同理，第二个for循环功能是将Str2中值为97的元素重赋值为52，即将a重赋值为4；

![sp1_[SWPUCTF 2021 新生赛]re1](https://raw.github.com/netaves/repositpry/master/helloCTF/writeup_0/images/sp1_[SWPUCTF 2021 新生赛]re1.png)

![sp2_[SWPUCTF 2021 新生赛]re1](https://raw.github.com/netaves/repositpry/master/helloCTF/writeup_0/images/sp2_[SWPUCTF 2021 新生赛]re1.png)

得到Flag：{easy_reverse}



[鹤城杯 2021]easy_crypto

附件下载解压缩后是一个.txt文件，内容为：公正公正公正诚信文明公正民主公正法治法治诚信民主自由敬业公正友善公正平等平等法治民主平等平等和谐敬业自由诚信平等和谐平等公正法治法治平等平等爱国和谐公正平等敬业公正敬业自由敬业平等自由法治和谐平等文明自由诚信自由平等富强公正敬业平等民主公正诚信和谐公正文明公正爱国自由诚信自由平等文明公正诚信富强自由法治法治平等平等自由平等富强法治诚信和谐；

![sp0_[鹤城杯 2021]easy_crypto](https://raw.github.com/netaves/repositpry/master/helloCTF/writeup_0/images/sp0_[鹤城杯 2021]easy_crypto.png)

在http://www.hiencode.com/cvencode.html解码：

![sp1_[鹤城杯 2021]easy_crypto](https://raw.github.com/netaves/repositpry/master/helloCTF/writeup_0/images/sp1_[鹤城杯 2021]easy_crypto.png)

得到Flag：{IlUqU9O5guX6YiITsRNPiQmbhNRjGuTP}



[第五空间 2021]签到题

读题：

![sp0_[第五空间 2021]签到题](https://raw.github.com/netaves/repositpry/master/helloCTF/writeup_0/images/sp0_[第五空间 2021]签到题.png)

得到Flag：{welcometo5space}