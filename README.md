### meangpu digital_garden

A reminder for myself...
open `content` folder in obsidian

### การเพิ่มไฟล์จาก obsidian หลักมาอันนี้

export target file using `markdown export` plugin from my main vault, so that it add image file along with text file

เรื่องไฟล์ภาพ เราอาจต้องมา auto ย้ายอีกทีให้ตรงคือ บางทีมันอยู่ใน

`Content/Note/Files`
แทนที่จะเป็น
`Content/Files`

เราต้องย้ายมันให้ไปอยู่ถูกที่

### preview page

คือ preview หน้าใน localhost ก่อน

```
npx quartz build --serve
```

### Build page

and each time I want to update page use command
คือ ดันการเปลี่ยนแปลงขึ้นหน้า web ให้ พร้อม auto push / commit

```
npx quartz sync
```
