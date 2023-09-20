<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WEB FINAL PROJECT</title>
  <style>
    /* Thiết lập các kiểu CSS */
    body {
      font-family: sans-serif;
      background-color: #006699; 
	  letter-spacing: 1px; /*Dãn chữ */
	  line-height: 1.5; /*Dãn dòng */
    }
    
    h1 {
      color: #000; 
      text-align: center; 
      padding: 40px; 
      background-color: #6699CC; 
      border: 2px solid #000; /* Đường viền cho khung */
    }
    
    p {
      color: red; 
      text-align: center; 
    }
    
    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 30px;
      background-color: #99CCFF; 
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
	  font-size: 18px;
    }
    
    .profile-image {
      display: block;
      margin: 20px auto;
      max-width: 200px; 
      height: auto;
    }
	
    table {
      border-collapse: collapse;
      width: 100%;
    }
  
    th, td {
      border: 1px solid #000;
      padding: 8px;
      text-align: left;
    }
	
    ul {
      margin-left: 20px;
      margin-bottom: 20px;
    }
    
    ol {
      margin-left: 20px;
      margin-bottom: 20px;
    }
    
    .link {
      display: block;
      text-align: center;
      margin-bottom: 20px;
    }
    
    .iframe {
      margin: 20px auto;
      text-align: center;
    }
    
    form {
      text-align: center;
    }
    
	.caption {
	  text-align: center; /* Căn giữa chú thích */
	  color: #666; /* Màu chữ (ví dụ: đỏ) */
	  font-style: italic; /* Kiểu chữ nghiêng */
	}
	
    button {
      padding: 10px 20px;
      background-color: #6699CC;
      color: #ffffff; 
      border: none;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>TRANG WEB CỦA LÊ THIÊN NHI!</h1> 
    <p>Chào mừng cô và các bạn đã ghé xem trang web bài final project của mình!</p> 
    <img src="anh ca nhan.jpg" alt=" Photo" class="profile-image"> 
    <table>
     <tr>
      <td>Tên:</td>
      <td>Lê Thiên Nhi</td>
     </tr>
     <tr>
      <td>Ngày sinh:</td>
      <td>12/06/2003</td>
     </tr>
     <tr>
      <td>Quê quán:</td>
      <td>Bạc Liêu</td>
     </tr>
     <tr>
      <td>Lớp:</td>
      <td>MAS1</td>
     </tr>
     <tr>
      <td>Trường:</td>
      <td>Quản Trị Và Kinh Doanh</td>
     </tr>
  </table>
    <p>Các trang mạng xã hội của mình:</p> 
    <ol>
      <li><a href="https://www.facebook.com/thiennhi120603"> Facebook</a></li>
      <li><a href="https://www.instagram.com/160808_03161127/"> Instagram</a></li>
    </ol> 
	<p class="profile-image">Sở thích của mình:</p>
	<ul>
		<li>Thể thao: mình khá hứng thú khi tham gia các hoạt động thể thao vì nó giúp mình tăng cường sức khỏe về mặt thể chất lẫn tinh thần. Các môn thể thao mình thường chơi là bơi lội và bóng đá, bóng chuyền,... Mình cũng hay tham gia vào các hoạt động ngoại khóa liên quan đến thể thao do nhà trường tổ chức.  </li>
	<figure>
		<img src="the thao.jpg" alt="My Photo" class="profile-image">
		<figcaption class="caption">Ảnh mình tham gia thi bóng đá tại hội thao chào mừng ngày 26/3</figcaption>
	</figure> 
		<li>Nghe nhạc: mình rất thích nghe nhạc, mình có thể dành cả ngày chỉ để ngôì nghe nhạc vì nó không chỉ mang lại âm nhạc và giai điệu tuyệt vời mà còn có thể tạo ra những trạng thái tinh thần khác nhau. Khi ngồi nghe nhạc, mình có thể cảm nhận và truyền tải những cảm xúc sâu sắc mà từng bài hát mang lại. Dạo gần đây mình rất thích nghe bài "Đường tôi chở em về" của anh "bui truonglinh", khi nghe bài này mình cảm nhận được những cung bậc cảm xúc từ niềm vui, hy vọng đến sự nhẹ nhàng và ấm áp. Cô và các bạn cùng nghe thử bài này qua video dưới đây với mình nha!</li>
    </ul>	
    <div class="iframe">
      <iframe width="auto" height="auto" src="https://www.youtube.com/embed/OuNo8Tkb3lI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name"><br>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email"><br>
      <button type="submit">Submit</button> 
    </form>
	</div>
	<footer>
		<p style="color: white;">&copy; 2023 Lê Thiên Nhi. Final Project.</p>
	</footer>	
</body>
</html>
