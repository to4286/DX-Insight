### 1. 제목 (Headers):

"#"이 적을 수록 제목의 외형크기가 커진다.
```markdown
# 제목1
## 제목2
### 제목3
```
---

### 2. 볼드 및 이텔릭(Bold & Italic):

```markdown
**볼드 텍스트**
*이텔릭 텍스트*
```
결과: **볼드 텍스트**, *이탤릭 텍스트*

---

### 3. 목록(Lists):

첫 줄에 숫자를 입력 후, .와 함께 space를 누르면 숫자 순서대로 목록이 생성된다. 첫 줄에 -로 시작하고 space를 누르고 문자를 입력하는 순서없는 목록이 된다.

```markdown
- 항목 1
- 항목 2
  - 하위 항목
1. 순서 있는 항목 1
2. 순서 있는 항목 2
```
결과:

- 항목 1
- 항목 2
	- 하위 항목
1. 순서 있는 항목 1
2. 순서 있는 항목 2

---

### 4. 링크(Links):

문서내의 링크를 지정한다. [] 안에는 메시지 () 안에는 링크정보를 입력한다.

```markdown
[링크 텍스트](http://www.google.com)
```

결과: [링크텍스트](http://www.google.com)

---

### 5. 이미지(Images):

링크와 같지만 !로 시작한다. 그리고 url이나 경로명을 ()에 넣는다.

```markdown
![](
https://media1.giphy.com/media/xUPGcl6cOTC5TC2pEY/giphy.gif?cid=ecf05e478h94wnl5lpyf7f0uv4kzdb6pe2622xby2l7v2whv&ep=v1_gifs_search&rid=giphy.gif&ct=g)
```

결과: ![](https://media1.giphy.com/media/xUPGcl6cOTC5TC2pEY/giphy.gif?cid=ecf05e478h94wnl5lpyf7f0uv4kzdb6pe2622xby2l7v2whv&ep=v1_gifs_search&rid=giphy.gif&ct=g)


---

### 6. 코드(Code):

소스코드를 표시한다. 첫줄에 사용하는 언어를 표시하면 해당언어에 맞게 syntaxhighighting도 지원한다.

```python
인라인 코드: '코드 예제'
코드 블록:

~~~python
def hello_world():
	print("Hello, world!")
~~~
```

결과:

```python
def hello_world():
	print("Hello, world!")
```

---

### 7. 인용문(Blockquotes):

```markdown
> 이것은 인용문입니다.
```

결과:

> 이것은 인용문입니다.

---

### 8. 구분선:

-를 3개 입력하면 구분선을 표시한다.

```markdown

---

```

결과:

---

### 9. 표:

```markdown
| 제목 | 내용 |
| --- | --- |
| 고양이 | 성격은 특이하지만 보고 있으면 기분이 좋아지는 동물 |
```

결과:

| 제목  | 내용                           |
| --- | ---------------------------- |
| 고양이 | 성격은 특이하지만 보고 있으면 기분이 좋아지는 동물 |






