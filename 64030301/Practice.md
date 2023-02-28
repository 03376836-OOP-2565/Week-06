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
![image](https://user-images.githubusercontent.com/115066329/221875553-d2ab21a8-84eb-489f-af1b-56893db0dad6.png)

3.2 นักศึกษาคิดว่าที่ผิดพลาดนั้นเกิดจากอะไร
```text
ชื่อตัวแปรไม่ถูกต้องตามกฎ   
```
3.3 จะแก้ไขให้ถูกต้องได้อย่างไร
![image](https://user-images.githubusercontent.com/115066329/221876675-00b812c9-6a8c-4a94-aafb-918dd711eb58.png)


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
ผลที่ได้
![image](https://user-images.githubusercontent.com/115066329/221877337-e37c6cfa-88a0-4c48-a527-c845a63a5a4d.png)
![image](https://user-images.githubusercontent.com/115066329/221877425-957ce3a5-13f5-484b-9992-c2980942b442.png)
แก้ไข
![image](https://user-images.githubusercontent.com/115066329/221877726-ea4441e4-1f58-4cc1-8813-1fd73caebc08.png)
ผลที่ได้อีกครั้ง
![image](https://user-images.githubusercontent.com/115066329/221877913-db9cefb1-6298-4d8b-aab3-b220fed6fba1.png)


#### ชุดที่ 2 ####
```cs
Console.WriteLine($"{3} and {1}");
Console.WriteLine($"{3} and {1}");
Console.WriteLine($"{3.0d} and {1.0001d}");
Console.WriteLine($"{3:F2} and {1000.123:F1}");
Console.WriteLine($"{3.123456:F2} and {5.123000:F4}");
```
ผลที่ได้
![image](https://user-images.githubusercontent.com/115066329/221878244-6d988cdc-a552-442b-b715-aa82867ab3ad.png)
ผลลัพธ์
![image](https://user-images.githubusercontent.com/115066329/221878405-4ebe76db-cc37-490f-92ee-4a10b2df12ee.png)


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
ผลที่ได้
![image](https://user-images.githubusercontent.com/115066329/221878713-93da7820-83ca-4f4b-b73f-96af761e751c.png)
ผลลัพธ์
![image](https://user-images.githubusercontent.com/115066329/221878809-07dc4826-f96e-49ae-96f4-75ae440326b9.png)

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
ผลที่ได้
![image](https://user-images.githubusercontent.com/115066329/221878939-4e8b9931-a0a3-46f3-b81c-01a6764a23cb.png)
ผลลัพธ์
![image](https://user-images.githubusercontent.com/115066329/221879045-36b184e1-9a32-4ff1-a4df-d78ba2b0a045.png)

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
ผลที่ได้
![image](https://user-images.githubusercontent.com/115066329/221879398-e0ec0b58-2ed5-4910-b060-016eb5f5af3c.png)
![image](https://user-images.githubusercontent.com/115066329/221879344-e9cbb6a5-c26b-4be5-8bf8-3855ad82e5d6.png)
![image](https://user-images.githubusercontent.com/115066329/221879586-0bdcd577-4016-416d-81c0-bc5cae736b78.png)
แก้ไข
![image](https://user-images.githubusercontent.com/115066329/221879867-e2751841-e572-4acd-8501-946fdf059991.png)
ผลที่ได้อีกครั้ง
![image](https://user-images.githubusercontent.com/115066329/221880068-5b31a714-c5de-42d6-ac86-2eeccc9ebe1c.png)


#### ชุดที่ 6 ####
```cs
const double i = 123.456789;
Console.writLine($"{i,10:F1}");
Console.writLine($"{i,10:F2}");
Console.writLine($"{i,10:F3}");
Console.writLine($"{i,10:F4}");
Console.writLine($"{i,10:F5}");
```
ผลที่ได้
![image](https://user-images.githubusercontent.com/115066329/221880204-d137035c-17db-4547-ba8a-2f32aff4dd0b.png)
![image](https://user-images.githubusercontent.com/115066329/221880295-8dc2ffd0-25f4-4090-957e-2f1f5a47fc66.png)
![image](https://user-images.githubusercontent.com/115066329/221880500-756e79bf-6843-4ea2-91b1-482afaee4437.png)
แก้ไข
![image](https://user-images.githubusercontent.com/115066329/221880836-9568385b-c879-4129-a3a0-f66b78b14036.png)
ผลที่ได้อีกครั้ง
![image](https://user-images.githubusercontent.com/115066329/221881017-c3e9628d-ba68-46ec-bcc1-a6b56328afca.png)


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
ผลที่ได้
![image](https://user-images.githubusercontent.com/115066329/221881577-8f154f4d-5a42-46e6-bcd8-292f5ac2be94.png)
![image](https://user-images.githubusercontent.com/115066329/221881644-ae4fd5e8-7534-466b-baa6-444d4f49767f.png)
![image](https://user-images.githubusercontent.com/115066329/221881749-fed584ec-3ce5-4111-bb88-25baa6b38101.png)
แก้ไข
![image](https://user-images.githubusercontent.com/115066329/221882252-cb5e6549-ac92-497f-b6cb-b8102fe328fc.png)
ผลที่ได้อีกครั้ง
![image](https://user-images.githubusercontent.com/115066329/221882343-6ce170db-5596-450f-8692-f2118bf424c5.png)


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
```text
error
```

2. บรรทัดไหนของโปรแกรมที่มี error บ้าง เพราะอะไร
```text
21,22,23,24 ชื่อ class Number ต้องเป็นพิมพ์เล็ก
22,23,27,29 เพราะไม่ได้ประกาศตัวแปรใน class ให้เป็น static
```

3. ถ้าจะให้โปรแกรมทำงานได้ สามารถแก้ไขอย่างไรได้บ้าง
![image](https://user-images.githubusercontent.com/115066329/221884304-cdc47bbd-7527-4098-81a4-6e1fcc8f2d69.png)
ผลที่ได้
![image](https://user-images.githubusercontent.com/115066329/221884479-111398a9-d2a9-487f-a392-9781465b1ef0.png)
