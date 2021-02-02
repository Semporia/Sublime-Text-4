# Sublime text 4


  - 基于 Seti_UI 优化支持 Sublime text 4 的 Drak 主题。
  - 主题方案 Blue
  - 配色方案 Monokai 

# 预览

### HTML
<p align="center">
  <img src="https://raw.githubusercontent.com/Semporia/Sublime-Text-4/master/HTML.png" align="center">
  <br><br>
</p>

### CSS
<p align="center">
  <img src="https://raw.githubusercontent.com/Semporia/Sublime-Text-4/master/CSS.png" align="center">
  <br><br>
</p>

### JavaScript
<p align="center">
  <img src="https://raw.githubusercontent.com/Semporia/Sublime-Text-4/master/JavaScript.png" align="center">
  <br><br>
</p>

### Python
<p align="center">
  <img src="https://raw.githubusercontent.com/Semporia/Sublime-Text-4/master/Python.png" align="center">
  <br><br>
</p>

## 自定义配置

```js
{
  "auto_complete_triggers": [
  {
    "characters": ": ",
    "selector": "source.css",
  }],
  "color_inactive_tabs": true,
  // 配色方案
  "color_scheme": "Packages/Seti_UI/Scheme/Seti Monokai.tmTheme",
  // "theme": "Seti.sublime-theme",
  // 整体界面
  "theme": "Seti Monokai.sublime-theme",
  //
  "folder_no_icon": true,
  // On retina Mac
  "font_options": ["gray_antialias"],
  // 字体
  "font_face": "Menlo",
  // 字体大小
  "font_size": 12.5,
  // 行间距底部
  "line_padding_bottom": 4,
  // 行间距顶部
  "line_padding_top": 4,
  // 文字倾斜
  "font_options": ["no_italic"],
  // 显示行号边栏
  // "gutter": false, 
  // 显示行号
  "line_numbers": true,
  // 高亮当前行
  "highlight_line": true,
  // 显示空白符
  // "draw_white_space": "all",

  // 状态栏显示当前文件编码
  "show_encoding": true,
  // 右侧总是显示代码地图可视区域
  "always_show_minimap_viewport": true,
  // 显示可视区域部分的边框
  // "draw_minimap_border": true, 
  // 左侧边栏文字加粗
  // "bold_folder_labels": true, 
  // 制表位的对齐线
  "indent_guide_options": ["draw_normal", "draw_active"],
  // 记忆之前打开的文件
  "remember_open_files": true,
  // "overlay_scroll_bars": "system",
  // 高分屏必须调整此设置
  "dpi_scale": 1.0,
  // 标题栏显示打开文件的完整路径
  "show_full_path": false,

  // 删除你想要忽略的插件，需要重启
  "ignored_packages": [
    // 是否禁用 vim 模式
    "Vintage"
  ],
  // 自动匹配引号，括号等
  "auto_match_enabled": true,
  // 光标样式
  "caret_style": "smooth", // 光标闪动方式 "smooth", "phase", "blink", "wide" and "solid"
  // "caret_extra_bottom": 1,
  // "caret_extra_top": 1,
  // "caret_extra_width": 1,

  // "mouse_wheel_tabswitch": false,
  // 当前窗口中打开文件
  "open_files_in_new_window": false,
  // Tab键制表符宽度
  "tab_size": 2,
  // 空格代替tab
  "translate_tabs_to_spaces": true,
  // Word wrapping - follow PEP 8 recommendations
  // "rulers": [ 82, 92 ],
  // true | false | auto
  "word_wrap": true,
  // 设置窗口内文字区域的宽度
  // "wrap_width": 200,
  // 禁止自动更新
  "update_check": false,

  // Seti 基本设置
  "Seti_no_blue_bar": true,
  // tab close button ("Seti_accent": false) 关闭标签设置
  "Seti_teal_tabclose": true,
  //选项卡
  //选项卡高度=35
  "Seti_tabs_small": true,
  //=翼片高度40
  "Seti_tabs_med": true,
  //翼片高度“SETI＝45”/“SETI_orig=54” 
  "Seti_tabs_big": true,
  "Seti_tabs_no_min_width": true,
  //选项卡fontsize=12
  "Seti_tab_font_12": true,
  //打开选项卡浏览
  /*"mouse_wheel_tabswitch": false,*/
  //取下L/R箭头、有效(当“使能_tab_滚动”：真)
  "Seti_no_scroll_icons": true,
  //拆下/小彩色条在未保存标签“没有口音”
  "Seti_no_under_bar": true,
  //Make活动选项卡以粗体字体标记
  "Seti_bold_slctdtab_labels": true,
  //使用新的特征标签集(>=3127)
  "Seti_use_system_title_bar": false,

  //选项卡保存（“SETI_*_口音”：假)
  "Seti_seablue_tab": true,
  //选项卡标签
  "Seti_blue_label": true,
  //SCROLLBAR

  //滚动条宽度/高度=6
  "Seti_SB_med": true,
  //滚动条宽度/高度=10
  "Seti_SB_big": false,
  "Seti_blue_scrollbar": false,
  "Seti_seablue_scrollbar": false,

  //边栏
  //图标相同的“打开文件夹”
  "Seti_ClosedFolder_same": false,
  //删除文件夹图标关闭_
  "Seti_ClosedFolder_remove": false,
  //更改文件夹图标以关闭_点
  "Seti_ClosedFolder_dots": false,
  //动画//文件夹图标栏
  "Seti_ClosedFolder_anim": false,
  //问题///（133）
  "Seti_sb_no_icons": false,
  //问题/(133)
  "Seti_sb_blank": false,

  //填充
  //填充条目栏=3
  "Seti_sb_small_padding": false,
  //填充条目栏＝10
  "Seti_sb_big_padding": true,
  //边栏衬垫树=15
  "Seti_sb_tree_med": false,
  //填充树栏＝10
  "Seti_sb_tree_small": true,
  //问题/(88)
  "Seti_sb_tree_tiny": false,
  //问题/(88)
  "Seti_sb_tree_miny": false,
  //Show/箭头组文件夹栏
  "Seti_show_group_arrows": true,

  //标签
  //使文件选择的文本以粗体工具条
  "Seti_bold_slctdfile_labels": false,
  "Seti_sidebar_font_size_12": false,
  "Seti_sidebar_font_size_13": false,
  "Seti_sidebar_font_size_14": false,
  "Seti_sidebar_font_Ubuntu": false,
  "Seti_sidebar_font_Fira": false,
  "Seti_sidebar_font_Hack": false,
  "Seti_sidebar_font_Source": false,
  //标题字体尺寸=12
  "Seti_heading_font_12": true,

  //标题
  //字体加粗制作标题
  "Seti_bold_heading": true,
  //删除”文件夹，组1，等等。”
  "Seti_no_heading": false,
  //IMG大顶侧边栏标题
  "Seti_top_heading_big": true,
  //IMG小顶部侧边栏标题
  "Seti_top_heading_small": true,
  //顶部工具条的悬停动画首部IMG“没有特色”
  "Seti_top_heading_anim": false,
  //替代侧边栏/行亮点
  "Seti_alt_tree_row": false,


  //视图
  //使用padding_LINE_line_bottom/top_padding＝5
  "Seti_pad_5": false,
  //使用padding_LINE_line_bottom/top_padding=3
  "Seti_pad_3": true,
  // 拆下衬垫///从顶部向下快速面板
  "Seti_panel_nrml": false,
  //折叠箭头来改变黑
  "Seti_dark_fold_button": true,
  //映射
  "Seti_seablue_map": true,
  //状态栏
  "Seti_seablue_statusbar": true,
  //标题栏的常规选项
  "Seti_accent": true,
  "Seti_accent_seablue": false,

  //关闭GPU
  "gpu_window_buffer": false,
}
```
