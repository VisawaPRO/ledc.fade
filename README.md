# Example นี้มีชื่อว่า ledc.fade
โดยการทำงานของ Example นี้คือจะทำให้ led ค่อยๆสว่างขึ้นและค่อยๆดับลง
#
ขั้นตอนแรกเลือก Example
# ![image](https://github.com/user-attachments/assets/7ae2ffdb-e725-4e0b-83ae-9a8a243ae912)
รันและbuildโปรแกรม
# ![image](https://github.com/user-attachments/assets/0da5fc30-6e6c-49f7-9260-2cf17f02ef4d)
ด้วยมีการต่อสายไฟเข้า led ดังนี้
|GPIO 18|GPIO 19|GPIO 4|GPIO 5|
|-------|-------|------|------|

# จะได้ผลลัพธ์ดังนี้
# ![image](https://github.com/user-attachments/assets/d7104470-3d20-47e3-bb83-c66405f0dba8)

# แก้ไขเพิ่มเติม
สามารถปรับความเร็วของการค่อยๆสว่างค่อยๆดับได้
# ![image](https://github.com/user-attachments/assets/90d6bfca-82e4-45c0-9413-4cee427ee988)

```
#define LEDC_TEST_FADE_TIME    (3000)
```
สามารถเปลี่ยนเป็นค่าที่ต้องการได้ เช่น 1000 จะทำให้กระบวนการทุกอย่างเร็วขึ้น
