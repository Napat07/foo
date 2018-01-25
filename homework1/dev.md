# คำสั่งต่างๆ

## ทำการดึงข้อมูลจาก repository จากเครื่องอื่น
> git clone [url]

## ทำการสร้าง branch ใหม่
> git branch <namebranch>

## ทำการทดสอบตำแหน่งของ branch
> git branch -a

## คำสั่งย้าย branch
> git checkout <namebranch>

## คำสั่งเพื่อส่งการเปลี่ยนแปลงของ branch ที่ต้องการไปยัง remote repository
> git push origin <branch>

## เป็นการ Merge ข้อมูล
> git merge --no-ff <namebranch>

## ต้องการ merge การเปลี่ยนแปลงจาก branch อื่น มายัง branch ปัจจุบัน
> git merge <branch>

## push ข้อมูลเข้าไปใน Branch นั้นๆ
> git push -u origin Branch(nameBranch)
