# Logic
กำหนดสถานการณ์จำลองต่อไปนี้ 
จงใช้หลักการทางตรรกะเพื่อพิสูจน์หาว่าคำสั่งใดที่ทำให้เกิดข้อผิดพลาดในโปรแกรม
และเขียนโปรแกรมด้วยภาษา Python เพื่อทดสอบพร้อมแสดงเอาท์พุตที่ได้

1. ถ้าโปรแกรมไม่แสดงข้อความ “Number Format Exception” แล้วโปรแกรมไม่มีข้อผิดพลาดในคำสั่ง Random r = new Random(Double.parseDouble(x))
2. ถ้าโปรแกรมแสดงข้อความ “Divided by zero” แล้วโปรแกรมมีข้อผิดพลาดในคำสั่ง double y = a / b;
3. ถ้าโปรแกรมแสดงข้อความ “Segmentation Fault” แล้วโปรแกรมมีข้อผิดพลาดในคำสั่ง Random r = new Random(Double.parseDouble(x))
4. โปรแกรมแสดงข้อความ “Low Memory” และโปรแกรมไม่แสดงข้อความ “Number Format Exception”
5. โปรแกรมแสดงข้อความ “Segmentation Fault” หรือโปรแกรมมีข้อผิดพลาดในคำสั่ง Object o = new Object()
