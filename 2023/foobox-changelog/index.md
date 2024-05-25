# foobox 更新日志

<img src="changelog.png" width="325">
{{< admonition success "2024-5-25, 7.27版 + 6.27重制版" >}}
* 优化播放列表视图，修正上次更新发现的一些 bug。
* 博客转移到 https://dream7180.github.io。 
{{< /admonition >}}
{{< admonition example "2024-5-18, 7.26版 + 6.26重制版" >}}
* 右栏小播放列表视图完全重写。
* 用 Jsplitter 的作为分离器，UI 更有整体感。
* 许多优化和 bug 修正。
* foobox 7 64 位版本。
* 32 位 foobox 为基于 7 的 foobox 6 重制版，添加了 UI Hacks，整合了两个版本的特点。
* foobox-video 安装包可选 (对应 6 和 7) 版。  
{{< /admonition >}}
{{< admonition example "2024-4-05, 7.25版" >}}
* 播放列表视图添加点击中键可快速查询鼠标所指的音频的文件信息，shift+中键可添加项目到播放队列。
* 优化暗色风格的高亮变色，简介面板 Biography 小优化，其他代码检修和优化。
* 把视频面板组件和配置 foo-youtube 从 foobox 安装包分离，并加入可选的 foo-mpv 打包为独立的绿色安装包 foobox-video，有需要可一并下载。 
{{< /admonition >}}
{{< admonition example "2024-3-14, 7.24版" >}}
* 优化播放列表管理器及封面浏览器的滚动，确保最顶一栏项目完整显示。
* 安装包不再集成 foobar2000 程序，仅含 foobox 主题及所需第三方组件，绿色安装，自由便捷。 
{{< /admonition >}}
{{< admonition example "2024-3-02, 7.23版" >}}
* 更新 foobar2000 v2.1.2 Asion 汉化版，升级 jsplitter 到 3.6.1.3。 
* 封面浏览器文件夹视图添加媒体库一级目录模式，通过顶栏右上切换按钮切换，顶栏左上视图切换添加单独的文件夹图标。
* 修正已 bugs，优化运行性能，封面浏览器创建智能播放列表更准确。 
{{< /admonition >}}
{{< admonition example "2024-2-25, 7.22版" >}}
* 更新 foobar2000 v2.1.2 Asion 汉化版，修正了一些 bugs。  
* foobox 设置加入“重置电台地址”按钮，如果播放列表管理面板菜单里加载不了电台列表，可以更新版本后重置一下。  
* 修正一些 bugs，更新电台列表地址（更换 github 加速地址）。  
{{< /admonition >}}
{{< admonition example "2024-2-14, 7.21版" >}}
* 更新 foobar2000 v2.1.2 Asion 汉化版。  
* foobox 设置加入播放列表管理面板的电台列表地址管理，并支持多地址，其配置写入 foobox 的 config 文件而不是放在面板属性里。
* 外置音频编辑器设置写入 foobox 的 config 文件而不是放在面板属性里。
* UI优化：喜爱 (mood) 图标换成心形；修正播放列表视图正在播放的曲目在背景太黑时喜爱和等级图标显示不清的问题；音量图标优化。
* 添加电音流派；添加 DFF 和 DSF 两种音频格式的图标。
{{< /admonition >}}
{{< admonition example "2024-1-18, 7.20版" >}}
* (2024-2-01) 升级主程序到 foobar2000 v2.1.2 汉化版及一些组件升级。
* 优化简介面板，解决退出崩溃。
{{< /admonition >}}
{{< admonition example "2024-1-05, 7.19版" >}}
* 升级 ESLyric。
* 优化安装/卸载程序，修正安装包中的多个问题。
* 修正 UI 的一些 bug 及其他优化。
* 简介面板的一些防崩溃修正。  
{{< /admonition >}}
{{< admonition example "2023-12-23, 7.18版" >}}
* 升级到 foobar2000 v2.1 汉化版。
* 升级简介面板 Biography 到 1.4.2。
* 优化播放列表管理器和方面浏览器面板布局，更简洁、整合度更高。
* 一些 bug 修正，优化预设等。
{{< /admonition >}}
{{< admonition example "2023-12-02, 7.17版" >}}
* 修正 bug，例如特殊字符导致不能搜索及创建智能列表出错。
* 修正简介列表导致的崩溃。
* 升级 ESLyric 等组件。
* 整合 foobox 风格文件类型图标。
* 较完善的安装包。
{{< /admonition >}}
{{< admonition example "2023-10-14, 7.16版" >}}
* 去除媒体库面板，改为右下媒体库弹出按钮，可选择打开专辑列表或分面(2.0+).
* 增加可视化面板(声谱+foo_enhanced_spectrum_analyzer).
* 引入对简介面板(Wil-B)、视频面板(foo_youtube 或 foo_mpv)的支持，可在主菜单--视图--布局--快速设置里自由切换组合.
* 修正 bug，精修底部工具栏 UI，升级 ESLyric 组件.
{{< /admonition >}}
{{< admonition example "2023-09-24, 7.15版" >}}
* 改进封面浏览器的缓存机制，大大提升缓存效率，封面缓存建立完成后的使用体验会流畅很多。
* 升级请手动删除原有的 profile\foobox\covercache 下的将作废的缓存文件。
* foobox 设置里添加缓存专辑封面的依据是否区分专辑艺术家的选项，默认不区分以提高性能。
* UI 改进，bug 修正。
* 升级 ESLyric 组件。
{{< /admonition >}}
{{< admonition example "2023-09-05, 7.14版" >}}
* 紧急修正了播放列表布局中的一些bug。
{{< /admonition >}}
{{< admonition example "2023-09-03, 7.13版" >}}
* 修正了布局中列的顺序不能保存的问题。
* 其他小修正和优化。
{{< /admonition >}}
{{< admonition example "2023-08-31, 7.12版" >}}
* 精修底部工具栏播放控制图标。
* 修正了布局删除按钮意外删除默认布局的bug。
* 升级 ESLyric 组件。
{{< /admonition >}}
{{< admonition example "2023-08-15, 7.11版" >}}
* 跟进 foobar2000 2.0 的特性，可以为单独的播放列表保存布局，在播放列表视图分栏标题右键菜单里保存新的布局。
* 布局、自定义分组、自定义列的配置将保存到 foobar2000 用户配置目录下的 foobox 目录下，不用担心升级后配置会被重置。
* 脚本和封面缓存的存放位置都改变了，集中存放到 foobar2000 用户配置目录下的 foobox 目录下，封面缓存自动重建。
* 升级后原有用户配置目录下的 cache 目录和 foobar2000\themes\foobox 脚本目录请手动删除。
* 升级 ESLyric 组件。
* 脚本优化，以及一些 bug 修正。
{{< /admonition >}}
{{< admonition example "2023-06-23, 7.10版" >}}
* 去掉渣音质的蜻蜓FM，集成了高品质的网络电台，仍然在搜索框菜单里载入，感谢 [fanmingming](https://github.com/fanmingming) 维护的电台列表。
* 电台封面下载请到仓库 https://github.com/dream7180/foobox-icons
* 完善了拖放。
* 修正了播放统计信息组件导致封面刷新的bug。
* 修正了光标跟随播放的bug，及其他发现的小bug。
* 升级 Eslyric 的部分脚本
{{< /admonition >}}
{{< admonition example "2023-05-25, 7.9版" >}}
* 加入 foobar2000 2.0 新标签 %year% 的支持（仍支持 1.x 版本）。
* 播放列表视图里添加滚动步长设置。
* 播放工具栏 UI 优化，其中在 foobox 设置里加入是否显示“打开”和“停止”按钮的选项。
* 修正了用户提出的一些 bugs。
{{< /admonition >}}
{{< admonition example "2023-04-05, 7.8版" >}}
* 改善播放列表管理器的UI交互，如播放列表点击右键时。
* 改善方面浏览器按目录分组时的识别规则，以前的封面识别有问题的朋友需重置一下缓存。
* 修正封面浏览器按艺术家-专辑分组时不能以专辑关键词进行屏幕搜索的bug。
* 封面浏览器过滤栏现在可以用title来进行过滤。
* 为设置Musictag路径添加浏览按钮，方便使用。
* 播放和暂停按钮改为实心。
* 播放列表视图添加一个取样率的列。
* 其它bug修正和改良。
{{< /admonition >}}
{{< admonition example "2023-2-08, 7.7版" >}}
* 删除播放列表添加确认窗口，可在选项里取消。
* 载入动画等 UI 元素的优化美化。
* 精简一些不常用的分组参数。
* 文件夹分组封面设置支持多个封面文件名字。
* bug 修正与优化。
{{< /admonition >}}
{{< admonition example "2023-2-08, 7.6版" >}}
修正了几个重要的bug及优化，建议foobox6和7的用户都升级到此最新版。  
**其中封面浏览面板请重置一下缓存，点击该面板顶栏右键菜单->显示->重置磁盘缓存**。
{{< /admonition >}}
{{< admonition warning "2023-1-31, 7.5版" >}}
修正 bug 以及优化一些设置，图标精修；  
右栏封面面板右键菜单添加封面淡入淡出效果的开关；  
播放列表管理器菜单添加过滤栏的开关（默认隐藏过滤栏）；  
增加封面浏览器缓存功能对内嵌封面的支持； 
{{< /admonition >}}
{{< admonition warning "2023-1-17, 7.4版" >}}
修正一些UI及高亮变色的bug并优化细节；  
浅色风格下如果图片颜色太浅则高亮不会跟随变色；  
高亮色不跟随封面变色时可以自定义歌词的高亮色；  
默认恢复播放列表视图的选择菜单。
{{< /admonition >}}
{{< admonition warning "2023-1-13, 7.3版" >}}
修正bug及优化，优化对foobar2000-2.0深色模式的支持，提高搜索栏媒体库搜索的精度，优化蜻蜓FM，完善快捷键等。
{{< /admonition >}}
{{< admonition warning "2023-1-04, 7.2版" >}}  
bug修正和代码优化，面板内容丰富，加入DUI频谱等。
{{< /admonition >}}
{{< admonition warning "2022-12-29, 7.1版" >}}  
改用基于SMP的JSSplitter；UI优化；bug修正及代码进一步改良。
{{< /admonition >}}
{{< admonition warning "2022-12-11, 7.0版" >}}  
改用原生 DUI + 蜘蛛猴面板(SMP)，精简优化, 修正了很多 bug，更省资源更流畅。同时为 foobar2000 2.0版准备。
{{< /admonition >}}

{{< admonition bug "之前的旧版重要节点记录" >}}  
**2022-11-05, 6.6.13 版（6 最后一版）**

**2018-1-20, 6.0版**

**2017-12-16, 5.16版 （5 最后一版）**

**2016-2-21, 5.0版**

**2014-8-18, 4.0版**

**2014-1-11, 3.0版**

**2012-11-28，2.1版 （2.0为测试版）**

**2012-11-16，1.0版**
{{< /admonition >}}