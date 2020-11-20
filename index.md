## Welcome to GitHub Pages
一、基本概念
　　1.1 必须了解的概念
  
　　（1）仓库 - Repository

　　仓库即你的项目，你想在GitHub上开源一个项目，那就必须要新建一个Repository。如果你开源的项目有多个，那么你就有多个Repositories。

　　（2）收藏 - Star

　　收藏项目，方便下次查看。如果你的项目被收藏的次数越多，那么你的项目也就越受广大开发者的欢迎咯。

　　（3）复制克隆项目 - Fork

　　如果你开源了一个项目，别人想在你这个项目的基础之上做些改进，然后应用到自己的项目中，这时他就可以Fork你的项目，然后他的GitHub主页上就多了一个项目，只不过这个项目是基于你的项目为基础（本质上是在你的项目基础之上建立了一个分支Branch）。Fork之后，他就可以随心所欲地去改进，但是丝毫不会影响原有项目的代码与结构。

　　（4）发起请求 - Pull Request

　　如果别人在你的项目基础之上做了一些改进，并且觉得改得很不错，应该要把这些改进让更多的人受益。于是，他就想把自己的改进合并进原有项目之中，这时他就可以发起一个Pull Request。而原有项目创建人也就是你，可以收到这个请求，这个时候你可能会仔细review他的代码，并且测试后觉得OK，就可以接受他的Pull Request，之后他做的改进就可以融入到原有项目之中了。

　　（5）关注 - Watch

　　类似于微博中的关注，如果你Watch了某个项目，那么以后只要这个项目有任何更新，你都会第一时间收到关于这个项目的通知提醒。

　　（6）事务卡片 - Issue

　　你开源了一个项目，别人发现你的项目中有bug，或者哪些地方做的不够好，他就可以给你提一个Issue（即问题）。你如果看到了这些Issue，就可以逐个去Fix修复，修复OK之后就可以一个一个地Close掉。

　　（7）GitHub主页

　　如果你注册了一个GitHub账号，那么久会有一个属于你的GitHub主页，该页面左侧主要显示用户动态以及关注用户/仓库的动态，右侧则显示所有的Git库。

　　（8）仓库主页

　　仓库主页主要显示项目的信息，如：项目代码、版本、收藏/关注/Fork情况 等等。

　　（9）个人主页

　　个人信息：头像、个人简介、关注我的人，我关注的人，我关注的Git库，我的开源项目，我贡献的开源项目信息 等等。


1.2 必须完成的准备
　　要使用GitHub，首先必须得注册一个GitHub账号啦！

　　注册过程很easy，就跟你平时注册小网站会员一样，详细信息可以浏览：点此了解注册详情

　　需要注意的地方就是，选择Free免费账号完成设置！那么收费的跟免费的有什么区别呢？私有的仓库只有自己或者指定的朋友才有权限操作。



　　注册完成之后，记住要验证邮箱！如果未验证邮箱，那么你是没法做后续操作的。



二、GitHub基本操作


　　2.1 创建仓库
　　在GitHub中点击New repository活着Start a Project即可：



　　现在我新建一个仓库，这个仓库假设是我写的一个数据结构的实例程序Demo程序库：

　　Step1.填写必要信息：



　　Step2.浏览仓库主页



　　2.2 创建文件
　　在刚刚的仓库主页中点击 Create new file 按钮，即可进入新文件页面：

　　Step1.填写必要信息之文件信息



　　Step2.填写必要信息之记录信息



　　Step3.浏览提交文件记录



　　Step4.浏览具体文件信息



　　2.3 编辑文件
　　在指定的文件名处直接点击文件名链接，即可进入编辑界面：

　　Step1.点击文件名：



　　Step2.修改文件信息



　　假如我们要加入一行文本信息：

　　继续填写提交记录日志信息：



　　Step3.浏览修改后的文件



　　2.4 删除文件
　　在指定的文件名处直接点击文件名链接，即可进入文件信息界面，点击删除按钮：

　　Step1.点击删除按钮



　　Step2.填写日志记录并点击Commit Changes



　　Step3.删除的文件不会出现在项目结构中，只能通过提交日志记录查看：



　　

　　2.5 上传文件
　　在仓库主页点击Upload files按钮进入上传页面，选择要上传的文件，点击上传即可。注意：这里可以一次性上传多个文件。



　　2.6 搜索仓库文件
　　在仓库主页点击Find file按钮，即可进入搜索页面：



　　假如我要搜索log，由于项目中没有log文件，所以没有搜索结果：



　　2.7 下载/检出项目
　　在仓库主页点击Clone or download按钮，即可弹出下载提示框：



　　2.8 GitHub Issues
　　假如张三发现了李四的开源项目中存在一个bug，那么张三就可以为这个项目新建一个issue，我们可以把它理解为项目的问题列表，参与这个项目的开发者们可以在问题列表中进行交流：

　　Step1.新建Issue



　　Step2.填写Issue信息，告知项目开发者



　　Step3.修复完成之后，可以回复Issue信息，告知提问者该Issue已修复



　　Step4.一般来说会由提问者来Close这个Issue，当然也可以由项目拥有者来Close。



　　

　　2.9 Fork 复制克隆一个开源项目
　　假设我最近对StackExchange.Redis这个开源客户端项目很感兴趣，那么我可以Fork一下，看看有什么可以学习有什么可以优化的，我只需要点击Fork按钮，即可一秒建立一个Branch：



　　克隆之后，你的主页会多一个project，并且会注明forked from StackExchange.Redis



　　如果你在修改完善了部分代码之后觉得你想把你的change融入到原有项目之中，让更多的人受益，那么你可以发起一个Pull Request：



　　点击之后，会显示所有你的修改，相当于你在提交之前review一下你的修改记录，这里我啥也没改，所以显示 There isn’t anything to compare.



　　当你commit你的change之后，原有项目的所有者就会在他的GitHub主页看到谁谁谁提交了他的代码，并会看到你的comment。



　　这时，他就可以看到你做的文件修改，并选择review你的代码，最后决定是否merge到他的原有项目之中。
  
  三、Git基本操作


　　3.1 安装Git
　　可以去官网选择下载，这里使用的是Git-2.9.0 64位版本：点我下载

　　全程傻瓜化安装，下一步即可，可以把命令模式和图形界面模式都勾选上。



　　3.2 Git基本流程


　　3.3 Git初始化操作及仓库管理
　　这里我们主要采用命令行模式，这也是Linux服务器的精髓所在，图形模式很easy，看看就会了。

　　（1）设置基本信息

-- 设置用户名

git config --global user.name 'zhangsan'

-- 设置账户邮箱

git config --global user.email 'zhangsan@qq.com'　　

　　新建一个文件夹作为你的Git Workspace，然后打开Git Bash命令行界面：



　　（2）初始化一个新的Git仓库

　　Step1.创建一个仓库文件夹，这里取名跟刚刚在GitHub里面一样的DataStructure.Demo.CSharp

　　Step2.在文件内初始化Git（创建Git仓库）

--初始化

git init



　　（3）向仓库中添加文件

　　假设我们写了一个MyArrayStack类，我们把他copy到该文件夹中，使用以下命令加入到暂存区中：

git add MyArrayStack.cs



　　然后我们需要将暂存区文件添加到仓库：

git commit -m 'add MyArrayStack.cs'


　　这时我们再通过git status查看，你会发现已经没有什么文件更改或要提交的文件了。

　　（4）修改文件

　　当你修改了文件之后，通过git status可以查看到你修改了什么东西，同样还是要经历提交到暂存区再提交到仓库的步骤，此处不再赘述。

　　（5）删除文件

　　当你不再想要某个代码文件时，你可以通过git rm filename的命令删除文件：

git rm MyArrayStack.cs



　　3.4 使用Git管理远程仓库
　　我们刚刚提到Git的基本流程是工作区到暂存区再到Git仓库，那么Git仓库和远程仓库又是如何联系起来的呢？



　　（1）Git克隆操作：将远程仓库复制到本地

git clone https://github.com/edisonchou/DataStructure.Demo.CSharp　　





　　（2）修改代码，按照老步骤提交到Git仓库

　　这里因为原始项目是啥也没有，所以我索性把我之前写的一个数据结构的Demo程序库直接拖动到了这个文件夹中。

-- 添加所有文件

git add --all　

git status

git commit -m 'add solution code'　



　　这时我们已经提交到了git仓库，需要同步到github远程仓库了：

git push

-- 后面可能会要求你输入账号和密码



　　这时我们再次进入GitHub主页，可以看到我们的项目已经有刚刚同步的代码了：



　　PS：如果出现git push错误，提示The requested URL returned error : 403 Forbidden while accessing.你可以输入用户名密码或者远程地址采用这种类型（vi.git/config）

　　将[remote "orgin"] url=https://github.com/用户名/仓库名.git

　　改为[remote "orgin"] url=https://github.com/用户名:密码@github.com/用户名/仓库名.git

四、GitHub Pages搭建网站
　　4.1 个人站点
　　GitHub要求个人站点的仓库名称必须是 用户名.github.io, 例如edisonchou.github.io

　　建立方法很简单，也是新建一个repository，然后填写你的个人站点名，例如 edisonchou.github.io。之后通过Git，你可以将你在本地开发的html网页同步到github，之后你就可以通过域名访问你的个人站点啦！



　　发布之后的个人站点如下：



　　4.2 项目站点
　　搭建后的访问域名为：https://用户名.github.io/仓库名

　　（1）进入项目主页，点击Settings

　　（2）在Settings页面，点击Launch automatic page generator来自动生成主题页面

　　（3）新建站点基础信息设置

　　（4）选择主题

　　（5）生成网页
