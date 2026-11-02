Method	URI	คำอธิบาย	Status Code ที่เป็นไปได้
GET	/api/v1/students	ดึงรายชื่อนิสิตทั้งหมด	200
GET	/api/v1/students/1	ดึงข้อมูลนิสิตรายบุคคล (รองรับ ?include=courses)	200
POST	/api/v1/students	เพิ่มนิสิตใหม่	201 
PUT	/api/v1/students/2	แก้ไขข้อมูลนิสิตทั้งระเบียน	200
PATCH	/api/v1/students/3	แก้ไขข้อมูลนิสิตบางส่วน	200 
DELETE	/api/v1/students/99	ลบนิสิต	 404