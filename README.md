# ENGSE601 · ตัวอย่างงานกลุ่มที่ทำครบ · Team00 (Case X)

> **นี่คือ repo ตัวอย่างของผู้สอน ไม่ใช่งานของนักศึกษา**
> ทีม Team00 เป็นทีมสมมติ ใช้ระบบ Case X และแอปสาธิต Case X Mini v0.9 แทนโครงงาน ENGSE212
> ใช้ดู **รูปแบบ ชื่อไฟล์ ที่วางไฟล์ และระดับความละเอียด** แล้วทำกับโครงงานของทีมเอง
> **ห้ามคัดลอกข้อความหรือหลักฐาน** งานที่คัดลอกจากตัวอย่างนี้ได้ 0 ในส่วนนั้น

repo นี้จัดเรียงแบบเดียวกับ [template ของรายวิชา](https://github.com/se-rmutl/engse601-project-template) ทุกไฟล์อยู่ในตำแหน่งที่ทีมต้องวางจริง เปิด [SUBMISSIONS.md](SUBMISSIONS.md) เทียบกับ repo ของทีมได้ทีละแถว

## งานทั้งหมดในตัวอย่างนี้

| # | งาน | ไฟล์ในตัวอย่าง | ใช้กรณีศึกษา | ดูอะไร |
|---|---|---|---|---|
| G1 | W01 Quality Risk Cards | [W01_Team00_Quality-Risk-Cards_v1.pdf](WEEKS/week-01/submission/W01_Team00_Quality-Risk-Cards_v1.pdf) | RMUTL Smart Campus | ตัวอย่างผลงานสำเร็จที่ใช้ในห้อง |
| G2 | W02 Project Quality Route Map | [W02_Team00_Project-Quality-Route-Map_v1.pdf](WEEKS/week-02/submission/W02_Team00_Project-Quality-Route-Map_v1.pdf) | RMUTL Smart Campus | ตัวอย่างผลงานสำเร็จที่ใช้ในห้อง |
| G3 | W03 Revised Critical Requirements | [W03_Team00_Revised-Critical-Requirements_v1.pdf](WEEKS/week-03/submission/W03_Team00_Revised-Critical-Requirements_v1.pdf) | RMUTL Smart Campus | ตัวอย่างผลงานสำเร็จที่ใช้ในห้อง |
| G4 | W04 SRS Review, RTM Lite และ Gate A | [W04_Team00_SRS-Review-and-RTM_v1.pdf](WEEKS/week-04/submission/W04_Team00_SRS-Review-and-RTM_v1.pdf) · [ไฟล์ทำงาน](WEEKS/week-04/work/) | **Case X SRS v1.1** | Review Log ที่มีทั้งข้อที่ผ่านและข้อค้นพบ · RTM · Gate A แบบมีเงื่อนไข |
| G5 | W05 Requirement-to-Design Trace | [W05_Team00_Requirement-to-Design-Trace_v1.pdf](WEEKS/week-05/submission/W05_Team00_Requirement-to-Design-Trace_v1.pdf) | Case X HLD v0.9 | ตัวอย่างงานเสร็จของสัปดาห์ที่ 5 |
| G6 | ใบงานครั้งที่ 1 ส่วน B | [S1-B_Team00.pdf](01-plan/S1-B_Team00.pdf) · [อ่านบนเว็บ](01-plan/S1-B_Team00.md) | Case X feature ส่งคำขอ | กฎ ภาพส่วนประกอบพร้อมป้ายที่มา ข้อค้นพบ 4 ส่วน Entry/Exit |
| G7 | ใบงานครั้งที่ 2 ส่วน B | [S2-B_Team00.pdf](02-test-design/S2-B_Team00.pdf) · [อ่านบนเว็บ](02-test-design/S2-B_Team00.md) | Case X Mini feature ส่งคำขอ | ความต้องการ เทคนิค ชุดกรณีทดสอบ สอบกลับ ทบทวน |
| G8 | ใบงานรวม 3–4 ส่วน B1 | [execution-report.md](03-test-execution/execution-report.md) · [tests/](03-test-execution/tests/) · [evidence/](03-test-execution/evidence/) | Case X Mini v0.9 | ผลรันจริงรวมข้อที่ไม่ผ่าน ภาพหน้าจอ UAT ที่ยังไม่ได้ทำ |
| G9 | ใบงานรวม 3–4 ส่วน B3 | [TEAM.md](TEAM.md) · [AI-LOG.md](AI-LOG.md) | — | ใครทำส่วนไหน และบันทึก AI ที่ตรวจแล้ว |

**ไม่มี** ใบงานรวม 3–4 ส่วน B2 และสัปดาห์ที่ 6–17 เพราะไม่ได้สอนในภาคนี้

## งานเชื่อมกันอย่างไร

```text
W03–W04  ทบทวนความต้องการ ──► Gate A แบบมีเงื่อนไข (TBD-X-04 ยังไม่มีคำตอบ)
W05      ทบทวนเอกสารออกแบบ ──► รู้ว่ากฎแต่ละข้ออยู่ที่ส่วนประกอบไหน
ครั้งที่ 1  เลือก feature ส่งคำขอ ──► ข้อค้นพบ I-03 · ขอบเขต · Entry/Exit
ครั้งที่ 2  ออกแบบกรณีทดสอบ 14 ข้อ ──► ชุดอ้างอิงรุ่น v1 (ยังไม่มีผลรัน)
ครั้งที่ 3  รันชุดอ้างอิงกับ v0.9 ──► ผลจริง 12 ผ่าน 2 ไม่ผ่าน + หลักฐาน
```

รหัสเดียวกันใช้ต่อกันทุกครั้ง เช่น TC-02 ออกแบบในครั้งที่ 2 ด้วยค่าขอบ 3 วัน แล้วรันจริงในครั้งที่ 3 และไม่ผ่าน ทีมไม่ได้แก้ผลที่คาดหวังให้ตรงผลจริง

## ตัวอย่างนี้ทำอะไรต่างจากงานของทีม

| เรื่อง | ในตัวอย่างนี้ | งานของทีม |
|---|---|---|
| ระบบที่ใช้ | Case X และแอปสาธิต Case X Mini v0.9 | โครงงาน ENGSE212 ของทีม ตามที่ใบงานกำหนด |
| W01–W03 | ไฟล์ตัวอย่างผลงานสำเร็จที่ใช้ในห้อง (Smart Campus) ตั้งชื่อใหม่ตามรูปแบบ | งานที่ทีมทำเอง |
| W04 | ทำใหม่ด้วย Case X SRS v1.1 เพื่อให้เห็นรูปแบบ (ในห้องใช้ Smart Campus) | งานที่ทีมทำเอง |
| ผู้ทำ | ผู้สอนจัดทำร่วมกับ Claude (AI) ดู [AI-LOG.md](AI-LOG.md) | สมาชิกทีม |
| ผลการรัน | รันจริงกับแอป v0.9 เมื่อ 20 ต.ค. 2569 ผลอยู่ใน `03-test-execution/evidence/` | ต้องรันเองกับระบบของทีม |

## ใช้ตัวอย่างนี้อย่างไร

1. ทำงานของทีมเองก่อน แล้วจึงเปิดตัวอย่างนี้เทียบทีละแถวใน [SUBMISSIONS.md](SUBMISSIONS.md)
2. ดูว่าทุกข้อค้นพบอ้างรหัสและรุ่นของเอกสาร ทุกผลรันมีไฟล์หลักฐาน และข้อที่ไม่ผ่านถูกบันทึกตามจริง
3. ดูชื่อไฟล์ ใช้ `<TeamName>` เดียวกันทุกไฟล์ ตัวอย่างนี้ใช้ `Team00`
4. ดูผลตรวจความครบในแท็บ **Actions** ของ repo นี้ ทีมจะเห็นแบบเดียวกันเมื่อ push

## เอกสารต้นทาง

| เอกสาร | ที่อยู่ |
|---|---|
| CaseX SRS v1.1 | [ENGSE_CaseX_SRS_v1_1_Practical_TH.docx](https://se-rmutl.github.io/engse601/materials/casex/ENGSE_CaseX_SRS_v1_1_Practical_TH.docx) |
| CaseX HLD v0.9 | [ENGSE601_CaseX_HLD_v0_9_Draft_for_Review_TH.docx](https://se-rmutl.github.io/engse601/materials/casex/ENGSE601_CaseX_HLD_v0_9_Draft_for_Review_TH.docx) |
| แอป Case X Mini v0.9 | [CaseXMini_v0.9_Student_S3.zip](https://se-rmutl.github.io/engse601/materials/app/CaseXMini_v0.9_Student_S3.zip) |
| เว็บรายวิชา | https://se-rmutl.github.io/engse601/ |
| Course Repo | https://github.com/se-rmutl/ENGSE601 |
