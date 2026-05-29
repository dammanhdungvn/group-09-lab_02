# BAI TAP CA NHAN

## Dam Manh Dung - 2A202600741

**Nhom:** 09  
**De tai nhom da chon:** AI Report Assistant - AI ho tro sinh vien xay dung bao cao du an.  
**Vai tro ca nhan:** dua ra candidate problem chinh, tong hop workflow, viet problem statement, chon metric va lap luan vi sao nen chon Workflow thay vi Agent.

---

# 1. Individual Problem Scan

## 1.1. Scan rong 10 problems

| # | Lang kinh | Problem quan sat duoc | Ai dang dau? | Dau hieu that |
|---:|---|---|---|---|
| 1 | Ton thoi gian / AI co the tot hon | Lam xong du an nhung mat rat lau de viet bao cao hoan chinh | Sinh vien lam bai tap lon/do an | Thong tin nam rai rac o code, README, anh demo, test |
| 2 | Lap lai | Moi lan nop bai phai tao lai folder, README, report, checklist | Sinh vien | De quen file hoac dat sai ten |
| 3 | Ton thoi gian | Khong biet bat dau report tu chuong nao, viet y nao truoc | Sinh vien moi lam do an | Blank page, tri hoan den gan deadline |
| 4 | AI co the tot hon | Kho chuyen noi dung ky thuat thanh giai thich de hieu | Sinh vien IT | Biet code chay gi nhung kho dien dat trong bao cao |
| 5 | Pain tu nguoi khac | Bao cao nhom bi lech giong van va trung/lap y | Nhom sinh vien | Moi nguoi viet mot phan, tong hop cuoi rat met |
| 6 | Lap lai | Tim lai cau tra loi/huong dan cu trong Discord/LMS mat thoi gian | Hoc vien trong lop | Hay hoi lai deadline, format, yeu cau nop bai |
| 7 | Ton thoi gian | Tong hop meeting notes/action items sau khi hoc nhom | Nhom sinh vien | Sau buoi hop van quen ai lam gi |
| 8 | Pain tu nguoi khac | Ban moi tham gia du an khong hieu cau truc source code | Thanh vien moi | Phai hoi lai nguoi cu nhieu lan |
| 9 | Lap lai / Ton thoi gian | Sua format Markdown/LaTeX/Word theo mau truong | Sinh vien | Loi bang, hinh, heading, muc luc |
| 10 | AI co the tot hon | Review bai nop xem co thieu rubric nao khong | Sinh vien truoc khi nop | Gan deadline moi phat hien thieu phan kiem thu/tai lieu tham khao |

## 1.2. Chon top 3

| Rank | Problem | Vi sao chon | Dieu con chua chac |
|---:|---|---|---|
| 1 | AI ho tro sinh vien xay dung bao cao du an | Actor ro, workflow dai, dau that, co the do bang thoi gian va so muc thieu | Can do baseline that tren nhieu bao cao |
| 2 | Tim lai huong dan/cau tra loi cu trong Discord/LMS | Nhieu hoc vien hoi lai cung mot thong tin, AI search co the huu ich | Data access va privacy |
| 3 | Review bai nop theo rubric truoc deadline | Tac dong truc tiep toi diem nop bai, co checklist ro | Co the Rule/checklist da du cho phan lon case |

---

# 2. Top 3 Problem Cards

## Problem Card #1 - AI Report Assistant

**Problem 1 cau:**  
Sinh vien lam xong san pham du an nhung mat nhieu thoi gian de tong hop source code, README, hinh demo, test result va ghi chu thanh mot bao cao co cau truc, dung su that va co bang chung.

**Actor:**  
Sinh vien/nhom sinh vien lam bai tap lon, do an mon hoc, bao cao thuc tap hoac do an tot nghiep.

**Thoi diem / boi canh:**  
Sau khi san pham da co demo chay duoc va truoc deadline nop bao cao.

**Current workflow 3-7 buoc:**

1. Tim lai source code, README, screenshot, test result.
2. Doc lai rubric/mau bao cao cua giang vien.
3. Tu lap outline.
4. Viet noi dung tung chuong.
5. Chen hinh, bang, ket qua kiem thu.
6. Sua format Markdown/LaTeX/Word.
7. Review va nop.

**Bottleneck:**  
Viet noi dung tung chuong va gan bang chung dung cho tung claim. Uoc luong 10-18 gio trong tong 24-40 gio lam bao cao.

**Impact:**  
Sinh vien de thieu bang chung, de viet sai voi san pham thuc te, va thuong don viec vao vai ngay cuoi deadline.

**Success metric:**  
Giam thoi gian co ban nhap dau tien tu 24-40 gio xuong 9-16 gio; so muc thieu trong checklist <= 1; claim khong co bang chung trong final = 0.

**Non-AI alternative:**  
Mau bao cao + checklist + folder template. Cach nay giam sot format nhung khong giai quyet het viec dien dat va tong hop bang chung.

**AI hypothesis:**  
AI co the phan loai tai lieu, goi y outline, tao evidence matrix, draft tung phan dua tren du lieu that. Sinh vien van review va chiu trach nhiem.

**Quick gut:**  
Workflow.

### Draft current workflow

```text
CURRENT STATE - 24-40 gio

[Tim tai lieu du an: 3-6h]
-> [Doc rubric/mau: 1-2h]
-> [Lap outline: 2-4h]
-> [Viet noi dung: 10-18h] <-- bottleneck
-> [Chen hinh/test/reference: 4-6h]
-> [Sua format: 2-4h]
-> [Review va nop: 2-4h]
```

### Draft future workflow

```text
FUTURE STATE - 9-16 gio

[Upload/goi tai lieu du an]
-> [Rule check file bat buoc]
-> [AI phan loai + tao evidence matrix]
-> [AI de xuat outline]
-> [AI draft tung phan dua tren evidence]
-> [Sinh vien review/sua/xac nhan]
-> [Export Markdown/LaTeX]

Fallback: khong co bang chung -> danh dau "Can bo sung", khong duoc bia.
```

## Problem Card #2 - Tim lai huong dan cu trong Discord/LMS

**Problem 1 cau:**  
Hoc vien mat thoi gian tim lai deadline, format nop bai, link tai lieu va cau tra loi cu vi thong tin nam rai rac trong Discord/LMS.

**Actor:**  
Hoc vien trong lop, dac biet nguoi hoc lai sau buoi hoc hoac vao muon.

**Current workflow:**

1. Nho mang mang minh da thay thong tin o dau.
2. Search Discord/LMS bang keyword.
3. Doc nhieu thread/tin nhan.
4. Hoi lai ban hoc/giang vien neu khong tim thay.
5. Tong hop lai thanh viec can lam.

**Bottleneck:**  
Search va doc thread mat 10-20 phut/lần; co khi hoi lai cung mot cau.

**Impact:**  
Mat thoi gian cho ca nguoi hoi va nguoi tra loi; de nop sai format.

**Success metric:**  
Giam thoi gian tim thong tin tu 10-20 phut xuong duoi 3 phut; giam cau hoi lap lai trong Discord.

**Non-AI alternative:**  
FAQ co dinh + pin message + README tong hop.

**AI hypothesis:**  
AI search/tom tat dua tren tai lieu lop, tra loi kem link nguon.

**Quick gut:**  
Workflow hoac Agent nho, nhung can xem privacy/data access.

### Draft workflow

```text
CURRENT: [Can tim thong tin] -> [Search keyword] -> [Doc nhieu thread] -> [Hoi lai] -> [Lam bai]
FUTURE:  [Hoi assistant] -> [Lay cau tra loi kem link nguon] -> [Hoc vien kiem link] -> [Lam bai]
```

## Problem Card #3 - Review bai nop theo rubric

**Problem 1 cau:**  
Truoc deadline, sinh vien khong chac bai nop da du cac muc rubric hay chua, dan den thieu phan quan trong nhu workflow, metric, boundary hoac reflection.

**Actor:**  
Sinh vien nop bai lab/do an co rubric ro.

**Current workflow:**

1. Doc lai rubric.
2. Mo tung file bai nop.
3. Tu check xem co du muc chua.
4. Sua them cac phan con thieu.
5. Nop bai.

**Bottleneck:**  
Tu doi chieu rubric voi bai nop thu cong, de bo sot vi doc qua nhanh luc gan deadline.

**Impact:**  
Mat diem vi thieu field bat buoc, du y tuong co the dung.

**Success metric:**  
Giam so field thieu sau khi nop xuong 0-1; thoi gian self-check tu 30-45 phut xuong 10-15 phut.

**Non-AI alternative:**  
Checklist checkbox theo rubric.

**AI hypothesis:**  
AI doc bai nop va rubric, danh dau muc nao da co, muc nao con mo ho, muc nao thieu. Khong cham diem thay giang vien.

**Quick gut:**  
Rule + Workflow.

### Draft workflow

```text
CURRENT: [Doc rubric] -> [Mo tung file] -> [Tu check] -> [Sua] -> [Nop]
FUTURE:  [Upload bai + rubric] -> [Rule/AI tao checklist] -> [Flag muc thieu] -> [Sinh vien sua] -> [Nop]
```

---

# 3. Card toi pitch voi nhom

**Card toi muon pitch nhat:** AI Report Assistant.

**Vi sao:**  
Day la problem toi thay sat voi de tai slide va trai nghiem hoc tap. No khong bat dau bang "lam chatbot", ma bat dau bang workflow that: sinh vien da co source code/demo/test nhung bi nghen o viec tong hop va trinh bay thanh bao cao.

**Cau hoi toi muon nhom challenge:**

```text
Neu chi dung template + checklist thi da du chua, hay phai can AI de draft/tong hop?
AI duoc phep lam toi dau de khong bien thanh viet thay sinh vien?
Metric nao chung minh giai phap tot hon, ngoai cam giac "nhanh hon"?
```

---

# 4. Toi da tham gia vao phan nao?

| Hoat dong | Toi da lam gi? | Ket qua / anh huong |
|---|---|---|
| Scan ca nhan | Dua ra 10 problems tu hoc tap, nop bai, lam nhom | Co du input de chon top 3 |
| Pitch Problem Card | Pitch AI Report Assistant | De tai duoc nhom chon lam candidate chinh |
| Challenge bai cua ban khac | Hoi tool format co giai quyet bottleneck narrative khong | Nhom khong chon bai qua hep ve format |
| Gom trung / cluster | Gom cac y ve report, evidence, format, reference | Nhom thay duoc problem lon la "tong hop bao cao tu du an that" |
| Chon candidate problem | De xuat chon AI Report Assistant | Nhom dong thuan vi workflow va metric ro |
| Validation / research | Tong hop nguon Overleaf, Gemini Drive, Copilot, Grammarly | Nhom thay khong nen build agent tu dong nop bao cao |
| Workflow nhom | Ve current/future workflow va bottleneck | Nhom co before/after ro de dua vao report |
| Problem Statement | Viet v0/v1 voi actor, bottleneck, metric, boundary | Giam viec noi chung chung "AI giup viet bao cao" |
| Rule / Workflow / Agent | Lap luan chon Workflow | Nhom tranh nhay som sang Agent |
| Decision | De xuat Go voi pilot nho | Co cach test thuc te va rollback |

---

# 5. Bang dung AI trong qua trinh lam bai

| Phase | Toi dung AI de lam gi? | AI huu ich o dau? | AI sai/hoi hot o dau? | Toi sua gi bang nhan dinh cua minh? |
|---|---|---|---|---|
| Scan | Goi y them lang kinh problem | Giup mo rong tu report sang rubric, Discord, review bai nop | Co y qua rong nhu "AI tro ly hoc tap toan dien" | Chi giu pain co workflow that |
| Problem Card | Nho AI phan bien actor, workflow, metric | Giup thay metric "nhanh hon" chua du | AI co xu huong de xuat agent som | Ha ve Workflow |
| Workflow | Chuyen mo ta thanh before/after steps | Giup ro bottleneck va human boundary | Ban dau gop chung review va viet bao cao | Tach review thanh buoc kiem soat chat luong |
| Research | Tim tool/pattern tuong tu | Goi y Overleaf, Gemini Drive, Copilot, writing assistant | Mot so claim ve tiet kiem thoi gian khong co nguon | Chi giu link chinh thuc, khong dung so lieu chua verify |
| Problem Statement | Hoi field nao mo ho | Giup them boundary "khong co evidence thi flag" | AI viet lai qua dep nhung hoi chung | Toi dua lai vao boi canh sinh vien nop bao cao |
| Rule / Workflow / Agent | So sanh muc do phu hop | Giup thay Rule van co vai tro trong checklist | De xuat agent doc repo tu dong qua manh | Chon Workflow co human review |
| Decision | Kiem tra Go/Not Yet/No-Go | Giup co pilot nho va rollback | Co xu huong optimistic | Them dieu kien ha scope neu draft sai qua nhieu |

---

# 6. Reflection ca nhan

Qua bai lab nay, toi hoc duoc rang mot y tuong AI tot khong bat dau tu viec "co model nao hay" ma bat dau tu actor, workflow, bottleneck va metric. Ban dau de tai "AI ho tro viet bao cao" nghe rat de bi hieu thanh AI viet thay sinh vien. Sau khi ve workflow, toi thay problem dung hon la sinh vien co nhieu thong tin that nhung khong biet tong hop va trinh bay chung thanh bao cao co bang chung.

Khi nghe cac ban trong nhom dua ra y tuong ve format, citation va lam viec nhom, toi thay cac y do deu dung nhung khong phai bottleneck lon nhat. Neu chi lam tool format LaTeX, sinh vien van bi ket o viec viet noi dung. Neu chi lam checklist, sinh vien biet minh thieu gi nhung van phai tu viet lai. Vi vay toi dong y voi huong Workflow: checklist/rule cho phan ro rang, AI cho phan phan loai va draft, con sinh vien review de dam bao hoc that va dung that.

Nhom co luc gan bi solution-first khi nghi den Agent tu doc repo va tu tao bao cao. Toi thay rui ro lon o day la AI co the bia tinh nang, bia ket qua test, hoac viet ra noi dung nghe hop ly nhung khong co trong san pham. Vi vay boundary quan trong nhat la: khong co bang chung thi khong duoc xem la su that. AI chi duoc danh dau thieu hoac de xuat can bo sung, khong duoc lap khoang trong bang noi dung tuong tuong.

Dong gop that su cua toi la dua problem chinh vao nhom, giu mạch problem -> workflow -> metric -> boundary, va lap luan vi sao chon Workflow thay vi Agent. Neu lam lai, toi se validate som hon voi nhieu sinh vien hon, dac biet do thoi gian viet bao cao that su va dem so muc bi thieu trong cac bai nop cu. Khi do metric se manh hon, khong chi dua tren uoc luong cua nhom.

---

# 7. Tu kiem cuoi bai

- [x] Co scan 10 problems, vuot muc toi thieu 5.
- [x] Co top 3 Problem Cards voi actor, workflow, bottleneck, impact, metric.
- [x] Co draft current/future workflow cho top 3.
- [x] Co noi dung pitch va cau hoi challenge.
- [x] Co vai tro ca nhan trong hoi tu nhom.
- [x] Co bang dung AI va neu ro AI sai/hoi hot o dau.
- [x] Co reflection ca nhan ve vai tro, bai hoc, dieu se thay doi neu lam lai.
- [x] Tu giai thich duoc mạch problem -> workflow -> metric -> boundary -> do phu hop AI.

