# Markdown-Grammar
Markdown is a mark language and is useful in writing blogs or documents. This repository show markdown grammar to learn and use it quickly.

# Getting started
### index
>#### [title](#title)
>#### [blockquote](#blockquote)
>#### [font style](#font-style)
>#### [code](#code)
>#### [list](#list)
>#### [split line](#split-line)
>#### [link](#link)
>#### [tag](#tag)
>#### [table](#table)
<!-- title -->
### title {#title}
```markdown
# title1
## title2
### title3
#### title4
##### title5
###### title6
```
# title1
## title2
### title3
#### title4
##### title5
###### title6
<!-- blockquote -->
### blockquote {#blockquote}
```markdown
> blockquote1
>> blockquote2
>>> blockquote3
```
> blockquote1
>> blockquote2
>>> blockquote3
<!-- code -->
### code {#code}
```markdown
    ```[c|java|html|python...]
        <!-- code -->
    ```
```
```c
int main() {
    println("c code")
}
```
```java
public static void main(String[] args) {
    System.out.println("java code");
}
```
<!-- font style -->
### font style {#font style}
```markdown
*italic font* 
**bold font**
```
*italic font* 
**bold font**
<!-- list -->
### list {#list}
#### unordered list
```Markdown
- first
- second
- third
```
- first
- second
- third
#### ordered list
```markdown
1. first
2. second
3. third
```
1. first
2. second
3. third
<!-- split line -->
### split line {#split line}
```markdown
---
```
---
<!-- link -->
### link {#link}
#### anchor
create anchor
```markdown
##### my anchor {#my anchor}
```
##### my anchor {#my anchor}
```markdown
[to my anchor](#my-anchor)
```
[to my anchor](#my-anchor)
> ! Link target must not contain  whitespace or uppercase character, use '-' instead of whitespace and lowercase.
#### external
```markdown
[personal blog](http://www.liyupi.top)
```
[personal blog](http://www.liyupi.top)
<!-- tag -->
### tag {#tag}
```markdown
`ctrl+a` `ctrl+d`
```
`ctrl+a` `ctrl+d`
<!-- table -->
### table {#table}
#### align
left `|:---|`
right `|---:|`
center  `|:--:|`  
```markdown
| name  | age | sex | salary |
|-------|:---:|-----|-------:|
| wang  | 30  | m   | $1,000 |
| ming  | 20  | f   | $2,000 |
| candy | 10  | f   | $0     |
```
| name  | age | sex | salary |
|-------|:---:|-----|-------:|
| wang  | 30  | m   | $1,000 |
| ming  | 20  | f   | $2,000 |
| candy | 10  | f   | $0     |
<!-- back to top -->
[back to top ↑](#markdown-grammar)
