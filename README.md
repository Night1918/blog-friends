# [友情链接](https://blog.night1918.top/link/)

## 友链交换须知

1. 原则上只接受博客类型的友链申请。
2. 网站的域名是很重要的，如果你的域名是免费域名的话就请不要来申请友链啦。
   - 免费域名 **包括但不限于** 下述定义：
     - 由 Freenom 公司运营的免费域名后缀，如 `.ml`、`.tk`。
     - 其他不包含在 Public Suffix List 中的 **免费子域名** 服务。
     - 由于下述免费子域名服务拒绝提交至 Public Suffix List，根据第二条的定义将会被拒绝：`oschina.io`、`gitee.io`、`coding.me`、`coding.io`、`coding-pages.com`。
   - 免费域名 **不包括** 下述定义：
     - 向 Freenom 公司付费购买的 `.ml`、`.tk` 等域名
     - 其他任何包含于 [Public Suffix List](https://publicsuffix.org/list/) 的免费子域名服务，如 `github.io`，`gitlab.io`，`now.sh` 等。
3. 不接受存在商业性质广告的网站，不接受奇奇怪怪的网站和营销号网站（包括但不限于资源站、商务性质网站）。
4. 会正确使用 Git 和 GitHub 。
5. 最终解释权归 Night1918 所有。

## 友链交换流程

1. 先添加本站的友链。
   - Name
     - `夜辰 | Night1918 Blog`
   - URL
     - `https://blog.night1918.top`
   - Logo
     - Favicon
       - [`64x64`, png](https://resource.night1918.top/avatar/avatar_64x64.png)
       - [`128x128`, png](https://resource.night1918.top/avatar/avatar_128x128.png)
       - [`256x256`, png](https://resource.night1918.top/avatar/avatar_256x256.png)
       - [`500x500`, png](https://resource.night1918.top/avatar/avatar_500x500.png)
       - [`512x512`, png](https://resource.night1918.top/avatar/avatar_512x512.png)
       - [`1024x1024`, png](https://resource.night1918.top/avatar/avatar_1024x1024.png)
     - [Banner](https://resource.night1918.top/avatar/avatar_raw.jpg)
     - 如果你的友链页面没有放 Logo 的地方就可以不用放了哦~
   - Slogan
     - `学习,就是发现自己越来越菜的过程`
2. 准备一个自己站点的 Logo。
   - Logo 的外形应为正方形或圆形
   - 长度与宽度应小于 **`512px`** ，以 `128px` 为佳
   - 使用常见文件格式，如 **`png`（推荐）**、`jpg`、`svg` 等（不包括 `tiff`、`icns`）
   - 文件大小应小于 **512 KiB** ，以 128 KiB 以内为佳
   - Logo 应符合 Gravater **G 分级** 要求（即适合在任何网站上展示给任何年龄段的任何人）
3. 准备需要展示的站点名称，长度应小于 30 个半角字符或 15 个全角字符，否则在展示时可能会被截断。
   - 站点名称应适合在任何网站上展示给任何年龄段的任何人
4. （可选）准备一条 Slogan，长度建议小于 36 个半角字符或 18 个全角字符，否则在展示时可能会被截断。
   - Slogan 应适合在任何网站上展示给任何年龄段的任何人
5. 在 GitHub 上 Fork 这个仓库。
6. 在 `img` 下提交 Logo 文件。
   - 文件名格式为 `[domain].[format]`，如 `example.com.png`，`blog.example.com.jpg`
   - Commit 的标题应为 `Add: [filename] ( [url] )`，如 `Add: example.com.png ( https://example.com )`
7. 修改 `links.json` 文件，注意格式，可以到`https://www.bejson.com/`校验格式是否正确。
   - 按照如下格式将你的网站信息添加到 `links.json` 文件中：
    ```json
     [
        {
            "title": "Site Name", //网站名称，请使用双引号包裹
            "website": "https://example.com", //网站链接
            "image": "example.com.png", //Logo 的文件名
            "description": "Slogan" //Slogan，请使用双引号包裹
        }
    ]
    ```
   - Commit 的标题应为 `Add: [sitename] ( [url] )`，如 `Add: example blog ( https://example.com )`
8. 完成上述步骤后，请新建一个 Pull Request。
   - Pull Request 标题应为 `Add: [sitename] ( [url] )`，如 `Add: example blog ( https://example.com )`
9. 当你发起的 Pull Request 被 Review 并被通过、合并后，你的网站将会在 24 个小时内显示在 [友链页面](https://blog.night1918.top/link/)。

---

<sub>本仓库灵感来源于 <a href="https://github.com/SukkaW/Friends">SukkaW/Friends</a> ，在此表示感谢。</sub><br>