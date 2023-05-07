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
    unit sun_to_earch = 149668992;
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
```text
2,4,5,8,9,10
```
3.1 compiler ฟ้องว่าอะไร
![image](https://user-images.githubusercontent.com/100436724/236651469-813d2ad7-7646-403c-afe9-57846fd2cb54.png)

3.2 นักศึกษาคิดว่าที่ผิดพลาดนั้นเกิดจากอะไร
```text
ชื่อตัวแปรไม่ถูกต้องตามกฎ   
```
3.3 จะแก้ไขให้ถูกต้องได้อย่างไร
![image](https://user-images.githubusercontent.com/100436724/236651622-9b9f8a28-a6de-44fd-b81c-eededf91b7e7.png)


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

![image](https://user-images.githubusercontent.com/100436724/236651745-d613d372-3b80-43c5-aa6c-44e463a8b5fa.png)
แก้ไข
![image](https://user-images.githubusercontent.com/100436724/236651771-e55670b6-3f29-4568-bc58-c68902ea7db3.png)



#### ชุดที่ 2 ####
```cs
Console.WriteLine($"{3} and {1}");
Console.WriteLine($"{3} and {1}");
Console.WriteLine($"{3.0d} and {1.0001d}");
Console.WriteLine($"{3:F2} and {1000.123:F1}");
Console.WriteLine($"{3.123456:F2} and {5.123000:F4}");
```
![image](https://user-images.githubusercontent.com/100436724/236651783-89c31fc3-fd07-430a-812c-885ed3b193d2.png)


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
![image](https://user-images.githubusercontent.com/100436724/236651806-51f8c4e1-c42e-464e-9550-fef5f581a4cb.png)

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
![image](https://user-images.githubusercontent.com/100436724/236651818-ac4677bb-e872-4213-8826-67330c2eb313.png)

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
แก้ไข
![image](https://user-images.githubusercontent.com/100436724/236651924-f752da25-8d7a-4721-bc67-70b046798d12.png)


#### ชุดที่ 6 ####
```cs
const double i = 123.456789;
Console.writLine($"{i,10:F1}");
Console.writLine($"{i,10:F2}");
Console.writLine($"{i,10:F3}");
Console.writLine($"{i,10:F4}");
Console.writLine($"{i,10:F5}");
```
![image](https://user-images.githubusercontent.com/100436724/236651938-f43c4fc2-61b2-4506-8f12-b8a98e2801e0.png)
แก้ไข
![image](https://user-images.githubusercontent.com/100436724/236652026-cd0ac1bf-637f-4ffc-b692-ede125545585.png)


#### ชุดที่ 6 ####
```cs
string name = "Hello";
Console.writeLine(String.Format("{0} there. I said {0}! {0}???", name));
Console.WriteLine($"{2:d} {0:d} {1:d}", 1, 2, 3);
Console.WriteLine($"Hello " + $"World");
Console.WriteLine($"Here comes a slash \\");
Console.WriteLine($"|{999, 10}|");
Console.WriteLine($"|{000,-10}|");
Console.WriteLine($"The value: {500}.");
Console.WriteLine($"The value: {500:C}.");
Console.WriteLine($"{12.3456789,-10:F4}");
Console.WriteLine($"{12.3456789,-10:C}");
Console.WriteLine($"{12.3456789,-10:E3}");
Console.WriteLine($"{65535,-10:x}");
Console.WriteLine($"{65535,-10:X}");
int i;
Console.writeLine("Value\tSquared\tCubed");
for (i = 1; i < 10; i++)
    Console.writeLine($"{i}\t{i*i}\t{i*i*i}");
Console.WriteLine($"{1234.56789:#.###}.");
```
![image](https://user-images.githubusercontent.com/100436724/236652038-6cd7864e-e4ab-42c8-80c1-4945755e018e.png)
แก้ไข
![image](https://user-images.githubusercontent.com/100436724/236652076-799d19b3-c39f-4dd7-9403-d202747791d6.png)

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
```
error
```
2. บรรทัดไหนของโปรแกรมที่มี error บ้าง เพราะอะไร
```
21,22,23,24 ชื่อ class Number ต้องเป็นพิมพ์เล็ก
22,23,27,29 เพราะไม่ได้ประกาศตัวแปร class ให้เป็น static
```
3. ถ้าจะให้โปรแกรมทำงานได้ สามารถแก้ไขอย่างไรได้บ้าง
![image](https://user-images.githubusercontent.com/115066329/221884304-cdc47bbd-7527-4098-81a4-6e1fcc8f2d69.png)

```
