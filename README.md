# markdown-syntax

#### 참고 사이트

> - [markdown syntax](https://www.markdownguide.org/basic-syntax/#code)  
> - [markdownguide](https://www.markdownguide.org/)  
> - [github](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)  


# Heading 표시(`#`)

- Command Mode에서 작업 : Esc 또는 Ctrl + m
- Command Mode에서 키보드 1 -> Enter -> Down 키로 입력할 수도 있음

***- syntax:***

```markdown
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
##### Heading level 6
```

***- result:***

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
##### Heading level 6


# 줄바꿈(space space enter)

***- syntax:***

```markdown
space space enter  
후 실행하면 줄바꿈으로 표기된다.  

이 줄은 edit mode 에서
enter 후 바로 입력하여 2줄로 표시되는데 실행하면 줄바꿈이 안된다.  

- 또는 줄의 처음을 `-`, `+`, `*`, `#`, `>` 등 특수한 목적의 문자로 시작하면 줄바꿈 된다.
- This is the first line.  
And this is the second line. 
```

***- result:***

space space enter  
후 실행하면 줄바꿈으로 표기된다.  

이 줄은 edit mode 에서
enter 후 바로 입력하여 2줄로 표시되는데 실행하면 줄바꿈이 안된다.  

- 또는 줄의 처음을 `-`, `+`, `*`, `#`, `>` 등 특수한 목적의 문자로 시작하면 줄바꿈 된다.
- This is the first line.  
And this is the second line. 


# Bold(`**`), Italic(`*`), Bold and Italic(`***`)

***- syntax:***

```markdown
I just love **bold text**.  
This text is *really important*.  
Love **is** bold.  
A *cat* meow  
This is really ***very*** important text. 
```

***- result:***

I just love **bold text**.  
This text is *really important*.  
Love **is** bold.  
A *cat* meow  
This is really ***very*** important text.  


# Blockquotes(`>`, `>>`: 인용부호)

***- syntax:***

```markdown
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

***- result:***

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

# Lists(`1. `, `2. `, `3. `)

***- syntax:***

```markdown
1. First item   
2. Second item
```

***- result:***

1. First item   
2. Second item  

--- 

***- syntax:***

```markdown
1. First item
2. Second item  
    1. Indented item  
    2. Indented item
3. Third item 
```

***- result:***

1. First item
2. Second item  
    1. Indented item  
    2. Indented item
3. Third item 

# Unordered Lists(`- `, `+ `, `* `)

***- syntax:***

```markdown
- 🍎
- 🍋
```

***- result:***

- 🍎
- 🍋

---

***- syntax:***

```markdown
- First item
- Second item 
```

***- result:***

- First item
- Second item  

---  

***- syntax:***
```markdown
* First item
* Second item  
```

***- result:***  
* First item
* Second item  

---

***- syntax:***

```markdown
+ First item  
+ Second item 
```

***- result:***

+ First item  
+ Second item  

---

***- syntax:***

```markdown
- First item  
- Second item  
    - Indented item  
    - Indented item  
- Fourth item  
```

***- result:***

- First item  
- Second item  
    - Indented item  
    - Indented item  
- Fourth item  


# Code(`)

***- syntax:***

```markdown
- At the command prompt, type `nano`.
- ``Use `code` in your Markdown file.``
```

***- result:***

- At the command prompt, type `nano`.
- ``Use `code` in your Markdown file.``


# Code Block(```언어명)

## 사용언어명을 명시하지 않음(```)

***- syntax:***

```markdown
` ` `
name = input('your name: ')
print(name)
` ` `
```

***- result:***

```
name = input('your name: ')
print(name)
```

## 사용언어명을 명시(```python   code)

***- syntax:***

```markdown
` ` `python
name = input('your name: ')
print(name)
` ` `
```

***- result:***

```python
name = input('your name: ')
print(name)
```

# Horizontal Rules(`***`, `---`, `___`)

***- syntax:***

```markdown
***
```

***- result:***

***

***- syntax:***

```markdown
---
```

***- result:***

---

***- syntax:***

```markdown
___
```

***- result:***

___


# Image(`![Image](url)`)

> Drag & Drop 로 가능  

***- syntax:***

```markdown
![Image](http://url/a.png) 
```

***- result:***

![Image](http://url/a.png) 


# Url(`[link](http://google.com)`)

***- syntax:***

```markdown
[link](http://google.com)
```

***result:***

[link](http://google.com)


# Table(`|`, `---`, `:`)

- `:` 는 정렬, `:---` 좌측 정렬, `---:` 우측 정렬, `:---:` 가운데 정렬

***- syntax:***

```markdown
|Header|Description|
|---|---|
|cell|cell|
|cell|cell|
```

***- result:***

|Header|Description|
|---|---|
|cell|cell|
|cell|cell|

***- syntax:***  
```markdown
|Header|Description|
|:---:|:---|
|cell|cell|
|cell|cell|
```

***- result:***

|Header|Description|
|:---:|:---|
|cell|cell|
|cell|cell|


# Task lists

***- syntax:***

```markdown
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull requestTask lists
```

***- result:***

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull requestTask lists


# 호환성을 위해 문장 앞뒤로 빈줄 삽입을 해야 하는 상황

 - Heading(`#`) 문자
 - Blockquotes(`>`) 문자
 - Line(`---`) 문자
 
 - 예제)
  ```
  # Heading 아래에 빈줄 샆입
 
 > Blockquotes 위에 빈줄 삽입
 > 여기는 붙어서
 >
 > Blockquotes 아래에 빈줄 삽입
 
 글을 쓰면, 아래에 Line 있으므로 Line 위, 아래에 빈줄 삽입
 
 ---
 
 위에 Line 이 있으므로 빈줄 삽입
 ```
