zww's JA2 1.13 Packages
============

1.13 + UC1.13 + UC1.13TBS lang zh_CN + ja2_cn.exe（简称：JA2 1.13 + UC1.13 TBS中文汉化版）

注意1：下面列出的 Ja2_Options.INI 选项不要去修改
----
ENABLE_CREPITUS = FALSE
• There were no Crepitus in the original Urban Chaos. The Sci-Fi mode “monster” for the original Urban Chaos was incomplete and involved robots instead of bugs.
• The v1.13 project fixed a bug with Bug Quest randomization, allowing the Crepitus side-quest to be randomized among the mines (instead of just Drassen). This means that the Bug Quest will have unpredictable consequences to the maps and Urban Chaos storyline when using current JA2 v1.13.

USE_EXTERNALIZED_LOADSCREEN = FALSE
• Some sectors will cause the game to crash. This feature is not expected to be implemented in the near future.

SHOW_CAMOUFLAGE_FACES = FALSE
• No plans on adding graphics to allow use of this purely cosmetic feature.

ATTACHMENT_DROP_RATE = 100
• Do not change this or default attachments, such as the Folding Stock System item, will not always be dropped when DROP ALL is disabled.

AIMING_BURST_PENALTY = 1
• The Burst and Auto penalties have already been increased to balance for Aimed Burst/Auto feature.

INITIAL_MERC_ARRIVAL_LOCATION = 14424
• As of 2011 Spring (Closed Beta) this is needed to direct mercs to correct landing grid in A9.


*** The following depends on which UC-1.13 campaign you have selected ***

INDIVIDUAL_CIVILIAN_NAMES = TRUE (zPackage是选用New Maps，所以应该设置为 TRUE)
• Original Urban Chaos uses one civilian group to represent two different “factions” in Danubia, therefore this option should not be changed if your are playing the "Old Maps," vfs_config.UC113OldMaps, campaign.
• The "New Maps," vfs_config.UC113, campaign has separated civilian groups, therefore this option may be changed to TRUE.

注意2：XML Editor的使用
----
如果需要使用 XML Editor，那么需要
1. 把 Data-UC_Graphics 里面的文件复制并覆盖到 Data-UC113
2. 用文本编辑器打开 XMLEditorInit.xml，把 <Data_Directory_1>Data-1.13</Data_Directory_1> 改为 <Data_Directory_1>Data-UC113</Data_Directory_1>