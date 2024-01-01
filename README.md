<div align="center">

[![LOGO](Ink%20Canvas/Resources/InkCanvas.png?raw=true "LOGO")](# "LOGO")

# Ink-Canvas
[Direct Download](https://githubfast.com/WXRIW/Ink-Canvas/releases/latest "Latest Releases") | [User Guide ](https://githubfast.com/WXRIW/Ink-Canvas/blob/master/Manual.md "Instructions and Guide") | [Frequently Asked Questions ](https://githubfast.com/WXRIW/Ink-Canvas#FAQ "FAQ")
  
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FWXRIW%2FInk-Canvas.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FWXRIW%2FInk-Canvas?ref=badge_shield) [![Communication Group](https://img.shields.io/badge/-%E4%BA%A4%E6%B5%81%E7%BE%A4%20891915376-blue?style=flat&logo=TencentQQ)](https://jq.qq.com/?_wv=1027&k=NvlM1Rgg)  ![GitHub issues](https://img.shields.io/github/issues/WXRIW/Ink-Canvas?logo=github)


  
A fantastic Ink Canvas in WPF/C#, with fantastic support for Seewo Boards.


The school switched from traditional projectors to Seewo whiteboards. Developed this whiteboard due to the difficulty of using the pre-installed Seewo software and the lack of similar user-friendly drawing software. 

  [<img src="https://get.microsoft.com/images/en-US%20dark.svg" style="width: 200px;"/>](https://www.microsoft.com/store/apps/9NXJFDD97XJ3?cid=ghreadme)
</div>

## 🔧 Features
Optimized support for Microsoft PowerPoint (strongly not recommended to use WPS, as it may cause WPS to freeze and WPS has poor touch screen support; PPT can be navigated by clicking, not swiping, and cannot be zoomed in or out)
Star1Star1One end of the pen writes with a fine tip, while the other end is an eraser (this function is not supported by Seewo whiteboard)Star1Star1
You can also erase directly with your hand (just like Seewo whiteboard)
Supports Active Pen (pressure sensitivity)
Similar functionality can be provided for other infrared screens; everyone is welcome to test it out!

## ⚠️ Reminder
- Before asking a question, please read the [FAQ](https://githubfast.com/WXRIW/Ink-Canvas#FAQ "FAQ").
- If you encounter a problem, please try to solve it yourself first. If you are unable to solve it, please briefly describe the difference between your expectations and reality. If necessary, please provide the steps to reproduce the issue or error logs¹ (with appropriate screenshots), and wait for a reply.
- Valid opinions and reasonable suggestions for new features will be replied to and considered by the developers. Ink Canvas is not a commercial software, so please refrain from rushing the developers. Patience will help make the software have fewer bugs and more stability.

> Waiting is a form of wisdom.

[1]: For long texts, you can use an online clipboard (such as https://pastes.dev/). After pasting, click "`SAVE`" and then copy the link for sharing.

## 📗 FAQ
### How to fix partially displayed icons as "□" in systems below Windows 10?
[Click to download](https://aka.ms/SegoeFonts "SegoeFonts") SegoeFonts file, install the `SegMDL2.ttf` font from the compressed package, and then restart to resolve the issue.

### Why does the program crash after clicking on "Play" and flipping one page?
It may be due to unactivated `Microsoft Office`. Please activate it manually.

### Why doesn't the drawing board program switch to PPT mode after playing?
If you have previously installed `WPS` and encountered this issue after uninstallation, it may be caused by an unresolved problem. You can try reinstalling WPS.
> "Hello, we have received your feedback and forwarded it to our technical team for further analysis. Please pay attention to future updates of WPS." - Reply from WPS Customer Support

Additionally, PPT files in protected (read-only) mode will not be recognized.

### Why can't I launch the Star1Star1 program after installation?
Please check if `.Net Framework 4.7.2` or a higher version is installed on your computer. If not, please download it from the official website.
If the issue persists, check if `Microsoft Office` is installed on your computer. If not, please install it and try again.

### Where should I submit feature requests and error reports?

1. GitHub Issues

    Feature request: https://githubfast.com/WXRIW/Ink-Canvas/labels/enhancement/new 

    Error report: https://githubfast.com/WXRIW/Ink-Canvas/labels/bug/new

2. Tencent QQ
    [![Communicate Group](https://img.shields.io/badge/-%E4%BA%A4%E6%B5%81%E7%BE%A4%20891915376-blue?style=flat&logo=TencentQQ)](https://jq.qq.com/?_wv=1027&k=NvlM1Rgg) 

### What should I do if alternating between devices with different screen sizes or using fingers or a large pen tip causes it to be recognized as an eraser?
Click on the "Settings" button in the drawing board and enable the `Special Screen` option. This should resolve the issue.


## Thanks
Thanks [yuwenhui2020](https://githubfast.com/yuwenhui2020) for contributions to the `Ink Canvas documentation`!

Thanks [CN-Ironegg](https://githubfast.com/CN-Ironegg), [jiajiaxd](https://githubfast.com/jiajiaxd), [Kengwang](https://githubfast.com/kengwang), [Raspberry Kan](https://githubfast.com/Raspberry-Monster) for contributing code to this project!.

## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FWXRIW%2FInk-Canvas.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FWXRIW%2FInk-Canvas?ref=badge_large)
