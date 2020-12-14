# Create your Image Service by UpIC & GitHub

### For what?

I assume you are a software engineer like to write blogs with a great deal of picture, but you don't know where to store your pictures
to use them easily. You want to access the pictures through your blogs as fast as you can, you are finding the solutions.

Now you have these options => ***but***:

1. Upload them with your blogs together => ***make your folder heavy***
1. Upload them to some other image service => ***tedious, someday could not access***

### A better way to store your public pictures

Hey man, you are a software engineer! Why not use GitHub to store your pictures? It's free! And you can use cdn to view it:
`https://cdn.jsdelivr.net/gh/{YourName}/{YourRepo}@{Branch}/{folder}/{filename}`

Like this: `https://cdn.jsdelivr.net/gh/Fatezhang/FigureCloud@master/uPic/happy.gif`

![Happy](https://cdn.jsdelivr.net/gh/Fatezhang/FigureCloud@master/uPic/happy.gif)

Someone would say: it's tedious too😩! But, what if you have an automatic uploading tool?

### Try UPic ➕ GitHub

#### What is &nbsp;__[UPic](https://github.com/gee1k/uPic)__?

> uPic(upload Picture) is an image(file) hosting client for Mac.

💡 Tips： They can automatic uploading local file and screenshot, meanwhile the menu bar shows the uploading progress constantly. File's link will automatically copied to the clipboard when finish upload, make you insert pictures quickly when you are blogging or chatting. Link’s format can be a normal URL, HTML or Markdown, it's totally up to you.

#### Install

1. Install with brew

`brew cask install upic`

1. Download from github or Gitee

Click [release](https://github.com/gee1k/uPic/releases) to download.

If you have difficulty accessing Github in mainland China, you can download it from [Gitee release](https://github.com/gee1k/uPic/releases).

#### How to use it?

1. Create a token in your [GitHub settings](https://github.com/settings/tokens)
1. Open the preference of uPic: 
   ![oqdLfF](https://cdn.jsdelivr.net/gh/Fatezhang/FigureCloud@master/uPic/oqdLfF.png)

1. In `Host` section, fill in your name, repo name, branch name and token, also you can check the CDN checkbox to speed up access.
   ![e7o4dc](https://cdn.jsdelivr.net/gh/Fatezhang/FigureCloud@master/uPic/e7o4dc.png)
   
1. In `advance` section, set up your shortcut, and start to use.
