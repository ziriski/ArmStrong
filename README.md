# ArmStrong
261491, 261492 Project | CPE CMU 2020  

**Installation**__
สามารถติดตั้งไฟล์ ArmStrong.apk ลงบนอุปกรณ์ Android ได้เลย 

**Installation สำหรับ Unity Project**__
1.  สร้าง Unity Project แบบ Universal Render Pipeline
2.  Import ArmStrong.unitypackage
3.  ติดตั้ง Post Peocessing Package โดยเข้าไปที่ Window > Package Manager จากนั้นทำการค้นหาและติดตั้ง Post Processing
4.  เพิ่ม Scene ใน Build Settings โดยเข้าไปที่ File > Build Settings จากนั้นนำ Scene ในโฟลเดอร์ Scenes มาใส่ในช่อง Scenes In Build 
    โดยเรียงลำดับดังนี้ 

    0     Login
    1     SignUp
    2     Home
    3     Line
    4     Circle
    5     Square
    6     Horizontal
    7     Vertical
    8     Random
    9     Info

5.  ตั้งค่า Build สำหรับ Android โดยการเลือก Android ในช่อง Platform จากนั้นกด Switch Platform

**Database**__
ฐานข้อมูลของผู้เล่นในระบบจะถูกบันทึกไว้ใน Firebase Realtime Database__
https://siri-thesis-default-rtdb.firebaseio.com/ __
โดยโปรแกรมสามารถเข้าถึงฐานข้อมูลนี้ผ่าน Rest Client API ซึ่งถูกติดตั้งไว้ใน ArmStrong.unitypackage เป็นที่เรียบร้อยแล้ว
