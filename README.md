<div style="text-align: center; font-size: xxx-large; margin-top: 1em; margin-bottom: 0.5em;"> <strong>EasyTool</strong> </div>
<div style="text-align: center;"> EasyTool 多功能插件工具集</div>
<div style="text-align: center;">
    <p>
        <a href="https://gitee.com/milubin/easy-tool-plugin/badge/star.svg" target="_blank">
            <img src="https://gitee.com/milubin/easy-tool-plugin/badge/star.svg" alt="Gitee Start" />
        </a>
        <a href="https://img.shields.io/github/license/java-horse/EasyTool-Plugin" target="_blank">
            <img src="https://img.shields.io/github/license/java-horse/EasyTool-Plugin" alt="Github license" />
        </a>
        <a href="https://img.shields.io/github/followers/java-horse" target="_blank">
            <img src="https://img.shields.io/github/followers/java-horse" alt="Github followers" />
        </a>
    </p>
    <p>
        <a href="https://img.shields.io/jetbrains/plugin/v/21589" target="_blank">
            <img src="https://img.shields.io/jetbrains/plugin/v/21589" alt="JetBrains Plugin Version" />
        </a>
        <a href="https://img.shields.io/jetbrains/plugin/d/21589" target="_blank">
            <img src="https://img.shields.io/jetbrains/plugin/d/21589" alt="JetBrains Plugin Download" />
        </a>
        <a href="https://img.shields.io/jetbrains/plugin/r/stars/21589" target="_blank">
            <img src="https://img.shields.io/jetbrains/plugin/r/stars/21589" alt="JetBrains Plugin Starts" />
        </a>
        <a href="https://img.shields.io/github/languages/code-size/java-horse/EasyTool" target="_blank">
            <img src="https://img.shields.io/github/languages/code-size/java-horse/EasyTool" alt="Code Size" />
        </a>
        <a href="https://img.shields.io/github/languages/count/java-horse/EasyTool" target="_blank">
            <img src="https://img.shields.io/github/languages/count/java-horse/EasyTool" alt="Languages" />
        </a>
    </p>
    <p>
        <a href="https://img.shields.io/github/last-commit/java-horse/EasyTool" target="_blank">
            <img src="https://img.shields.io/github/last-commit/java-horse/EasyTool" alt="Last Commit" />
        </a>
        <a href="https://img.shields.io/badge/Java-17-blue" target="_blank">
            <img src="https://img.shields.io/badge/Java-17-blue" alt="JDK17" />
        </a>
        <a href="https://img.shields.io/github/created-at/java-horse/EasyTool" target="_blank">
            <img src="https://img.shields.io/github/created-at/java-horse/EasyTool" alt="Create At" />
        </a>
        <a href="https://img.shields.io/github/v/tag/java-horse/EasyTool" target="_blank">
            <img src="https://img.shields.io/github/v/tag/java-horse/EasyTool" alt="Tag Version" />
        </a>
        <a href="https://img.shields.io/github/repo-size/java-horse/EasyTool" target="_blank">
            <img src="https://img.shields.io/github/repo-size/java-horse/EasyTool" alt="Repo Size" />
        </a>
        <a href="https://img.shields.io/github/languages/top/java-horse/EasyTool" target="_blank">
            <img src="https://img.shields.io/github/languages/top/java-horse/EasyTool" alt="Languages Rate" />
        </a>
    </p>
</div>

## 简介|Intro

`EasyTool` 是一个支持多系统平台的IDE插件工具集，具有日常编程过程中常用的功能特性，包括但不限于中英字符互转、
中英语句互译、Swagger2.x、Swagger3.x 注解一键生成、JavaDoc注释一键生成、一键导入YApi接口文档、MybatisLog日志还原、
Git提交规范模板、Git Emoji表情弹窗、 BackgroundImagePlus背景轮播、代码块一键截图、API一键转Markdown/Curl格式、
开发常用Widget效率小组件、 JSON转Tree视图/转格式化/转Bean实体类、CamelCase驼峰转化等一系列开发功能特性。
提供一系列可视化、个性化的配置界面， 具体功能可在安装插件后尽情体验。

## 安装|Install

### 在线安装

打开`IDE`的`Setting`页面并搜索`Plugin`，点击`Marketplace`，输入`EasyTool`，点击`Install`即可。
![在线安装EasyTool插件示例](https://s11.ax1x.com/2024/01/27/pFn7p9J.png)

### 离线安装

打开 [Gitee](https://gitee.com/milubin/easy-tool-plugin) 仓库
或者 [Github](https://github.com/java-horse/EasyTool-Plugin) 仓库,
或者 [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/21589-easytool/) 插件市场，
下载仓库中版本号最新版离线插件源码资源包（非最新版可能会有隐藏小BUG）。
打开`IDE`的`Setting`页面并搜索`Plugin`，导入插件源码资源包，重启IDE即可
![离线安装EasyTool插件示例](https://s11.ax1x.com/2024/03/02/pF0WO39.png)
![离线安装EasyTool插件示例](https://s11.ax1x.com/2024/01/27/pFn7Fnx.png)

## 特性|Feature

以下列举特性不分优先级，均是日常编程过程中常用的功能特性。

* 中英文字符互转
    * 支持全局代码编辑器中文字符在编程过程中自动转为英文字符，可自定义字符映射关系和是否启动 `Other Settings` -> `EasyTool` -> `Convert`
* 中英互译
    * 支持选中编辑器文本进行翻译，翻译规则：中文自动翻译为驼峰形式的英文变量且自动替换，英文自动翻译为中文。插件内置了十余种
      免费高效的翻译渠道引擎共大家选择（`Free`标识表示无需配置密钥免费使用，`推荐`
      标识表示厂商免费权益较高），可按需配置 `Other Settings` -> `EasyTool` -> `Translate`，
      内置翻译渠道引擎如下：
        * 百度翻译（推荐）
        * 有道翻译（推荐）
        * 阿里翻译（`极力推荐, 免费权益额度、准确率高`）
        * 金山翻译（Free）
        * 腾讯翻译
        * 华为翻译
        * 火山翻译
        * 讯飞翻译
        * 小牛翻译（`极力推荐, 免费权益额度高`）
        * 彩云翻译
        * 同花顺翻译
        * CNKI学术翻译
        * 有道翻译（Free）
        * 微软翻译（API）
        * 微软翻译（Free）
        * 谷歌翻译（API）
        * 谷歌翻译（Free）
        * Libre翻译（Free）
    * 支持开源大模型翻译引擎
        * 通义千问
        * 文心一言
        * 月之暗面-Kimi
* 一键生成`Swagger2.x`、`Swagger3.x`注解
    * 支持根据 `Javadoc` 生成 `Swagger2.x`、`Swagger3.x` 相关注解，如果没有 `Javadoc` 会尝试翻译处理(翻译可能会有点慢, 请耐心等待)
    * 支持选中类名、方法名、字段名等不同粒度一键生成（同时支持光标放置在类名、方法名、字段名等位置上）
    * 支持在 SwaggerView 弹窗中自由选中需要生成注解的类、方法、属性 (类似批量选中效果)
* 一键生成 JavaDoc 注释
    * 支持一键生成指定类、方法、属性的JavaDoc注释，快捷键: `ALT + M`
    * 支持自定义JavaDoc生成模板及Groovy脚本值设置
* 支持一键导入YApi接口文档, 包括YApi项目UI配置页面, 兼容各颗粒度范围导入(文件、类、接口)`Mybatis Log`日志还原
    * 支持将Mybatis的Console控制台SQL执行日志自动还原为可读的SQL语句，可以自定义SQL还原过滤规则、可设置SQL脚本打印文本颜色
    * 支持选中SQL日志并右键启动SQL还原弹窗进行SQL还原转换处理
    * 功能启动路径：`Tools` -> `EasyTool` -> `Mybatis Log`，点击之后会出现一个SQL还原功能窗口
* 支持 `Navigate` -> `Request Service` 搜索 Controller Mapping 方法
    * 使用快捷键：`Ctrl + Shift + \`，调出`Request Service` 搜索框，输入接口关键字即可搜索定位到对应方法
* 参考 `GenerateAllSetter` 插件，支持 IDEA Postfix 语法自动生成 POJO 的所有Setter/Getter 以及 POJO 之间的属性转换
    * 在`POJO`变量后通过 `.allset` 自动生成所有Setter
    * 在`POJO`变量后通过 `.allget` 自动生成所有Getter
    * 在`POJO`变量后通过 `.allsetn` 自动生成所有Setter (未填充默认值)
    * 在`POJO`变量后通过 `.convert` 自动生成对象属性转换 (示例: target.setXxx(source.getXxx).convert)
* 支持选中`Cron`表达式动态解析、自动识别`@Scheduled`注解并在右侧添加小图标按钮
* 支持 Git Commit 时按照模板进行提交信息填写并自动按照规范格式组装
* 支持 Git Commit 时添加 Emoji 标识
    * 支持 Git Commit Message 消息文本输入 英文冒号+Emoji英文字符 自动提示（支持Markdown、Java、Txt等文件）
* 支持选中文本右键快捷Web搜索，默认内置常用百度、必应、谷歌等引擎
    * 支持自定义配置Web搜索引擎
* 支持快捷生成 `serialVersionUID`, 快捷键: `CTRL + SHIFT + ALT + \`
    * 自动识别JDK版本生成不同规范的`serialVersionUID`
* 支持自动复制接口完整URL，自动尝试获取项目端口号（自动尝试读取项目配置文件）
    * 支持自定义配置域名及端口，默认端口为`8080`
* 支持CamelCase驼峰命名风格转换其他各种命名风格
* 支持当前打开文件的Tab标签高亮显示, 可在通用设置页面自定义高亮颜色
* 支持选中代码块一键截图功能, 快捷键: `CTRL + ALT + 5`
    * 支持生成图片质量设置、水印设置
* 支持Entity普通实体类批量生成JSON注解的View视窗, 快捷键: `CTRL + ALT + 6`
* 支持常用的Widget工具小组件View视窗(EasyTool -> Widget -> Core), 快捷键: `CTRL + ALT + 7`
    * URL转码
    * Cron预览
    * QR二维码（条形码）
    * YML转换
    * EXCEL解析
    * Timestamp时间戳
    * Base64转码
    * Simple计算器（加、减、乘、除、取余、括号）
    * SQL日志还原
    * Windows进程管理
    * JSON格式化
* 支持JSON一键转JSONTree视图，支持JSONPath表达式搜索，支持JSON一键转为Bean实体类

## 示例|Example

|                                    仅配置UI界面                                     |                                       --                                       |
|:------------------------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| ![2024-09-07_10-52-43.png](https://s2.loli.net/2024/09/07/Py7wHIpZ9fcA1j5.png) | ![2024-09-07_10-55-00.png](https://s2.loli.net/2024/09/07/gemWP2RjMYZIsrn.png) |
| ![2024-09-07_10-55-59.png](https://s2.loli.net/2024/09/07/eLImiqztYFsbVTP.png) | ![2024-09-07_10-56-06.png](https://s2.loli.net/2024/09/07/ykh5GJARIqEeBF7.png) |
| ![2024-09-07_10-56-16.png](https://s2.loli.net/2024/09/07/eXQ9PWkKorE2ZGV.png) | ![2024-09-07_10-56-22.png](https://s2.loli.net/2024/09/07/PpncxVjg28f7RCS.png) |
| ![2024-09-07_10-56-27.png](https://s2.loli.net/2024/09/07/5rxZiuXBhF1P49b.png) | ![2024-09-07_10-56-33.png](https://s2.loli.net/2024/09/07/SEcD9THj2Cxb6Ao.png) |
| ![2024-09-07_10-56-38.png](https://s2.loli.net/2024/09/07/g2lDO4IrNsU1xBd.png) | ![2024-09-07_11-27-56.png](https://s2.loli.net/2024/09/07/tdI3TvYbCDQw6Xa.png) |

## 捐赠|Donate

| 平台  |                          😎                           |
|:---:|:-----------------------------------------------------:|
| 微信  |  ![微信](https://s11.ax1x.com/2024/02/01/pFMJ0aD.png)   |
| 支付宝 |  ![支付宝](https://s11.ax1x.com/2024/02/01/pFMJwVO.png)  |
| 公众号 | ![微信公众号](https://s11.ax1x.com/2024/02/01/pFMJaqK.jpg) |



