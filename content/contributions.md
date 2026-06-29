---
title: Contributions
date: 2024-11-23T04:12:38+08:00
update: 2026-03-21T12:58:20+08:00
draft: false
layoutBackgroundHeaderSpace: false
cardViewScreenWidth: false
showTableOfContents: true
---

## Add New/Update Member Profile

#### STEP 1

**Fork** [this](https://github.com/nousagigang/nousagigang) repository

{{< github repo="nousagigang/nousagigang" showThumbnail=true >}}

<br>
{{< alert >}}
  If you've already forked it, ignore this step.
{{< /alert >}}

#### STEP 2

**Create a new folder** with `your-username` inside of `content/members` directory

{{< accordion mode="collapse" separated=true >}}
  {{< accordionItem title="See the file structure" icon="lightbulb" open=false >}}
```shell
.
└── content
    └── members
        ├── _index.md
        ├── members.json
        └── your-username
            ├── index.md
            └── feature.jpg
```
  {{< /accordionItem >}}
{{< /accordion >}}

<br>
{{< alert >}}
  Replace 'your-username' with your actual username.
{{< /alert >}}

#### STEP 3

**Create a new `index.md` file**

{{< alert >}}
  If you've already have a member profile page, ignore this step.
{{< /alert >}}

> [!TIP]-
> If you have [Hugo](https://gohugo.io) installed on your terminal, you can easily do steps 2 and 3 by using this command:
> 
> `hugo new content members/your-username/index.md`

#### STEP 4

Inside of your `index.md`, **Add** and/or **Update** this code below:

```md
---
title: 'username'
tags: ['Game']
weight: 01
layoutBackgroundHeaderSpace: false
---

![image](#link)

## Info:
- Username: username
- Bio: Gamer Writer Developer
- Socials:
    - [Facebook](#!)
    - [Instagram](#!)
```

> [!TIP]- Add feature or background images (Optional)
> - You can change the default background of your members profile page by adding an image with `background.jpg` filename to your folder (`./content/members/your-username`).
> - You can also change the default feature image of your profile page by doing the same. Just use `feature.jpg` as your filename.

#### STEP 5

Finally, commit all your changes and **send a pull request**. Please wait for it to be approved.

___

## Request to Add/Update Member Profile

If you don’t know how to code and don't want to do all these, you can simply **create a thread** on NSG's Discord server `#support` channel with your request message and wait for server staff to assist you.

> [!TIP]
> Be specific with your thread title.

___

## Spacial Thanks 🙏

- [Hugo](https://gohugo.io/) *(static site generator)*
- [Blowfish](https://blowfish.page/) by [Nuno Coraco](https://github.com/nunocoracao) *(🔥 Hugo theme)*
- [GitHub](https://github.com/) *(code hosting)*
- [Auto Creative](https://auto.creavite.co/) *(GIF banners)*
- [Google Gemini](https://gemini.google.com/) *(creative writing)*
- [Dola, formerly Cici](https://www.dola.com/) *(background images)*
- [ChatGPT](https://chatgpt.com/) *(help fix broken stuff)*
- and to all the developers who made this website possibly all-free 🧡
