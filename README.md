# Grocery Store POS

ระบบหน้าร้าน POS สำหรับร้านขายของ

## โครงสร้าง
- `index.html` — หน้าเว็บ POS
- `supabase/functions/pos/index.ts` — Supabase Edge Function สำหรับให้บริการหน้าเว็บ

## การตั้งค่า
ใช้ Supabase Auth สำหรับเข้าสู่ระบบ และอ่านข้อมูลสินค้าจากตาราง `public.products` โดยใช้ Row Level Security

> รุ่นปัจจุบันเป็นรุ่นทดสอบ ยังไม่รองรับการชำระเงินจริงหรือการบันทึกยอดขาย
