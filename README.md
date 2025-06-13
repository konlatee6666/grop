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
<title>อาหารคาว</title>
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

<h1>อาหารคาว</h1>
<div class="food-list">
  <div class="food-item">
    <img class="food-image" src="d:\รูปอาหารคาว\1.jpg" alt="ต้มยำกุ้ง">
    <div class="food-info">
      <div class="food-category">ต้มยำกุ้ง</div>
      <div class="food-name">ต้มยำกุ้งน้ำข้น</div>
      <div class="food-price">ราคา 80 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\รูปอาหารคาว\2.jfif" alt="ส้มตำ">
    <div class="food-info">
      <div class="food-category">ส้มตำ</div>
      <div class="food-name">ตำปูปลาร้า</div>
      <div class="food-price">ราคา 60 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\รูปอาหารคาว\3.jpg" alt="แกงเขียวหวาน">
    <div class="food-info">
      <div class="food-category">แกงเขียวหวาน</div>
      <div class="food-name">แกงเขียวหวาน</div>
      <div class="food-price">ราคา 80 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\รูปอาหารคาว\4.jpg" alt="หมูย่าง">
    <div class="food-info">
      <div class="food-category">หมูย่าง</div>
      <div class="food-name">คอหมูย่าง</div>
      <div class="food-price">ราคา 90 บาท</div>
    </div>
  </div>
</div>
<div class="food-list">
  <div class="food-item">
    <img class="food-image" src="d:\รูปอาหารคาว\5.jpg" alt="ยำมาม่าทะเล">
    <div class="food-info">
      <div class="food-category">ยำมาม่า</div>
      <div class="food-name">ยำมาม่าทะเล</div>
      <div class="food-price">ราคา 100 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\รูปอาหารคาว\6.jpg" alt="ยำวุ้นเส้น">
    <div class="food-info">
      <div class="food-category">ยำวุ้นเส้น</div>
      <div class="food-name">ยำวุ้นเส้นกุ้ง</div>
      <div class="food-price">ราคา 80 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\รูปอาหารคาว\7.jpg" alt="ยำทะเล">
    <div class="food-info">
      <div class="food-category">ยำทะเล</div>
      <div class="food-name">ยำทะเล</div>
      <div class="food-price">ราคา 120 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\รูปอาหารคาว\8.jpg" alt="สเต็กเนื้อ">
    <div class="food-info">
      <div class="food-category">สเต็ก</div>
      <div class="food-name">สเต็กเนื้อ</div>
      <div class="food-price">ราคา 150 บาท</div>
    </div>
  </div>
</div>
<div class="food-list">
  <div class="food-item">
    <img class="food-image" src="d:\รูปอาหารคาว\9.jfif" alt="สเต็กหมู">
    <div class="food-info">
      <div class="food-category">สเต็ก</div>
      <div class="food-name">สเต็กหมู</div>
      <div class="food-price">ราคา 150 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\รูปอาหารคาว\10.jpg" alt="สุกี้หมู">
    <div class="food-info">
      <div class="food-category">สุกี้</div>
      <div class="food-name">สุกี้หมู</div>
      <div class="food-price">ราคา 60 บาท</div>
    </div>
  </div>

  <div class="food-item">
    <img class="food-image" src="d:\รูปอาหารคาว\11.jpg" alt="ราดหน้า">
    <div class="food-info">
      <div class="food-category">ราดหน้า</div>
      <div class="food-name">ราดหน้าหมู</div>
      <div class="food-price">ราคา 60 บาท</div>
    </div>
  </div>
  
  <div class="food-item">
    <img class="food-image" src="d:\รูปอาหารคาว\12.jpg" alt="ต้มจืด">
    <div class="food-info">
      <div class="food-category">ต้มจืด</div>
      <div class="food-name">ต้มจืด</div>
      <div class="food-price">ราคา 60 บาท</div>
    </div>
  </div>
</body>
</html>
