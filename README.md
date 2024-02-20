# VATPRC-official-sector
Leave you features &amp; Issues to improve an official VATPRC sector


# 停机位自动分配功能所需文件

```
{机场代码} | 文件夹
├── {机场代码}-Airlines.txt
├── {机场代码}-usestand.txt
├── {机场代码}-Wingspan.txt
```

## 机位
所有机位所支持的格式为两种：
- 单独机位，如101；表示101机位
- 范围机位。如101-105；表示从101至105的所有机位

多个机位应使用`,`将其区分。例如`101,105,107-109,20L,20R`

## {机场代码}-Airlines.txt
格式：
  - `机位\t航空公司`

航空公司应为三字码，多个航空公司以`,`分割

例如：`401-466\tCCA,CCD,CDC`

## {机场代码}-usestand.txt
格式：
  - `机位\t类别`

类别分为以下几种：
- `DOM`  | 表示国内机位
- `INT`  | 表示国际机位
- `CARGO` | 表示货运机位
- `BUSINESS` | 表示公务机位

！仅可四选一！

例如：`215,219-240,301-337,401-413\tDOM`

## {机场代码}-Wingspan.txt
格式：
  - `机位\t翼展`

翼展为数字

例如：`308,403,405,406-440\t69`

##
## 完成上述文件后，可提交至扇区组，通过检查后，会在下期随更新同步上线
