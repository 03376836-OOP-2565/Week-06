# แบบฝึกหัด

## 1. ให้นักศึกษาพิจารณาชื่อตัวแปรตามตารางต่อไปนี้ ว่าสามารถใช้ได้หรือไม่ พร้อมบอกเหตุผล

| ที่ | ชื่อตัวแปร | ใช้ได้/ไม่ได้ | เหตุผล |
|---:|:-------:|-----------|-------|
|  1.1 | xxx         | ใ ช้ได้  | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ
|  1.2 | null        | ใช้ไม่ได้ | เป็นคำสงวนในภาษา C#
|  1.3 | _value      |  ใ ช้ได้ | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ       
|  1.4 | First-name  |ใช้ไม่ได้  | ห้ามมีตัวดำเนินการอยู่ในชื่อตัวแปร        
|  1.5 | Hello!      |ใช้ไม่ได้  | ห้ามมีตัวดำเนินการอยู่ในชื่อตัวแปร       
|  1.6 | w * h       |ใช้ไม่ได้  | ชื่อตัวแปรห้ามเว้นวรรค
|  1.7 | time        |ใ ช้ได้   | ไม่มีตัวอักษรละเมิดกฎการตั้งชื่อ       
|  1.8 | do          |ใช้ไม่ได้  | do เป้นคำสั่งของ loop do while       
|  1.9 | Do          |ใ ช้ได้   | ไม่มีตัวอักษรละเมิดกฎการตั้งชื่อตัวแปร       
| 1.10 |  14February |ใช้ไม่ได้  | ชื่อตัวแปรไม่สามรถใช้เลขได้       
| 1.11 |  1adkrabang |ใช้ไม่ได้  | ห้ามมี . ในชื่อตัวแปร       
| 1.12 | Double      |ใ ช้ได้   | ไม่มีตัวอักษรละเมิดกฎการตั้งชื่อตัวแปร        
| 1.13 | My Car      |ใช้ไม่ได้  | ชื่อตัวแปรห้ามเว้นวรรค       
| 1.14 | my_home     |ใ ช้ได้   | ไม่มีตัวอักษรละเมิดกฎการตั้งชื่อตัวแปร       
| 1.15 | Int         |ใ ช้ได้   | ไม่มีตัวอักษรละเมิดกฎการตั้งชื่อตัวแปร   

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
uint sun_to_earch = 149668992;
```

2.4 ชาวนามีวัว 12 ตัว ม้า 68 ตัว และ ไก่ 12,000 ตัว ตามกฎหมาย เมืองนี้อนุญาตให้เลี้ยงสัตว์ที่เท้าได้ไม่เกินครอบครัวละ 200 ตัว (มี 3 ตัวแปร)
```csharp
byte cow = 12;
byte horse = 68;
ushort chiken = 12000;
int animal_one_family = 200;
```

2.5 แดงวัดขนาดของบ้าน พบว่าต้องใช้อิฐจำนวน 1325.8 ชิ้น แต่เมื่อไปถึงร้านก่อสร้าง พบว่าเขาขายอิฐเป็นยก ยกละ 10 ก้อน ไม่ขายเป็นเศษ
```csharp
ushort brickstore = 10;
double brickuse = 1325.8;
```

2.6 แสงเดินทางด้วยความเร็ว 299,337.984 กิโลเมตรต่อวินาที  ดาวศุกร์ห่างจากดวงอาทิตย์ 108,200,000 กิโลเมตร อยากทราบว่าแสงใช้เวลาในการเดินทางกี่วินาที (มี 3 ตัวแปร)
```csharp
double lightspeed = 299337.984;
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
``` text
2,4,5,8,9,10
```

3.1 compiler ฟ้องว่าอะไร
![image](https://user-images.githubusercontent.com/115066208/221413672-4ae55456-6b79-4234-a97e-8db646f86beb.png)


3.2 นักศึกษาคิดว่าที่ผิดพลาดนั้นเกิดจากอะไร
``` text
ชื่อตัวแปรไม่ถูกต้องตามกฎ
```

3.3 จะแก้ไขให้ถูกต้องได้อย่างไร
![image](https://user-images.githubusercontent.com/115066208/221414003-c5c0b7c8-c339-487b-a4ef-960f7bdae3b7.png)


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
ผล<br>
![image](https://user-images.githubusercontent.com/115066208/221414425-ab95fd9c-e98b-4734-bc3c-9a84f458a407.png)

แก้ไข<br>
![image](https://user-images.githubusercontent.com/115066208/221414505-72950f15-8c97-4f55-8c3b-5f9fad33674e.png)

ผลการรันอีกครั้ง<br>
![image](https://user-images.githubusercontent.com/115066208/221414538-af777a81-a79b-4848-a566-7b4c43540dbb.png)

#### ชุดที่ 2 ####
```cs
Console.WriteLine($"{3} and {1}");
Console.WriteLine($"{3} and {1}");
Console.WriteLine($"{3.0d} and {1.0001d}");
Console.WriteLine($"{3:F2} and {1000.123:F1}");
Console.WriteLine($"{3.123456:F2} and {5.123000:F4}");
```
![image](https://user-images.githubusercontent.com/115066208/221414846-43877c56-a001-4856-b7c3-004e7bf43493.png)
![image](https://user-images.githubusercontent.com/115066208/221414864-a62d78fc-1677-4476-a260-f241de2a2157.png)


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
![image](https://user-images.githubusercontent.com/115066208/221414927-498a0643-8b4f-4b82-b4d2-a9ab8a9ba72d.png)


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
![image](https://user-images.githubusercontent.com/115066208/221415028-7c1e9541-c820-4e0a-a378-e3343b3d4be5.png)


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
![image](https://user-images.githubusercontent.com/115066208/221415207-6a36b45a-647a-4332-a540-467aae234d6b.png)


#### ชุดที่ 6 ####
```cs
const double i = 123.456789;
Console.writLine($"{i,10:F1}");
Console.writLine($"{i,10:F2}");
Console.writLine($"{i,10:F3}");
Console.writLine($"{i,10:F4}");
Console.writLine($"{i,10:F5}");
```
![image](https://user-images.githubusercontent.com/115066208/221415410-2f71a0f0-cd03-4bd3-978e-28e77f542a81.png)



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
![image](https://user-images.githubusercontent.com/115066208/221415561-2c377437-940d-4761-a7bb-7f3ade620e6a.png)
![image](https://user-images.githubusercontent.com/115066208/221415588-fa2d2c74-dfb3-4f6e-a580-765e0381a109.png)


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
``` text
error
```

2. บรรทัดไหนของโปรแกรมที่มี error บ้าง เพราะอะไร
``` text
21, 22, 23, 24 ชื่อ class Number ต้องเป็นพิมพ์เล็ก 
22, 23, 27, 29 เพราะไม่ได้ประกาศตัวแปรใน class ให้เป็น static
```

3. ถ้าจะให้โปรแกรมทำงานได้ สามารถแก้ไขอย่างไรได้บ้าง
![image](https://user-images.githubusercontent.com/115066208/221415745-c603706d-f632-41ca-ad95-b1a92112f4df.png)
![image](https://user-images.githubusercontent.com/115066208/221415759-27675ee2-6b15-44c0-adbf-5280cdac9c2e.png)

