# mac_ime_locker
切换输入法辅助的小工具，目前可以在豆包语音输入法之后切换回来原来输入法。 

豆包的语音输入法很强大，但是文字输入还是习惯用搜狗，参考Paxxs的[脚本](https://github.com/Paxxs/Doubao-ime-hammerspoon)的思想做了个小工具，方便切换。
目前只能切回搜狗，因为主要考虑自己的需要，如果还有其它人有什么想法欢迎提供，我们改改：）
程序用了沙盒，不访问外网，不需要系统权限，也不用键盘钩子。基本原理就是检测输入法切换事件，如果是豆包输入法，检测是否存在语音框，如果有的话，就等待，没有了语音框之后，切回搜狗输入法。另外一个是强制切回输入法，用来不小心切到了豆包的情况（不过更合理的逻辑可能是切换到下一个输入法）


https://github.com/user-attachments/assets/89442eea-99fc-427a-a0b6-1189126555be

<img width="297" height="314" alt="15时19分28秒_261015_MINI" src="https://github.com/user-attachments/assets/263e6ee7-aac6-4ba3-a948-e50cfb4ecbc0" />
