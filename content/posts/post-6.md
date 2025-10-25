---
title: "ОБРАЗЦЫ КРАТКОГО КОДИРОВАНИЯ ОБЪЕКТОВ - hugo shortcodes"
date: 2025-10-18T12:13:36+05:30
description: "Пример записи с разными образцами краткого кодирования изображений, видео, фрагментов кода и т.д. (Hugo shortcodes) для вставки в записи."
tldr: "Образцы Hugo Shortcodes для копи-паста"
tags: [For copy-paste]
draft: true
toc: true
---
**Введение**

Это пример записи, имеющей принятую на этом сайте структуру, с разными образцами обрабатываемого Hugo краткого кодирования разных объектов, которые можно вставлять в записи на этом сайте (Hugo Shortcodes).
При документировании посредством Hugo и определенной темы для него полезна «заготовка» для документов, где собраны все примеры доступного наполнения записей с помощью так называемых Hugo Shortcodes. Здесь - именно такая заготовка для записей на сайте. 

##  1. Изображения / Images
Пример для вставки в запись изображения по ссылке с внешнего сайта (unsplash.com). Изображение вставляется дважды, с указанными названиями, при этом ему задаются разные размеры:
{{< figure src="https://images.unsplash.com/photo-1560032779-0a8809186efd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80" title="Dave Herring, photo 1" >}}

{{< figure src="https://images.unsplash.com/photo-1560032779-0a8809186efd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=80" title="Dave Herring, photo 2" >}}

##  2. Код из Github Gist
Пример для вставки Gist (короткого фрагмента кода) с сайта Github по имени пользователя и gist_id:
{{< gist spf13 7896402 >}}

##  3. Видео с Youtube / Youtube video
Пример для вставки видео с Youtube по короткой ссылке. Видео можно просматривать и управлять просмотром, читая запись:
{{< youtube w7Ft2ymGmfc >}}

##  4. Видео с Vimeo / Vimeo video
Пример для вставки видео с сайта Vimeo.com по идентификатору. Видео также можно просматривать и управлять просмотром, читая запись:
{{< vimeo id="146022717" >}}

##  5. Пост из X (ex-Twitter) / Tweet
Пример для вставки поста из сети X (ex-Twitter) по имени пользователя и id поста:
{{< tweet user="GoHugoIO" id="877500564405444608" >}}

##  6. Пост из Instagram
Пример для вставки поста из сети Instagram по id поста:
{{< instagram BWNjjyYFxVx >}}

##  7. Врезки / Callouts

### 7.1 "По умолчанию" / Original

{{< callout emoji="⚡️" text="Это врезка 'по умолчанию' / This is an original callout." >}}

### 7.2 Предупреждение / Warning

{{< callout type="warning" text="This is a warning callout." >}}

### 7.3 Предостережение / Alert

{{< callout type="alert" text="This is an alert callout." >}}

### 7.4 Подсказка / Tip

{{< callout type="tip" text="This is a tip callout." >}}

### 7.5 Пользовательская / Custom

{{< callout type="custom" emoji="⚡️" title="Custom callout" text="This is custom text for a custom callout." style="background-color: transparent; border: 3px solid #d340e0;" >}}
