# lab05
## Point: 2
### Point:  2.1 - 2.2
<img width="569" alt="Screenshot 2567-12-19 at 22 52 49" src="https://github.com/user-attachments/assets/22ec033b-d12b-4368-8340-f0f7e8e40c86" />

### Point:  2.3

1. cd .
  ```   
คำอธิบาย: . หมายถึง ไดเรกทอรีปัจจุบัน (current directory)

ผลลัพธ์: ไม่มีการเปลี่ยนแปลงตำแหน่ง (ยังอยู่ในไดเรกทอรีเดิม)
 ``` 
2. cd ..
 ``` 
คำอธิบาย: .. หมายถึง ไดเรกทอรีระดับบน (parent directory)

ผลลัพธ์: จะย้ายไปยังไดเรกทอรีที่อยู่เหนือไดเรกทอรีปัจจุบัน
 ``` 
3. cd ~
 ``` 
คำอธิบาย: ~ หมายถึง ไดเรกทอรีบ้านของผู้ใช้ (home directory) ซึ่งเป็นตำแหน่งเริ่มต้นของผู้ใช้งาน

ผลลัพธ์: จะย้ายไปยังไดเรกทอรี /home/<username> (ในกรณีนี้คือ /Users/thanathorn)
 ``` 
4. cd /
 ```    
คำอธิบาย: / หมายถึง root directory หรือโฟลเดอร์ราก ซึ่งเป็นตำแหน่งสูงสุดในโครงสร้างของไฟล์ระบบ

ผลลัพธ์: จะย้ายไปยังไดเรกทอรี /
 ``` 
5. cd $
 ```   
คำอธิบาย: $ ไม่มีความหมายในบริบทของคำสั่ง cd (มันอาจหมายถึงการเรียกตัวแปรใน shell แต่ต้องตามด้วยชื่อของตัวแปร เช่น $HOME)

ผลลัพธ์: `ระบบแจ้งว่า "No such file or directory" เนื่องจากไม่มีไฟล์หรือไดเรกทอรีชื่อ $`
 ``` 
สรุป

pwd : ใช้ตรวจสอบตำแหน่งปัจจุบันในไฟล์

cd . : อยู่ในไดเรกทอรีเดิม

cd .. : กลับไปยังไดเรกทอรี parent

cd ~ : กลับไปยัง Home directory

cd / : ไปยังไดเรกทอรีรากของระบบ root directory

cd $ : ใช้ผิด เพราะ $ ต้องตามด้วยตัวแปรที่ถูกต้อง เช่น $HOME

mkdir: ใช้สร้างไดเรกทอรีใหม่

mkdir 953234: สร้างไดเรกทอรีชื่อ 953234 ในตำแหน่งปัจจุบัน

### Point: 2.4

<img width="442" alt="Screenshot 2567-12-19 at 23 06 50" src="https://github.com/user-attachments/assets/cdf094ea-1bb8-4804-909f-4723e5cf1965" />

## Point: 3

### Point: 3.1
<img width="450" alt="Screenshot 2567-12-19 at 23 14 43" src="https://github.com/user-attachments/assets/d01b2f31-0350-49b0-975c-f058cc8ddc42" />



### Point: 3.2

<img width="1196" alt="Screenshot 2567-12-19 at 23 57 46" src="https://github.com/user-attachments/assets/e21b0c45-9e1e-4d2f-b0c5-05138aff99d0" />

<img width="440" alt="Screenshot 2567-12-20 at 00 00 52" src="https://github.com/user-attachments/assets/bea21ec9-504b-4b34-9743-5f946f9ce016" />

### Point: 3.3

ls: ใช้สำหรับแสดงรายการไฟล์และโฟลเดอร์ในโฟลเดอร์ปัจจุบัน
Lists the contents of a directory in a simple format (files and directories only, without details).

ls -alt:

 ```
-a: Shows all files, including hidden files (those starting with a .)แสดงไฟล์ที่ซ่อนไว้ (ไฟล์ที่ขึ้นต้นด้วย .).
-l: Provides a detailed list (permissions, ownership, size, etc.)แสดงรายละเอียดเพิ่มเติม เช่น สิทธิ์การเข้าถึง, ขนาดไฟล์, วันที่เวลาในการแก้ไข.
-t: Sorts the list by modification time, showing the most recently modified files first เรียงลำดับไฟล์ตามเวลาที่ถูกแก้ไขล่าสุด (ใหม่สุดไปเก่าสุด)
.
 ```
### Point: 3.4

<img width="534" alt="Screenshot 2567-12-20 at 00 10 40" src="https://github.com/user-attachments/assets/4b50cc7d-f773-45c6-afb5-aa032e64983c" />


### Point: 3.5 - 3.6

<img width="556" alt="Screenshot 2567-12-20 at 00 14 03" src="https://github.com/user-attachments/assets/f6191fe6-a31d-4e4c-8dc9-0e5a0f703323" />

### Point: 3.7 - 3.10

<img width="1214" alt="Screenshot 2567-12-20 at 00 16 45" src="https://github.com/user-attachments/assets/6eefe759-15d4-46e6-8378-fcee28ec168d" />
<img width="483" alt="Screenshot 2567-12-20 at 00 21 01" src="https://github.com/user-attachments/assets/2c986ac3-cdfe-4192-8095-6f4cba32b677" />
<img width="376" alt="Screenshot 2567-12-20 at 00 20 40" src="https://github.com/user-attachments/assets/fba341a7-bd5a-45b2-852a-69e621d314c5" />



  
