# toolchain-release为Overwatch模型提取

为 Overwatch 中的模型语音贴图特效动作进行提取，由yretenai提供代码siyu196重新整合，让提取变得更简单。

#### 下载与部署方法

1.下载 toolchain-release。
#### 下载地址: [toolchain-release](https://codeload.github.com/siyu196/toolchain-release/zip/refs/heads/main)
#### 
1. 把下载得ZIP文件解压至文件夹。
1. 点击进入解压好的文件夹里，单击上方的文件目录，输入CMD。按Enter键，出现命令窗口例如"D:\OW\toolchain-release>"即可成功。
2. 输入命令
##
datatool D:\bxyx\Overwatch extract-unlocks "E:\Output path" Mercy
</br>
## 注意
D:\bxyx\Overwatch"是你的游戏目录.
</br>
E:\Output path"是你的文件保存目录.
</br>
Mercy是你的准备要提取英雄的名字
</br>
#### 地图提取
4. 同理，将extract-unlocks替换成extract-maps。把名字改为你所需要的地图名称即可，中英支持。
</br> 
datatool D:\bxyx\Overwatch extract-maps "E:\Output path" 国王大道 
</br> 

## 守望先锋中英文对照表
- **ROLE 角色类型**
  - **OFFENSE HEROES 突击型英雄**
    - Doomfist 末日铁拳
    - Genji 源氏
    - McCree 麦克雷
    - Pharah 法老之鹰
    - Reaper 死神
    - Soldier: 76 士兵76
    - Sombra 黑影
    - Tracer 猎空
    - Bastion 堡垒
    - Hanzo 半藏
    - Junkrat 狂鼠
    - Mei 小美
    - Torbjörn 托比昂
    - Widowmaker 黑百合

  - **TANK HEROES 重装型英雄**
    - D.Va D.Va
    - Orisa 奥丽莎
    - Reinhardt 莱因哈特
    - Roadhog 路霸
    - Winston 温斯顿
    - Zarya 查丽娅

  - **OFFENSE HEROES 突击型英雄**
    - Brigitte 布丽吉塔
    - Ana 安娜
    - Lúcio 卢西奥
    - Mercy 天使
    - Moira 莫伊拉
    - Symmetra 秩序之光
    - Zenyatta 禅雅塔/

## 守望先锋中英文对照表
- **MAP 地图**
  - **DORADO 多拉多**
  - **EICHENWALDE 艾兴瓦尔德**
  - **HANAMURA 花村**
  - **HOLLYWOOD 好莱坞**
  - **HORIZON LUNAR COLONY 地平线月球基地**
  - **ECOPOINT: ANTARCTICA 生态监测站：南极洲**
  - **JUNKERTOWN 渣客镇**
  - **KING'S ROW 国王大道**
  - **ROUTE 66 66号公路**
  - **TEMPLE OF ANUBIS 阿努比斯神殿**
  - **VOLSKAYA INDUSTRIES 沃斯卡娅工业区**
  - **WATCHPOINT: GIBRALTAR 监测站：直布罗陀**
  - **BLIZZARD WORLD 暴雪世界**
  - **AYUTTHAYA 阿育陀耶**
  - **BLACK FOREST 黑森林**
  - **CASTILLO 城堡**
  - **CHÂTEAU GUILLARD 吉拉德堡**
  - **NECROPOLIS 墓园**
  - **NUMBANI 努巴尼**
  - **ILIOS 伊利奥斯**
    - Lighthouse 灯塔
    - Ruins 废墟
    - Well 深井
  - **LIJIANG TOWER 漓江塔**
    - Control Center 控制中心
    - Garden 庭院
    - Night Market 夜市
  - **NEPAL 尼泊尔**
    - Sanctum 圣坛
    - Shrine 圣所
    - Village 村庄
  - **OASIS 绿洲城**
    - City Center 中心
    - Gardens 花园
    - University 大学
## 更新地址
后续更新地址https://ci.appveyor.com/project/yretenai/OWLib
