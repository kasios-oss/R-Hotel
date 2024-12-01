## R-Hotel
# นี้คือโปรเจคของฉัน เว็บไซต์จองโรงแรมของวิทยาลัย
# Project Overview.
```
	เนื่องจากในปัจจุบันนี้มีการจองห้องพักออนไลน์เยอะมาก อินเทอร์เน็ตมีอิทธิพลกับงานทุกสาขาอาชีพรวมทั้งงานสื่อสารมวลชนด้วย สำหรับงานสื่อสารมวลชนเป็นงานที่ต้องเน้นความรวดเร็วเป็นหลักให้ทันกับสถานการณ์บ้านเมืองในปัจจุบัน เพราะข่าวสารนั้นมีการอัพเดตอยู่ตลอดเวลา มิใช่มีประโยชน์เพียงแค่นี้ อีกทั้งยังสามารถใช้ในการติดต่อสื่อสาร การโฆษณาสินค้า การค้าขาย รวมทั้งการประชาสัมพันธ์ การสื่อสารโดยใช้อินเทอร์เน็ตในปัจจุบันนั้นถือว่าเป็นการสื่อสารที่ไร้พรมแดน มีการเข้าถึงกลุ่มเป้าหมายได้ในจำนวนมากได้เป็นเวลาอันรวดเร็วและใช้ต้นทุนต่ำ และอินเทอร์เน็ตถือว่าเป็นสื่อที่สามารถตอบสนองต่อความต้องการของสื่อมวลชนตามความต้องการดังกล่าว
	โดยทางวิทยาลัยอาชีวศึกษาภูเก็ตมีโรงแรมเป็นของตัวเอง ชื่อ R-Hotel และด้วยงานที่มีจำนวนมากและเร่งรีบจึงทำให้ไม่มีการจองห้องพักอย่างเป็นระบบ ส่งผลให้มีการพลาดลูกค้าที่จะเข้ามาใช้บริการ เนื่องจากการจองห้องยังมีแค่เว็บที่เอาไว้ดูห้องได้อย่างเดียวแต่ทำการจองไม่ได้ ถ้าจะจองก็ต้องโทรประสานกับประชาสัมพันธ์เพื่อจะขอจองห้องพัก จึงจำเป็นต้องพัฒนาเว็บไซต์ให้สามารถแก้ปัญหาเหล่านี้ได้
```
## Project Assumption.
``` 
ตัวเว็บแอพพลิเคชั่นจะมีหน้าต่าง Login และระบบฐานข้อมูลของลูกค้า หรือ User สามารถกดลืมรหัสผ่าน หรือสมัครใหม่ได้ เว็บแอพพลิเคชั่นระบบการจองห้องพัก R-Hotel มีตัวเลือกห้องที่สามารถให้ลูกค้าเลือกเข้าไปชมในหน้าเว็บได้ดด้วยตนเอง 
```
## Scope Boundaries
```
	สิ่งที่จะทำ
1)	เว็บแอพพลิเคชั่นระบบการจองห้องพัก R-Hotel จองห้องพักได้อย่างถูกต้อง
2)	เว็บแอพพลิเคชั่นระบบการจองห้องพัก R-Hotel ทำการ Login ได้
3)	เว็บแอพพลิเคชั่นระบบการจองห้องพัก R-Hotel สามารถชำระเงินได้
สิ่งที่จะไม่ทำ
1)	เว็บแอพพลิเคชั่นระบบการจองห้องพัก R-Hotel จะไม่มีระบบคืนเงิน
2)	เว็บแอพพลิเคชั่นระบบการจองห้องพัก R-Hotel จะไม่มีระบบการจองอย่างอื่นเพิ่มเติม

	ตัวเว็บแอพพลิเคชั่นจะมีหน้าต่าง Login และระบบฐานข้อมูลของลูกค้า หรือ User สามารถกดลืมรหัสผ่าน หรือสมัครใหม่ได้ เว็บแอพพลิเคชั่นระบบการจองห้องพัก R-Hotel มีตัวเลือกห้องที่สามารถให้ลูกค้าเลือกเข้าไปชมในหน้าเว็บได้ดด้วยตนเอง 
```

## High Level Deliverables
-	เว็บแอพพลิเคชั่นการจองห้องพัก จะมีการโชว์ให้ลูกค้าเห็นทุกมุมของห้องพักก่อนจอง
-	เว็บแอพพลิเคชั่นการจองห้องพัก จะต้องชำระเงินก่อนที่จะสิ้นสุดการขาย