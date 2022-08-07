# DuckyScript

DuckyScript是BadUSB的脚本。

#### 脚本说明

1. **脚本规定了全部采用大写。**
2. **采用关键字符串进行编写**

| 命令      | 例子          | 说明                                                         |
| --------- | ------------- | ------------------------------------------------------------ |
| REM       | REM hello     | 脚本注释，REM后不执行任何命令，可以单独使用REM，无意义。     |
| DELAY     | DELAY 1000    | 休眠1秒。                                                    |
| STRING    | STRING A B C  | 输出字符串A B C，单独使用STRING，不输出。                    |
| STRINGE   | STRINGE A B C | 输出字符串A B C，并按下回车按键，单独使用STRING，不输出，只按下回车按键。 |
| KEY       | KEY A         | 按下A按键。                                                  |
| GUI       | GUI           | 按下windows按键，组合使用GUI R，表示按下Windows和R按键。     |
| MENU      | MENU          | 按下MENU按键，想当于鼠标右键，组合使用MENU A，表示按下鼠标右键和A按键。 |
| ALT       | ALT           | 按下ALT按键，组合使用ALT A，表示按下ALT和A按键。             |
| SHIFT     | SHIFT         | 按下SHIFT按键，组合使用SHIFT A，表示按下SHIFT和A按键，在小写状态下输出大写A。 |
| CTRL      | CTRL          | 按下CTRL按键，组合使用CTRL C，表示按下CTRL和C按键。          |
| SPACE     | SPACE         | 按下空格按键。                                               |
| TAB       | TAB           | 按下TAB按键。                                                |
| DOWN      | DOWN          | 按下DOWN按键。                                               |
| LEFT      | LEFT          | 按下LEFT按键。                                               |
| RIGHT     | RIGHT         | 按下RIGHT按键。                                              |
| UP        | UP            | 按下UP按键。                                                 |
| ENTER     | ENTER         | 按下UP按键。                                                 |
| PS        | PS            | 按下PrtSC按键。                                              |
| LOCK      | LOCK          | 大写锁定，长按大写按键。                                     |
| LOOPSPACE | LOOP  2       | 循环下面的脚本2遍。                                          |
| LENDTAB   | LEND          | 循环结束。                                                   |
| REPEAT    | REPEAT 10     | 重复下一条指令10遍。                                         |

#### 例子1（输出Hello World）

```
REM Hello World
DELAY 1000
GUI R
DELAY 500
STRINGE CMD
DELAY 500
STRINGE echo Hello World
DELAY 500
```

