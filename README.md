![mahua](mahua-logo.jpg)
## 练习6：计算未选课人数
programming language: Matlab,R2020a
问题描述：120人选课id偶数的选a课id%5==0的选b课id%7==0的选c问多少人没选课(答案：41)

代码
```
total=0;
factor=0
for ii=1:120
    factor =0;
    if rem(ii,2)==0
        factor=0;
    elseif rem(ii,5)==0
        factor=0;
    elseif rem(ii,7)==0
        factor =0;
    else
        factor =1;
    end
    total=total +factor;
end
```

## 问题反馈
有任何问题，欢迎反馈给我，联系方式如下

* 邮件(james#outlook.com, 把#换成@)

## 感激
感谢以下单位,排名不分先后

* [algorithm](https://www.1point3acres.com/bbs/thread-298965-1-1.html/)
* [matlab cody](https://ww2.mathworks.cn/matlabcentral/cody/)

## 关于作者

