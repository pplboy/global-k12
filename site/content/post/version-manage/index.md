---
title: "版本号规范"
date: 2019-01-04T15:04:10.000Z
description: 版本号规范
image: 
---

语义化版本号
project-name v0.0.0-beta
项目名 
第一个0 不兼容版本 对应.
第二个0 兼容下的功能升级 对应分支中的功能特性 branch
第三个0 bug修复. 对应bug 以及 hot fix分支

alpha : 是内部测试版,一般不向外部发布,会有很多Bug.一般只有测试人员使用。
beta : 也是测试版，这个阶段的版本会一直加入新的功能。在Alpha版之后推出。&nbsp;
rc : (Release　Candidate) 候选版本。系统平台上就是发行候选版本。RC版不会再加入新的功能了，主要着重于除错。
ga : Gamma - 
在很多软件下载的时候，你会发觉标识为GA或者CRx等。比如MySQL和JBoss都采用这种标识。那什么是GA呢。GA是Generally Available的缩写，意思是开发团队认为该版本是稳定版（有的软件可能会标识为stable版或者production版，其意思和GA相同），可以在较为关键的场合使用。 
　　如果你是要用在生产中的软件，或者你是一个新手，那么你最好选用GA版本。这是测试最为充分，最为稳定的版本。



----------------
Alpha： 


是内部测试版,一般不向外部发布,会有很多Bug.一般只有测试人员使用。 




Beta： 


也是测试版，这个阶段的版本会一直加入新的功能。在Alpha版之后推出。 




RC：(Release　Candidate) 


顾名思义么 ! 用在软件上就是候选版本。系统平台上就是发行候选版本。RC版不会再加入新的功能了，主要着重于除错。 




RTM：(Release to Manufacture) 


是给工厂大量压片的版本，内容跟正式版是一样的，不过RTM版也有出限制、评估版的。但是和正式版本的主要程序代码都是一样的。 




OEM： 
是给计算机厂商随着计算机贩卖的，也就是随机版。只能随机器出货，不能零售。只能全新安装，不能从旧有操作系统升级。包装不像零售版精美，通常只有一面CD和说明书(授权书)。 




RVL： 
号称是正式版，其实RVL根本不是版本的名称。它是中文版/英文版文档破解出来的。 




EVAL： 
而流通在网络上的EVAL版，与“评估版”类似，功能上和零售版没有区别。 




RTL：Retail(零售版) 
是真正的正式版，正式上架零售版。在安装盘的i386文件夹里有一个eula.txt，最后有一行EULAID，就是你的版本。比如简体中文正式版是EULAID:WX.4_PRO_RTL_CN，繁体中文正式版是WX.4_PRO_RTL_TW。其中：如果是WX.开头是正式版，WB.开头是测试版。_PRE，代表家庭版；_PRO，代表专业版。 
---------------------------------------------------------------------------------------------------------------------------------------- 


V（Version）：即版本，通常用数字表示版本号。(如:EVEREST　Ultimate　v4.20.1188　Beta　) 
Build：用数字或日期标示版本号的一种方式。(如:VeryCD　eMule　v0.48a　Build　071112) 
SP：Service　Pack，升级包。(如:Windows　XP　SP　2/Vista　SP　1) 


授权和功能划分： 
Trial：试用版，通常都有时间限制，有些试用版软件还在功能上做了一定的限制。可注册或购买成为正式版 
Unregistered：未注册版，通常没有时间限制，在功能上相对于正式版做了一定的限制。可注册或购买成为正式版。 
Demo：演示版，仅仅集成了正式版中的几个功能，不能升级成正式版。 
Lite：精简版。 
Full　version：完整版，属于正式版。 


语言划分： 
SC：Simplified　Chinese简体中文版。 
CN　：　简体中文版 
GBK：简体中文汉字内码扩展规范版。 
TC：Traditional　Chinese繁体中文版。 
CHT　：　繁体中文版 
BIG5：繁体中文大五码版。 
EN　：　英文版 
Multilanguage　：　多语言版 
UTF8：Unicode　Transformation　Format　8　bit，对现有的中文系统不是好的解决方案。 






开发阶段划分： 
α（Alpha）版：内测版，内部交流或者专业测试人员测试用。Bug较多，普通用户最好不要安装。 
β（Beta）版：公测版，专业爱好者大规模测试用，存在一些缺陷，该版本也不适合一般用户安装。 
γ（Gamma）版：相当成熟的测试版，与即将发行的正式版相差无几。 
RC版：Release　Candidate。 
RC　版。是　Release　Candidate　的缩写，意思是发布倒计时，候选版本，处于Gamma阶段，该版本已经完成全部功能并清除大部分的BUG。到了这个阶段只会除BUG，不会对软件做任何大的更改。从Alpha到Beta再到Gamma是改进的先后关系，但RC1、RC2往往是取舍关系。 
Final：正式版。 


其他版本 
Enhance　：增强版或者加强版　属于正式版1 
Free　：自由版 
Release　：发行版　有时间限制 
Upgrade　：升级版 
Retail　　：零售版 
Cardware　：属共享软件的一种，只要给作者回复一封电邮或明信片即可。（有的作者并由此提供注册码等），目前这种形式已不多见。/　S 
Plus　：属增强版，不过这种大部分是在程序界面及多媒体功能上增强。 
Preview　：预览版 
Corporation　&　Enterprise　：企业版 
Standard　：标准版 
Mini　：迷你版也叫精简版只有最基本的功能 
Premium　：　贵价版 
Professional　：　专业版 
Express　：　特别版 
Deluxe　：　豪华版 
Regged　：　已注册版 


Rip　：是指从原版文件（一般是指光盘或光盘镜像文件）直接将有用的内容（核心内容）分离出来，剔除无用的文档，例如PDF说明文件啊，视频演示啊之类的东西，也可以算做是精简版吧…但主要内容功能是一点也不能缺少的！另：DVDrip是指将视频和音频直接从DVD光盘里以文件方式分离出来。 






RTM　版　：这基本就是最终的版本，英文是　Release　To　Manufactur，意思是发布到生产商。 
Original　Equipment　Manufacturer　(OEM)　 
You　may　license　products　through　an　Original　Equipment　Manufacturer　(OEM).　These　products,　such　as　Windows　operating　systems,　come　installed　when　you　purchase　a　new　computer.　 
OEM软件是给电脑生产厂的版本，无需多说。　 


Full　Packaged　Product　(FPP)/Retail　 
Physical,　shrink-wrapped　boxes　of　licensed　product　that　can　be　purchased　in　a　local　retail　store　or　any　local　software　retailer.　 
FPP就是零售版（盒装软件），这种产品的光盘的卷标都带有"FPP"字样，比如英文WXP　Pro的FPP版本的光盘卷标就是WXPFPP_EN，其中WX表示是Windows　XP，P是Professional（H是Home），FPP表明是零售版本，EN是表明是英语。获得途径除了在商店购买之外，某些MSDN用户也可以得到。 
Volume　Licensing　for　Organizations　(VLO)　 
You　may　enjoy　potentially　significant　savings　by　acquiring　multiple　product　licenses.　Depending　on　the　size　and　type　of　your　organization.　 
团体批量许可证（大量采购授权合约），这是为团体购买而制定的一种优惠方式。这种产品的光盘的卷标都带有"VOL"字样，取"Volume"前3个字母，以表明是批量，比如英文WXP　Pro的VOL版本的光盘卷标就是WXPVOL_EN，其中WX表示是Windows　XP，P是Professional（VOL没有Home版本），VOL表明是团体批量许可证版本，EN是表明是英语。获得途径主要是集团购买，某些MSDN用户也可以得到。 
---------------------------------------------------------------------------------------------------------------------------------------- 


在很多软件下载的时候，你会发觉标识为GA或者CRx等。比如MySQL和JBoss都采用这种标识。那什么是GA呢。GA是Generally Available的缩写，意思是开发团队认为该版本是稳定版（有的软件可能会标识为stable版或者production版，其意思和GA相同），可以在较为关键的场合使用。 
　　如果你是要用在生产中的软件，或者你是一个新手，那么你最好选用GA版本。这是测试最为充分，最为稳定的版本。