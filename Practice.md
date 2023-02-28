# แบบฝึกหัด

## 1. ให้นักศึกษาพิจารณาชื่อตัวแปรตามตารางต่อไปนี้ ว่าสามารถใช้ได้หรือไม่ พร้อมบอกเหตุผล

| ที่ | ชื่อตัวแปร | ใช้ได้/ไม่ได้ | เหตุผล |
|---:|:-------:|-----------|-------|
|  1.1 | xxx         | ใ ช้ได้  | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ
|  1.2 | null        | ใช้ไม่ได้ | เป็นคำสงวนในภาษา C#
|  1.3 | _value      |   ใช้ได้     |  ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ      
|  1.4 | First-name  |   ใช้ไม่ได้    |  ห้ามมี- ในชื่อ        
|  1.5 | Hello!      |    ใช้ไม่ได้    |   ห้ามมี ! ในชื่อ       
|  1.6 | w * h       |   ใช้ไม่ได้     |  ห้ามวรรค       
|  1.7 | time        |   ใช้ได้      |  ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ      
|  1.8 | do          |    ใช้ไม่ได้     |   เป็นคำสั่ง     
|  1.9 | Do          |    ใช้ได้     |   ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ     
| 1.10 |  14February |     ใช้ไม่ได้    |    ไม่ใช้ตัวเลข    
| 1.11 |  1adkrabang |    ใช้ได้     |      ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ  
| 1.12 | Double      |     ใช้ได้    |    ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ    
| 1.13 | My Car      |     ใช้ไม่ได้    |    ห้ามวรรค    
| 1.14 | my_home     |     ใช้ได้    |  ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ      
| 1.15 | Int         |    ใช้ได้     |   ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ 

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
    uint sun_to_earth = 149668992;
```

2.4 ชาวนามีวัว 12 ตัว ม้า 68 ตัว และ ไก่ 12,000 ตัว ตามกฎหมาย เมืองนี้อนุญาตให้เลี้ยงสัตว์ที่เท้าได้ไม่เกินครอบครัวละ 200 ตัว (มี 3 ตัวแปร)

```csharp
    byte cow = 12;
    byte horse = 68;
    ushort chicken = 12000;
    int animal_one_fammily = 200;
```

2.5 แดงวัดขนาดของบ้าน พบว่าต้องใช้อิฐจำนวน 1325.8 ชิ้น แต่เมื่อไปถึงร้านก่อสร้าง พบว่าเขาขายอิฐเป็นยก ยกละ 10 ก้อน ไม่ขายเป็นเศษ

```csharp
    ushort brickFstore = 10;
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

- 2,4,5,8,9,10

3.1 compiler ฟ้องว่าอะไร

3.2 นักศึกษาคิดว่าที่ผิดพลาดนั้นเกิดจากอะไร

-ชื่อตัวแปรเป็นพิมพ์ใหญ่ซึ่งผิด
-Boolพิมใหญ่ 
-Flase

3.3 จะแก้ไขให้ถูกต้องได้อย่างไร

![ภาพ](https://user-images.githubusercontent.com/112167732/221600264-2925ce21-88a7-434d-b178-4492bd1d8064.png)


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

![ภาพ](https://user-images.githubusercontent.com/112167732/221601743-40779bb4-36e0-4a45-a7da-b1bab5c4d17f.png)


#### ชุดที่ 2 ####
```cs
Console.WriteLine($"{3} and {1}");
Console.WriteLine($"{3} and {1}");
Console.WriteLine($"{3.0d} and {1.0001d}");
Console.WriteLine($"{3:F2} and {1000.123:F1}");
Console.WriteLine($"{3.123456:F2} and {5.123000:F4}");
```

![ภาพ](https://user-images.githubusercontent.com/112167732/221602075-95feeaad-5bfd-4c7d-ad5e-82cd7add0481.png)


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

![ภาพ](https://user-images.githubusercontent.com/112167732/221603731-d79aecee-3588-40ee-ac61-71de9db96a9d.png)


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

![ภาพ](https://user-images.githubusercontent.com/112167732/221603139-e987557e-42be-4b73-80e6-cae7a390bda7.png)



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

![ภาพ](https://user-images.githubusercontent.com/112167732/221604334-e1522cbc-fd2e-4d38-9c2e-e826fe37f9ea.png)


#### ชุดที่ 6 ####
```cs
const double i = 123.456789;
Console.writLine($"{i,10:F1}");
Console.writLine($"{i,10:F2}");
Console.writLine($"{i,10:F3}");
Console.writLine($"{i,10:F4}");
Console.writLine($"{i,10:F5}");
```

![ภาพ](https://user-images.githubusercontent.com/112167732/221604798-70812c66-9bba-4bd5-80ac-97b2b0530d12.png)


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

![ภาพ](https://user-images.githubusercontent.com/112167732/221605706-95fe847b-a251-4773-b646-90d742bfbc54.png)


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

-error

2. บรรทัดไหนของโปรแกรมที่มี error บ้าง เพราะอะไร

-Number ต้องเป็น number 21,22,23,24
-บรรทัด 14,15 ทำให้บรรทัด 22,24 ผิดเพราะ ลืมกำหนดstatic


3. ถ้าจะให้โปรแกรมทำงานได้ สามารถแก้ไขอย่างไรได้บ้าง

![ภาพ](https://user-images.githubusercontent.com/112167732/221734203-018b1959-bbeb-4338-8fb2-b34687fe00e4.png)



