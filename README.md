# นี้คือตัวอย่างสำหรับโปรแกรม

### วิธีติดตั้ง

เปิด CMD / Terminal

```python
pip install sawschool
```

### วิธีเล่น

เปิด IDLE ขึ้นมาแล้วพิมพ์...

```python
from sawschool import Student, SpecialStudent

print('======1 Jan======')
Student0 = SpecialStudent('Mark Zuckerberg','Bill Gates')
Student0.ShowAskEXP() 
Student0.ShowEXP()

student1 = Student('Albert')
print(student1.name)
student1.Hello()

print('------------')
student2 = Student('Steve')
print(student2.name)
student2.Hello()
print('======2 Jan======')
print('------uncle : ใครอยากเรียนโค๊ดดิ้งบ้าง?---(10 exp)---')
student1.AddEXP(10)

print('======3 Jan======')
student1.name = 'Albert Eistein'
print('ตอนนี้ exp ของแต่ละคนได้เท่าไหร่แล้ว')

print(student1.name, student1.exp)
print(student2.name, student2.exp)
print('======4 Jan======')

for i in range(5):
	student2.Coding()

student1.ShowEXP()
student2.ShowEXP()



```



