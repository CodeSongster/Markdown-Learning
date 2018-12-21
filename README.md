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
### title
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
### blockquote
```markdown
> blockquote1
>> blockquote2
>>> blockquote3
```
> blockquote1
>> blockquote2
>>> blockquote3
<!-- code -->
### code
#### use ```
    ```[c|java|html|python...]
        <!-- code -->
    ```
such as java code

```java
public static void main(String[] args) {
    System.out.println("java code");
}
```
#### use indent
you can use tab of four whitespace before every line of code
```markdown
    int main() {
        println("c code")
    }
```
result
```c
int main() {
    println("c code")
}
```
<!-- font style -->
### font style
```markdown
*italic font* 
**bold font**
```
*italic font*   
**bold font**
<!-- list -->
### list
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
### split line
```markdown
---
```
---
<!-- link -->
### link
#### anchor
```markdown
[back to top ↑](#markdown-grammar)
```
[back to top ↑](#markdown-grammar)
> ! link target must be lowercase and contains no whitespace
#### external
```markdown
[personal blog](http://www.liyupi.top)
```
[personal blog](http://www.liyupi.top)
<!-- tag -->
### tag
```markdown
`ctrl+a` `ctrl+d`
```
`ctrl+a` `ctrl+d`
<!-- table -->
### table
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
