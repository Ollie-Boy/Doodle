+++
title = "What Doodle theme can provide to you"
date = "2024-11-07"
draft = false
description = "My golden fingers."
tags = ["hugo","perosonalize"]
+++

# blockquote
1. **Normal quote:**
```txt
{{</* blockquote >}}
  This is a simple quote.
{{< /blockquote */>}}
```
{{< blockquote >}}
  This is a simple quote.
{{< /blockquote >}}

2. **Quote with author:**
```txt
{{</* blockquote author="`Ollie`" >}}
  This is a quote with only an author named Ollie.
{{< /blockquote */>}}
```
{{< blockquote author="Ollie" >}}
  This is a quote with only an author named Ollie.
{{< /blockquote >}}

3. **Quote with author and source:**
```txt
{{</* blockquote author="Ollie" source="Source" >}}
  This is a quote from Ollie and source "source."
{{< /blockquote */>}}
```
{{< blockquote author="Ollie" source="Source" >}}
  This is a quote from Ollie and source "source."
{{< /blockquote >}}

4. **Quote with author and link:**
```txt
{{</* blockquote author="Ollie" link="https://example.com" >}}
  This is a quote from Ollie and links to https://example.com.
{{< /blockquote */>}}
```
{{< blockquote author="Ollie" link="https://example.com" >}}
  This is a quote from Ollie and links to https://example.com.
{{< /blockquote >}}

5. **Quote with author, link and title:**
```txt
{{</* blockquote author="Ollie" link="https://example.com" title="title" >}}
  This is a quote from Ollie and links to https://example.com with title "title".
{{< /blockquote */>}}
```
{{< blockquote author="Ollie" link="https://example.com" title="title" >}}
  This is a quote from Ollie and links to https://example.com with title "title".
{{< /blockquote >}}
# image gallery
```txt
{{</* image-gallery gallery_dir="/images/Usage For Shortcodes" */>}}
```
{{< image-gallery gallery_dir="/images/Usage For Shortcodes" >}}
# sidenote
```txt
{{</* sidenote `
Some content.
` >}}
This is a sidenote. :smile:
{{< /sidenote */>}}
```
{{< sidenote `
Some content.
` >}}
This is a sidenote. :smile:
{{< /sidenote >}}
```txt
{{</* sidenote `
Another content.
` left >}}
And sidenote on the left side. :sunglasses:
{{< /sidenote */>}}
```
{{< sidenote `
Another content.
` left >}}
And sidenote on the left side. :sunglasses:
{{< /sidenote >}}
# audio
```txt
{{</* audio mp3="/audio/bird-sing.mp3" */>}}
{{</* audio mp3="/audio/Voicy_Happy Happy Happy.mp3" */>}}
{{</* audio mp3="/audio/we-wish-you-a-merry-christmas-happy-remix-background-intro-theme-277943.mp3" */>}}
```
{{< audio mp3="/audio/bird-sing.mp3">}}
{{< audio mp3="/audio/Voicy_Happy Happy Happy.mp3" >}}
{{< audio mp3="/audio/we-wish-you-a-merry-christmas-happy-remix-background-intro-theme-277943.mp3" >}}

{{< sidenote `
# collapsible
` left >}}
From collapsible to badge, all codes are based on [zwbetz-gh](https://zwbetz.com/)'s [papercss-hugo-theme](https://github.com/zwbetz-gh/papercss-hugo-theme), I appreciate. ❤️
{{< /sidenote >}}
```txt
{{</* collapsible "One Layer Collapsible" */>}}
Content here.
{{</* /collapsible */>}}
```
{{< collapsible "One Layer Collapsible" >}}
Content here.
{{< /collapsible >}}
```txt
{{</* collapsible "A" */>}}
Some contents here.
{{</* /collapsible */>}}
{{</* collapsible "B" */>}}
Other contents here.
{{</* /collapsible */>}}
```
{{< collapsible "A" >}}
Some contents here.
{{< /collapsible >}}
{{< collapsible "B" >}}
Other contents here.
{{< /collapsible >}}
# color
```txt
{{</* color "primary" */>}}
Primary
{{</* /color */>}}
```
{{< color "primary" >}}
Primary
{{< /color >}}
```txt
{{</* color "secondary" */>}}
Secondary
{{</* /color */>}}
```
{{< color "secondary" >}}
Secondary
{{< /color >}}
```txt
{{</* color "success" */>}}
Success
{{</* /color */>}}
```
{{< color "success" >}}
Success
{{< /color >}}
```txt
{{</* color "warning" */>}}
Warning
{{</* /color */>}}
```
{{< color "warning" >}}
Warning
{{< /color >}}
```txt
{{</* color "danger" */>}}
Danger
{{</* /color */>}}
```
{{< color "danger" >}}
Danger
{{< /color >}}
```txt
{{</* color "muted" */>}}
Muted
{{</* /color */>}}
```
{{< color "muted" >}}
Muted
{{< /color >}}
# alert
```txt
{{</* alert >}}
Normal
{{< /alert */>}}
```
{{< alert >}}
Normal
{{< /alert >}}
```txt
{{</* alert "primary" */>}}
Primary
{{</* /alert */>}}
```
{{< alert "primary" >}}
Primary
{{< /alert >}}
```txt
{{</* alert "secondary" */>}}
Secondary
{{</* /alert */>}}
```
{{< alert "secondary" >}}
Secondary
{{< /alert >}}
```txt
{{</* alert "success" */>}}
Success
{{</* /alert */>}}
```
{{< alert "success" >}}
Success
{{< /alert >}}
```txt
{{</* alert "warning" */>}}
Warning
{{</* /alert */>}}
```
{{< alert "warning" >}}
Warning
{{< /alert >}}
```txt
{{</* alert "danger" */>}}
Danger
{{</* /alert */>}}
```
{{< alert "danger" >}}
Danger
{{< /alert >}}
```txt
{{</* alert "muted" */>}}
Muted
{{</* /alert */>}}
```
{{< alert "muted" >}}
Muted
{{< /alert >}}

# background
```txt
{{</* background "primary" */>}}
Primary
{{</* /background */>}}
```
{{< background "primary" >}}
Primary
{{< /background >}}
```txt
{{</* background "secondary" */>}}
Secondary
{{</* /background */>}}
```
{{< background "secondary" >}}
Secondary
{{< /background >}}
```txt
{{</* background "success" */>}}
Success
{{</* /background */>}}
```
{{< background "success" >}}
Success
{{< /background >}}
```txt
{{</* background "warning" */>}}
Warning
{{</* /background */>}}
```
{{< background "warning" >}}
Warning
{{< /background >}}
```txt
{{</* background "danger" */>}}
Danger
{{</* /background */>}}
```
{{< background "danger" >}}
Danger
{{< /background >}}
```txt
{{</* background "muted" */>}}
Muted
{{</* /background */>}}
```
{{< background "muted" >}}
Muted
{{< /background >}}

# badge
```txt
{{</* badge >}}normal{{< /badge */>}}
```
{{< badge >}}normal{{< /badge >}}
```txt
{{</* badge "primary" >}}primary{{< /badge */>}}
```
{{< badge "primary" >}}primary{{< /badge >}}
```txt
{{</* badge "secondary" >}}secondary{{< /badge */>}}
```
{{< badge "secondary" >}}secondary{{< /badge >}}
```txt
{{</* badge "success" >}}success{{< /badge */>}}
```
{{< badge "success" >}}success{{< /badge >}}
```txt
{{</* badge "warning" >}}warning{{< /badge */>}}
```
{{< badge "warning" >}}warning{{< /badge >}}
```txt
{{</* badge "danger" >}}danger{{< /badge */>}}
```
{{< badge "danger" >}}danger{{< /badge >}}
```txt
{{</* badge "muted" >}}muted{{< /badge */>}}
```
{{< badge "muted" >}}muted{{< /badge >}}

# Emojis
Just look this: https://gohugo.io/quick-reference/emojis/.

# Katex

```txt
Euler's identity: $e^{i\pi} + 1 = 0$

$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$
```

Euler's identity: $e^{i\pi} + 1 = 0$

$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$