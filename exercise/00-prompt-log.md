**ภาษา:** ภาษาไทย | [English](00-prompt-log.en.md)

# บันทึกการใช้ prompt

**ชื่อ / รหัสนิสิต: ปุณณวิศว์ สุภาวสุวัตร์ 6731332321**
**agent ที่ใช้: Codex**
**โมเดล: GPT sol6,GPT sol6.1**
**แพ็กเกจที่ใช้: GPT plus**

บันทึกทุกคำขอที่ส่งให้ agent ช่อง "ไฟล์ที่ agent อ่าน" คือไฟล์ที่ agent รายงาน หรือที่นิสิตเห็นว่า agent เปิด

| # | งาน / run | agent + โมเดล | ข้อความที่ส่ง (ย่อ) | ไฟล์ที่ agent อ่าน | อยู่ในขอบเขตหลักฐานที่อนุญาตหรือไม่ | มีประโยชน์ (1–5) | หมายเหตุ |
|---|---|---|---|---|---|---|---|
| 1 | 1-A |codex GPT6-sol() | `prompts/1-…` run A | prompts/1-recover-architecture.md และ system/online-boutique/protos/demo.proto|อยู่ |4 | |
| 2 | 1-B |codex GPT6-sol() | `prompts/1-…` run B |prompts/1-recover-architecture.md, system/online-boutique/protos/demo.proto และไฟล์ใน system/online-boutique/kubernetes-manifests/ ได้แก่ adservice.yaml, cartservice.yaml, checkoutservice.yaml, currencyservice.yaml, emailservice.yaml, frontend.yaml, kustomization.yaml, loadgenerator.yaml, paymentservice.yaml, productcatalogservice.yaml, recommendationservice.yaml และ shippingservice.yaml |อยู่ |5 | |
| 3 | 2-a |codex GPT6-sol() | `prompts/2-…` run a |prompts/2-write-adr.md และ docs/adr/template.md |อยู่ |4 | |
| 4 | 2-b |codex GPT6.1-sol() | `prompts/2-…` run b |prompts/2-write-adr.md ,docs/adr/template.md ,docs/scenario.md ,docs/adr/0001-use-redis-for-cart-storage.md ,system/online-boutique/src/checkoutservice/main.go |อยู่ |5 | |
| 5 | 3 |codex GPT6.1-sol() | `prompts/3-…` |prompts/3-review-adr.md ,docs/adr/0002-adr.md ,docs/scenario.md ,exercise/outputs/3-review.md |อยู่ |5 | |
| 6 | | | | | | | |
| 7 | | | | | | | |
