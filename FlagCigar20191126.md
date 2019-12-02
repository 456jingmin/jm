Question 1-5： BAM FLAG
1. Explain BAM FLAG value： 143
143=128+8+4+2+1=10001111
表示两条read都没有正确比对到参考序列上。

2. Explain BAM FLAG value： 99
99=64+32+2+1=1100011
表示第一条read和参考序列完全匹配，第二条read与参考序列的反向互补序列相匹配。

3. Explain BAM FLAG value：516
516=512+4=1000000100
表示该read没有比对到参考序列上。

4. Explain BAM FLAG value： 2064
2064=2048+16=100000010000
表示补充匹配的read比对到参考序列的反向互补序列上。

5. Explain BAM FLAG value： 147
147=128+16+2+1=10010011
表示第二条read比对到参考序列的反向互补序列上，与参考序列完全匹配。

Question 6-10： BAM CIGAR
6. Explain BAM CIGAR：14M2D31M
表示该read开始的14bp比对到参考序列上，接下来的2bp序列删除，最后的31bp能够比对上参考序列。

7. Explain BAM CIGAR：3S6M1D5M
表示该read开始的3bp被跳过，接着的6bp比对上了参考序列，接着的1bp序列删除，最后的5bp与参考序列匹配。

8. Explain BAM CIGAR: 6M14N5M
表示该read开始的6bp比对上了参考序列，接着的14bp被跳过，最后的5bp比对上了参考序列。

9. Explain BAM CIGAR: 7M5D8M2I14M  (小写：7m5d8m2i14m）
表示该read开始的7bp与参考序列匹配，接着的5bp序列删除，之后的8bp比对上了参考序列，接着的2bp序列插入，最后的14bp比对上了参考序列。

10. how long is the read with alignment CIGAR of 7M5D8M2I14M?
34bp

