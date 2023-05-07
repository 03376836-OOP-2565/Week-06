# แบบฝึกหัด

## 1. ให้นักศึกษาพิจารณาชื่อตัวแปรตามตารางต่อไปนี้ ว่าสามารถใช้ได้หรือไม่ พร้อมบอกเหตุผล

| ที่ | ชื่อตัวแปร | ใช้ได้/ไม่ได้ | เหตุผล |
|---:|:-------:|-----------|-------|
|  1.1 | xxx         | ใช้ได้  | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ
|  1.2 | null        | ใช้ไม่ได้ | เป็นคำสงวนในภาษา C#
|  1.3 | _value      | ใช้ได้   | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ      
|  1.4 | First-name  |ใช้ไม่ได้  | ห้ามมีตัวดำเนินการอยู่ในชื่อตัวแปร         
|  1.5 | Hello!      | ใช้ไม่ได้ |ห้ามมีตัวดำเนินการอยู่ในชื่อตัวแปร      
|  1.6 | w * h       | ใช้ไม่ได้ | ชื่อตัวแปรห้ามเว้นวรรค        
|  1.7 | time        |ใช้ได้        | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ       
|  1.8 | do          | ใช้ไม่ได้ |     do เป็นคำสั่งของ loop do while   
|  1.9 | Do          | ใช้ได้       | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ       
| 1.10 |  14February |ใช้ไม่ได้  |       ชื่อตัวแปรไม่สามารถใช้เลขได้ 
| 1.11 |  1adkrabang |ใช้ไม่ได้  |      ห้ามมี . ในชื่อตัวแปร  
| 1.12 | Double      | ใช้ได้       | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ       
| 1.13 | My Car      | ใช้ไม่ได้ |     ชื่อตัวแปรห้ามเว้นวรรค   
| 1.14 | my_home     |ใช้ได้        | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ       
| 1.15 | Int         |  ใช้ได้      | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ  

## 2.  จงบอกชนิดข้อมูลที่สามารถรองรับค่าต่อไปนี้อย่างเหมาะสมพร้อมทั้งใส่ค่าเริ่มต้นตามที่กำหนดให้ ถ้าข้อใดมีหลายตัวแปร ให้ระบุให้ครบ
 

2.1 (ตัวอย่าง) เสียงเดินทางด้วยความเร็ว 340.0 เมตรต่อวินาที

```csharp
    float speedOfSound = 340.0f;
```

2.2 จำนวนนักศึกษาในชั้นเรียนนี้คือ 42 คน

```csharp
    byte student = 42;
```

2.3 ระยะห่างจากดวงอาทิตย์ถึงโลกคือ 149,668,992 กิโลเมตร

```csharp
    unit sun_to_earth = 149668992;
```
2.4 ชาวนามีวัว 12 ตัว ม้า 68 ตัว และ ไก่ 12,000 ตัว ตามกฎหมาย เมืองนี้อนุญาตให้เลี้ยงสัตว์ที่เท้าได้ไม่เกินครอบครัวละ 200 ตัว (มี 3 ตัวแปร)

```csharp
    byte cow = 12f;
    byte hourse = 68;
    ushort chicken = 12000;
    int animal_one_family = 200;
```

2.5 แดงวัดขนาดของบ้าน พบว่าต้องใช้อิฐจำนวน 1325.8 ชิ้น แต่เมื่อไปถึงร้านก่อสร้าง พบว่าเขาขายอิฐเป็นยก ยกละ 10 ก้อน ไม่ขายเป็นเศษ

```csharp
    ushort bricktore = 10;
    double brickuse = 1325.8;
```


2.6 แสงเดินทางด้วยความเร็ว 299,337.984 กิโลเมตรต่อวินาที  ดาวศุกร์ห่างจากดวงอาทิตย์ 108,200,000 กิโลเมตร อยากทราบว่าแสงใช้เวลาในการเดินทางกี่วินาที (มี 3 ตัวแปร)

```csharp
    double lightspeed = 299337;
    float venus_to_sun = 108200000;
    float travel;
```


# งานฝึกเขียนโปรแกรม

## Project 6.1 การประกาศตัวแปร ## 

1. สร้าง consol project

2. ใน method main ให้ประกาศตัวแปรดังต่อไปนี้

``` text
int var = 30;
Int var1;
int var2, var3;
int var4 = var5;
Int var6 = 2, var7;
int var8 = 10 * 5;
int var9 = var;
int var10, Char c1, Float f1;
double d1 = False;
Bool b1 = 0;
```

3. มีบรรทัดใดบ้าง ที่มีข้อความผิดพลาด 
```csharp
2,4,5,8,9,10
```
3.1 compiler ฟ้องว่าอะไร

![image](https://user-images.githubusercontent.com/115066431/236655447-a4b295b8-a304-4fc7-b9ad-5f49b4fe7f9e.png)


3.2 นักศึกษาคิดว่าที่ผิดพลาดนั้นเกิดจากอะไร
```csharp
1. ชื่อตัวแปรไม่ถูกต้องตามกฎ
2. กำหนดค่าตัวแปร var4 ด้วยตัวแปร var5 ที่ยังไม่ได้ประกาศ หรือไม่มีค่าที่กำหนดไว้
3. ประกาศตัวแปร var6 และ var7 โดยกำหนดค่าเริ่มต้นแบบเดียวกัน แต่ไม่ได้ระบุชนิดของตัวแปร var7
4.ประกาศตัวแปร d1 ด้วยค่า False ซึ่งไม่ถูกต้อง เนื่องจากตัวแปร d1 เป็นชนิด double ซึ่งไม่สามารถเก็บค่า Boolean ได้
```
3.3 จะแก้ไขให้ถูกต้องได้อย่างไร

![image](https://user-images.githubusercontent.com/115066431/236655813-2fb161dd-a144-4659-9ce5-a28f2023d432.png)


## Project 6.2 การใช้งานตัวแปรใน string interpreter ## 

String interpreter จะช่วยตีความให้ค่าในตัวแปรชนิดต่างๆ กลายเป็น string โดยอัตโนมัติ ดังตัวอย่าง

 ```cs
int a = 100;
string s = $"a = {a}";
 ```

ตัวแปร `a` ในเครื่องหมาย `{ }` จะถูกแปลงเป็นข้อความ เทียบเท่ากับการใช้ `a.ToString();` 


1. สร้าง consol project
2. ใน method Main() ให้เขียนโปรแกรมต่อไปนี้ (แบ่งเป็นรอบๆ ตามชุดที่กำหนด) รันและบันทึกผล 
3. อธิบายสิ่งที่เกิดขึ้นในแต่ละบรรทัด
#### 4. ถ้ามีที่ผิดใน code ให้แก้ไขให้ถูกต้องจนรันได้และนำส่วนที่แก้ไขแล้วมาใส่ในใบงานด้วย (เขียนในส่วนคำตอบ ไม่ต้องแก้ในส่วนของโจทย์)


#### ชุดที่ 1 ####
```cs
Console.writeLine("{0} and {1}", 3,5);
Console.writeLine("{0} and {1}", 3.0,5.0);
Console.writeLine("{0} and {1}", 3.0d, 5.0d);
Console.writeLine("{0:F1} and {1:F1}", 3.0, 5.0);
Console.writeLine("{0:F2} and {1:F2}", 3.0d, 5.0d);
```

![image](https://user-images.githubusercontent.com/115066431/236655882-80390f41-eb59-487e-bda2-7d6a2b452515.png)

```cs
แก้ไข (เปลี่ยน w เป็น W)
```

![image](https://user-images.githubusercontent.com/115066431/236655935-d029b345-b684-43f4-b60f-8e67b4594854.png)

```cs
Console.WriteLine("{0} and {1}", 3,5);
แสดงผลลัพธ์เป็น 3 and 5 โดยใช้ตำแหน่งของ Argument ในการแทนที่ {0} และ {1} ใน string format ตามลำดับ
Console.WriteLine("{0} and {1}", 3.0,5.0);
แสดงผลลัพธ์เป็น 3 and 5 โดยใช้ตำแหน่งของ Argument ในการแทนที่ {0} และ {1} ใน string format ตามลำดับ ซึ่ง Argument ในที่นี้เป็นตัวเลขแบบทศนิยม
Console.WriteLine("{0} and {1}", 3.0d, 5.0d);
แสดงผลลัพธ์เป็น 3 and 5 โดยใช้ตำแหน่งของ Argument ในการแทนที่ {0} และ {1} ใน string format ตามลำดับ ซึ่ง Argument ในที่นี้เป็นตัวเลขแบบทศนิยมขนาดใหญ่ (double)
Console.WriteLine("{0:F1} and {1:F1}", 3.0, 5.0);
แสดงผลลัพธ์เป็น 3.0 and 5.0 โดยใช้ Format Specifier :F1 ในการแสดงผลทศนิยม 1 ตำแหน่ง สำหรับ Argument ในที่นี้เป็นตัวเลขแบบทศนิยม
Console.WriteLine("{0:F2} and {1:F2}", 3.0d, 5.0d);
แสดงผลลัพธ์เป็น 3.00 and 5.00 โดยใช้ Format Specifier :F2 ในการแสดงผลทศนิยม 2 ตำแหน่ง สำหรับ Argument ในที่นี้เป็นตัวเลขแบบทศนิยมขนาดใหญ่ (double)
```

#### ชุดที่ 2 ####
```cs
Console.WriteLine($"{3} and {1}");
Console.WriteLine($"{3} and {1}");
Console.WriteLine($"{3.0d} and {1.0001d}");
Console.WriteLine($"{3:F2} and {1000.123:F1}");
Console.WriteLine($"{3.123456:F2} and {5.123000:F4}");
```
![image](https://user-images.githubusercontent.com/115066431/236655964-4e1e4c73-5e34-47ad-9a43-db5ced873796.png)

```cs
บรรทัดที่ 1 และ 2: แสดงผลลัพธ์เป็น "3 and 1" ซึ่งเป็นการแสดงค่าตัวเลข 3 และ 1 ในรูปแบบของ string interpolation โดยไม่มีการจัดรูปแบบหรือการแปลงรูปแบบใดๆ
บรรทัดที่ 3: แสดงผลลัพธ์เป็น "3 and 1" เช่นเดียวกับบรรทัดที่ 1 และ 2 แต่ใช้ตัวเลขทศนิยมในการแสดงค่า
บรรทัดที่ 4: แสดงผลลัพธ์เป็น "3.00 and 1000.1" ซึ่งแสดงค่าตัวเลข 3 และ 1000.123 โดยแปลงเป็นรูปแบบทศนิยมที่มีจุดทศนิยม 2 ตำแหน่ง และ 1 ตำแหน่งตามลำดับ โดยใช้รูปแบบ F2 และ F1
บรรทัดที่ 5: แสดงผลลัพธ์เป็น "3.12 and 5.1230" ซึ่งแสดงค่าตัวเลข 3.123456 และ 5.123000 โดยแปลงเป็นรูปแบบทศนิยมที่มีจุดทศนิยม 2 ตำแหน่ง และ 4 ตำแหน่งตามลำดับ โดยใช้รูปแบบ F2 และ F4
```


#### ชุดที่ 3 ####
```cs
Console.WriteLine($"         1111111111222222");
Console.WriteLine($"1234567890123456789012345");
Console.WriteLine($"{1,0}");
Console.WriteLine($"{1,1}");
Console.WriteLine($"{1,2}");
Console.WriteLine($"{1,3}");
Console.WriteLine($"{1,4}");
Console.WriteLine($"{1,5}");
Console.WriteLine($"{1,10}");
Console.WriteLine($"{1,15}");
Console.WriteLine($"{1,20}");
Console.WriteLine($"{1,22}");
Console.WriteLine($"{1,25}");
```

![image](https://user-images.githubusercontent.com/115066431/236656016-721db524-b155-4938-8325-32ecfeaa840f.png)

```cs
บรรทัดที่ 1-2: แสดงตัวอย่างตำแหน่งของเลขที่ใส่เข้าไปใน string interpolation
บรรทัดที่ 3-12: แสดงตัวเลข 1 โดยมีจำนวนเว้นวรรคทางขวาของตัวเลข 1 ต่างกันออกไป เริ่มต้นจากเว้นวรรค 0 จนถึง 25 ที่มีการเว้นวรรคทางขวา 25 ตำแหน่ง
```

#### ชุดที่ 4 ####
```cs
int i = 123456789;
Console.WriteLine("Regular string format");
Console.WriteLine("{0}",i);
Console.WriteLine("String interpreter");
Console.WriteLine($"None ==> {i}");
Console.WriteLine($"   E ==> {i:E}");
Console.WriteLine($"   F ==> {i:F}");
Console.WriteLine($"   G ==> {i:G}");
Console.WriteLine($"   N ==> {i:N}");
Console.WriteLine($"   P ==> {i:P}");
Console.WriteLine($"   X ==> {i:X}");
```

![image](https://user-images.githubusercontent.com/115066431/236656026-51925e12-80fb-4391-91ea-ee1c42766966.png)

```cs
สิ่งที่เกิดขึ้นในแต่ละบรรทัด
int i = 123456789; ประกาศตัวแปร i และกำหนดค่าให้เป็น 123456789 ซึ่งเป็นจำนวนเต็ม (integer)
Console.WriteLine("Regular string format"); แสดงข้อความ "Regular string format" บนหน้าจอ
Console.WriteLine("{0}",i); แสดงค่าของตัวแปร i โดยใช้รูปแบบของ string format ที่เป็น "0" แทนตัวแปรที่จะถูกแทนที่ ในกรณีนี้คือ i
Console.WriteLine("String interpreter"); แสดงข้อความ "String interpreter" บนหน้าจอ
Console.WriteLine($"None ==> {i}"); แสดงค่าของตัวแปร i โดยใช้รูปแบบของ string interpolation ซึ่งจะแทนที่ตัวแปร i ในสตริงที่เป็นข้อความ "None ==> {i}" ในกรณีนี้คือ "None ==> 123456789"
Console.WriteLine($" E ==> {i:E}"); แสดงค่าของตัวแปร i ในรูปแบบทางตัวเลขเชิงวิทยาศาสตร์ (scientific notation) โดยใช้รูปแบบของ string interpolation และตัว specifier "E" ซึ่งจะแสดงเป็นสัญลักษณ์ e และตามด้วยจำนวนเต็ม 2 หลักที่แสดงทศนิยม ในกรณีนี้คือ " E ==> 1.234568E+008"
Console.WriteLine($" F ==> {i:F}"); แสดงค่าของตัวแปร i ในรูปแบบทางตัวเลขที่มีจุดทศนิยม (fixed-point notation) โดยใช้รูปแบบของ string interpolation และตัว specifier "F" ซึ่งจะแสดงจำนวนเต็ม หรือจำนวนที่มีจุดทศนิยมตามที่กำหนด ในกรณีนี้คือ " F ==> 123456789.00"
Console.WriteLine($" G ==> {i:G}"); แสดงเลข i โดยใช้รูปแบบของ "General" format specifier ซึ่งจะแสดงตัวเลขโดยไม่ต้องใช้ทศนิยมเมื่อจำเป็นแต่จะแสดงทศนิยมในกรณีที่ต้องการ โดยจัดตำแหน่งไว้ทางขวาของช่องว่าง 10 ช่อง
Console.WriteLine($" N ==> {i:N}"); แสดงเลข i โดยแปลงเป็นรูปแบบทศนิยมที่มีจุดทศนิยม 2 ตำแหน่ง และเพิ่มเครื่องหมาย "," ในที่ที่เป็นพิมพ์ดีกว่า โดยจัดตำแหน่งไว้ทางขวาของช่องว่าง 10 ช่อง
Console.WriteLine($" P ==> {i:P}"); แสดงเลข i โดยแปลงเป็นรูปแบบเปอร์เซ็นต์ที่มีจุดทศนิยม 2 ตำแหน่ง และเพิ่มเครื่องหมาย "%" ต่อท้ายตัวเลข โดยจัดตำแหน่งไว้ทางขวาของช่องว่าง 10 ช่อง
```


#### ชุดที่ 5 ####
```cs
int i = 123456789;
Console.WriteLin("Regular string format");
Console.WriteLin("         {0,20}",i);
Console.WriteLin("String interpreter");
Console.WriteLin($"None ==> {i,20}");
Console.WriteLin($"   E ==> {i,20:E}");
Console.WriteLin($"   F ==> {i,20:F}");
Console.WriteLin($"   G ==> {i,20:G}");
Console.WriteLin($"   N ==> {i,20:N}");
Console.WriteLin($"   P ==> {i,20:P}");
Console.WriteLin($"   X ==> {i,20:X}");
```
![image](https://user-images.githubusercontent.com/115066431/236656123-1872fdbc-7cab-42f4-bcd1-7f8cd8acf491.png)

```cs
แก้ไข ( เติมตัว e ลงไปใน WriteLin)
```

![image](https://user-images.githubusercontent.com/115066431/236656082-b8c543cb-8cd5-4981-9f0b-33df010e7d1b.png)

```cs
สิ่งที่เกิดขึ้นในแต่ละบรรทัด
Console.WriteLine("Regular string format"); // แสดงข้อความ "Regular string format" บนหน้าจอ
Console.WriteLine(" {0,20}", i); // แสดงเลข i โดยจัดตำแหน่งไว้ทางขวาของช่องว่าง 20 ช่อง
Console.WriteLine("String interpreter"); // แสดงข้อความ "String interpreter" บนหน้าจอ
Console.WriteLine($"None ==> {i,20}"); // แสดงเลข i โดยจัดตำแหน่งไว้ทางขวาของช่องว่าง 20 ช่อง โดยไม่มีการกำหนดรูปแบบ
Console.WriteLine($" E ==> {i,20:E}"); // แสดงเลข i โดยแปลงเป็นรูปแบบ Scientific Notation โดยจัดตำแหน่งไว้ทางขวาของช่องว่าง 20 ช่อง
Console.WriteLine($" F ==> {i,20:F}"); // แสดงเลข i โดยแปลงเป็นรูปแบบทศนิยมที่มีจุดทศนิยม 2 ตำแหน่ง โดยจัดตำแหน่งไว้ทางขวาของช่องว่าง 20 ช่อง
Console.WriteLine($" G ==> {i,20:G}"); // แสดงเลข i โดยแปลงเป็นรูปแบบทศนิยม โดยไม่มีจุดทศนิยมหรือจุดทศนิยมเพียงตำแหน่งเดียว โดยจัดตำแหน่งไว้ทางขวาของช่องว่าง 20 ช่อง
Console.WriteLine($" N ==> {i,20:N}"); // แสดงเลข i โดยแปลงเป็นรูปแบบทศนิยมที่มีจุดทศนิยม 2 ตำแหน่ง และเพิ่มเครื่องหมาย "," ในที่ที่เป็นพิมพ์ดีกว่า โดยจัดตำแหน่งไว้ทางขวาของช่องว่าง 20 ช่อง
Console.WriteLine($"   P ==> {i,20:P}"); // แสดงเลข i โดยแสดงเป็นรูปแบบของเปอร์เซ็นต์ (%), ซึ่งจะแปลงค่า i ให้อยู่ในรูปแบบของทศนิยม 2 ตำแหน่ง และเพิ่มเครื่องหมาย % ต่อท้าย โดยจัดตำแหน่งไว้ทางขวาของช่องว่าง 20 ช่อง
Console.WriteLine($"   X ==> {i,20:X}"); // ในบรรทัดนี้จะแสดงเลขฐานสิบหก (hexadecimal) ของตัวแปร i โดยจัดตำแหน่งไว้ทางขวาของช่องว่าง 20 ช่อง
```


#### ชุดที่ 6 ####
```cs
const double i = 123.456789;
Console.writLine($"{i,10:F1}");
Console.writLine($"{i,10:F2}");
Console.writLine($"{i,10:F3}");
Console.writLine($"{i,10:F4}");
Console.writLine($"{i,10:F5}");
```
```cs
แก้ไข ( เปลี่ยน w เป็น W และ เติมตัว e ลงไปใน writLine)
```

![image](https://user-images.githubusercontent.com/115066431/236656158-14974d4b-dbfc-4da2-9c5a-b9a67adfe707.png)

```cs
สิ่งที่เกิดขึ้นในแต่ละบรรทัด
บรรทัดที่ 1: แสดงค่าของ i โดยกำหนดให้แสดงผลแบบจองช่อง 10 ตำแหน่งเต็ม (F1) ดังนั้นจะแสดงผลเป็น " 123.5" (มีช่องว่างนำหน้า)
บรรทัดที่ 2: แสดงค่าของ i โดยกำหนดให้แสดงผลแบบจองช่อง 10 ตำแหน่งเต็ม (F2) ดังนั้นจะแสดงผลเป็น " 123.46" (มีช่องว่างนำหน้า)
บรรทัดที่ 3: แสดงค่าของ i โดยกำหนดให้แสดงผลแบบจองช่อง 10 ตำแหน่งเต็ม (F3) ดังนั้นจะแสดงผลเป็น " 123.457" (มีช่องว่างนำหน้า)
บรรทัดที่ 4: แสดงค่าของ i โดยกำหนดให้แสดงผลแบบจองช่อง 10 ตำแหน่งเต็ม (F4) ดังนั้นจะแสดงผลเป็น " 123.4568" (มีช่องว่างนำหน้า)
บรรทัดที่ 5: แสดงค่าของ i โดยกำหนดให้แสดงผลแบบจองช่อง 10 ตำแหน่งเต็ม (F5) ดังนั้นจะแสดงผลเป็น " 123.45679" (มีช่องว่างนำหน้า)
```

#### ชุดที่ 6 ####
```cs
string name = "Hello";
Consol.writeLine(String.Format("{0} there. I said {0}! {0}???", name));
Consol.writeLine($"{2:d} {0:d} {1:d}", 1, 2, 3);
Consol.writeLine($"Hello " + $"World");
Consol.writeLine($"Here comes a slash \\");
Consol.writeLine($"|{999, 10}|");
Consol.writeLine($"|{000,-10}|");
Consol.writeLine($"The value: {500}.");
Consol.writeLine($"The value: {500:C}.");
Consol.writeLine($"{12.3456789,-10:F4}");
Consol.writeLine($"{12.3456789,-10:C}");
Consol.writeLine($"{12.3456789,-10:E3}");
Consol.writeLine($"{65535,-10:x}");
Consol.writeLine($"{65535,-10:X}");
int i;
Console.writeLine("Value\tSquared\tCubed");
for (i = 1; i < 10; i++)
    Console.writeLine($"{i}\t{i*i}\t{i*i*i}");
Console.WriteLine($"{1234.56789:#.###}.");
```
![image](https://user-images.githubusercontent.com/115066431/236656929-9b981641-6700-4cd3-9a48-49b40e3feb7a.png)

```cs
แก้ไข ( เปลี่ยน w เป็น W และ เติมตัว e ลงไปใน Consol)
```

![image](https://user-images.githubusercontent.com/115066431/236656825-29ea193e-2dc4-4936-8b8e-1c62cb628be9.png)

```cs
สิ่งที่เกิดขึ้นในแต่ละบรรทัด
บรรทัดที่ 3: ประกาศตัวแปรชื่อ name และกำหนดค่าเป็น "Hello"
บรรทัดที่ 4: ใช้ String.Format() เพื่อสร้างข้อความที่มีการใช้ตัวแปร name ในหลายๆ ตำแหน่ง โดยใช้ {0} เพื่อแทนตัวแปร name ในข้อความ
บรรทัดที่ 5: ใช้ $ เพื่อแทนที่ String.Format() ในการสร้างข้อความที่ใช้ตัวแปร 2 ตัวในการแสดงผล
บรรทัดที่ 6: ใช้การต่อ String ด้วย + เพื่อสร้างข้อความ "Hello World"
บรรทัดที่ 7: ใช้ \ เพื่อแสดงเครื่องหมาย backslash () ในข้อความ
บรรทัดที่ 8-9: ใช้ {n,width} เพื่อจัดรูปแบบการแสดงผลให้เป็นคอลัมน์ โดยการกำหนด width ให้เป็น 10 ตัวอักษร และใช้ 0 ในการเติมช่องว่างของจำนวนที่มีน้อยกว่า width
บรรทัดที่ 10-11: ใช้ {n,format} เพื่อแสดงผลตัวเลข โดยใช้ format เป็น C และ F4 ตามลำดับ เพื่อแสดงผลตัวเลขเป็นเงินและเลขทศนิยม 4 ตำแหน่ง
บรรทัดที่ 12-13: ใช้ {n,format} เพื่อแสดงผลตัวเลข โดยใช้ format เป็น E3 และ x หรือ X เพื่อแสดงผลตัวเลขในรูปแบบ scientific notation และ hexa decimal
บรรทัดที่ 14 ถึง 15: ใช้ {i}\t{i * i}\t{i * i * i} เพื่อแสดงผลตัวเลข i และ i ยกกำลังสอง และ i ยกกำลังสาม โดยคั่นด้วย tab
บรรทัดที่ 16-17: ใช้ string interpolation และ #.### เพื่อแสดงผลตัวเลข 1234.56789 ในรูปแบบที่มีจำนวนทศนิยม 3 ตำแหน่ง
บรรทัดที่ 18: ปิดการทำงานของโปรแกรม ด้วย Console.WriteLine(".") แสดงผล "." และขึ้นบรรทัดใหม่
```

---- 

## Project 6.3 static keyword ## 
1. สร้าง project ชนิด console
2. เขียนโปรแกรมต่อไปนี้
#### 3. ถ้ามีที่ผิดใน code ให้แก้ไขให้ถูกต้องจนรันได้และนำส่วนที่แก้ไขแล้วมาใส่ในใบงานด้วย (เขียนในส่วนคำตอบ ไม่ต้องแก้ในส่วนของโจทย์)


```cs
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;


namespace method_examples
{
    class number
    {
        static public int numberInt1;
        static public double numberDouble1;
        public int numberInt2;
        public double  numberDouble2;
    }
    class Program
    {
        static void Main()
        {
            Number.numberInt1 = 10;
            Number.numberInt2 = 20;
            Number.numberDouble1 = 100.500;
            Number.numberDouble2 = 200.500;

            Console.WriteLine($"NumberInt1 = {number.NumberInt1}");
            Console.WriteLine($"NumberInt2 = {number.NumberInt2}");
            Console.WriteLine($"NumberDouble1 = {number.NumberDouble1}");
            Console.WriteLine($"NumberDouble2 = {number.NumberDouble2}");

        }
    }
}
```



### คำถาม ###

1. ผลการทำงานเป็นอย่างไร

![image](https://user-images.githubusercontent.com/115066431/236657048-fe2ca5b4-5834-4a5a-bb40-7e103af07556.png)


2. บรรทัดไหนของโปรแกรมที่มี error บ้าง เพราะอะไร

บรรทัดที่ 9: ชื่อ class ไม่ตรงกับชื่อที่เรียกใช้ในโปรแกรม ซึ่งจะทำให้โปรแกรมไม่สามารถค้นหา class นั้นได้ แก้ไขโดยเปลี่ยนชื่อ class เป็น Number แทน number
บรรทัดที่ 16-19: ใช้ชื่อ class ผิด โดยเรียกใช้ number แทน Number 



3. ถ้าจะให้โปรแกรมทำงานได้ สามารถแก้ไขอย่างไรได้บ้าง

![image](https://user-images.githubusercontent.com/115066431/236657206-e4585ca2-c3c3-4ae5-a14d-d3e3a5bcab4d.png)

