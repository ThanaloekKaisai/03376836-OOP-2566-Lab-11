# 3 #
![image](https://github.com/ThanaloekKaisai/03376836-OOP-2566-Lab-11/assets/144195683/d2cb4956-4cce-4623-b238-68604547075a)
```
สามารถ build ได้ เพราะ การสร้างคลาส Animal และคลาสลูกของมันอย่าง Dog, Fish, และ Bird ซึ่งแต่ละคลาสลูกมีเมทอด Move ที่ได้รับการโอเวอร์ไรด์ (override) 
จากคลาส Animal โดยแต่ละเมทอด Move ของคลาสลูกจะแสดงข้อความที่บอกถึงวิธีการเคลื่อนที่ของสัตว์แต่ละชนิด และเรียกใช้เมทอด Move ของคลาสแม่ด้วยคำสั่ง base.Move()
```
# 5 #
![image](https://github.com/ThanaloekKaisai/03376836-OOP-2566-Lab-11/assets/144195683/af0cc0ce-c232-4236-a8d3-5bb83ad8fcb2)
```
สามารถ Run ได้ เพราะ ใช้เมทอดของคลาสเดียวกันในลักษณะที่แตกต่างกันขึ้นอยู่กับประเภทของวัตถุที่เรียกใช้เมทอดนั้น 
ๆ ซึ่งเป็นเหตุผลในการทำให้เราสามารถเรียกใช้เมทอด Move() ของคลาส Animal
```

# อธิบาย #
```
โปรแกรมจะแสดงผล
Dog: Running on the ground.
Move successfully.
Fish: Swimming in the water.
Move successfully.
Bird: Flying in the air.
Move successfully.
