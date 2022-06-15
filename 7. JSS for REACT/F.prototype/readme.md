# Homework_codecamp_11
    1. Jirapat Pojjariyaporn
- Exercise
    1. สร้าง new Rabbit() ขึ้นมา
        - ถ้ามีการ alert บรรทัดดังกล่าวจะได้อะไรออกมา
            - Rabbit.prototype = {};
        - ถ้ามีการเปลี่ยนบรรทัดสีเหลืองจะเป็นอย่างไร
            - rabbit.prototype.eats = false;
            - delete rabbit.eats;
            - delete Rabbit.prototype.eats;
    2. ถ้าต้องการสร้างใช้ constructor ของ obj เราสามารถเขียนแบบนี้ได้ไหม
        - let obj2 = new obj.constructor();