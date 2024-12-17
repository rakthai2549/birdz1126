# Calculator

by Tanapattara Wongkhamchan,
670000000-0,
Computer and Infomation Science, KKU

# การรับและการแสดงผลข้อมูล

รับข้อมูลจากผู้ใช้งาน และทำงานผ่านการกดปุ่มเพื่อคำนวนตัวเลข

## ปุ่มบวก

```
private void button1_Click(object sender, EventArgs e)
{
    // ข้อความตัวอักษร
    string inputNum1 = num1.Text;
    string inputNum2 = num2.Text;
    // convert string to number (integer)
    int iNum1 = Int32.Parse(inputNum1);
    int iNum2 = Int32.Parse(inputNum2);
    // int ทำให้เราสามารถทำการ + - * / ได้
    int iResult = iNum1 + iNum2;
    // ที่ตัวแปรชื่อ result
    // มีคุณสมบัติชื่อ Text
    result.Text = iResult.ToString();
}
```

### รับข้อมูล

ตัวอย่าง

```

```

### แปลงชนิดของข้อมูล

ตัวอย่าง

```

```

### คำนวนผลลัพท์

ตัวอย่าง

```

```

### แสดงผล

ตัวอย่าง

```

```
## ปุ่มบวก
private void result1_Click(object sender, EventArgs e)
{
   string inputnum1 = num1.Text;
   string inputnum2 = num2.Text; 
    
    int inum1 = Int32.Parse(inputnum1);
    int inum2 = Int32.Parse(inputnum2);
    int iresult = inum1 + inum2;
    result.Text = iresult.ToString();
}
## ปุ่มลบ
private void button3_Click(object sender, EventArgs e)
{
    string inputnum1 = num1.Text;
    string inputnum2 = num2.Text;

    int inum1 = Int32.Parse(inputnum1);
    int inum2 = Int32.Parse(inputnum2);
    int iresult = inum1 - inum2;
    result.Text = iresult.ToString();
}
## ปุ่มคูณ
private void button1_Click(object sender, EventArgs e)
{
    string inputnum1 = num1.Text;
    string inputnum2 = num2.Text;

    int inum1 = Int32.Parse(inputnum1);
    int inum2 = Int32.Parse(inputnum2);
    int iresult = inum1 * inum2;
    result.Text = iresult.ToString();
}
## ปุ่มหาร
private void button4_Click(object sender, EventArgs e)
{
    string inputnum1 = num1.Text;
    string inputnum2 = num2.Text;

    int inum1 = Int32.Parse(inputnum1);
    int inum2 = Int32.Parse(inputnum2);
    int iresult = inum1 / inum2;
    result.Text = iresult.ToString();
}
## ปุ่มลบข้อมูล
private void button2_Click(object sender, EventArgs e)
{
    num1.Text = "";
    num2.Text = "";
    result.Text = "";
}