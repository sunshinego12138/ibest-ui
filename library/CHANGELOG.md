# 版本记录

## 1.0.0 初版

## 1.0.1 
1. Readme内容调整

## 1.0.2
1. package增加`keywords`、`tags`、`homepage`、`repository`
2. 代码格式以及注释调整

## 1.0.3
1. checkbox组件UI展示bug修复

## 1.1.0
1. 增加empty组件以及对应的展示页面

## 1.2.0
1. 增加dialog组件以及对应的展示页面

## 1.3.0
1. 兼容API 11

## 1.4.0
1. 编写stepper组件以及对应的展示页面

## 1.5.0
1. 增加calendar组件


## 1.6.0
1. 增加toast组件

## 1.7.0
1. 增加loading组件
2. 修复若干bug

## 1.8.0
1. 增加tab组件

## 1.9.0
1. 增加Cascader与Popup组件

## 1.9.1
1. Cascader与Popup组件代码大小写格式纠正

## 1.10.0
1. 增加Form以及Field组件

## 1.11.0
1. 增加: Picker、DatePicker、TimePicker、PickerGroup 
2. Cascader组件支持双向绑定;
3. Tab组件支持双向绑定, 优化参数声明。

## 1.11.1
1. bug修复

## 1.12.0
1. 新增numberKeyboard、passwordInput组件 ;
2. popup 新增 maskColor 属性 ;
3. 新增全局初始化方法 IBestInit ;
4. 一些样式优化 。

## 1.12.1
watermark引用文件大小写不一致报错bug修复

## 1.13.0
1. 增加search rate组件
2. watermark组件使用stack包裹
3. button组件增加宽高设置

## 1.14.0
1. Search 组件增加 customRightButton 属性
2. 增加 IBestActionSheet API
3. 增加 IBestSignature 组件
4. 组件库初始化变更

## 1.15.0
新增:
1. 增加 slider 滑块组件;
2. 增加 Uploader 文件上传组件;
3. 增加图片预览api IBestImagePreview;
4. tab组件新增 fontSize 属性;
5. form组件新增 getFormValues 方法, 同步获取表单数据。

兼容变更:
1. 所有组件(Watermark、Signature除外)颜色相关属性类型改为 RescourseColor 。

## 1.16.0

新增:
1. 增加 IBestDialogUtil 弹框API;
2. IBestDialog 增加 visible、theme、buttonSpace、confirmButtonBgColor、cancelButtonBgColor、closeOnBackPress、onOpen、onClose 属性;
3. 增加 IBestNotify 消息提示API;
4. IBestToast 增加 showLoading 方法.

变更:
IBestDialog 组件显隐控制方式由原来的controller方式变为由 visible 属性控制, 简化使用.


优化:
1. 优化 IBestLoading 组件动画效果;
2. 优化 IBestPopup 组件隐藏动画效果.

## 1.17.0

1. 新增 IBestIcon 组件;
2. 新增 IBestPullRefresh 下拉刷新组件;
3. IBestTab 新增 onTabClick 事件;
4. 增加导出 IBestCascaderContent 级联组件, 可独立在页面中使用或与其他自定义组件组合使用;
5. IBestCell 增加 leftIcon leftIconColor leftIconSize rightIcon rightIconColor rightIconSize 属性;
6. IBestActionSheet 增加 cancelTextColor、beforeClose 属性.

另: 新发布 @ibestservices/area-data 库, 可用于Cascader相关组件.


## 1.17.1

1. 修复bug

