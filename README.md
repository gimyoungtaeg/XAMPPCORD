```html
<!DOCTYPE html>
<html lang="ko">
<head><meta charset="UTF-8">
	<title>HTML intro</title>   <!-- -->
</head>
<body> 
	<h2>여러분을 환영합니다!!</h2> 
	<h2>Unordered List</h2>
	<u1 type="square">
	<li>Coffee</li>
	<li>Tea</li>
	<li>Milk</li>
</u1>
<a href="http://www.gachon.ac.kr" target="_blank">Gacheon</a> <br><!-- 언더바 블랭크는 새 창에서 열린다.-->
<h1>Menu</h1>
<a href="#index1">Coffee</a><br>
<a href="#index2">Cake</a><br>
<a href="#index3">Juice</a><br>
<h2 id="index1">Menu01::Coffee</h2>
<ul>
	<li>Americano</li>
	<li>Cappuccino</li>
	<li>Cafe latte</li>
</ul>
	<h2 id="index2">Menu02::Cake</h2>
<ul>
	<li>Carrot cake</li>
	<li>black tea cake</li>
	<li>strawberry shortcake</li>
</ul>
<h2 id="index3">Menu03::Juice</h2>
<ul>
	<li>orange</li>
	<li>grape</li>
	<li>watermelon</li>
</ul>

<img src="img/im.jpeg">
	<table border="1"><!--테이블은 공간을 나누는 개념 -->
		<tr>
			<th>no.</th>
			<th>name</th>
			<th>email</th>
			<th>tel</th>
		</tr>
		<tr>
			<td>1</td>
			<td>Justin Born</td>
			<td>Justin@google.com</td>
		</tr>
		<tr>
			<td>4</td>
			<td>Mola</td>
			<td>mola@naver.com</td>
			<td>010-4444-5555</td>
		</tr>
	</table>
	<h2>html-11.html:Naver search</h2>
	<form action="2.html">
		search: <input type="text">
		<input type="submit" value="search">
	</form>
	<form>
		<fieldset>
			<legend>성별</legend><!--체크 리스트 하나만 선택됨 -->
			남성<input type="radio" name="gender"value="male"checked/>
			여성<input type="radio" name="gender"value="female"/>
		</fieldset>
		<fieldset>
			<legend>취미</legend><!-- 중복 선택이 가능한 체크리스트-->
			운동<input type="checkbox" name="hobby"value="exercise" checked/>
			영화<input type="checkbox" name="hobby"value="movie"/>
			음악<input type="checkbox" name="hobby"value="music"/>
			기타<input type="checkbox" name="hobby"value="ect"/>
		</fieldset>
	</form>
</body>
<html>
```
