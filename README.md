# 🏥 HIS-FHIR Integration System

ระบบ Hospital Information System (HIS) ที่ใช้มาตรฐาน **FHIR (Fast Healthcare Interoperability Resources)** เพื่อรองรับการเชื่อมต่อข้อมูลสุขภาพระหว่างโรงพยาบาลและระบบสุขภาพอื่น ๆ ได้อย่างมีประสิทธิภาพ

---

## Features

- ใช้มาตรฐาน **HL7 FHIR R4** สำหรับการจัดการข้อมูลผู้ป่วยและข้อมูลทางการแพทย์
- พัฒนาโดยใช้ **HAPI FHIR** ซึ่งเป็น Java framework สำหรับสร้าง FHIR Server/Client
- รองรับการเข้าถึงข้อมูลผู้ป่วยผ่าน REST API (เช่น `GET /Patient/{id}`)
- รองรับการ version ข้อมูลของ FHIR Resources (เช่น `GET /Patient/{id}/_history/{vid}`)
- รองรับ JSON และ XML เป็นรูปแบบข้อมูล
- ออกแบบมาเพื่อเชื่อมต่อกับระบบโรงพยาบาลภายนอก หรือหน่วยบริการสุขภาพอื่น ๆ
