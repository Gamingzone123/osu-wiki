---
no_native_review: true
---

# osu!catch ranking criteria

***注意: 这个文件是[通用 Ranking Criteria](/wiki/Ranking_Criteria)的扩展。***

为了使 [osu!catch](/wiki/Game_mode/osu!catch) 特定模式的[谱面](/wiki/Beatmap)通过[谱面 Ranking 程序](/wiki/Beatmap_ranking_procedure)，则必须遵守 **osu!catch Ranking Criteria** 内列出的[规定和准则](/wiki/Ranking_Criteria#general-terms)。

## 全局

全局规定和准则适用于所有种类的 osu!catch 难度。与节奏相关的规定和准则适用于歌曲为 4/4 拍，约 180 BPM 的谱面。如果歌曲明显快于或慢于 180 BPM，某些规则内限制的指标会不一样。更详细的说明请参考：[缩放 BPM](/wiki/Ranking_Criteria/Scaling_BPM)

### 常规

#### 规定

- **你的谱面必须理论上可以 SS。** 这意味着必须可以完全接住所有[水果/大果](/wiki/Hit_object/Fruit)、[水滴/中果](/wiki/Hit_object/Juice_stream#drop)、[小水滴/小果](/wiki/Hit_object/Juice_stream#droplet)。
- **除非强制使用默认皮肤，谱面必须设置至少两种不同的自定义 [combo 颜色](/wiki/Beatmapping/Combo_colour)。** 任何情况下，combo 颜色组不能与谱面的背景图片、故事板、背景视频相混淆。这保证了玩家能看清所有物件，并避免使用了自定义 combo 颜色组的物件不会凑巧与背景元素相混淆。
- **请勿在 hitnormal 音效较弱时使用[键盘音](/wiki/Beatmapping/Hitsound#keysound)。** 如果键盘音与歌曲混淆，此时玩家不能获得足够的反馈。

#### 准则

- **所有圆圈和滑条头都应对齐在歌曲内明显的声音上。** 通常可以放在清晰的打击音处，也可以用于表现持续的声音，放在它前后几乎听不见声音的位置。
- **扩展滑条 (Extended Slider) 的滑条尾应按照歌曲节拍结构对齐。** 推荐使用 1/4、1/8、1/16 节拍细分来贴合直拍 (Straight Beat) 结构的歌曲，使用 1/6、1/12 节拍细分来贴合摇摆拍 (Swing Beat) 结构的歌曲。如果歌曲的节拍类型在特定位置与以上推荐有所不同，则应优先根据歌曲实际情况来贴合。
- **[跳](/wiki/Gameplay/Dash)和[红果跳](/wiki/Gameplay/Hyperdash)的后一个物件不应过于靠近游戏区域的左右边缘。** 盘子有可能因为触碰游戏区域的左右边缘 (x:16 和 x:496) 而被阻挡（俗称撞墙），从而毁坏玩家的手感。
- **确保 [Combo](/wiki/Beatmapping/Combo) 不要过长。** 玩家接到的[水果/大果](/wiki/Hit_object/Fruit)会堆放在盘子中，这可能会阻碍玩家的视线。注意，滑条尾、滑条折返和[转盘](/wiki/Hit_object/Spinner)的[香蕉](/wiki/Hit_object/Banana)也算作“水果”。应该定时地使用新的 Combo 来清空盘子以避免这种情况。
- **尽量在每个难度中都至少使用一个[转盘](/wiki/Hit_object/Spinner)，以使谱面变得多样、排行榜分数有所区分。** 但是如果这首歌的任何位置都不适合放置转盘，也不需要强行放一个。
- **[分数因子 (OD)](/wiki/Beatmapping/Overall_difficulty) 应该与[下落速度 (AR)](/wiki/Beatmapping/Approach_rate) 的值相同。** 这只是个标准化的值。OD 不会影响游戏，也不会影响[转盘](/wiki/Hit_object/Spinner)中[香蕉](/wiki/Hit_object/Banana)的总数，它只会影响谱面的理论最高分数。
  - 在两者的值不相同的情况下，OD 的数值不能超过下一更高难度的 OD 值。
- **[滑条点倍率](/wiki/Beatmapping/Slider_tick_rate)应按歌曲节奏类型来设置。** 举个例子，如果你的歌曲包含了 1/3 节拍细分的段落，那么此时很不适合使用 2 倍或 4 倍滑条点倍率。
- **在谱面的所有难度内需使用相同的滑条点倍率。** 因为它仅仅反映了歌曲的属性，而不是谱面的属性。然而，在低难谱面内也可以使用较低的滑条点倍率来降低对新手玩家的准确度要求，且能让他们能跟上歌曲的节奏。但单纯地通过使用较高的滑条点倍率来提高分数、连击、难度是毫无意义的做法。
- **避免使用亮度小于等于 50 的 [Combo 颜色](/wiki/Beatmapping/Combo_colour)。** 暗色会干扰低背景亮度下[水果/大果](/wiki/Hit_object/Fruit)的读图。
- **避免当处于 kiai 时间时，使用亮度大于等于 220 的 [Combo 颜色](/wiki/Beatmapping/Combo_colour)。** 闪光瞎眼。

### 皮肤

#### 规定

- **必须使用 v2 自定义皮肤格式。** 这能保证所有的皮肤能正确地显示。需要的文件名为：`fruit-catcher-idle.png`、`fruit-catcher-kiai.png`、`fruit-catcher-fail.png`。
- **自定义皮肤内的水果必须包含所有需要的元素，而且需映射为灰度图。** 这确保自定义皮肤元素能清晰可辨。需要的元素已在[皮肤/osu!catch](/wiki/Skinning/osu!catch) 中列出。另外，推荐使用透明的叠加层元素。
- **皮肤元素必须与它们对应的默认皮肤样本大小一致。** 这能使它们正确地反映物件的判定区域，而不会对游玩产生负面影响。当前默认皮肤的[水果/大果](/wiki/Hit_object/Fruit)尺寸为 128x128 像素、[水滴/中果](/wiki/Hit_object/Juice_stream#drop)为 82x103 像素、盘子为 306x320 像素。

#### 准则

- **若要自定义盘子皮肤，则应该在皮肤中额外添加元素 `lighting.png`。** 这个元素默认为 184x184 像素大小。且它可根据所需元素是否可见而选择使用或舍弃。

## 具体难度

具体难度的规定和准则只适用于与它们在文中所列出位置相对应的难度，因此*不是**每个** osu!catch 难度都适用*。与节奏相关的规定和准则适用于歌曲为 4/4 拍，约 180 BPM 的谱面。如果歌曲明显快于或慢于 180 BPM，某些规则内限制的指标会不一样。更详细的说明请参考：[缩放 BPM](/wiki/Ranking_Criteria/Scaling_BPM)

### 难度名

*主页面：[难度命名](/wiki/Ranking_Criteria/Difficulty_naming)*

- ![](/wiki/shared/diff/easy-c.png?20211215) Cup
- ![](/wiki/shared/diff/normal-c.png?20211215) Salad
- ![](/wiki/shared/diff/hard-c.png?20211215) Platter
- ![](/wiki/shared/diff/insane-c.png?20211215) Rain
- ![](/wiki/shared/diff/expert-c.png?20211215) Overdose

### 触发参考时间

| 难度 | 基础白果跳 | 短时白果跳 | 基础红果跳 | 短时红果跳 |
| :-- | :-- | :-- | :-- | :-- |
| **Cup** | - | - | - | - |
| **Salad** | 250 ms 或更长 | 125-249 ms | - | - |
| **Platter** | 125 ms 或更长 | 62-124 ms | 250 ms 或更长 | 125-249 ms |
| **Rain** | 125 ms 或更长 | 62-124 ms | 125 ms 或更长 | 62-124 ms |
| **Overdose** | - | - | - | - |

### ![](/wiki/shared/diff/easy-c.png?20211215) Cup

#### 规定

- **不能使用任何形式的[跳](/wiki/Gameplay/Dash)和[红果跳](/wiki/Gameplay/Hyperdash)。** 这样能保证新手玩家有良好的游戏体验。可以通过“不使用跳键来获得 SS 评价”的方式来测试谱面。
- **物件与转盘前后之间必须至少间隔 250 毫秒，** 这保证玩家能顺利读图。

#### 准则

- **包括滑条尾和滑条折返，[Combo](/wiki/Beatmapping/Combo) 不应该超过 8 个物件。** [转盘](/wiki/Hit_object/Spinner)除外。
- **谱面物件密度应主要由 1/1 节奏组成。** 1/2 或 1/3 节奏应极少使用。

#### 难度设定准则

- [下落速度 (AR)](/wiki/Beatmapping/Approach_rate)、[分数因子 (OD)](/wiki/Beatmapping/Overall_difficulty) 应在 4-6 之间。
- [扣血速度 (HP)](/wiki/Beatmapping/HP_drain_rate) 应在 2-3 之间。
- [物件大小 (CS)](/wiki/Beatmapping/Circle_size) 应在 2-3 之间。

### ![](/wiki/shared/diff/normal-c.png?20211215) Salad

#### 规定

- **不能使用任何[红果跳](/wiki/Gameplay/Hyperdash)。** 这能保证新玩家能从学会处理简单的白果跳开始。
- **[跳](/wiki/Gameplay/Dash)前后的两个物件相隔时间必须长于 125 毫秒（在 240 BPM 的歌曲内约为 1/2）。** 在作图时一般会限制为 180 BPM 下的 1/2。
- **[基础](/wiki/Gameplay/Dash_snapping#basic-snapped)[白果跳](/wiki/Gameplay/Dash)不能连续使用超过 2 次。**
- **[短时](/wiki/Gameplay/Dash_snapping#higher-snapped)[白果跳](/wiki/Gameplay/Dash)之后只能接[走路](/wiki/Gameplay/Walk)排列。**
- **不能使用任何[边缘/极限跳](/wiki/Gameplay/Edge_dash)。** 接这种排列需要玩家拥有极精确的操纵手法，而新手通常都接不住。
- **物件与转盘前后之间必须至少间隔 250 毫秒（在 240 BPM 的歌曲内约为 1/1）。** 这保证玩家能顺利读图。

#### 准则

- **所有水果间的距离应让玩家能清晰分辨应该[走路](/wiki/Gameplay/Walk)还是[跳](/wiki/Gameplay/Dash)。** 这是为了让玩家能轻松读出谱面要跳的位置。
- **不同节奏类型的[基础](/wiki/Gameplay/Dash_snapping#basic-snapped)[白果跳](/wiki/Gameplay/Dash)不应相连。** 如：1/1 白果跳与 1/2 白果跳直接相连。
- **[短时](/wiki/Gameplay/Dash_snapping#higher-snapped)[白果跳](/wiki/Gameplay/Dash)后不应使用[反向](/wiki/Beatmapping/Antiflow)梗。**
- **包括滑条尾和滑条折返，[Combo](/wiki/Beatmapping/Combo) 不应该超过 10 个物件。** [转盘](/wiki/Hit_object/Spinner)除外。
- **谱面物件密度应主要由 1/1 或 1/2 节奏组成。** 1/3 或 1/4 节奏应极少使用。

#### 难度设定准则

- [下落速度 (AR)](/wiki/Beatmapping/Approach_rate)、[分数因子 (OD)](/wiki/Beatmapping/Overall_difficulty) 应在 6-7 之间。
- [扣血速度 (HP)](/wiki/Beatmapping/HP_drain_rate) 应在 3-5 之间。
- [物件大小 (CS)](/wiki/Beatmapping/Circle_size) 应在 2.5-3.5 之间。

### ![](/wiki/shared/diff/hard-c.png?20211215) Platter

#### 规定

- **[基础红果跳](/wiki/Gameplay/Hyperdash)前后的两个物件相隔时间必须长于 125 毫秒（在 240 BPM 的歌曲内约为 1/2）。** 在作图时一般会限制为 180 BPM 下的 1/2。
- **不能在[水滴/中果](/wiki/Hit_object/Juice_stream#drop)和滑条折返上使用任何[红果跳](/wiki/Gameplay/Hyperdash)。** 这种排列需要玩家有较高的控制力和精度，且玩家可能无法读清滑条路径。
- **不同节奏类型的[基础红果跳](/wiki/Gameplay/Hyperdash)不应相连。** 如：1/2 红果跳与 1/4 红果跳直接相连。
- **[基础](/wiki/Gameplay/Dash_snapping#basic-snapped)[红果跳](/wiki/Gameplay/Hyperdash)不能连续使用超过 2 次。**
- **[短时](/wiki/Gameplay/Dash_snapping#higher-snapped)[红果跳](/wiki/Gameplay/Hyperdash)不能与任何形式的[跳](/wiki/Gameplay/Dash)相连。**
- **[跳](/wiki/Gameplay/Dash)前后的两个物件相隔时间必须长于 62 毫秒（在 240 BPM 的歌曲内约为 1/4）。** 在作图时一般会限制为 180 BPM 下的 1/4。
- **[基础](/wiki/Gameplay/Dash_snapping#basic-snapped)[白果跳](/wiki/Gameplay/Dash)不能连续使用超过 4 次。**
- **[短时](/wiki/Gameplay/Dash_snapping#higher-snapped)[白果跳](/wiki/Gameplay/Dash)不能连续使用超过 2 次，且中途不能改变方向。**
- **不能使用任何[边缘/极限跳](/wiki/Gameplay/Edge_dash)。** 接这种排列需要玩家拥有极精确的操纵手法，而经验较少的玩家通常都接不住。
- **物件与转盘开头之间必须至少间隔 125 毫秒（在 240 BPM 的歌曲内约为 1/2）。** 这保证玩家能顺利读图。
- **物件与转盘结尾之间必须至少间隔 250 毫秒（在 240 BPM 的歌曲内约为 1/1）。** 这保证玩家能顺利读图。

#### 准则

- **不应使用超远的[红果跳](/wiki/Gameplay/Hyperdash)。** [基础](/wiki/Gameplay/Dash_snapping#basic-snapped)红果跳推荐限制为[触发距离](/wiki/Glossary/Trigger_distance)的 1.5 倍内，而[短时](/wiki/Gameplay/Dash_snapping#higher-snapped)红果跳推荐限制为[触发距离](/wiki/Glossary/Trigger_distance)的 1.3 倍内。
- **可以在[基础](/wiki/Gameplay/Dash_snapping#basic-snapped)[红果跳](/wiki/Gameplay/Hyperdash)内使用[反向](/wiki/Beatmapping/Antiflow)梗。** 若使用，则后接[走路](/wiki/Gameplay/Walk)的基础红果跳应限制为触发距离的 1.2 倍内，后接[基础](/wiki/Gameplay/Dash_snapping#basic-snapped)[白果跳](/wiki/Gameplay/Dash)的基础红果跳应限制为触发距离的 1.1 倍内。
- **最好不要在[短时](/wiki/Gameplay/Dash_snapping#higher-snapped)[红果跳](/wiki/Gameplay/Hyperdash)后使用[反向](/wiki/Beatmapping/Antiflow)梗。** 若使用，则它应限制为[触发距离](/wiki/Glossary/Trigger_distance)的 1.1 倍。
- **包括滑条尾和滑条折返，[Combo](/wiki/Beatmapping/Combo) 不应该超过 12 个物件。** [转盘](/wiki/Hit_object/Spinner)除外。
- **谱面物件密度应主要由 1/2 或 1/3 节奏组成。** 1/4 或 1/6 节奏应极少使用。

#### 难度设定准则

- [下落速度 (AR)](/wiki/Beatmapping/Approach_rate)、[分数因子 (OD)](/wiki/Beatmapping/Overall_difficulty) 应在 7-8.2 之间。
- [扣血速度 (HP)](/wiki/Beatmapping/HP_drain_rate) 应在 4-5 之间。
- [物件大小 (CS)](/wiki/Beatmapping/Circle_size) 应在 3-4 之间。

### ![](/wiki/shared/diff/insane-c.png?20211215) Rain

#### 规定

- **[跳](/wiki/Gameplay/Dash)前后的两个物件相隔时间必须长于 62 毫秒（在 240 BPM 的歌曲内约为 1/4）。** 在作图时一般会限制为 180 BPM 下的 1/4。
- **[基础](/wiki/Gameplay/Dash_snapping#basic-snapped)[红果跳](/wiki/Gameplay/Hyperdash)不能连续使用超过 4 次。**
- **当使用滑条头尾作为[基础](/wiki/Gameplay/Dash_snapping#basic-snapped)[红果跳](/wiki/Gameplay/Hyperdash)时，则不能连续使用超过 2 次。** 滑条路径必须简单且易于跟随。
- **[短时](/wiki/Gameplay/Dash_snapping#higher-snapped)[红果跳](/wiki/Gameplay/Hyperdash)不能与[短时](/wiki/Gameplay/Dash_snapping#higher-snapped)[白果跳](/wiki/Gameplay/Dash)和任何形式的[红果跳](/wiki/Gameplay/Hyperdash)相连。** 短时红果跳只能与走路或基础白果跳相连。
- **不能使用滑条头尾作为[短时](/wiki/Gameplay/Dash_snapping#higher-snapped)[红果跳](/wiki/Gameplay/Hyperdash)。**
- **物件与转盘前后之间必须至少间隔 125 毫秒（在 240 BPM 的歌曲内约为 1/2）。** 这保证玩家能顺利读图。

#### 准则

- **不应在[水滴/中果](/wiki/Hit_object/Juice_stream#drop)和滑条折返上使用任何[红果跳](/wiki/Gameplay/Hyperdash)。**
- **不同节奏类型的[基础红果跳](/wiki/Gameplay/Hyperdash)不应相连。** 如：1/1 红果跳与 1/2 红果跳直接相连。
- **若在[短时](/wiki/Gameplay/Dash_snapping#higher-snapped)[红果跳](/wiki/Gameplay/Hyperdash)后使用[反向](/wiki/Beatmapping/Antiflow)[跳](/wiki/Gameplay/Dash)，则反向跳应长于 250 毫秒（在 240 BPM 的歌曲内约为 1/1）。
- **[边缘/极限跳](/wiki/Gameplay/Edge_dash)只能独立使用（与其他任何[跳](/wiki/Gameplay/Dash)都不相连）。**
- **包括滑条尾和滑条折返，[Combo](/wiki/Beatmapping/Combo) 不应该超过 16 个物件。** [转盘](/wiki/Hit_object/Spinner)除外。
- **谱面物件密度应主要由 1/2 搭配 1/4，或 1/3 搭配 1/6 节奏组成。** 1/8 或者更密的节奏应极少使用。

#### 难度设定准则

- [下落速度 (AR)](/wiki/Beatmapping/Approach_rate)、[分数因子 (OD)](/wiki/Beatmapping/Overall_difficulty) 应在 7-9 之间。
- [扣血速度 (HP)](/wiki/Beatmapping/HP_drain_rate) 应在 5-6 之间。
- [物件大小 (CS)](/wiki/Beatmapping/Circle_size) 应在 3-5 之间。

### ![](/wiki/shared/diff/expert-c.png?20211215) Overdose

#### 规定

- **物件与转盘开头之间必须至少间隔 62 毫秒（在 240 BPM 的歌曲内约为 1/4）。** 这保证玩家能顺利读图。
- **物件与转盘结尾之间必须至少间隔 125 毫秒（在 240 BPM 的歌曲内约为 1/2）。** 这保证玩家能顺利读图。

#### 准则

- **只应在滑条路径必须简单且易于跟随时，在[水滴/中果](/wiki/Hit_object/Juice_stream#drop)和滑条折返上使用[红果跳](/wiki/Gameplay/Hyperdash)。** 这避免了谱面不会出现过于混乱复杂的滑条排列。过于混乱复杂的滑条形状所产生的水滴、折返红果跳的游玩体验通常不佳，而且很毁准确率，收益极低。
- **不应连续使用比 1/8 更密的[红果跳](/wiki/Gameplay/Hyperdash)。**
- **[边缘/极限跳](/wiki/Gameplay/Edge_dash)不能连续使用超过 3 个物件（2 次），也不应在[红果跳](/wiki/Gameplay/Hyperdash)之后使用。**
- **包括滑条尾和滑条折返，[Combo](/wiki/Beatmapping/Combo) 不应该超过 16 个物件。** [转盘](/wiki/Hit_object/Spinner)除外。
- **谱面物件密度应主要由 1/2 搭配 1/4，或 1/3 搭配 1/6 节奏组成。** 1/8 或者更密的节奏应极少使用。

#### 难度设定准则

- [下落速度 (AR)](/wiki/Beatmapping/Approach_rate)、[分数因子 (OD)](/wiki/Beatmapping/Overall_difficulty) 应在 8-10 之间。
- [扣血速度 (HP)](/wiki/Beatmapping/HP_drain_rate) 应在 6-7 之间。
- [物件大小 (CS)](/wiki/Beatmapping/Circle_size) 应在 3-6 之间。
