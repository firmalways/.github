## FirmAlways

AI สำหรับองค์กรไทย ที่บริษัทคุมเองว่า AI เห็นข้อมูลอะไร

**[FirmAlways Gate](https://github.com/firmalways/gate)**: ด่านกรองข้อมูลส่วนบุคคลภาษาไทยแบบโอเพนซอร์ส ซ่อนเลขบัตรประชาชน ชื่อ เบอร์โทร เลขบัญชี และข้อมูลอ่อนไหวตาม PDPA มาตรา 26 ก่อนส่งข้อความให้ ChatGPT, Claude หรือ Gemini แล้วใส่ค่าจริงคืนในคำตอบ

```bash
curl -fsSL https://firmalways.meapplication.co.th/install.sh | sh
firmalways-gate scan "นายสมชาย ใจดี โทร 0812345678"
```

**[FirmAlways Pro](https://firmalways.meapplication.co.th/pro/)**: นโยบายข้อมูลแยกแผนก รายงาน PDPA สำหรับ DPO และ license แบบออฟไลน์ ติดตั้งใน cloud หรือสำนักงานของคุณ [ขอทดลองใช้](https://github.com/firmalways/gate/discussions/new?category=pro)

Website: [firmalways.meapplication.co.th](https://firmalways.meapplication.co.th) · Security reports: [SECURITY.md](https://github.com/firmalways/gate/blob/main/SECURITY.md)
