# Eroducate项目规范

为了保证Eroducate资产的可塑性和可维护性，所有操作Eroducate资产的人员必须严格遵守以下流程和规则。

## 视频资产
1. 素材拍摄完后必须全部按照FASMEC分类法进行分类和粗剪，同时在粗剪阶段丢弃的片段不要立刻删除，请全部移动到彩蛋文件夹供彩蛋剪辑使用。
2. 素材剪辑完成后必须分段（按照剧情模块）导出，一定不要结合在一起导出。
3. 剪辑完成的视频在上字幕前一定要全组人先全部看一遍确认没有任何剪辑问题
4. 上字幕阶段时和全组人确认沟通好字幕样式再开始上字幕
5. 在上完字幕后不要删除字幕工程文件，请务必分别导出每一个片段的字幕工程文件并且和相对应原视频保存在同一文件夹内
6. 字幕人员一定要确认最终字幕效果后再提交导出的文件
7. 转码最终文件为中等比特率格式，并且保留源文件
8. 上传文件到服务器时一定注意bucket名字是否正确权限是否设置正确
9. 以上所有步骤在操作时务必确保视频文件名不变（名字为FASMEC格式）

## FASMEC Quick Notation Method
### Why FASMEC?
FASMEC Quick Notation Method is designed to quikcly annotate all the clips in a massive Multi Ending Visual Novel project. It's both easy to learn and to understand. Using the FASMEC Quick Notation Method, you can even add your own notation symbols such as N for Night or f for Flash.
### Definition
``` var num = any positive integers; ```
 * F: Female Line 
 * M: Male Line 
 * A + num: Act num 
 * S + num: Shot num 
 * C + num: Choice num 
 * E + num: Establishing Shot/Insert Shot/Cutaway Shot num
### Linked Nomination
You can use Linked Notation when it comes to a Choice under another Choice.  

E.G: FA2C1C1S2= Female Line Act2 Choice1's Choice 1 Shot1
### Examples
FA1S1 = Female Line Act1 Shot 1  
MA1C1C2S1 = Male Line Act1 Choice1's Choice2 Shot1
### FASMEC Converter 立项阶段
What's even more exciting is that you get to use an app to quickly rename your shots or translate them into Human English.
Download link: Under Development

## 图像资产
1. 所有图像资产请务必正确命名及分类
2. 在上传或使用任何图像资产前请务必和全组人沟通
3. 转换图像资产为任意格式后请保留原格式文件

## 设计资产 （.PSD,.Ai,...)
1. 尽量不要rasterize（栅格化）图层
2. 设计资产在导出时确认好分辨率
3. 不要在导出后删除设计资产，请备份
4. logo等更适合矢量化的图像资产请尽量使用Illustrator制作
5. 设计完成后请和全组人讨论
6. Eroducate蓝：```#7ca4ca ```
7. Eroducate粉：```#f5b5e7```
8. 请所有设计务必以上面两个颜色（或任选一，或渐变）为主色调

## 文档资产
1. 请务必沟通好剧本撰写之间的转折并确认剧本的可实现性
2. 请务必使用Eroducate剧本格式法撰写剧本以及科普
3. 在拍摄完成后请务必及时对剧本进行更新

## Eroducate剧本格式法
- 每个act的开头格式：  
Act任意数字 （标题2居中）  
Setting：任意环境设置

- 人物每段话的格式：  
人名 任意动作 （表情和心理描述）：人物说的话

- 选项格式：

请务必注意缩进格式

>选择：
   >>A：任意选项  

   >>B：任意选项

>>A：  
任意剧情
>>B：  
任意剧情  
选择：
>>> A：任意选项  
>>> B：任意选项  
>>> A:  
>>> 任意剧情  
>>> B:  
>>> 任意剧情

## Flowchart
请一定要在拍摄完每一集后根据剧本制作相对应的flow chart，方便对照
参考 flow chart：https://www.processon.com/view/link/5e38f963e4b03ae34a31aaba
