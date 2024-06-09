---
type: PostLayout
title: Easy Way To Create An USB Drive With Windows To Go
date: '2024-05-14'
author: content/data/person1.json
excerpt: >-
  Windows to go is a useful tool for hardware test, data recovery or data
  destruction.
featuredImage:
  type: ImageBlock
  url: /images/usb-svgrepo-com.svg
  altText: Thumbnail
  elementId: ''
  styles:
    self:
      padding:
        - pt-0
        - pl-0
        - pb-0
        - pr-0
bottomSections:
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-3
          - pl-3
          - pb-3
          - pr-3
  - type: RecentPostsSection
    title:
      type: TitleBlock
      text: Recent posts
      color: text-dark
      styles:
        self:
          textAlign: center
    recentCount: 3
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
slug: windows-10-to-go
isFeatured: false
isDraft: false
seo:
  type: Seo
  metaTitle: lorem-ipsum
  metaDescription: lorem-ipsum
  addTitleSuffix: false
  metaTags: []
colors: bg-light-fg-dark
styles:
  self:
    flexDirection: row
---
# Windows 10 To Go

In this post, we’ll explore a simple way to create Windows 10 To Go. Before we begin, you’ll need a Windows 10 ISO image. If you already have one, proceed to Part 2. If not, I recommend obtaining it directly from Microsoft using the Media Creation Tool or creating an ISO image from your installation disk.

**Part 1**

Here’s the link to download the previously mentioned tool. Click to download the image: Microsoft Windows 10 Download.

<https://www.microsoft.com/en-us/software-download/windows10>

To obtain a Windows 10 ISO image, run the Media Creation Tool. As of the creation of this post, version 21H2 is the latest, but it’s recommended to use the most recent version from Microsoft’s official site.![](https://preview--magnificent-steel-ff249.stackbit.dev/_static/app-assets/public/images/media.png)

![](/images/win10-1.png)

Wait until the application displays the terms and conditions screen; this might take a few minutes.

![](/images/win10-2.png)

Accept the terms and conditions to proceed to the next step.

![](/images/win10-3.png)

In this window, you’ll be asked what you want to do. While this tool can also be used to upgrade from Windows 7 to Windows 10 (the first option), our goal here is to obtain an ISO image. Therefore, choose the second option and click Next.

In the next step, to change the language, edition, and architecture, uncheck the “Use the recommended options for this PC” box. Select the desired language, edition, and architecture, then click Next.

![](/images/win10-4.png)

***

This step presents two options: the first for creating a Windows installation USB device, and the second for downloading an ISO file to burn onto a DVD. We need the second option to create Windows 10 To Go, so select it and click Next.

![](/images/win10-5.png)

Choose a name and location to save the file.

![](/images/win10-6.png)

Now, wait for the file to download; this may take several minutes. Wait until the next window appears.

![](/images/win10-7.png)

If you’ve reached this window, the download is complete. Simply click Finish to exit the program.

![](/images/win10-8.png)

**Part 2**

Let’s proceed with the second part of creating Windows 10 To Go using the Rufus tool. Here are the steps:

**Download Rufus**:

*   You can download Rufus from its official website: <https://rufus.ie/en/>

*   Make sure to get the latest version (4.4 at the time of writing).

**Prepare Your USB Drive**:

*   You’ll need a USB drive with at least 32 GB of capacity. Larger drives are recommended to allow space for additional applications.

*   Connect your USB drive to your computer.

![](/images/rufus-wintogo.png)

*   Run the Rufus software on your Windows 10 or Windows 11 PC.

**Configure Rufus**:

*   Select your USB drive from the “Device” drop-down menu.

*   Click the “Select” button next to the “Boot Selection” field and choose your Windows 10/11 ISO image file.

*   In the “Image option” field, change it to “Windows to Go.”

**Start the Process**:

![](/images/rufus-wintogofatality.png)

*   Confirm that you’re ready to proceed (this is the point of no return).

*   Click “OK” and wait for Rufus to create the bootable USB drive.

![](https://preview--magnificent-steel-ff249.stackbit.dev/_static/app-assets/public/images/rufus-wintogo-version.png)

*   Select the one version of windows and click Ok and wait until Rufus says Ready, this may take several minutes.

***

**Boot from the USB Drive**:

*   Once the process is complete, you can boot any compatible terminal using the USB drive.

*   Depending on the brand and model of the terminal, you may need to modify the boot sequence or select the USB drive from the boot menu.

Remember that creating a Windows To Go USB drive allows you to run Windows 10/11 from the USB drive itself. It’s a handy solution for portable computing or troubleshooting. Good luck! 
