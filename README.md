# Learning_Ubunt

# Ubuntu 命令大全
 
- 查看隐藏的文件夹，以.vim为例，这个.表示是隐藏的文件件。按ctrl+h即可查看隐藏的文件夹。


# 安装软件

- 安装中文输入法

  若没有安装iBus框架，可以自己安装IBus框架，在终端输入以下命令   
  sudo apt-get install ibus ibus-clutter ibus-gtk ibus-gtk3 ibus-qt4     
  启动IBus框架，在终端输入：    
  im-switch -s ibus    
  Sun拼音输入法：   
  sudo apt-get install ibus-sunpinyin      
  谷歌拼音输入法：  
  sudo apt-get install ibus-googlepiny  
  ibus-setup  
  打开IBus 设置，在输入法选项卡下的自定义活动输入法中，选择谷歌拼音输入法即可。  
  通常情况下，IBus图标（一个小键盘）会出现在桌面右上角的任务栏中。有时候这个图标会自行消失，可使用以下命令，找回消   失的IBus图  
  ibus-daemon -drx  

- 安装texlive

  suto apt-get install texlive-full
  
- 安装sublime text

  sudo add-apt-repository ppa:webupd8team/sublime-text-2   
  sudo apt-get update  
  sudo apt-get install sublime-text 
