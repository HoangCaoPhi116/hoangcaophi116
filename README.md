<!DOCTYPE html>
<html>
<head>
</head>
<body>
	<a href="https://topdev.vn/blog/can-giua-phan-tu-trong-css/">Căn giữa CSS</a>
	<h1>CSS Transforms</h1>
	<p>CSS Transforms cho phép bạn translate(dịch), rotate(xoay), scale(tỉ lệ), skew(nghiêng) phần tử.
	</p>
	<p>Là sự thay đổi hình dạng, kích thước và vị trí.</p>
	<p>Những phương thức thông dụng :</p>
	<ul>
		<li>translate()</li>
		<li>rotate()</li>
		<li>scale()</li>
		<li>skewX()</li>
		<li>skewY()</li>
		<li>matrix()</li>
	</ul>
	<h3>Phương thước translate() di chuyển phần tử từ vị trí hiện tại của mình(theo trục X và Y)</h3>
	<p>Ví dụ dưới đây di chuyển phần tử div 50px sang bên phải và 100px xuống phía dưới theo vị trí hiện tại.</p>
	<pre>
		div {
 			 -ms-transform: translate(50px, 100px); /* IE 9 */
 			 -webkit-transform: translate(50px, 100px); /* Safari */
  			 transform: translate(50px, 100px);
		}
	</pre>
	<a href="https://www.w3schools.com/css/tryit.asp?filename=trycss3_transform_translate">Tự mình thử</a>
	<h3>Phương thức rotate() xoay phần tử theo chiều kim đồng hồ hoặc ngược chiều kim đồng hồ theo độ đo</h3>
	<p>Ví dụ dưới đây xoay cùng chiều kim đồng hồ lệch 20 độ</p>
	<pre>
		div {
 			 -ms-transform: rotate(20deg); /* IE 9 */
 			 -webkit-transform: rotate(20deg); /* Safari */
 			  transform: rotate(20deg);
		}
	</pre>
	<a href="https://www.w3schools.com/css/tryit.asp?filename=trycss3_transform_rotate2">Ví dụ</a>
	<p>Sử dụng giá trị âm thì xoay ngược chiều kim đồng hồ</p>
	<h3>Phương thức scale() để tăng phần tử số lần so với kích thước ban đầu của nó</h3>
	<p>Ví dụ dưới đây tăng phần tử div 2 lần so với chiều rộng và 3 lần so với chiều cao.</p>
	<pre>
		div {
		  -ms-transform: scale(2, 3); /* IE 9 */
		  -webkit-transform: scale(2, 3); /* Safari */
		  transform: scale(2, 3);
		}
	</pre>
	<a href="https://www.w3schools.com/css/tryit.asp?filename=trycss3_transform_scale">Ví dụ</a>
	<h3>Phương thức skewX()</h3>
	<p>Làm lệch phần tử chiều dọc theo chiều X</p>
	<p>Ví dụ dưới đây nghiêng phần tử 20 độ theo chiều dọc với trục Ox</p>
	<pre>
		div {
			  -ms-transform: skewX(20deg); /* IE 9 */
			  -webkit-transform: skewX(20deg); /* Safari */
			  transform: skewX(20deg);
		}
	</pre>
	<a href="https://www.w3schools.com/css/tryit.asp?filename=trycss3_transform_skewx">Ví dụ</a>
	<h3>Phương thức skewY()</h3>
	<a href="https://www.w3schools.com/css/tryit.asp?filename=trycss3_transform_skewy">Ví dụ</a>
	<h3>Phương thức skew()</h3>
	<a href="https://www.w3schools.com/css/tryit.asp?filename=trycss3_transform_skew2">Ví dụ</a>
	<p>Là sự kết hợp của skewX() và skewY()</p>
	<h3>Phương thức matrix() kết hơp tất cả phương thức 2D ở trên</h3>
	<b>matrix(scaleX(),skewY(),skewX(),scaleY(),translateX(),translateY())</b></br>
	<a href="https://www.w3schools.com/css/tryit.asp?filename=trycss3_transform_matrix1">Ví dụ</a>
	<h1>CSS 3D Transforms</h1>
	<h3>Phương thức rotateX()</h3>
	<p>Phương thức giúp phần tử xoay quanh trục X với 1 yếu tố nhất định(kiểu xoay tờ giấy quanh trục ox)</p>
	<pre>
		#myDiv {
		  -webkit-transform: rotateX(150deg); /* Safari */
 		   transform: rotateX(150deg);
		}
	</pre>
	<a href="https://www.w3schools.com/css/tryit.asp?filename=trycss3_transform_rotateX">Ví dụ</a>
	<h3>Phương thức rotateY()</h3>
	<p>Phương thức giúp phần tử xoay quanh trục Y với 1 yếu tố nhất định(kiểu xoay tờ giấy quanh trục oy)</p>
	<pre>
		#myDiv {
		  -webkit-transform: rotateY(150deg); /* Safari */
 		   transform: rotateY(150deg);
		}
	</pre>
	<a href="https://www.w3schools.com/css/tryit.asp?filename=trycss3_transform_rotateY">Ví dụ</a>
	<h3>Phương thức rotateZ()</h3>
	<p>Phương thức giúp phần tử xoay quanh trục Z với 1 yếu tố nhất định(kiểu xoay tờ giấy quanh trục oz)</p>
	<pre>
		#myDiv {
		  -webkit-transform: rotateZ(150deg); /* Safari */
 		   transform: rotateZ(150deg);
		}
	</pre>
	<a href="https://www.w3schools.com/css/tryit.asp?filename=trycss3_transform_rotateZ">Ví dụ</a>
	<h1>CSS Transitions	</h1>
</body>
</html>
