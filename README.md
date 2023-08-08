替换 LabVIEW INI 中的 `QuickDropDiagramShortcuts` 为以下内容，从而让 Quick Drop 可以使用英文搜索对应的 LabVIEW 原生函数节点.

```
QuickDropDiagramShortcuts="-inf:负无穷大;1dg:单按钮对话框;2as:矩阵大小;2dg:双按钮对话框;3dg :三按钮对话框;aae:数组元素相加;absolute value:绝对值;ac:数组常量;access rights:访问权限;ad1:加1;add:加;add:加;add array elements:数组元素相加;allspoll:串行轮询所有设备;always copy:总是复制;and:与;and array elements:数组元素与操作;append true/false string:添加真/假字符串;array max & min:数组最大值与最小值;array of strings to path:字符串数组至路径转换;array size:数组大小;array to cluster:数组至簇转换;array to spreadsheet string:数组至电子表格字符串转换;arraymeminfo:数组内存信息;as:数组大小;asb:数组子集;atch:匹配模式;athc:路径常量;ats:数组至电子表格字符串转换;automation close:关闭自动化;automation open:打开自动化;avg:均值;ba:创建数组;bath:创建路径;bbn:按名称捆绑;bitpack to array:比特包至数组;bluetooth close connection:关闭蓝牙连接;bluetooth create listener:创建蓝牙侦听器;bluetooth discover:搜索蓝牙设备;bluetooth open connection:打开蓝牙连接;bluetooth read:读取蓝牙数据;bluetooth wait on listener:等待蓝牙侦听器;bluetooth write:写入蓝牙数据;boolean array to number:布尔数组至数值转换;boolean to (0,1):布尔值至(0,1)转换;build array:创建数组;build path:创建路径;bundle:捆绑;byte array to string:字节数组至字符串转换;call chain:调用链;cancel notification:取消通知;car:复合运算;cast unit bases:基本单位转换;cbc:颜色盒常量;cbr:通过引用调用;cc:簇常量;ccat:连接字符串;cds:条件禁用结构;cerr:清除错误;cf:关闭文件;clear fixed-point overflow status:清除定点溢出状态;close file:关闭文件;close file:关闭文件;close reference:关闭引用;close variable connection:关闭变量连接;cluster to array:簇至数组转换;cmd:执行系统命令;coerce to type:强制转换至类型;complex conjugate:复共轭;complex to polar:复数至极坐标转换;complex to re/im:复数至实部虚部转换;control help window:控制帮助窗口;control online help:控制在线帮助;copy:复制;copy:复制;cosecant:余割;cosine:余弦;cotangent:余切;cpu information:CPU信息;cr:关闭引用;create folder:创建文件夹;create network stream endpoint:创建网络流端点;create network stream reader endpoint:创建网络流读取方端点;create network stream writer endpoint:创建网络流写入方端点;create unique network stream endpoint:创建唯一网络流端点;create unique network stream reader endpoint:创建唯一网络流读取方端点;create unique network stream writer endpoint:创建唯一网络流写入方端点;create user event:创建用户事件;crf:打开/创建/替换文件;cs:条件结构;csc:类说明符常量;current processor id:当前进程ID;current vi's menubar:当前VI菜单栏;current vi's path:当前VI路径;cv:当前VI路径;data cache size:数据缓冲区大小;datasocket close:关闭DataSocket;datasocket open:打开DataSocket;datasocket read:读取DataSocket;datasocket write:写入DataSocket;date/time to seconds:日期/时间至秒转换;dbl:转换为双精度浮点数;dc:DBL数值常量;dds:程序框图禁用结构;dec:减1;decimal digit?:十进制数？;decimal string to number:十进制数字符串至数值转换;decrement:减1;default directory:默认目录;delete:删除;delete:删除;delete data value reference:删除数据值引用;delete menu items:删除菜单项;delete variant attribute:删除变体属性;delete waveform attribute:删除波形属性;deny access:拒绝访问;dequeue element:元素出队列;destroy stream endpoint:销毁流端点;destroy user event:销毁用户事件;devclear:设备清零;devclearlist:设备清零列表;device control/status:设备控制/状态;dfa:删除数组元素;divide:除;divide:除;dq:元素出队列;dv:除;dynamic fpga interface cast:动态FPGA接口转换;ea:空数组？;eath:空路径常量;ec:错误簇常量;ecf:错误代码至错误簇转换;empty array?:空数组？;empty string/path?:空字符串/路径？;enable menu tracking:启用菜单跟踪;enablelocal:启用本地模式;enableremote:启用远程模式;enqueue element:元素入队列;enqueue element at opposite end:队列最前端插入元素;eof:EOF;eq:等于？;equal to 0?:等于0？;equal?:等于？;eqz:等于0？;er:错误下拉列表;erg:合并错误;ess:小于？;esseq:小于等于？;esseqz:小于等于0？;essz:小于0？;estr:空字符串/路径？;estrc:空字符串常量;evstr:事件结构;exclusive or:异或;exponential:指数;exponential (arg) -1:exp(x)-1;ext:转换为扩展精度浮点数;fb:反馈节点;fc:假常量;fca:首次调用？;file dialog:文件对话框;file dialog:文件对话框;file/directory info:文件/目录信息;file/directory info:文件/目录信息;findlstn:查找侦听器;findrqs:查找请求设备;first call?:首次调用？;fixed-point overflow?:定点溢出？;fixed-point to integer cast:定点转换为整型;flatten to string:平化至字符串;flattened string to variant:平化字符串至变体转换;floating point equal?:浮点数等于？;flush file:刷新文件;flush file:刷新文件;flush queue:清空队列;flush stream:刷新流;for:For循环;format date/time string:格式化日期/时间字符串;format value:格式化值;fpga refnum to session:FPGA引用句柄至会话句柄转换;fract/exp string to number:分数/指数字符串至数值转换;fs:For循环;fss:平铺式顺序结构;fstr:格式化写入字符串;fxp:转换为定点数;generate front panel activity:产生前面板活动;generate occurrence:产生事件发生;generate user event:产生用户事件;generate user-defined trace event:产生用户定义Trace事件;geq:大于等于？;geqz:大于等于0？;get datalog position:获取数据记录位置;get date/time in seconds:获取日期/时间（秒）;get date/time string:获取日期/时间字符串;get drag drop data:获取拖放数据;get file position:获取文件位置;get file size:获取文件大小;get help window status:获取帮助窗口状态;get menu item info:获取菜单项信息;get menu selection:获取所选菜单项;get menu short cut info:获取快捷菜单信息;get notifier status:获取通知器状态;get number of records:获取记录数量;get permissions:获取权限;get queue status:获取队列状态;get type and creator:获取文件类型和创建者;get variant attribute:获取变体属性;get volume info:获取卷信息;get waveform attribute:获取波形属性;gpib clear:GPIB清零;gpib initialization:GPIB初始化;gpib misc:GPIB其他命令;gpib read:GPIB读取;gpib serial poll:GPIB串行轮询;gpib status:GPIB状态;gpib trigger:GPIB触发;gpib wait:GPIB等待;gpib write:GPIB写入;gr:大于？;greater or equal to 0?:大于等于0？;greater or equal?:大于等于？;greater than 0?:大于0？;greater?:大于？;grz:大于0？;handle peek:句柄取数;handle poke:句柄存数;hex digit?:十六进制数？;hexadecimal string to number:十六进制数字符串至数值转换;hyperbolic cosecant:双曲余割;hyperbolic cosine:双曲余弦;hyperbolic cotangent:双曲余切;hyperbolic secant:双曲正割;hyperbolic sine:双曲正弦;hyperbolic tangent:双曲正切;i16:转换为双字节整型;i32:转换为长整型;i64:转换为64位整型;i8:转换为单字节整型;implies:蕴含;in range and coerce:判定范围并强制转换;include fixed-point overflow status:包括定点溢出状态;increment:加1;index string array:索引字符串数组;inf:正无穷大;insert menu items:插入菜单项;integer to fixed-point cast:整型转换为定点;interpolate 1d array:一维数组插值;inverse cosecant:反余割;inverse cosine:反余弦;inverse cotangent:反余切;inverse hyperbolic cosecant:反双曲余割;inverse hyperbolic cosine:反双曲余弦;inverse hyperbolic cotangent:反双曲余切;inverse hyperbolic secant:反双曲正割;inverse hyperbolic sine:反双曲正弦;inverse hyperbolic tangent:反双曲正切;inverse secant:反正割;inverse sine:反正弦;inverse tangent:反正切;inverse tangent (2 input):反正切（2个输入）;ip to string:IP地址至字符串转换;irda close connection:关闭红外线连接;irda create listener:创建红外线侦听器;irda discover:搜索红外线;irda open connection:打开红外线连接;irda read:读取红外线数据;irda wait on listener:等待红外线侦听器;irda write:写入红外线数据;isdebuggingactive:调试有效;ivi delete session:IVI删除会话句柄;ivi new session:IVI新建会话句柄;join numbers:整数拼接;leak variant value reference:释放变体值引用;less or equal to 0?:小于等于0？;less or equal?:小于等于？;less than 0?:小于0？;less?:小于？;lexical class:字符类;list directory:列表目录;list folder:罗列文件夹;lock range:锁定范围;logarithm base 10:底数为10的对数;logarithm base 2:底数为2的对数;logarithm base x:底数为X的对数;logical shift:逻辑移位;lossy enqueue element:有损耗元素入队列;makeaddr:生成地址;mantissa & exponent:尾数与指数;match first string:匹配字符串;match pattern:匹配模式;match true/false string:匹配真/假字符串;matrix size:矩阵大小;max & min:最大值与最小值;mod:商与余数;move:移动;move:移动;multiply:乘;multiply:乘;multiply array elements:数组元素相乘;na:初始化数组;nae:数组元素与操作;nan:非法数字/路径/引用句柄？;natural logarithm:自然对数;natural logarithm (arg +1):自然对数 (Arg +1);nc:数值常量;ndx:索引数组;negate:取相反数;neq:不等于？;neqz:不等于0？;nes:元素同址操作结构;new data value reference:新建数据值引用;new directory:新建目录;new file:新文件;new vi:新建VI;new vi object:新建VI对象;not:非;not a number/path/refnum?:非法数字/路径/引用句柄？;not and:与非;not equal to 0?:不等于0？;not equal?:不等于？;not exclusive or:同或;not or:或非;nq:元素入队列;nt:非;number of cache levels:缓存级别数量;number to boolean array:数值至布尔数组转换;number to decimal string:数值至十进制数字符串转换;number to engineering string:数值至工程字符串转换;number to exponential string:数值至指数字符串转换;number to fractional string:数值至小数字符串转换;number to hexadecimal string:数值至十六进制字符串转换;number to octal string:数值至八进制字符串转换;nv:调用节点;obtain notifier:获取通知器引用;obtain queue:获取队列引用;octal digit?:八进制数？;octal string to number:八进制字符串至数值转换;old visa open:旧VISA打开;one button dialog:单按钮对话框;open application reference:打开应用程序引用;open device:打开设备;open file:打开文件;open vi object reference:打开VI对象引用;open vi reference:打开VI引用;open/create/replace datalog:打开/创建/替换数据记录文件;open/create/replace file:打开/创建/替换文件;or:或;or array elements:数组元素或操作;package matrix:包矩阵;passcontrol:传递控制权;path to array of strings:路径至字符串数组转换;path to string:路径至字符串转换;path type:路径类型;pick line:选行并添加至字符串;polar to complex:极坐标至复数转换;polar to re/im:极坐标至实部虚部转换;power of 10:10的幂;power of 2:2的幂;power of x:X的幂;ppoll:并行轮询;ppollconfig:并行轮询配置;ppollunconfig:取消并行轮询配置;preserve run-time class:保留运行类;preview queue element:预览队列元素;printable?:可打印？;qr:商与余数;quit labview:退出LabVIEW;quotient & remainder:商与余数;ra:反转一维数组;random number (0-1):随机数(0-1);ras:替换数组子集;rbf:读取二进制文件;rcvrespmsg:从之前设备中读取数据;re/im to complex:实部虚部至复数转换;re/im to polar:实部虚部至极坐标转换;read datalog:读取数据记录文件;read device:读取设备;read file:读取文件;read from binary file:读取二进制文件;read from text file:读取文本文件;readstatus:读取状态;receive:接收数据;receivesetup:准备接收;reciprocal:倒数;refnum to path:引用句柄至路径转换;refnum to session:引用句柄至会话句柄转换;register session:注册会话句柄;release notifier:释放通知器引用;release queue:释放队列引用;remove fixed-point overflow status:删除定点溢出状态;replace substring:替换子字符串;request deallocation:请求释放内存;resetsys:系统复位;resize matrix:调整矩阵大小;resource index:资源索引;reverse 1d array:反转一维数组;reverse string:反转字符串;rn:属性节点;rndd:向下取整;rndu:向上取整;rotate:循环移位;rotate 1d array:一维数组循环移位;rotate left with carry:带进位的左移位;rotate right with carry:带进位的右移位;rotate string:字符串移位;round to nearest:最近数取整;round toward +infinity:向上取整;round toward -infinity:向下取整;rt fifo create:RT FIFO创建;rt fifo delete:RT FIFO删除;rt fifo read:RT FIFO读取;rt fifo write:RT FIFO写入;rtf:读取文本文件;s1d:搜索一维数组;sath:拆分路径;sav:选择VI...;sb:减;sc:字符串常量;scale by power of 2:按2的幂缩放;scan string for tokens:在字符串中搜索标记;scan value:扫描值;se:选择;search 1d array:搜索一维数组;search and replace string:搜索替换字符串;search variable container:搜索变量容器;search/split string:搜索/拆分字符串;secant:正割;seconds to date/time:秒至日期/时间转换;seek:搜索;select:选择;send:发送;send notification:发送通知;sendcmds:发送命令;senddatabytes:发送数据;sendifc:发送IFC;sendlist:发送至设备列表;sendllo:发送LLO;sendsetup:发送设置;seng:字符串长度;serr:简易错误处理器;session to refnum:会话句柄至引用句柄转换;set datalog position:设置数据记录位置;set file position:设置文件位置;set file size:设置文件大小;set menu item info:设置菜单项信息;set number of records:设置记录数量;set occurrence:设置事件发生;set permissions:设置权限;set type and creator:设置文件类型和创建者;set variant attribute:设置变体属性;set waveform attribute:设置波形属性;setrwls:设置RWLS;settimeout:设置超时;sgl:转换为单精度浮点数;shared variable to string:共享变量至字符串转换;sign:符号;sinc:Sinc;sine:正弦;sine & cosine:正弦与余弦;size handle:设置句柄大小;sort 1d array:一维数组排序;sort array of string:字符串数组排序;split 1d array:拆分一维数组;split number:拆分数字;spreadsheet string to array:电子表格字符串至数组转换;sqr:平方根;square:平方;square root:平方根;srt:一维数组排序;sss:搜索/拆分字符串;sta:电子表格字符串至数组转换;stop:停止;string length:字符串长度;string subset:截取字符串;string to byte array:字符串至字节数组转换;string to ip:字符串至IP地址转换;string to path:字符串至路径转换;string to shared variable:字符串至共享变量转换;strip path:拆分路径;subtract:减;subtract:减;svr:静态VI引用;swap bytes:交换字节;swap values:交换值;swap vector element:交换向量元素;swap words:交换字;tangent:正切;tc:真常量;tcase:转换为小写字母;tcp close connection:关闭TCP连接;tcp create listener:创建TCP侦听器;tcp flattened read:TCP平化读取;tcp flattened write:TCP平化写入;tcp flex read:TCP自由读取;tcp flex write:TCP自由写入;tcp open connection:打开TCP连接;tcp read:读取TCP数据;tcp wait on listener:等待TCP侦听器;tcp write:写入TCP数据;tct:时间计数器;tdms close:TDMS关闭;tdms flush:TDMS刷新;tdms get properties:TDMS获取属性;tdms list contents:TDMS列出内容;tdms open:TDMS打开;tdms read:TDMS读取;tdms refnum to file id:TDMS引用句柄至文件ID;tdms refnum to file id:TDMS引用句柄至文件ID;tdms set properties:TDMS设置属性;tdms write:TDMS写入;tdms write ip:TDMS写入IP;temporary directory:临时目录;testsrq:测试SRQ;testsys:系统测试;text to utf-8:文本至UTF-8转换;threshold 1d array:以阈值插值一维数组;tick count (ms):时间计数器;to byte integer:转换为单字节整型;to double precision complex:转换为双精度复数;to double precision float:转换为双精度浮点数;to extended precision complex:转换为扩展精度复数;to extended precision float:转换为扩展精度浮点数;to fixed-point:转换为定点数;to long integer:转换为长整型;to lower case:转换为小写字母;to more generic class:转换为通用的类;to more specific class:转换为特定的类;to ole variant:转换为OLE变体;to probe string:转换为探针字符串;to quad integer:转换为64位整型;to single precision complex:转换为单精度复数;to single precision float:转换为单精度浮点数;to time stamp:转换为时间标识;to unsigned byte integer:转换为无符号单字节整型;to unsigned long integer:转换为无符号长整型;to unsigned quad integer:转换为无符号64位整型;to unsigned word integer:转换为无符号双字节整型;to upper case:转换为大写字母;to variant:转换为变体;to word integer:转换为双字节整型;tra:二维数组转置;transpose 1d array:一维数组转置;transpose 2d array:二维数组转置;transpose matrix:矩阵转置;trigger:触发;triggerlist:触发设备列表;tsc:转换为特定的类;tvar:转换为变体;two button dialog:双按钮对话框;type and creator:类型和创建者;type cast:强制类型转换;u16:转换为无符号双字节整型;u32:转换为无符号长整型;u64:转换为无符号64位整型;u8:转换为无符号单字节整型;ubn:按名称解除捆绑;udp close:关闭UDP;udp multicast open:打开UDP多点传送;udp open:打开UDP;udp read:读取UDP数据;udp write:写入UDP数据;unbitpack from array:数组至比特包;unbundle:解除捆绑;unflatten from string:从字符串还原;unflatten from xml:从XML还原;unleak variant value reference:取消释放变体值引用;unpackage matrix:未组合的矩阵;unregister for events:取消注册事件;unregister session:取消注册会话句柄;utf-8 to text:UTF-8至文本转换;vae:数组元素或操作;variant to data:变体至数据转换;variant to flattened string:变体至平化字符串转换;vc:变体常量;vi library:VI库;visa assert interrupt signal:VISA置中断信号有效;visa assert trigger:VISA置触发有效;visa assert utility signal:VISA置效用信号有效;visa clear:VISA设备清零;visa close:VISA关闭;visa disable event:VISA禁用事件;visa discard events:VISA放弃事件;visa enable event:VISA启用事件;visa find resource:VISA查找资源;visa flush i/o buffer:VISA清空I/O缓冲区;visa gpib command:VISA GPIB命令;visa gpib control atn:VISA GPIB控制ATN;visa gpib control ren:VISA GPIB控制REN;visa gpib pass control:VISA GPIB传递控制权;visa gpib send ifc:VISA GPIB传递IFC;visa in 16:VISA输入16;visa in 32:VISA输入32;visa in 64:VISA输入64;visa in 8:VISA输入8;visa lock:VISA锁;visa map address:VISA映射地址;visa map trigger:VISA映射触发;visa memory allocation:VISA内存分配;visa memory allocation ex:VISA内存分配Ex;visa memory free:VISA内存释放;visa move:VISA转移;visa move in 16:VISA转入16;visa move in 32:VISA转入32;visa move in 64:VISA转入64;visa move in 8:VISA转入8;visa move out 16:VISA转出16;visa move out 32:VISA转出32;visa move out 64:VISA转出64;visa move out 8:VISA转出8;visa open:VISA打开;visa out 16:VISA输出16;visa out 32:VISA输出32;visa out 64:VISA输出64;visa out 8:VISA输出8;visa peek 16:VISA取数16;visa peek 32:VISA取数32;visa peek 64:VISA取数64;visa peek 8:VISA取数8;visa poke 16:VISA存数16;visa poke 32:VISA存数32;visa poke 64:VISA存数64;visa poke 8:VISA存数8;visa read:VISA读取;visa read stb:VISA读取STB;visa read to file:VISA读取设备并写入文件;visa refnum to session:VISA引用句柄至会话句柄转换;visa set i/o buffer size:VISA设置I/O缓冲区大小;visa status description:VISA状态说明;visa unlock:VISA解锁;visa unmap address:VISA取消地址映射;visa unmap trigger:VISA取消触发映射;visa usb control in:VISA USB控制输入;visa usb control out:VISA USB控制输出;visa vxi cmd or query:VISA VXI命令或查询;visa wait on event:VISA等待事件;visa write:VISA写入;visa write from file:VISA读取文件并写入设备;volume info:卷信息;vr:打开VI引用;vsr:VI服务器引用;vtd:变体至数据转换;wait (ms):等待(ms);wait for activity:等待活动;wait for front panel activity:等待前面板活动;wait for gpib rqs:等待GPIB RQS;wait on notification:等待通知;wait on notification from multiple:等待多个通知;wait on notification from multiple with notifier history:等待带通知器历史的多个通知;wait on notification with notifier history:等待带通知器历史的通知;wait on occurrence:等待事件发生;wait until next ms multiple:等待下一个整数倍毫秒;waitsrq:等待SRQ;wat:等待(ms);wbf:写入二进制文件;wc:波形常量;white space?:空白？;write datalog:写入数据记录文件;write device:写入设备;write file:写入文件;write to binary file:写入二进制文件;write to text file:写入文本文件;ws:While循环;wtf:写入文本文件;x:乘;xae:数组元素相乘;y-th root of x:X的Y次根;"

```