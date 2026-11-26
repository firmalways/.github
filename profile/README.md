## FirmAlways

AI สำหรับองค์กรไทย ที่บริษัทคุมเองว่า AI เห็นข้อมูลอะไร

**[FirmAlways Personal](https://github.com/firmalways/personal)** (ฟรี): ส่วนขยายเบราว์เซอร์ ซ่อนข้อมูลส่วนตัวก่อนส่งให้ ChatGPT, Claude, Gemini ใช้บัญชีเดิม ทำงานในเครื่อง ไม่ต้องใช้ Terminal [ดาวน์โหลด](https://github.com/firmalways/personal/releases/latest)

**[FirmAlways Gate](https://github.com/firmalways/gate)** (Tier 1, สำหรับนักพัฒนา): ด่านกรองข้อมูลส่วนบุคคลภาษาไทยแบบโอเพนซอร์ส ซ่อนเลขบัตรประชาชน ชื่อ เบอร์โทร เลขบัญชี และข้อมูลอ่อนไหวตาม PDPA มาตรา 26 ก่อนส่งข้อความให้ ChatGPT, Claude หรือ Gemini แล้วใส่ค่าจริงคืนในคำตอบ

```bash
curl -fsSL https://firmalways.meapplication.co.th/install.sh | sh
firmalways-gate scan "นายสมชาย ใจดี โทร 0812345678"
```

**[FirmAlways Pro](https://firmalways.meapplication.co.th/pro/)** (Tier 2, สำหรับองค์กร): นโยบายข้อมูลแยกแผนก รายงาน PDPA สำหรับ DPO และ license แบบออฟไลน์ ติดตั้งใน cloud หรือสำนักงานของคุณ [ขอทดลองใช้](https://github.com/firmalways/gate/discussions/new?category=pro)

Website: [firmalways.meapplication.co.th](https://firmalways.meapplication.co.th) · Security reports: [SECURITY.md](https://github.com/firmalways/gate/blob/main/SECURITY.md)
