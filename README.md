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

ผลลัพธ์: จะย้ายไปยังไดเรกทอรี /home/<username> (ในกรณีนี้คือ /home/tonnoon2005)
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

cd . : อยู่ในไดเรกทอรีเดิม

cd .. : ถอยกลับไปยังไดเรกทอรีแม่

cd ~ : กลับไปยังไดเรกทอรีบ้านของผู้ใช้

cd / : ไปยังไดเรกทอรีรากของระบบ

cd $ : ใช้ผิด เพราะ $ ต้องตามด้วยตัวแปรที่ถูกต้อง เช่น $HOME

### Point: 2.4
  
![image](https://github.com/user-attachments/assets/362ffda0-4f5a-4768-9013-1fb362caf82e)
