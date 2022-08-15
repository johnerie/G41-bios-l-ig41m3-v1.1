# G41 bios l-ig41m3-v1.1
版本5VKT15A，推荐主板BIOS为5VKT-XX-A的机器升级。

测试支持E8500、Q9550S处理器、三星双面颗粒4G 1333内存条*2（8G）。

理论支持775平台E系列、Q系列CPU，理论支持DDR3 1066-1600 4G 双面颗粒内存条，理论整机最大可扩展至8G内存。

注意！！！！由于BIOS的版本或者在升级过程中出错，可能会造成不可恢复的后果。本文的升级过程仅供您参考，因为无法确定您操作的正确性，强烈建议，BIOS的升级工作由计算机专业技术人员来完成。如果自行升级，电池必须为满电，连接好电源适配器，不要在任何情况下断电或重新启动系统，这样做将严重损害您的系统。请提前备份电脑中所有的数据至U盘或移动硬盘。

主板型号：l-ig41m3-v1.1 （型号必须完全一致，且只支持该型号主板）

环境要求：winxp-win10 32/64 或 MS-DOS7.10

软件：
     win环境：AMIDEWIN、AFUWIN
     Dos环境：AMIDEDOS、AFUDOS
     
     可选：MS-DOS7.10.iso、DiskGenius、UltraISO

     
 食用方法：
     
     注意！！！首先请在win平台使用AFUWINGUI应用程序备份您的出厂BIOS为.ROM文件并妥善保存，以便必要时候恢复您的出厂BIOS。
     
     如果需要保留原机机型、序列号，推荐使用DOS环境安装。win环境安装可能出现开机丢失序列号报错。
     
     DOS：
        !!!!请再次确认您已备份您的出厂BIOS为.ROM文件，并妥善保存在安全的存储介质内 ->
        使用Ul将DOS系统安装到移动介质,将AMIDEDOS、AFUDOS、ROM放入移动介质根目录下->
        开机选择引导介质->
        启动DOS->
        输入:amidedos /all ->
        记录序列号信息 ->
        输入:(MB)自动刷入或(afudos.exe XXXXXX.ROM /p /b)手动刷入 ->
        重启->
        开机选择引导介质->
        启动DOS->
        输入：amidedos ->
        输入：amidedos  /all ->
        根据命令提示刷入相应的序列号 ->
        重启完成
        
      WIN:
          !!!!请再次确认您已备份您的出厂BIOS为.ROM文件，并妥善保存在安全的存储介质内。
          AFUWINGUI图形化界面操作，备份出厂BIOS，刷入新BIOS。
          AMIDEWIN恢复序列号（该操作在某些机器可能报d7/d8错误，请使用AMIDEDOS在DOS环境下恢复序列号）。
  
 
 注意事项：
 
      1.务必在WIN环境下使用AFUWINGUI备份您的出厂BIOS为xxx.ROM文件。
      
      2.请自行辨别上述方法以及文件是否适用于您的计算机和主板，使用上述方法刷机以及由此产生的任何后果由具体使用者承担。
  
  
  写在最后：
      老机器升级不易，且行且珍惜。机器原厂自带Bios不支持4G单条内存，Bios文件杂乱又难找，折腾了快一星期，刷了十几款Bios才找到适合的。 家悦E35xx系列的原始Bios型号开头对的上的应该可以完美使用，其他机器主板型号完全一致的刷上应该也没问题。有保留序列号和机器型号的强迫症患者可以去DOS模式刷上去。有什么问题欢迎Issues交流，所需文件自取。
  
        
