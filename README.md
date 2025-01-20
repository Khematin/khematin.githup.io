<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome Page</title>                 ใช้สำหรับกำหนดชื่อของหน้าเว็บที่จะแสดงในแถบชื่อ
  <style>
    body {
      background-color: #f0f8ff;
      font-family: Arial, sans-serif;              โค้ดนี้จะทำให้เนื้อหาภายในหน้าเว็บถูกจัดให้อยู่กลางหน้าจอทั้งในแนวนอนและแนวตั้ง ด้วยพื้นหลังสีฟ้าอ่อนและฟอนต์แบบ Arial โดยไม่มีการเว้นระยะรอบๆ หน้า.
      display: flex;
      justify-content: center;
      align-items: center;      
      height: 100vh;            
      margin: 0;                
    }
    .container {
      max-width: 800px;
      width: 100%;
      background-color: #ffffff;                                                                 .container จะมีขนาดที่ยืดหยุ่น แต่ไม่เกิน 800px ในความกว้าง
                                                                                                      พื้นหลังสีขาว, ขอบโค้งมน, เงาเบาๆ, และข้อความที่จัดกลาง
                                                                                                    มีช่องว่างรอบๆ เนื้อหาและช่องว่างระหว่าง .container กับส่วนอื่นๆ ในหน้าของคุณ
      padding: 20px;
      margin-top: 40px;
      border-radius: 10px;
      box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
      text-align: center;
    }
    h1 {
      color: #333333;
      font-size: 36px;                 ขนาดตัวอักษร
      margin-top: 50px;
    }
    p {
      color: #666666;
      font-size: 18px;                             ข้อความใน <p> จะมีสีเทา, ขนาดฟอนต์ 18px และมีระยะห่างระหว่างบรรทัดที่สบายตา (1.6 เท่าของขนาดฟอนต์)
                                                    ย่อหน้าจะมีความกว้างสูงสุด 600px และจะอยู่กลางหน้าจอ (ทั้งในแนวนอน)
                                                    มีช่องว่าง 20px รอบๆ ย่อหน้าเพื่อทำให้เนื้อหาดูไม่ชิดกับขอบ
                                                      ข้อความภายในย่อหน้าจะถูกจัดให้ตรงกลางในแนวนอ
      line-height: 1.6;
      max-width: 600px;
      margin: 20px auto;
      text-align: center;
    }    
    .cat-image {
      width: 500px;
      height: auto;                                                            
      margin: 20px auto;
      border-radius: 10px;
      box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);                                    ภาพจะมีความกว้าง 500px และความสูงจะปรับตามสัดส่วนภาพจะมีมุมโค้งมนที่ 10px และมีเงาบางๆ ที่ด้านล่าง
                                                                                  ภาพจะอยู่กลางในแนวนอนของหน้าเว็บ และมีช่องว่าง 20px ด้านบนและด้านล่าง
                                                                                การใช้ display: block; ทำให้สามารถจัดตำแหน่งภาพได้ง่ายและจัดการกับการวางภาพในพื้นที่หน้าเว็บ
    }
  </style>
</head>
<body>
  <div class="container">  
    <h1>ยินดีต้อนรับ</h1>    จะมีข้อความ "ยินดีต้อนรับ" แสดงเป็นหัวเรื่องใหญ่ที่สุด
    <p>เว็บเพจง่ายๆ</p>     ข้อความ "เว็บเพจง่ายๆ" จะแสดงในรูปแบบย่อหน้าทั่วไป
    <img class="cat-image" src="https://ichef.bbci.co.uk/news/640/cpsprodpb/9970/live/9e4ab180-fd11-11ed-b2aa-9935735a579c.png" alt="Cute Cat"> มีภาพแมวแสดงตาม URL ที่กำหนดไว้
  </div>  
</body>
</html>
