# แบบฝึกหัด

## 1. ให้นักศึกษาพิจารณาชื่อตัวแปรตามตารางต่อไปนี้ ว่าสามารถใช้ได้หรือไม่ พร้อมบอกเหตุผล

|    ที่ |  ชื่อตัวแปร   | ใช้ได้/ไม่ได้ | เหตุผล                                |
| ---: | :--------: | --------- | ------------------------------------ |
|  1.1 |    xxx     | ใช้ได้      | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ             |
|  1.2 |    null    | ใช้ไม่ได้    | เป็นคำสงวนในภาษา C#                    |
|  1.3 |   _value   | ใช้ได้      | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ             |
|  1.4 | First-name | ใช้ไม่ได้    | ตัวแปรจะต้องไม่ประกอบไปด้วยอักษรพิเศษทุกชนิด |
|  1.5 |   Hello!   | ใช้ไม่ได้    | ตัวแปรจะต้องไม่ประกอบไปด้วยอักษรพิเศษทุกชนิด |
|  1.6 |    w*h     | ใช้ไม่ได้    | ตัวแปรจะต้องไม่ประกอบไปด้วยอักษรพิเศษทุกชนิด |
|  1.7 |    time    | ใช้ได้      | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ             |
|  1.8 |     do     | ใช้ไม่ได้    | เป็นคำสงวนในภาษา C#                    |
|  1.9 |     Do     | ใช้ได้      | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ             |
| 1.10 | 21November | ใช้ไม่ได้    | ละเมิดกฎการตั้งชื่อ                       |
| 1.11 | ladkrabang | ใช้ได้      | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ             |
| 1.12 |   Double   | ใช้ได้      | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ             |
| 1.13 |   My Car   | ใช้ไม่ได้    | ละเมิดกฎการตั้งชื่อ                       |
| 1.14 |  my_home   | ใช้ได้      | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ             |
| 1.15 |    Int     | ใช้ไม่ได้    | เป็นคำสงวนในภาษา C#                    |

## 2.  จงบอกชนิดข้อมูลที่สามารถรองรับค่าต่อไปนี้อย่างเหมาะสมพร้อมทั้งใส่ค่าเริ่มต้นตามที่กำหนดให้ ถ้าข้อใดมีหลายตัวแปร ให้ระบุให้ครบ
 

2.1 (ตัวอย่าง) เสียงเดินทางด้วยความเร็ว 340.0 เมตรต่อวินาที

```csharp
    float speedOfSound = 340.0f;
```

2.2 จำนวนนักศึกษาในชั้นเรียนนี้คือ 42 คน
```csharp
    int numberOfStudents = 42;
```

2.3 ระยะห่างจากดวงอาทิตย์ถึงโลกคือ 149,668,992 กิโลเมตร
```csharp
    long distanceFromSunToEarth = 149668992L;
```

2.4 ชาวนามีวัว 12 ตัว ม้า 68 ตัว และ ไก่ 12,000 ตัว ตามกฎหมาย เมืองนี้อนุญาตให้เลี้ยงสัตว์ที่เท้าได้ไม่เกินครอบครัวละ 200 ตัว (มี 3 ตัวแปร)
```csharp
    int numberOfCows = 12;
    int numberOfHorses = 68;
    int numberOfChickens = 12000;
```

2.5 แดงวัดขนาดของบ้าน พบว่าต้องใช้อิฐจำนวน 1325.8 ชิ้น แต่เมื่อไปถึงร้านก่อสร้าง พบว่าเขาขายอิฐเป็นยก ยกละ 10 ก้อน ไม่ขายเป็นเศษ
```csharp
    float numberOfBricks = 1325.8f;
    int numberOfBricksPerBag = 10;
```

2.6 แสงเดินทางด้วยความเร็ว 299,337.984 กิโลเมตรต่อวินาที  ดาวศุกร์ห่างจากดวงอาทิตย์ 108,200,000 กิโลเมตร อยากทราบว่าแสงใช้เวลาในการเดินทางกี่วินาที (มี 3 ตัวแปร)
```csharp
    float speedOfLight = 299337.984f;
    long distanceFromSunToMars = 108200000L;
    float timeToTravel = 0.0f;
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
บรรทัดที่ 4, 5, 8, 9, 10
```

3.1 compiler ฟ้องว่าอะไร
```dotnetcli
/home/runner/LoneSubstantialDatasets/main.cs(12,16): error CS1044: Cannot use more than one type in a for, using, fixed, or declaration statement [/home/runner/LoneSubstantialDatasets/main.csproj]
/home/runner/LoneSubstantialDatasets/main.cs(12,21): error CS1002: ; expected [/home/runner/LoneSubstantialDatasets/main.csproj]
/home/runner/LoneSubstantialDatasets/main.cs(12,23): error CS1002: ; expected [/home/runner/LoneSubstantialDatasets/main.csproj]
/home/runner/LoneSubstantialDatasets/main.cs(12,23): error CS1513: } expected [/home/runner/LoneSubstantialDatasets/main.csproj]

The build failed. Fix the build errors and run again.
exit status 1
```

3.2 นักศึกษาคิดว่าที่ผิดพลาดนั้นเกิดจากอะไร
``` text
บรรทัดที่ 4: ไม่ได้ประกาศตัวแปร var5 ก่อนนำมาใช้ในการกำหนดค่าให้กับ var4
บรรทัดที่ 5: ไม่ได้ใช้ชื่อตัวแปร Int ในการประกาศตัวแปร var6
บรรทัดที่ 8: ประกาศตัวแปร var10 และ c1 แต่ไม่ได้ระบุประเภทของตัวแปร c1
บรรทัดที่ 9: ไม่สามารถกำหนดค่า False ให้กับตัวแปรประเภท double ได้ เนื่องจาก False เป็นค่าคงที่ประเภท boolean และไม่สามารถแปลงเป็นประเภท double ได้
บรรทัดที่ 10: ไม่สามารถกำหนดค่า 0 ให้กับตัวแปรประเภท bool ได้ เนื่องจาก 0 เป็นค่าคงที่ประเภท int และไม่สามารถแปลงเป็นประเภท bool ได้
```
3.3 จะแก้ไขให้ถูกต้องได้อย่างไร
```csharp
int var = 30;
int var1;
int var2, var3;
int var4 = var5; // ต้องกำหนดค่าให้กับ var5 ก่อนใช้งาน
int var5 = 50; // เพิ่มตัวแปร var5 เพื่อใช้ใน var4
int var6 = 2, var7;
int var8 = 10 * 5;
int var9 = var;
int var10; 
char c1; // ใช้คำว่า char ไม่ใช้ Char และไม่ต้องกำหนดค่าเริ่มต้น
float f1; // ไม่ต้องกำหนดค่าเริ่มต้น
double d1 = 0.0; // ใช้ค่าเริ่มต้น 0.0 แทน False
bool b1 = false; // ใช้คำว่า bool แทน Bool และใช้ค่าเริ่มต้น false แทน 0

```
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
- ผลการรัน
```cs
/home/runner/LoneSubstantialDatasets/main.cs(5,13): error CS0117: 'Console' does not contain a definition for 'writeLine' [/home/runner/LoneSubstantialDatasets/main.csproj]
/home/runner/LoneSubstantialDatasets/main.cs(6,13): error CS0117: 'Console' does not contain a definition for 'writeLine' [/home/runner/LoneSubstantialDatasets/main.csproj]
/home/runner/LoneSubstantialDatasets/main.cs(7,13): error CS0117: 'Console' does not contain a definition for 'writeLine' [/home/runner/LoneSubstantialDatasets/main.csproj]
/home/runner/LoneSubstantialDatasets/main.cs(8,13): error CS0117: 'Console' does not contain a definition for 'writeLine' [/home/runner/LoneSubstantialDatasets/main.csproj]
/home/runner/LoneSubstantialDatasets/main.cs(9,13): error CS0117: 'Console' does not contain a definition for 'writeLine' [/home/runner/LoneSubstantialDatasets/main.csproj]

The build failed. Fix the build errors and run again.
exit status 1
```
- แก้ไข
```cs
Console.WriteLine("{0} and {1}", 3,5);
Console.WriteLine("{0} and {1}", 3.0,5.0);
Console.WriteLine("{0} and {1}", 3.0d, 5.0d);
Console.WriteLine("{0:F1} and {1:F1}", 3.0, 5.0);
Console.WriteLine("{0:F2} and {1:F2}", 3.0d, 5.0d);
```
- ผลการรัน
```cs
3 and 5
3 and 5
3 and 5
3.0 and 5.0
3.00 and 5.00
```

#### ชุดที่ 2 ####
```cs
Console.WriteLine($"{3} and {1}");
Console.WriteLine($"{3} and {1}");
Console.WriteLine($"{3.0d} and {1.0001d}");
Console.WriteLine($"{3:F2} and {1000.123:F1}");
Console.WriteLine($"{3.123456:F2} and {5.123000:F4}");
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


#### ชุดที่ 6 ####
```cs
const double i = 123.456789;
Console.writLine($"{i,10:F1}");
Console.writLine($"{i,10:F2}");
Console.writLine($"{i,10:F3}");
Console.writLine($"{i,10:F4}");
Console.writLine($"{i,10:F5}");
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

2. บรรทัดไหนของโปรแกรมที่มี error บ้าง เพราะอะไร

3. ถ้าจะให้โปรแกรมทำงานได้ สามารถแก้ไขอย่างไรได้บ้าง
