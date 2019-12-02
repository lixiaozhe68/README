Answer to the 10 questions:
1.BAM FLAG value 143:
    read paired (0x1)
    read mapped in proper pair (0x2)
    read unmapped (0x4)
    mate unmapped (0x8)
    second in pair (0x80)
2.BAM FLAG value 99:
    read paired (0x1)
    read mapped in proper pair (0x2)
    mate reverse strand (0x20)
    first in pair (0x40)
3.BAM FLAG value 516:
    read unmapped (0x4)
    read fails platform/vendor quality checks (0x200)
4.BAM FLAG value 2064:
    read reverse strand (0x10)
    supplementary alignment (0x800)
5.BAM FLAG value 147:
    read paired (0x1)
    read mapped in proper pair (0x2)
    read reverse strand (0x10)
    second in pair (0x80)
6.14M2D31M: 检测序列与参考基因组相比，前14bp能够match上;中间有2bp的deletion;最后是31bp的match.
7.3S6M1D5M：检测序列与参考基因组相比，前3bp为soft clipping（软剪切）;接下来6bp能够match上；随后有1bp的deletion;最后是5bp的match.
8.6M14N5M：检测序列与参考基因组相比，前6bp能够match上；中间有14bp的skipped（跳跃）;最后是5bp的match.
9.7M5D8M2I14M：检测序列与参考基因组相比，前7bp能够match上;中间有5bp的deletion;随后又8bp的match;接下来insertion(插入)2bp;最后是14bp的match.
10.The long of 7M5D8M2I14M:31.
