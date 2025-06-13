<!DOCTYPE html>
<html lang="th">
<nav class="top-menu">
  <ul>
    <li><a href="home.html">หน้าหลัก</a></li>
    <li><a href="Savory food.html">อาหารคาว</a></li>
    <li><a href="dessert.html">อาหารหวาน</a></li>
    <li><a href="dink.html">เครื่องดื่ม</a></li>
    <li><a href="Snacks.html">ของทานเล่น</a></li>
    <li><a href="fruit.html">ผลไม้</a></li>
  </ul>
</nav>

<style>
/* จัดการเมนูหลัก */
.top-menu {
  background-color: #feb61e; /* สีพื้นหลังเมนู */
  padding: 10px 0;
}

.top-menu ul {
  list-style: none; /* ไม่มีจุดหน้าลิสต์ */
  margin: 0;
  padding: 0;
  text-align: center; /* จัดให้อยู่ตรงกลาง */
}

.top-menu ul li {
  display: inline-block; /* แสดงผลแบบบล็อกและจัดเรียงแนวนอน */
  position: relative; /* สำหรับเมนูย่อย */
}

.top-menu ul li a {
  color: rgb(3, 3, 3); /* สีตัวอักษร */
  text-decoration: none; /* ไม่มีขีดเส้นใต้ */
  padding: 15px 20px;
  display: block;
  transition: background-color 0.3s ease; /* เพิ่มเอฟเฟกต์เมื่อโฮเวอร์ */
}

.top-menu ul li a:hover {
  background-color:  #ffce65; /* สีพื้นหลังเมื่อโฮเวอร์ */
}

/* จัดการเมนูย่อย */
.top-menu ul .submenu {
  display: none; /* ซ่อนเมนูย่อยไว้ก่อน */
  position: absolute;
  background-color: #444; /* สีพื้นหลังเมนูย่อย */
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2); /* เงา */
  z-index: 1; /* ให้แสดงทับองค์ประกอบอื่น */
  text-align: left; /* จัดข้อความซ้าย */
}

.top-menu ul li:hover > .submenu {
  display: block; /* แสดงเมนูย่อยเมื่อโฮเวอร์ที่เมนูหลัก */
}

.top-menu ul .submenu li {
  display: block; /* แสดงผลแบบบล็อกสำหรับแต่ละรายการในเมนูย่อย */
}

.top-menu ul .submenu li a {
  padding: 12px 16px;
  color: white;
}

.top-menu ul .submenu li a:hover {
  background-color: #666; /* สีพื้นหลังเมื่อโฮเวอร์ที่เมนูย่อย */
}
</style>
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>ของทานเล่น</title>
<!-- โหลดฟอนต์ Kanit -->
<link href="https://fonts.googleapis.com/css2?family=Kanit&display=swap" rel="stylesheet" />
<style>
  body {
    font-family: 'Kanit', sans-serif;
    margin: 20px;
    background: #f9f9f9;
  }

  h1 {
    text-align: center;
    margin-bottom: 30px;
  }

  .food-list {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
  }

  .food-item {
    background: white;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    width: 220px;
    display: flex;
    flex-direction: column;
    overflow: hidden;
    transition: transform 0.2s ease;
  }
  
  .food-item:hover {
    transform: translateY(-5px);
  }

  .food-image {
    width: 100%;
    height: 140px;
    object-fit: cover;
  }

  .food-info {
    padding: 15px;
    flex-grow: 1;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }

  .food-category {
    font-size: 0.9rem;
    color: #777;
    margin-bottom: 8px;
    text-transform: capitalize;
  }

  .food-name {
    font-size: 1.2rem;
    font-weight: bold;
    margin-bottom: 10px;
  }

  .food-price {
    font-size: 1.1rem;
    color: #2c7a7b;
    font-weight: bold;
  }
</style>
</head>
<body>

<h1>ของทานเล่น</h1>
<div class="food-list">
  <div class="food-item">
    <img class="food-image" src="d:\ขนม\1.jpg" alt="กล้วยฉาบ">
    <div class="food-info">
      <div class="food-category">กล้วยฉาบ</div>
      <div class="food-name">กล้วยฉาบ</div>
      <div class="food-price">ราคา 40 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\ขนม\2.jpg" alt="ชีสบอล">
    <div class="food-info">
      <div class="food-category">ชีสบอล</div>
      <div class="food-name">ชีสบอล</div>
      <div class="food-price">ราคา 60 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\ขนม\3.jpg" alt="เห็ดเข็มทองทอด">
    <div class="food-info">
      <div class="food-category">เห็ดเข็มทองทอด</div>
      <div class="food-name">เห็ดเข็มทองทอด</div>
      <div class="food-price">ราคา 59 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\ขนม\4.jpg" alt="เปาะเปี๊ยะ">
    <div class="food-info">
      <div class="food-category">เปาะเปี๊ยะ</div>
      <div class="food-name">เปาะเปี๊ยะ</div>
      <div class="food-price">ราคา 50 บาท</div>
    </div>
  </div>
</div>
<div class="food-list">
  <div class="food-item">
    <img class="food-image" src="d:\ขนม\5.jpg" alt="หนังไก่ทอด">
    <div class="food-info">
      <div class="food-category">หนังไก่ทอด</div>
      <div class="food-name">หนังไก่ทอด</div>
      <div class="food-price">ราคา 39 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\ขนม\6.jpg" alt="ไข่ปลาทอด">
    <div class="food-info">
      <div class="food-category">ไข่ปลาทอด</div>
      <div class="food-name">ไข่ปลาทอด</div>
      <div class="food-price">ราคา 70 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\ขนม\7.jpg" alt="กุ๊ยช่ายทอด">
    <div class="food-info">
      <div class="food-category">กุ๊ยช่ายทอด</div>
      <div class="food-name">พิซซ่ามาร์เกริต้า</div>
      <div class="food-price">ราคา 50 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\ขนม\8.jpg" alt="ข้อไก่ทอด">
    <div class="food-info">
      <div class="food-category">ข้อไก่ทอด</div>
      <div class="food-name">ข้อไก่ทอด</div>
      <div class="food-price">ราคา 70 บาท</div>
    </div>
  </div>
</div>
<div class="food-list">
  <div class="food-item">
    <img class="food-image" src="d:\ขนม\9.jpg" alt="กล้วยทอด">
    <div class="food-info">
      <div class="food-category">กล้วยทอด</div>
      <div class="food-name">กล้วยทอด</div>
      <div class="food-price">ราคา 40 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\ขนม\10.jpg" alt="ขนมปากหม้อ">
    <div class="food-info">
      <div class="food-category">ขนมปากหม้อ</div>
      <div class="food-name">ขนมปากหม้อ</div>
      <div class="food-price">ราคา 60 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\ขนม\11.jpg" alt="ข้าวเกรียบ">
    <div class="food-info">
      <div class="food-category">ข้าวเกรียบ</div>
      <div class="food-name">ข้าวเกรียบ</div>
      <div class="food-price">ราคา 50 บาท</div>
    </div>
  </div>
  
  <div class="food-item">
    <img class="food-image" src="d:\ขนม\12.jpg" alt="กล้วยปิ่ง">
    <div class="food-info">
      <div class="food-category">กล้วยปิ่ง</div>
      <div class="food-name">กล้วยปิ่ง</div>
      <div class="food-price">ราคา 50 บาท</div>
    </div>
  </div>
</body>
</html>
