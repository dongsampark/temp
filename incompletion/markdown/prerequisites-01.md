# Markdown 사용

### Markdown 이란?
- Github 및 다양한 플랫폼에서 텍스트를 스타일링하기 위한 문법입니다.
- 사주 용하는 것들 위주로 정리하였으며, 이 외에 자세한 내용은 [개발자 사이트](http://daringfireball.net/projects/markdown/) 참고 하시길 바랍니다.

### 1. Header
```
# this is h1
## this is h2
### this is h3
#### this is h4
##### this is h5
###### this is h6
```
- `#` 기호를 이용하여 글자 크기를 조절 할 수 있습니다.
- `#` (h1), `##` (h2)는 자동으로 수평선(Horizontal Rule)이 생성 됩니다.

### 2. Horizontal Rule
```
*** (Asterisk)
--- (Hyphen)
___ (Underscore)
```

### 3. Blockquotes
```Bash
>
>>
```
- 인용문을 작성할때 사용합니다.

### 4. Lists
```Bash
* Red
* Green
* Blue

+ Red
  + Green
  + Blue

- Red
  - Green
    - Blue
```
- `*`, `+`, `-` 모두 동일한 기능을 합니다.

```Bash
# Ex1
1. A
2. B
3. C
# Ex2
3. A
9. C
5. B
# Ex3
8. C
2. A
4. B
```
- 숫자를 이용하여 목록을 만들 수 있습니다.
- `Ex2`, `Ex3`의 결과는 모두 `Ex1`과 동일 합니다.

### 5. Code Blocks
```
~~~
Hello World
~~~
```

~~~
```
Hello World
```
~~~
- Grave Accent ( \` ) 와 Tilde \( ~ )를 이용한다.
- Atom에서는 code 라고 입력한 후, Enter키를 이용하면 자동으로 코드 블록을 생성한다.

~~~c
```c
#include<stdio.h>
int main(int argc, char * argv[])
{
    printf("Hello World!\n");
    return 0;
}
```
~~~
- 코드에 사용된 언어를 명시하면, Syntax highlight가 활성화 된다.

### 6. Images
```
![TEXT](IMAGE_FILE_PATH)
![TEXT](IMAGE_URL)
```
- Repository 경로에 위치한 이미지와 외부에 위치한 이미지를 사용할 수 있습니다.

### 7. Link
```
https://github.com/parkdongsam
[PARK DongSam GitHub](https://github.com/parkdongsam)
```
- URL주소를 작성하면 자동으로 링크가되며, 다른 텍스트로 대체할 수 있습니다.
