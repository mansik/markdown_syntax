# markdown-syntax

#### 참고 사이트

> - [markdown syntax](https://www.markdownguide.org/basic-syntax/#code)  
> - [markdownguide](https://www.markdownguide.org/)  
> - [github](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)  


# Heading 표시(`#`)

- Command Mode에서 작업 : Esc 또는 Ctrl + m
- Command Mode에서 키보드 1 -> Enter -> Down 키로 입력할 수도 있음

# `#` Heading level 1
## `##` Heading level 2
### `###` Heading level 3
#### `####` Heading level 4
##### `#####` Heading level 5
##### `######` Heading level 6

# 줄바꿈(space space enter)

space space enter  
후 실행하면 줄바꿈으로 표기된다.  

이 줄은 edit mode 에서
enter 후 바로 입력하여 2줄로 표시되는데 실행하면 줄바꿈이 안된다.  

- 또는 줄의 처음을 `-`, `+`, `*`, `#`, `>` 등 특수한 목적의 문자로 시작하면 줄바꿈 된다.
- This is the first line.  
And this is the second line. 


# Bold(`**`), Italic(`*`), Bold and Italic(`***`)

I just love **bold text**.  
This text is *really important*.  
Love**is**bold.  
A*cat*meow  
This is really ***very*** important text.  


# Blockquotes(`>`, `>>`: 인용부호)

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

# Lists(`1. `, `2. `, `3. `)

1. First item   
2. Second item  
--- 
1. First item
2. Second item  
    1. Indented item  
    2. Indented item
3. Third item 

# Unordered Lists(`- `, `+ `, `* `)

- 🍎
- 🍋

---

- First item
- Second item  

---  

* First item
* Second item  

---

+ First item  
+ Second item  

---

- First item  
- Second item  
    - Indented item  
    - Indented item  
- Fourth item  


# Code(`)

- At the command prompt, type `nano`.
- ``Use `code` in your Markdown file.``


# Code Block(```언어명)

> 사용언어명을 명시하지 않음

```
name = input('your name: ')
print(name)
```

> 사용언어명을 명시

```python
name = input('your name: ')
print(name)
```

# Horizontal Rules(`***`, `---`, `___`)

***

---

___


# Image(`![Image](url)`)

> Drag & Drop 로 가능  

![Image](http://url/a.png) 


# Url(`[link](http://google.com)`)

[link](http://google.com)


# Table(`|`, `---`, `:`)

> `:` 는 정렬, `:---` 좌측 정렬, `---:` 우측 정렬, `:---:` 가운데 정렬

|Header|Description|
|---|---|
|cell|cell|
|cell|cell|


|Header|Description|
|:---:|:---|
|cell|cell|
|cell|cell|


# Task lists

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull requestTask lists
