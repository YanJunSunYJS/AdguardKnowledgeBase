---
title: Features overview
taxonomy:
    category:
        - docs
---

AdGuard 提供了一系列运行在各平台上拦截广告和跟踪器的软件产品。其中最流行的一款 AdGuard 产品便是可用于 5 个最流行浏览器的免费扩展：Chrome，Firefox，Edge, Opera 及 Yandex.Browser。浏览器扩展提供有基本的广告拦截功能，但无法与功能齐全的桌面程序相提并论，例如 [*AdGuard for Windows*](https://kb.adguard.com/en/windows/overview) 和 [*AdGuard for Mac*](https://kb.adguard.com/en/mac/overview)。

我们将用本文向您展示其所有有用选项。如您是搜寻一些特定信息，请直接导航到相应的项目或阅读整篇文章以了解更多产品信息。

<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/br_ext1.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">

- [可用性](#br-extension)
- [拦截广告](#adblocker)
    - [过滤器](#filters)
        - [自定义过滤器](#custom)
    - [用户规则](#user-rules)
    - [Allowlist](#allowlist)
- [隐身模式](#stealth-mode)
- [其它功能和选项](#other)
    - [常规](#general)
    - [杂项](#misc)
    - [关于](#about)
- [扩展的主菜单](#main-menu)
- [AdGuard 浏览器扩展对比 AdGuard 程序](#comparison)

<a name="br-extension"></a>
## 可用性

[AdGuard Browser extension](https://adguard.com/en/adguard-browser-extension/overview.html) 可用于大部分主流浏览器。您可通过浏览器在线商店或我们的官方网站找到它。
    
<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/all_browsers.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">

> 我们有用于 Safari 的单独扩展，因为自 [Safari 13](https://adguard.com/en/blog/adguard-safari-1-5.html) 其，大部分广告拦截扩展都遇到了大量的问题其中它们大多都停止了工作。我们开发了一款 [用于 Safari 的单独的扩展](https://kb.adguard.com/en/safari/overview)，其与本文所描述的扩展有着一些差异。

**请不要忘记各浏览器扩展的功能是受限于浏览器的能力。** 因此，如您要获得全部保护，则您最好把目光转向独立的计算机程序。我们会向您[解释原因](https://kb.adguard.com/en/browser-extensions/overview.html#comparison)。

<a name="adblocker"></a>    
## 拦截广告

拦截广告无疑是任何广告拦截器的关键功能，AdGuard 也不例外。浏览器扩展会成功拦截您浏览器内的任何网页广告。广告拦截是基于过滤器列表之上，或简称为 [过滤器](https://adguard.com/en/blog/how-ad-blocking-is-done.html)，这些过滤器可在 AdGuard 设置内开启或禁用。您可按需激活特定的过滤器以调整广告拦截。

<a name="filters"></a>
### 过滤器

从本质上讲，过滤器列表就是一套以特定语言书写的规则，广告拦截器作为规则解释器并执行它们。经过如此之后，您不便不会再看到网页上的广告了，生活变得更安逸。

<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/filters.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">

所有过滤器是依据其角色分组。例如，分类为广告拦截过滤器，隐私保护过滤器，社交媒体过滤器登封。您可单独的开启它们或一次性整组开启。

<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/ad_blocking_filters.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">

<a name="custom"></a>
#### 自定义过滤器 

While the features of other filter groups are more or less predictable, there is a group called *Custom* that may raise additional questions.

<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/custom.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">

In this tab you can add filters that are not present in the extension by default. There are plenty of [publicly available filters on the Internet](https://filterlists.com). Moreover, you can create and add your own filters. In fact, you can build any set of filters and customize ad blocking the way you like. 

要添加过滤器，只需点击 **添加自定义过滤器（Add custom filter）** 按钮并输入您所需的过滤器 URL 或文件路径，然后点击 **下一步（Next）** 按钮。

<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/custom_adding.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">
    
<a name="user-rules"></a>
### 用户规则

*User rules* is another tool that helps you personalize protection by adjusting it in a preferable way.

<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/user_rules.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">

In this tab it is possible to create your own filtering rules. There are several ways to add new rules. The most straightforward is to just type a rule in, but it requires some knowledge of the [rule syntax](https://kb.adguard.com/en/general/how-to-create-your-own-ad-filters).
    
Then, it's possible to import a ready-to-use filter list from a text file. *Make sure that different rules are separated by line breaks.*  Besides, you can export filtering rules created by you. But first and foremost, this option is for transferring your list of rules between browsers or devices, while for importing ready-to-use filters it is better to use [Custom filters](https://kb.adguard.com/en/browser-extensions/overview.html#custom).

When you add a website to allowlist (more about it [below](#allowlist)) or use [the Assistant tool](https://kb.adguard.com/en/browser-extensions/overview.html#assistant) for hiding an element on the page, a corresponding rule goes to *User rules*.
    
<a name="allowlist"></a>
### Allowlist

If you want to exclude certain websites from filtering, the *Allowlist* option will be of help. Here you can add particular websites to the list of exceptions, it will disable blocking for those trusted domains. Just put the websites you want to exclude into the Allowlist and the ad blocking rules won’t be applied to them. 

<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/allowlist.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">

The *Allowlist* can be inverted, too — you can unblock ads everywhere except the sites that you added to this list. Just activate the **Invert Allowlist** option.

<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/invert_allowlist.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">

Also, you can either import or export already existing lists of exclusions if needed. It is especially useful when you want to apply the same list of sites on other devices and you don’t want to spend time on its creation. The *Allowlist* can be configured just in a couple of clicks.

<a name="stealth-mode"></a>
## Stealth Mode

The *Stealth Mode* module aims to ensure the protection of sensitive personal information from online trackers and other fraudsters. 

<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/stealth_mode.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">

Stealth Mode can be flexibly adjusted — you can prohibit a website to receive the search requests you used to find it on the Internet, automatically delete both third-party and website’s own cookies, and so on. [A separate article](https://kb.adguard.com/en/general/stealth-mode) is devoted to all these features.

> Note that some of the *Stealth Mode* options available in full-fledged apps are not present in the browser extensions due to technical restrictions.
    
<a name="other"></a>
## Other features and options

Apart from the large key modules of AdGuard Browser extension there are several more specific but no less useful features that can be configured in the *General* and *Miscellaneous* sections of the extension settings. They'll help you customize the extension according to your individual needs.

<a name="general"></a>
### General

In the *General* settings you can allow [search ads and the self-promotion of websites](https://kb.adguard.com/en/general/search-ads-and-self-promotion), enable/disable the automatic activation of the most appropriate filters and indicate the filters update interval, etc.

<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/general.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">

Besides, here you can enable *Phishing and malware protection* (read more about [how it works](https://kb.adguard.com/en/general/how-malware-protection-works#phishing)).

In case you want to keep your settings configuration, you can use the **Export settings** option to save it as a file. And vice versa, use the **Import settings** button to upload settings from a previously stored settings file. You can even use it to quickly switch between different settings profiles or even to transfer settings configurations between different browsers. 

<a name="misc"></a>
### Miscellaneous 

The *Miscellaneous* settings section contains a range of various settings that are related to the ad blocking process and application usability.

<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/stealth_mode_misc.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">

From this settings tab you can activate optimized filters, enable notifications about extension updates, open the *Filtering log*, see the most recent *Changelog*, and reset blocked ads statistics by clicking the **Reset statistics** button.

Besides, you can opt to help us in the development of filters by sending some anonymized information. Naturally, all data is sent strictly anonymously, and it is crucial for us to obtain statistics on rules — which ones are triggered, on which websites and how often — because we use this data to optimize our filters. By agreeing to share this data, you will help us improve filtering, and eventually you will also help yourself, because the filters in the extension will become better. But don't worry, no data will be sent without your consent, this option is disabled by default.
    
<a name="about"></a>
### About

Among the rest of AdGuard settings tabs there is the *About* section where you can get some additional information (for example, what extension version you’re using). Here you will also find the links to the legal documents such as EULA (End User License Agreement) and Privacy policy, and to the repository of the Browser extension on GitHub.

<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/about.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">
    
<a name="main-menu"></a>
## Extension’s main menu

Now let's get back to the very beginning and have a look at the interface of the extension itself. You can summon it at any time by clicking on the extension's icon on any web page.

<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/adguard_br_extension.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">

<a name="assistant"></a>
It provides several options. You can hide any element on any page manually (corresponding rule will be added to *User rules*), open *Filtering log* to view the complete information about your browser's traffic, or look at a website’s security report. Besides, you can submit a complaint about any website (for example, if there are missed ads on the page — our filter engineers will review the report and fix the problem) and see the statistics on blocked ads. 

All web requests made by the browser are displayed in the *Filtering log*, along with detailed information about each request. The *Filtering log* makes it easy, for example, to monitor requests blocked by the AdGuard Browser extension. Besides, it allows you to block any request or add a previously blocked request to allowlist in two clicks. The *Filtering log* also offers you a wide variety of options for sorting web requests, which can be extremely helpful when creating your own filtering rules.
You can open the *Filtering log* by selecting the corresponding item in the main menu, or from the settings page (in the "Miscellaneous" tab). 

By clicking the icons in the top right corner of the screen you can open extension settings or stop protection by clicking the respective button. 

<a name="comparison"></a>
## AdGuard Browser extension vs. AdGuard standalone apps    

The main advantage of AdGuard standalone programs over browser extensions is that they can block ads in every browser and in almost all apps. You may use different browsers at the same time, the app will filter ads and online threats in all of them equally well.

The second significant difference is that the possibilities of extension-based ad blockers are strictly limited by what browsers allow and don't allow them to do. They are also intrinsically less powerful as they, for example, don't support some types of filtering rules that are available to standalone apps. Some browsers have policies that restrict ad blocking, and AdGuard for Windows or Mac couldn't care less about that. The apps are not limited by anything — when you choose the app, you choose the better filtering quality.

AdGuard Browser extension has its advantages: it's absolutely free, you don’t have to spend time and money on its installation, and once installed, it will filter ads and fight online threats as effectively as possible in your browser. Yet, compared to full-fledged apps for Mac and Windows, the extension has its disadvantages. We gathered them all together in the comparative table below to demonstrate the differences between AdGuard Browser extension and our standalone program.

<img src="https://cdn.adguard.com/public/Adguard/Blog/in-depth-extension/comparison2x.png" style="border: 1px solid #efefef; max-width: 600px; padding: 2px;">

`1 – within browser restrictions and only in the browser where it is installed;`

`2 –  the extension is unable to detect requests from other extensions. So if some other, malicious or tracking extension wants to send a request to its server to show you ads or track your activity, AdGuard Browser extension will not be able to block that request;`

`3 – not all types of ads and threats can be blocked by browser extensions because of certain browser restrictions. It means that some elements may get to the page and slow down the loading process. Besides, unlike browser ad blockers, AdGuard app blocks ads before they are loaded to the browser. This saves traffic and speeds up page loading.`
