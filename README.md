<!--body.special ul > li:first-child > ul > li {
  list-style-type: square;
}

list-style-type: square, disc, circle, etc... -->

# mlstudy
for machine learning study/ custom algorithm included


>0519 update
>
>adding and editing,simplifying functions
>
>_
>
>only df:
>
>pandas.reset_option('display.max_columns')
>
>=> reset options
>
>_
>
>dfn : numbering, dfv : variable_naming
>
> ex {1} {2} {3} ... /  <(x) <(y) <(z) ...
>
>=> just use it, and you know right then exactly.
>
>_
>
>dfx: extended
>
>pandas.set_option('display.max_columns', None)
>
>=> max row and col
>


<hr>

## Setting

1. 사용하기전 <br>
깃 클론 먼저 하시고 <br>
(google colab 사용시엔 앞에 !(느낌표)를 붙일것) <br>
 before using the functions, <br>
 you have to git clone this project. <br>
 (if using google colab, attach the {!} sign) <br>
 
`!git clone https://github.com/ironhopper/mlstudy.git`

2. 사용시 <br>
아래 헤더파일을 복사하여 원하는 프로젝트에 붙여줍니다. <br>
when using functions, <br>
copy and paste below header codes. <br>

```python
import sys
sys.path.append('mlstudy')
from array_check_function import df,dfn,dfv,dfx,dfnx,dfvx
```

3.  `df(X,Y)`   <br>
    `dfx(X,Y)`  <br>
               
                
이런식으로 사용합니다. <br>
df -> 간단하게 볼때 <br>
dfn,dfv -> 칼럼을 숫자로 구분, 칼럼을 변수명으로 구분(써보면 바로 압니다. 파이썬코드에 예제가 있으니 참고 바랍니다.)
dfx -> extended table(전체 데이터 확인용) 입니다. <br>
like above. <br>
df is simple view, <br>
dfx is extended view (full row and column. <br>

variable inspector 대용으로 만들었습니다. <br>
it is alternative of variable inspector <br><br>
<i>**<u>(<i>p.s.</i>)</u>..</i>
<!--    * 
      + PS -->

일반 array,list 도 사용가능하며 아래와 같이 <br>
you can use general array, list, and <br>

```python
Z = np.array([1,2,3])
```
ndarray 도 사용 가능합니다. <br>
ndarray also. <br>

물론 iris data set 도 사용됩니다.

<sub>다른 자료구조들은 사용하신분들의 제보(?)를 부탁드립니다..</sub>

<hr>
