VisionDatePicker
=====
* A simple and highly customizable oc date picker
* 简单易用、可高度自定义的日期选择控件

### Screenshots
None.

### Contents
## Installation 安装

* Just drag `VisionControl` folder into your project
* 将`VisionControl`文件夹拖入你的項目

### 在你需要使用Picker的文件中导入头文件:
```objective-c
#import "VisionDatePicker.h"
```
## Usage 使用方法
```objective-c
/* 注意：Picker必須聲明為全局變量或屬性，否則會自動回收
 */
@property (strong,nonatomic) VisionDatePicker *picker;
```

```objective-c
 //demo textField
UITextField *txt = [[UITextField alloc] initWithFrame:(CGRectMake(50, 100, 270, 40))];
txt.borderStyle = UITextBorderStyleRoundedRect;
[self.view addSubview:txt];
self.picker = [[VisionDatePicker alloc] initWithTextField:txt 
                                        format:@"yyyy-MM-dd hh:mm:ss"
                                        dateDefault:[NSDate date] 
                                        dateMode:(UIDatePickerModeDateAndTime)
                                        locale:[NSLocale currentLocale]];
```

## Features 特性
None.

## Requirements 要求
iOS 6 or later. Requires ARC  ,support iPhone/iPad

iOS 6及以上系统可使用. 本控件纯ARC，支持iPhone/iPad横竖屏
## More 更多 

Please create a issue if you have any questions.
Welcome to visit my [Blog](http://blog.viiio.com/ "Vision的博客")

## Licenses
All source code is licensed under the [MIT License](https://github.com/VIIIO/VisionDatePicker/blob/master/LICENSE "License").

