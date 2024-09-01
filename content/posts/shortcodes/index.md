---
title: "Shortcodes"
date: 2024-07-16T17:42:11+09:00
draft: false
tags:
    - "Hugo"
slug: "shortcodes"
---

Useful shortcodes that can be used in Markdown.

<!--more-->

## Embeded shortcodes

### figure

{{< figure src="./images/mathis_800x600.jpg" title="Mathis Castillo in Akita, Japan" >}}

### gist

{{< gist d4c2b0 9d0e3095bb16e7b049b10e8125155790 >}}

### highlight

{{< highlight go-html-template >}}
{{ range .Pages }}
  <h2><a href="{{ .RelPermalink }}">{{ .LinkTitle }}</a></h2>
{{ end }}
{{< /highlight >}}

{{< highlight go-html-template "lineNos=inline, lineNoStart=42" >}}
{{ range .Pages }}
  <h2><a href="{{ .RelPermalink }}">{{ .LinkTitle }}</a></h2>
{{ end }}
{{< /highlight >}}

## instragram

{{< instagram CydnHYfIsry >}}

## twitter

> [!IMPORTANT]
> The cause is unknown, but it may not render correctly.

{{< twitter user="josemaru_model" id="1814286755954397549" >}}

{{< twitter user="josemaru_model" id="1825014863921348774" >}}

## vimeo

{{< vimeo 55073825 >}}
