<!DOCTYPE html> 
<html Lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
    <h1>แบบสอบถาม</h1>
    <hr>

    <div class="container">
        <form action="">
            <h2>ข้อมูลผู้ตอบแบบสอบถาม</h2>
            <br>

            <div class="inputBox">
                <p>
                    <label for="username">ชื่อ-นามสกุล:</label>
                    <input type="text" >
                </p>
                <p>
                    <label for="num">ระหัสนักศึกษา</label>
                    <input type="password" >
                </p>
            </div> 


            <p>
                <label for="">เพศ: </label>
                <label for="male">ชาย</label>
                <input type="radio" name="male" id="male">
                <label for=>"หญิง"</label>
                <input type="radio" name="male" id="">
            </p>\

            <p>

                <label for ="faculty">สังกัดคณะ:</label>
                <select id="faculty" name="faculty">
                    <option value="science">วิทยาศาสตร์</option>
                    <option value="computer">วิทยาการคอมพิวเตอร์</option>
                    <option value="education">ครุศาสตร์</option>
                    <option value="education">บริหารธุรกิจและการจัดการ</option>
                    <option value="education">มนุษย์ศาสตร์</option>
                    <option value="education">เทคโนโลยีอุตสาหากรรม</option>
                    <option value="education">เกษตรศาสตร์</option>
                    <option value="education">พยาบาลศาสตร์</option>
                    <option value="education">สาธรณะสุขศาสตร์</option>
                    <option value="education">แพทย์แผนไทยและทางเลือก</option>
                    <option value="education">นิติศาสตร์</option>
                </select>
            </p>

            <p>
                <label for="">แม่สีที่ชอบ:</label>
                <label for="red">สีแดง</label>
                <input type="checkbox" name="gender" id="red">
                <label for="green">สีเขียว</label>
                <input type="checkbox" name="gender" id="green">
                <label for="fa">สีน้ำเงิน</label>
                <input type="checkbox" name="gender" id="fa">
            </p>

            <p>
                <label for="">ผลไม้ที่ชอบ:</label>
                <br>
                <label for="red">มะม่วง</label>
                <input type="checkbox" name="gender" id="red">
                <label for="green">น้อยหน่า</label>
                <input type="checkbox" name="gender" id="green">
                <label for="fa">ทุเรียน</label> 
                <input type="checkbox" name="gender" id="fa">
                <label for="fa">ลำใย</label>
                <input type="checkbox" name="gender" id="fa">
                <label for="fa">ฝรั่ง</label>
                <input type="checkbox" name="gender" id="fa">
                <br>
                <label for="fa">แตงโม</label>
                <input type="checkbox" name="gender" id="fa">
            </p>

            <p>
                <label for="">อาหารที่ชื่นชอบ</label>
                <label for="">ต้มยำกุ้ง</label>
                <input type="checkbox" name="gender" id="">
                <label for="">ไข่เจียวหมูสับ</label>
                <input type="checkbox" name="gender" id="">
                <label for="">แกงข่าไก่</label>
                <input type="checkbox" name="gender" id="">
            <br>
                <label for="">แกงเขียวหวานไก่</label>
                <input type="checkbox" name="gender" id="">
                <label for="">ผัดไทย</label>
                <input type="checkbox" name="gender" id="">
                <label for="">ราดหน้าหมี่กรอบ</label>
                <input type="checkbox" name="gender" id="">
            </p>

            <div class="btn-con">
                <button type="ok" id="ok" onclick="audio3.play()">
                    <a>Submit</a>
                    <!-- <img class="imgmaks" src="maki arrow.png" alt=""> -->
                </button>
            </div>

        </form>
    </div>
</body>

</html>