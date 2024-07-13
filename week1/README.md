- Task Link: https://courses.hexschool.com/courses/2020112211/lectures/53653896
- Precious Codepen: https://codepen.io/coding-angela25/pen/xxNmYYM

<img width="723" alt="SCR-20240713-khcf" src="https://github.com/user-attachments/assets/19ac750c-6990-4e61-9c30-b8b432308a39">


1. RESUME 建議使用 h2 呈現
2. img 的 alt 建議加入相關說明，若圖片失效，使用者能了解大致內容
3. .content 區塊建議改為 div>h3+ul 的方式呈現
```html
<div>
  <h3>Vito Evans</h3>
  <ul>
		<li><p>456 Walnut Avenue, Someville, USA</p></li>
 		<li> <p>+1 123 456 7890</p></li>
  		<li><p>info@hexschool.com</p></li>
  		<li><p>www.infohexschool.com</p></li>
	</ul>
</div>
<div>
  <h3>Education</h3>
	<ul>
		<li>
  			<span class="year">2014-2018</span>
  			<p>Bachelor of Science in Business Administration, University of California, Los Angeles</p>
		</li>		
		...
 	</ul>
</div>
```

4. Vito Evans 區塊的電話、郵件和網頁建議加入 a 連結連到相應位置
```html
<li> <p><a href="tel:+1 123 456 7890">+1 123 456 7890</a></p></li>
<li><p><a href="mailto:info@hexschool.com>info@hexschool.com</a></p></li>
<li><p><a href="www.infohexschool.com">www.infohexschool.com</a></p></li>
```

5. footer 的圖片外建議加入 a 連結連至相應位置
```html
<a href="#"><img src="https://raw.githubusercontent.com/hexschool/2022-web-layout-training/main/2023week1/line.png" class="icon"></a>
```

6. 建議加入 Reset，CodePen 設定如下圖
![alt text](https://images.hexschool.com/qa/12061549261454740128_2024-06-27T05:57:43Z.png)
![alt text](https://images.hexschool.com/qa/12061549261454740128_2024-06-27T05:57:53Z.png)

7. VITO 和上方不須有距離
8. VITO 和 RESUME 中間的圖片、footer 的 icon 沒有正確呈現喔
9. img 建議加入 display:block; 移除圖片下方多餘空間
10. VITO 和 RESUME 的 letter-spacing 為 0.12em
11.  建議在 .container 的 width 中設定整體寬度 1296px

計算方式如下:
![alt text](https://images.hexschool.com/qa/12061549261454740128_2024-06-27T06:01:39Z.png)


計算方式: 86\*12+24*11 = 1296
