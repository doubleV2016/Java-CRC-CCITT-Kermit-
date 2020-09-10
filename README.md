# Java-CRC-CCITT-Kermit-
Java CRC-CCITT (Kermit)

```
最近碰到个 CRC-CCITT (Kermit)校验算法，网上找了很久，毫无结果。
没找到任何JAVA版本的 CRC-CCITT (Kermit)，其他的语言也少！最后
在一个神奇的地方找到了一个C语言版本，java翻译版，特此分享！
```

使用方法
```
Crc.crc("123456789");//结果是0x8921
或
Crc.crc(byte[]);
```

最后附上一个可以在线验证校验结果的网站

https://www.lammertbies.nl/comm/info/crc-calculation
