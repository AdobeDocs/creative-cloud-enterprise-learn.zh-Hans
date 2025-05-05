---
title: 了解企业和Acrobat序列号过期的Creative Cloud
description: 了解Creative Cloud企业版和Acrobat版序列号的过期体验
role: Admin
level: Beginner, Intermediate
feature: Deploy
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: c57212d39b2e613964bc15d2967a1958dc0c8c8e
workflow-type: tm+mt
source-wordcount: '840'
ht-degree: 1%

---

# 了解企业和Acrobat序列号过期的Creative Cloud

过去，Adobe会使用我们的应用程序(即，Creative Suite、企业Creative Cloud、Acrobat XI、Acrobat DC)向企业定期许可协议(ETLA)上的客户颁发序列号。 这些序列号确实有一个过期日期。 一旦超过过期日期，产品将不再有效，因此务必要在序列号过期之前规划迁移。 本页概述为确保您的最终用户能够继续访问其Adobe应用程序和服务而必须采取的步骤。

## 检查序列号的到期日期

### 查找您的序列号

可通过[ETLA许可网站](https://licensing.adobe.com/) (LWS)获得与您的Adobe协议关联的序列号许可证。 请按照以下说明显示和下载：

1. 使用您的Adobe ID和密码登录到[Adobe许可网站](https://licensing.adobe.com/) (LWS)。
1. 选择&#x200B;**许可证>检索序列号**。
1. 输入您的&#x200B;**最终用户ID**&#x200B;或&#x200B;**部署到ID**。
1. （可选）选择&#x200B;**产品名称**、**产品版本**&#x200B;或&#x200B;**平台**&#x200B;以筛选结果。
1. 单击&quot;搜索&quot;。
1. 此时会显示产品名称和序列号。
1. （可选）选择“导出至CSV”以下载序列号列表。

![查找您的序列号](assets/retrieveserialnumbers.png)

### 检查过期日期

[AdobeExpiryCheck](https://helpx.adobe.com/cn/enterprise/kb/volume-license-expiration-check.html)是一个命令行实用程序，供IT管理员检查计算机上的Adobe产品使用的序列号是否已过期或即将过期。 该工具将显示产品许可标识符(LEID)、加密序列号和到期日期等信息。 此[页面](https://helpx.adobe.com/cn/enterprise/kb/volume-license-expiration-check.html)包含有关在Mac或Windows计算机上下载和使用此工具的说明。

## 了解序列号过期之前和之后的最终用户体验

Acrobat和Creative Cloud企业版应用程序都将开始从过期前60天开始显示消息（在应用程序中）。 序列号过期后，产品将停止工作，并提示用户采取操作。

### 企业体验Creative Cloud

以下信息概述了最终用户体验。 下面是一段简短的视频，随后将回顾最终用户体验。

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**过期前**

从序列号过期前60天开始，所有Creative Cloud企业版应用程序都会向最终用户显示一个“在产品中”对话框。 此消息将每周出现，直到过期前30天，然后每天出现，直到过期日期说明&#x200B;*您的许可证即将过期。 此Adobe产品使用的许可证将于2020年11月29日到期。 请联系您的管理员以确保继续访问*。

![过期消息前CCE](assets/cceexpiring.png)

**过期后**

序列号过期后，用户将无法再访问企业版应用程序的Creative Cloud。 过期后首次启动时，系统将向用户显示一个对话框，说明&#x200B;*您输入的序列号已过期。 无法为此产品授予许可。 请联系客户支持*。

![过期消息后CCE](assets/cceafterexpire.png)

在后续尝试启动应用程序时，将提示最终用户&#x200B;**立即登录**，之后选择创建自己的Adobe ID并进入试用模式。 但是，最终用户创建的任何新Adobe ID都不会与您组织的许可证关联，并且会给您的用户带来额外的混淆。 为避免业务中断和/或不必要的混淆，请在序列号到期之前将您的用户迁移到指定用户许可。

![CCE登录对话框1](assets/ccesignin1.png)

![CCE登录对话框2](assets/ccesignin2.png)

### Acrobat体验

以下信息概述了最终用户体验。 下面是一段简短的视频，随后将回顾最终用户体验。

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**过期前**

从序列号过期前60天开始，Acrobat会向最终用户显示产品内弹出消息。 这将每周显示一次，直到过期前7天。 然后，它每天开始显示，显示&#x200B;*您的Adobe Acrobat许可证将于2020年11月30日到期。 请联系您的管理员以继续使用Acrobat而不中断。*

![Acrobat即将过期消息](assets/acrobatexpiring.png)

**过期后**

序列号过期后，用户将无法再访问Acrobat。 过期后首次启动时，系统将向用户显示一个对话框，说明&#x200B;*您输入的序列号已过期。 无法为此产品授予许可。 请与客户支持联系。*

![过期消息后的Acrobat](assets/acrobatafterexpire.png)

在后续尝试启动Acrobat的所有操作中，系统将提示最终用户&#x200B;**立即登录**，之后选择创建自己的Adobe ID并进入试用模式。 但是，最终用户创建的任何新Adobe ID都不会与您组织的许可证关联，并且会给您的用户带来额外的混淆。

![对话框1中的Acrobat Sign](assets/acrobatsignin1.png)

![对话2中的Acrobat Sign](assets/acrobatsignin2.png)

## 如果您需要帮助，请联系我们

如果您对使用[AdobeExpiryCheck](https://helpx.adobe.com/cn/enterprise/kb/volume-license-expiration-check.html)工具有疑问，或者需要获得有关从序列号部署迁移到指定用户的帮助，您可以选择以下选项：
* 向Adobe企业入门团队发送电子邮件 — **entonb@adobe.com**
* 在[Admin Console](https://adminconsole.adobe.com/support)中打开支持票证
* 请联系您的Adobe客户团队
