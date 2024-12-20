# lab05
## Point: 2
### Point:  2.1 - 2.2
<img width="569" alt="Screenshot 2567-12-19 at 22 52 49" src="https://github.com/user-attachments/assets/22ec033b-d12b-4368-8340-f0f7e8e40c86" />

pwd : ใช้ตรวจสอบตำแหน่งปัจจุบันในไฟล์

cd . : อยู่ในไดเรกทอรีเดิม

cd .. : กลับไปยังไดเรกทอรี parent

cd ~ : กลับไปยัง Home directory

cd / : ไปยังไดเรกทอรีรากของระบบ root directory

cd $ : ใช้ผิด เพราะ $ ต้องตามด้วยตัวแปรที่ถูกต้อง เช่น $HOME

mkdir: ใช้สร้างไดเรกทอรีใหม่

mkdir 953234: สร้างไดเรกทอรีชื่อ 953234 ในตำแหน่งปัจจุบัน
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


## Point: 4

### Point: 4.1
<img width="440" alt="Screenshot 2567-12-20 at 00 28 31" src="https://github.com/user-attachments/assets/40f7d432-be46-40bc-a519-8c930e4605f0" />
<img width="365" alt="Screenshot 2567-12-20 at 00 28 41" src="https://github.com/user-attachments/assets/40b826cc-e47e-414b-ab5e-6b915e26c441" />
<img width="443" alt="Screenshot 2567-12-20 at 00 45 27" src="https://github.com/user-attachments/assets/08a7123e-fcde-46c9-8017-d38e7d96efe7" />

cat: 	แสดงเนื้อหาทั้งหมดของไฟล์

more: แสดงเนื้อหาแบบแบ่งหน้า (เหมาะสำหรับไฟล์ใหญ่)

### Point: 4.2

![Screenshot 2567-12-20 at 00 30 07](https://github.com/user-attachments/assets/ecce59b7-c833-4403-a19a-1f59805c5da2)

head: แสดงบรรทัดแรก (ค่าเริ่มต้น 10 บรรทัด)

tail: แสดงบรรทัดสุดท้าย (ค่าเริ่มต้น 10 บรรทัด)


### Point: 4.3

<img width="482" alt="Screenshot 2567-12-20 at 00 30 45" src="https://github.com/user-attachments/assets/66b863a8-5427-4f14-a04c-b48b2f8bcc95" />

wc ย่อมาจาก word count ใช้สำหรับนับจำนวนบรรทัด (lines), คำ (words), และอักขระ (characters) ในไฟล์ 
```
Number of lines: จำนวนบรรทัดในไฟล์
Number of words: จำนวนคำในไฟล์
Number of characters: จำนวนอักขระในไฟล์ (รวมทั้งช่องว่างและสัญลักษณ์ต่างๆ)
```

### Point: 4.4

<img width="477" alt="Screenshot 2567-12-20 at 00 37 28" src="https://github.com/user-attachments/assets/3ed7d42d-571d-4098-8034-ea65954853a3" />


### Point: 4.5

cat: 	แสดงเนื้อหาทั้งหมดของไฟล์

more: แสดงเนื้อหาแบบแบ่งหน้า (เหมาะสำหรับไฟล์ใหญ่)

head: แสดงบรรทัดแรก (ค่าเริ่มต้น 10 บรรทัด)

tail: แสดงบรรทัดสุดท้าย (ค่าเริ่มต้น 10 บรรทัด)

wc: นับจำนวนบรรทัด, คำ, และอักขระ

## Point: 5

- 5.1 What is an environment variable?

คำตอบ: Environment Variable คือค่าที่กำหนดไว้ในระบบปฏิบัติการเพื่อเก็บข้อมูลที่เกี่ยวข้องกับการตั้งค่าของโปรแกรมและระบบ ตัวแปรเหล่านี้ช่วยให้กระบวนการ (process) และโปรแกรมสามารถแชร์ข้อมูลที่สำคัญร่วมกันได้ เช่น:
```
PATH: กำหนดไดเรกทอรีสำหรับการค้นหาโปรแกรม
HOME: โฟลเดอร์บ้านของผู้ใช้งาน
USER: ชื่อผู้ใช้ที่ล็อกอินในระบบ
```

### Point: 5.2

<img width="567" alt="Screenshot 2567-12-20 at 01 11 59" src="https://github.com/user-attachments/assets/2e4a9eae-d827-4f0d-b9d9-9e5d4358319e" />

- 5.2 What does the command echo $PATH output and what does it mean?

คำตอบ: คำสั่ง echo $PATH ใช้สำหรับแสดงค่าของ Environment Variable ที่ชื่อ PATH ซึ่งเป็นรายการของไดเรกทอรีที่ระบบจะค้นหาเมื่อคุณพิมพ์คำสั่ง ตัวอย่างผลลัพธ์:

javascript
```
/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```
ความหมาย:

แต่ละไดเรกทอรีใน PATH คั่นด้วย :

เมื่อคุณรันคำสั่ง เช่น ls ระบบจะค้นหาไฟล์ที่ชื่อ ls ในไดเรกทอรีเหล่านี้ตามลำดับ



### Point: 5.3
<img width="611" alt="Screenshot 2567-12-20 at 01 16 15" src="https://github.com/user-attachments/assets/2a907442-09e8-4ae9-b151-d83158c3e8e0" />

- 5.3 What does the man which explain about the which command?

คำตอบ: 
```
คำสั่ง man which แสดงคู่มือของคำสั่ง which ซึ่งใช้สำหรับค้นหา absolute path ของคำสั่งหรือโปรแกรม
```



### Point: 5.4 - 5.5

<img width="425" alt="Screenshot 2567-12-20 at 01 14 56" src="https://github.com/user-attachments/assets/46cbf7ed-36fb-48a8-9cde-4403da74b975" />

- 5.4 What is the absolute path of the ls command?
  
คำตอบ: ใช้คำสั่ง:
```
which ls

ผลลัพธ์: /bin/ls

Absolute Path ของ ls: /bin/ls
```

- 5.5 What is the absolute path of the man command?
  
คำตอบ: ใช้คำสั่ง:
```
which man

ผลลัพธ์: /usr/bin/man

Absolute Path ของ man: /usr/bin/man

```

### Point: 5.6


- 5.1 What is an environment variable?

คำตอบ: Environment Variable คือค่าที่กำหนดไว้ในระบบปฏิบัติการเพื่อเก็บข้อมูลที่เกี่ยวข้องกับการตั้งค่าของโปรแกรมและระบบ ตัวแปรเหล่านี้ช่วยให้กระบวนการ (process) และโปรแกรมสามารถแชร์ข้อมูลที่สำคัญร่วมกันได้ เช่น:
```
PATH: กำหนดไดเรกทอรีสำหรับการค้นหาโปรแกรม
HOME: โฟลเดอร์บ้านของผู้ใช้งาน
USER: ชื่อผู้ใช้ที่ล็อกอินในระบบ
```
ตัวแปรเหล่านี้ถูกจัดเก็บเป็นคู่ key=value และสามารถเรียกดูได้ด้วยคำสั่ง เช่น printenv หรือ env


- 5.2 What does the command echo $PATH output and what does it mean?

คำตอบ: คำสั่ง echo $PATH ใช้สำหรับแสดงค่าของ Environment Variable ที่ชื่อ PATH ซึ่งเป็นรายการของไดเรกทอรีที่ระบบจะค้นหาเมื่อคุณพิมพ์คำสั่ง ตัวอย่างผลลัพธ์:

javascript
```
/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```
ความหมาย:

แต่ละไดเรกทอรีใน PATH คั่นด้วย :

เมื่อคุณรันคำสั่ง เช่น ls ระบบจะค้นหาไฟล์ที่ชื่อ ls ในไดเรกทอรีเหล่านี้ตามลำดับ


- 5.3 What does the man which explain about the which command?

คำตอบ: 
```
คำสั่ง man which แสดงคู่มือของคำสั่ง which ซึ่งใช้สำหรับค้นหา absolute path ของคำสั่งหรือโปรแกรม
```

- 5.4 What is the absolute path of the ls command?
  
คำตอบ: ใช้คำสั่ง:
```
which ls

ผลลัพธ์: /bin/ls

Absolute Path ของ ls: /bin/ls
```
- 5.5 What is the absolute path of the man command?
  
คำตอบ: ใช้คำสั่ง:
```
which man

ผลลัพธ์: /usr/bin/man

Absolute Path ของ man: /usr/bin/man

```
## Point: 6

### Point: 6.1

<img width="567" alt="Screenshot 2567-12-20 at 01 25 33" src="https://github.com/user-attachments/assets/77b54f75-398c-43d0-9e5d-74ed006f8ff5" />

- 6.1 Find your IP using the ifconfig command

คำสั่ง ifconfig ใช้เพื่อแสดงข้อมูลการตั้งค่าของเครือข่าย รวมถึง IP Address ของอินเทอร์เฟซเครือข่าย

คำสั่ง:
```
ifconfig
```


### Point: 6.2

<img width="494" alt="Screenshot 2567-12-20 at 01 26 12" src="https://github.com/user-attachments/assets/ba3c5641-115d-451a-b2b8-173554db15f5" />

- 6.2 Find the IP of www.google.com using the nslookup command

คำสั่ง nslookup ใช้สำหรับค้นหา IP Address ของโดเมนผ่าน DNS (Domain Name System)

คำสั่ง:
```
nslookup www.google.com
```


### Point: 6.3
<img width="578" alt="Screenshot 2567-12-20 at 01 44 33" src="https://github.com/user-attachments/assets/5e9d519d-eec0-4c90-ab67-f2fa2bef16cd" />
<img width="577" alt="Screenshot 2567-12-20 at 01 46 45" src="https://github.com/user-attachments/assets/40696472-2d7a-48d1-b2cd-d5bbe1154dd6" />
<img width="577" alt="Screenshot 2567-12-20 at 01 46 45" src="https://github.com/user-attachments/assets/5c0ba2e1-655a-4505-acf8-edc393cac7b5" />

- 6.3 Try to use ping and traceroute commands and explain what they are for
  
คำสั่ง ping

คำอธิบาย:ใช้ทดสอบความเชื่อมต่อระหว่างเครื่องของคุณและปลายทาง โดยส่งแพ็กเก็ต ICMP และตรวจสอบการตอบกลับ

คำสั่ง:
```
ping www.google.com
```

คำสั่ง traceroute

คำอธิบาย: ใช้ตรวจสอบเส้นทาง (hops) ที่ข้อมูลเดินทางจากเครื่องของคุณไปยังปลายทาง

คำสั่ง:
```
traceroute www.google.com
```

### Point: 6.4
<img width="648" alt="Screenshot 2567-12-20 at 01 47 56" src="https://github.com/user-attachments/assets/1dbec53a-4485-49af-ac23-b39452f74130" />

6.4 Execute netstat -n and explain what the resultant table is

คำอธิบาย:คำสั่ง netstat -n ใช้เพื่อแสดงตารางการเชื่อมต่อเครือข่ายในรูปแบบตัวเลข (numeric)

คำสั่ง:
```
netstat -n
```


### Point: 6.5

- 6.1 Find your IP using the ifconfig command

คำสั่ง ifconfig ใช้เพื่อแสดงข้อมูลการตั้งค่าของเครือข่าย รวมถึง IP Address ของอินเทอร์เฟซเครือข่าย

คำสั่ง:
```
ifconfig
```

- 6.2 Find the IP of www.google.com using the nslookup command

คำสั่ง nslookup ใช้สำหรับค้นหา IP Address ของโดเมนผ่าน DNS (Domain Name System)

คำสั่ง:
```
nslookup www.google.com
```

- 6.3 Try to use ping and traceroute commands and explain what they are for
  
คำสั่ง ping

คำอธิบาย:ใช้ทดสอบความเชื่อมต่อระหว่างเครื่องของคุณและปลายทาง โดยส่งแพ็กเก็ต ICMP และตรวจสอบการตอบกลับ

คำสั่ง:
```
ping www.google.com
```

คำสั่ง traceroute

คำอธิบาย: ใช้ตรวจสอบเส้นทาง (hops) ที่ข้อมูลเดินทางจากเครื่องของคุณไปยังปลายทาง

คำสั่ง:
```
traceroute www.google.com
```

6.4 Execute netstat -n and explain what the resultant table is

คำอธิบาย:คำสั่ง netstat -n ใช้เพื่อแสดงตารางการเชื่อมต่อเครือข่ายในรูปแบบตัวเลข (numeric)

คำสั่ง:
```
netstat -n
```

## Point: 7

### Point: 7.1

คำอธิบาย:

- คำสั่ง top ใช้สำหรับแสดงข้อมูลเกี่ยวกับกระบวนการ (processes) และทรัพยากรระบบ เช่น CPU, RAM และ Swap ที่ถูกใช้งานแบบเรียลไทม์
- มีประโยชน์สำหรับการตรวจสอบสถานะของระบบ เช่น:
- ดูว่ากระบวนการใดใช้ CPU หรือ RAM มากที่สุด
- ตรวจสอบว่าเครื่องมีการทำงานหนักหรือไม่
  <img width="727" alt="Screenshot 2567-12-20 at 01 51 50" src="https://github.com/user-attachments/assets/257e0fb3-af1e-461f-a039-c6b40bf62e9a" />
### Point: 7.2 - 7.3

คำอธิบาย:

- htop เป็นเครื่องมือที่คล้ายกับ top แต่มีอินเทอร์เฟซที่ใช้งานง่ายกว่า (แสดงผลในรูปแบบสีและสามารถเลื่อนดูได้)
- ผู้ใช้สามารถเลือกกระบวนการและจัดการ (kill, renice) ได้ง่ายขึ้น
 <img width="562" alt="Screenshot 2567-12-20 at 01 55 22" src="https://github.com/user-attachments/assets/88c3b0c9-7d21-44ee-833e-817ac07d0e40" />



# 
Thanathorn Teekawong Id: 662115021
