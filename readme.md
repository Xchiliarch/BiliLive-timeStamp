## 简介：

通过添加两个按钮及快捷键使用户能够在观看直播时快捷记录可用于切片的时间点或评论跳转。

- 在页面右边添加两个按钮，【添加时间点】【导出时间点】

- 通过Ctrl +F2打开面板进行高级控制

项目UI来源：[Add button for Smooth Scroll to the top / bottom](https://greasyfork.org/zh-CN/scripts/8719-add-button-for-smooth-scroll-to-the-top-bottom)

## 快捷键：
- 【Ctrl + F2】 打开控制面板
- 【Esc】 退出控制面板
- 【Shift + F】 添加时间点

## 功能：

- 通过快捷键或按钮标记当前直播间的时间点，使用直播左下角已推流时间进行标记
	1. 使用按钮
	    ![btn](https://raw.githubusercontent.com/Xchiliarch/BiliLive-timeStamp/main/pics/btn.png)
  	2. 使用快捷键 【Shift + F】记录后，可在浏览器控制台或在控制面板查看已记录的时间点
  ![time](https://raw.githubusercontent.com/Xchiliarch/BiliLive-timeStamp/main/pics/time.png)
  

## 面板：

![panel](https://raw.githubusercontent.com/Xchiliarch/BiliLive-timeStamp/main/pics/panel.png)

- **获取当前时间**：点击按钮获取当前时间点，或手动输入（请注意使用半角冒号）
- **时间-30s**：在时间点面板存在合法输入时，点击该按钮使时间点-30s
- **添加时间点**：将当前输入框内时间点添加到保存列表中
- **移除最近一个时间点**：删除最近一个添加的时间点
- **显示所有时间点**：显示当前已添加的所有时间点（该功能可能存在bug，在清空时间点后依然显示某些时间，请退出面板再次进入确认）
- **清空所有直播间时间点**：清空所有已记录的时间点（慎用）

```

```

