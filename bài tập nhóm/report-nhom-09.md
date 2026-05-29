# BAI TAP NHOM - GROUP 09

## AI ho tro sinh vien xay dung bao cao du an

**Repo nop bai:** `git@github.com:dammanhdungvn/group-09-lab_02.git`  
**Nhom:** 09  
**De tai:** AI Report Assistant - giup sinh vien bien nhung gi da lam trong du an thanh bao cao hoan chinh dang Markdown/LaTeX, co lien ket voi bang chung that.

| Ho va ten | Ma sinh vien | Vai tro trong bai nhom |
|---|---|---|
| Dam Manh Dung | 2A202600741 | Tong hop problem statement, workflow, metric, decision |
| Nguyen Hoang Thanh Tung | 2A202600846 | Gop y workflow hien tai, challenge rui ro AI bia noi dung |
| Dam Manh A | 2A202600xxx | Dong gop goc nhin sinh vien viet do an/bao cao |
| Nguyen Hoang Thanh B | 2A202600xxx | Dong gop goc nhin format, bang chung, demo, kiem thu |

---

# 1. Group convergence

## 1.1. Cac candidate problems ban dau

Nhom khong chot ngay "xay AI". Moi thanh vien dua ra cac van de quan sat duoc trong hoc tap, lam bai tap lon va lam du an.

| # | Nguoi dua ra | Candidate problem | Nguoi gap van de | Diem nghen | Cam nhan nhanh |
|---:|---|---|---|---|---|
| 1 | Dam Manh Dung | Sinh vien lam xong san pham nhung mat rat lau de viet bao cao du an | Sinh vien nam cuoi/lam bai tap lon | Tong hop source code, demo, test, README thanh bao cao | Rat phu hop |
| 2 | Dam Manh Dung | Khong biet cau truc bao cao nen bat dau tu dau | Sinh vien moi lam do an | Blank page, thieu outline | Phu hop |
| 3 | Dam Manh Dung | Bao cao thieu bang chung: anh demo, ket qua test, giai thich tinh nang | Sinh vien nop bai | Khong co evidence matrix | Rat phu hop |
| 4 | Thanh Tung | README va source code khong khop voi bao cao | Sinh vien dev | Update code nhung quen update tai lieu | Phu hop |
| 5 | Thanh Tung | Viet giai thich ky thuat kho hieu voi nguoi cham | Sinh vien IT | Chuyen code thanh ngon ngu hoc thuat | Phu hop |
| 6 | Thanh Tung | Can format LaTeX/Word theo mau truong | Sinh vien | Mat nhieu thoi gian sua format | Phu hop mot phan |
| 7 | Dam Manh A | Khong biet chen hinh/chung cu vao phan nao | Sinh vien lam demo | Evidence nam rai rac | Phu hop |
| 8 | Dam Manh A | Cuoi deadline moi phat hien thieu chuong kiem thu | Sinh vien | Checklist nop bai khong ro | Phu hop |
| 9 | Dam Manh A | Bao cao nhieu nguoi viet bi lech giong van | Nhom sinh vien | Khong thong nhat style | Phu hop |
| 10 | Nguyen Hoang Thanh B | Tim tai lieu tham khao va trich dan mat thoi gian | Sinh vien | Reference management | Phu hop nhung scope lon |
| 11 | Nguyen Hoang Thanh B | Chuyen noi dung tu Markdown sang LaTeX loi format | Sinh vien | Loi bang, hinh, citation | Phu hop mot phan |
| 12 | Nguyen Hoang Thanh B | Gop feedback cua giang vien vao ban sua kho theo doi | Sinh vien | Khong co version/checklist sua loi | Scope lon hon |

## 1.2. Gom trung / cluster

| Cluster | Candidates included | Pattern chung | Ghi chu |
|---|---|---|---|
| A. Tong hop bao cao tu du an that | 1, 2, 3, 4, 5, 7, 8 | Bien nhieu nguon du lieu du an thanh bao cao co cau truc | Cluster manh nhat |
| B. Format va xuat tai lieu | 6, 11 | Chuyen noi dung sang LaTeX/Word theo mau | Nen la mot phan trong workflow, khong phai problem chinh |
| C. Quan ly tham khao | 10 | Tim va trich dan tai lieu | Can giai phap rieng, de vuot scope lab |
| D. Lam viec nhom va version | 9, 12 | Nhieu nguoi viet, nhieu feedback, kho dong bo | Co lien quan nhung scope rong |

## 1.3. Shortlist

| Candidate | Vi sao vao shortlist | Rui ro / dieu chua ro |
|---|---|---|
| AI Report Assistant cho bao cao du an | Actor ro, workflow ro, dau that, co metric thoi gian va chat luong | Can tranh AI viet thay/tao noi dung khong co bang chung |
| Tool format bao cao Markdown/LaTeX | De hieu, de lam pilot | Chi giai quyet format, khong giai quyet tong hop noi dung |
| Evidence checklist cho bao cao | Giam thieu sot bang chung | Co the chi can rule/checklist, chua chac can AI |

## 1.4. Score de dong thuan

| Candidate | Actor ro | Workflow ro | Pain co evidence | Impact do duoc | Lam trong lab | So sanh R/W/A duoc | Nhom hieu domain | Tong |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| AI Report Assistant cho bao cao du an | 5 | 5 | 4 | 5 | 5 | 5 | 5 | 34 |
| Tool format Markdown/LaTeX | 5 | 4 | 4 | 3 | 5 | 3 | 5 | 29 |
| Evidence checklist cho bao cao | 5 | 4 | 4 | 4 | 5 | 4 | 5 | 31 |

**Candidate nhom chon:** AI Report Assistant cho bao cao du an.

**Vi sao chon:** day la bai toan co actor ro, workflow dai va lap lai, co bottleneck cu the o buoc tong hop/trinh bay, co the do thoi gian hoan thien ban nhap va so muc thieu bang chung. Giai phap khong can de AI tu viet thay toan bo bao cao, ma dat AI vao mot workflow co nguoi that kiem tra.

**Vi sao khong chon cac candidate con lai:** tool format chi giai quyet phan cuoi; evidence checklist huu ich nhung neu dung mot minh thi chua giai quyet van de sinh vien khong biet noi cac bang chung thanh narrative bao cao.

---

# 2. Quick validation + research

## 2.1. Quick validation

Ghi chu trung thuc: cac so lieu duoi day la uoc luong trong pham vi lab dua tren trai nghiem cua nhom va trao doi nhanh. Neu lam san pham that, nhom can do lai bang log/report mau trong pilot.

| Nguon | So nguoi / so mau | Tin hieu xac nhan | Tin hieu phan bac | Nhom sua problem the nao |
|---|---:|---|---|---|
| Thao luan noi bo nhom | 4 | Ca 4 thanh vien deu tung gap kho khi tong hop code, anh demo, test, README vao bao cao | Muc do dau khac nhau tuy mon hoc | Thu hep actor vao sinh vien lam bai tap lon/do an co source code va demo |
| Trao doi nhanh voi ban hoc | 5 | 4/5 noi viet bao cao ton nhieu ngay cuoi; 3/5 hay thieu hinh demo/test result | 1 ban noi chi can mau bao cao ro la du | Them non-AI alternative: template + checklist |
| Review noi dung slide de tai | 10 slide | Slide xac nhan cac pain: thong tin rai rac, kho trinh bay, de thieu bang chung, ap luc deadline | Chua co so lieu dinh luong that | Dat metric pilot de do: thoi gian draft, so muc thieu, so loi khong khop |

**Insight sau validation:**

```text
Pain khong nam o viec "AI viet ho bao cao".
Pain nam o viec sinh vien phai tong hop nhieu bang chung rai rac va bien chung thanh mot cau truc bao cao nhat quan.
```

## 2.2. Research giai phap da co

| Nguon / tool / case | Link | Ho giai quyet phan nao? | Diem manh | Khoang trong / rui ro | Bai hoc cho nhom |
|---|---|---|---|---|---|
| Overleaf | [overleaf.com/about/features-overview](https://www.overleaf.com/about/features-overview) | Viet, bien dich va cong tac tren tai lieu LaTeX | Tot cho format, collaboration, xuat PDF | Khong tu hieu source code/demo/test cua du an sinh vien | Nen xuat LaTeX/Markdown, nhung khong coi format la toan bo solution |
| Gemini in Drive | [support.google.com/drive/answer/15141241](https://support.google.com/drive/answer/15141241) | Tom tat va lay insight tu file/folder | Tot khi tai lieu nam trong Drive | Phu thuoc file duoc cung cap; can kiem nguon | AI co the ho tro doc/tom tat tai lieu, nhung phai co evidence link |
| GitHub Copilot | [docs.github.com/copilot](https://docs.github.com/en/copilot/overview-of-github-copilot/about-github-copilot) | Ho tro hieu/viet code va giai thich context code | Tot cho code-level explanation | Khong tu dong bien toan bo du an thanh bao cao hoc thuat | Co the dung nhu input giai thich module, khong thay report workflow |
| Grammarly AI Writing Assistant | [grammarly.com/ai-writing-assistant](https://www.grammarly.com/ai-writing-assistant) | Ho tro viet va sua ngon ngu | Tot cho dien dat, tone, grammar | Co the lam noi dung hay nhung khong dam bao dung voi du an | AI writing chi nen la buoc polish/draft, khong phai nguon su that |

**Research takeaway:**

```text
Nen chon Workflow: gom tai lieu du an -> phan loai -> de xuat outline -> tao evidence matrix -> draft tung phan -> sinh vien review -> xuat Markdown/LaTeX.
Khong nen chon Agent tu dong nop bao cao vi rui ro bia noi dung, sai bang chung va vuot boundary hoc tap.
```

---

# 3. Workflow before/after

## 3.1. Current workflow

```text
CURRENT STATE - 8 buoc, uoc luong 24-40 gio cho mot bao cao du an

[1 Hoan thanh source code/demo]
-> [2 Tim lai README, screenshot, test result, ghi chu: 3-6h]
-> [3 Doc lai yeu cau giang vien/mau bao cao: 1-2h]
-> [4 Tu lap outline bao cao: 2-4h]
-> [5 Viet cac chuong: mo dau, phan tich, thiet ke, cai dat, kiem thu: 10-18h] <-- bottleneck
-> [6 Chen hinh, bang, ket qua test, citation: 4-6h]
-> [7 Sua format Markdown/Word/LaTeX: 2-4h]
-> [8 Review lan cuoi va nop: 2-4h]
```

| Buoc | Actor | Input | Output | Thoi gian/tan suat | Ghi chu |
|---:|---|---|---|---|---|
| 1 | Sinh vien/nhom | Source code, demo | San pham co the chay | Theo tien do du an | Chua thanh bao cao |
| 2 | Sinh vien | Code, README, anh demo, test | Tap thong tin thô | 3-6 gio | Thong tin rai rac |
| 3 | Sinh vien | Rubric, mau bao cao | Danh sach yeu cau | 1-2 gio | De bo sot field |
| 4 | Sinh vien | Yeu cau + thong tin thô | Outline | 2-4 gio | Blank page |
| 5 | Sinh vien | Outline + bang chung | Ban nhap noi dung | 10-18 gio | Bottleneck chinh |
| 6 | Sinh vien | Anh/demo/test/reference | Bang chung trong bao cao | 4-6 gio | De chen sai/doi cho |
| 7 | Sinh vien | Ban nhap | File dung format | 2-4 gio | Nhieu loi nho |
| 8 | Sinh vien/nhom | File bao cao | Ban nop cuoi | 2-4 gio | Review thu cong |

**Bottleneck chinh:** buoc 5 va 6. Sinh vien biet minh da lam gi, nhung kho bien code/demo/test thanh van ban hoc thuat co cau truc va co bang chung.

## 3.2. Future workflow

```text
FUTURE STATE - 7 buoc, uoc luong 9-16 gio cho ban nhap dau tien

[1 Sinh vien upload/goi tai lieu: source, README, screenshot, test, rubric]
-> [2 Rule kiem tra file bat buoc va dat ten]
-> [3 AI phan loai tai lieu + tao evidence matrix]
-> [4 AI de xuat outline theo rubric]
-> [5 AI draft tung phan dua tren bang chung da co] <-- AI intervention point
-> [6 Sinh vien review, sua, bo sung, xac nhan su that] <-- human boundary
-> [7 Export Markdown/LaTeX/PDF va checklist nop bai]

Fallback:
Neu AI khong tim du bang chung -> danh dau "Can bo sung", khong tu bia.
Neu draft sai -> sinh vien loai bo doan sai va tu sua dua tren evidence.
```

| Metric | Truoc | Sau ky vong | Ghi chu |
|---|---:|---:|---|
| So buoc chinh | 8 | 7 | Khong giam nhieu buoc, nhung giam effort o buoc tong hop/viet |
| Thoi gian co ban nhap dau tien | 24-40 gio | 9-16 gio | Metric pilot can do bang time log |
| So muc bat buoc bi thieu | 3-5 muc/bao cao | <= 1 muc/bao cao | Do bang checklist theo rubric |
| So claim khong co bang chung duoc dua vao final | Chua kiem soat | 0 | Claim khong co evidence phai bi flag |
| Bottleneck moi | Review thu cong | Review va xac nhan su that | Chap nhan duoc vi day la boundary hoc tap |
| Risk moi | Khong co hallucination AI | AI co the draft sai | Giam bang evidence matrix va human review |

---

# 4. Problem Statement

## 4.1. Problem Statement v0

| Field | Noi dung |
|---|---|
| **Actor** | Sinh vien lam bai tap lon, do an mon hoc, bao cao thuc tap hoac do an tot nghiep. |
| **Workflow** | Sau khi lam xong san pham, sinh vien tim lai source code, README, anh demo, ket qua test, tai lieu tham khao, roi viet thanh bao cao dai theo mau giang vien. |
| **Bottleneck** | Tong hop va trinh bay lai toan bo du an thanh bao cao co cau truc, dung voi nhung gi da lam, co bang chung kem theo. |
| **Impact** | Mat 24-40 gio de co ban nhap dau tien; de thieu bang chung; co nguy co viet khong khop voi san pham thuc te; ap luc cao sat deadline. |
| **Success Metric** | Giam thoi gian co ban nhap dau tien xuong 9-16 gio; so muc thieu trong checklist <= 1; claim khong co bang chung trong final = 0. |
| **Boundary** | Khong de AI viet thay va nop thay; khong cho AI bia tinh nang/ket qua; khong thay sinh vien kiem chung noi dung; chi draft dua tren tai lieu duoc cung cap. |

## 4.2. Do phu hop AI

| Cau hoi | Danh gia cua nhom |
|---|---|
| Output co nhieu cach viet dung khong? | Co. Bao cao co tinh ngon ngu va cau truc hoc thuat. |
| Co can tong hop nhieu nguon khong? | Co. Source code, README, demo, test, rubric, references. |
| Co can AI tu quyet dinh hanh dong tiep theo khong? | Chua can trong pilot. Workflow co cac buoc ro. |
| Neu AI sai, hau qua co chap nhan duoc khong? | Chap nhan duoc neu AI chi draft va sinh vien review truoc khi nop. |

**O phu hop:** do mo ho cao, do phuc tap cao vua phai. Chon **Workflow co AI ho tro**, chua chon Agent tu dong.

---

# 5. Rule / Workflow / Agent

| Muc | Phuong an cho bai toan nhom | Khi nao du | Rui ro | Chon? |
|---|---|---|---|---|
| **No AI / Process fix** | Mau bao cao + checklist + folder template | Du neu sinh vien chi thieu format | Khong giai quyet viec bien du lieu rai rac thanh narrative | Khong chon lam toan bo |
| **Rule** | Kiem tra file bat buoc, ten file, so chuong, muc nao thieu bang chung | Du cho checklist va validation co quy tac ro | Khong giup viet/giai thich phan ky thuat | Dung mot phan |
| **Workflow** | Rule check input -> AI phan loai -> AI tao outline/evidence matrix -> AI draft -> sinh vien review -> export | Phu hop vi cac buoc ro, AI chi ho tro cac buoc ngon ngu/tong hop | Draft sai, thieu context, can human review | **Chon** |
| **Agent** | Agent tu doc repo, tu hoi them, tu viet, tu sua format, tu nop | Chi phu hop khi co moi truong du quyen, log tot, co guardrail manh | Qua rong, de hallucinate, rui ro hoc thuat | Chua chon |

**Muc chon:** Workflow.

**Vi sao chon:** workflow cua bai toan co duong di tuyen tinh va co nhieu buoc co the kiem soat. Rule phu hop cho checklist/file validation. AI phu hop cho phan phan loai, outline, draft narrative va phat hien missing evidence. Sinh vien van la nguoi xac nhan dung sai.

**Vi sao khong chon muc don gian hon:** Rule/checklist giam thieu sot nhung khong giai quyet bottleneck lon nhat la dien dat va ket noi bang chung thanh noi dung bao cao.

**Vi sao khong chon Agent:** pilot chua can AI tu lap ke hoach va tu hanh dong. Neu cho Agent tu doc repo/viet/nop, rui ro quyen truy cap, sai noi dung va vi pham nguyen tac hoc tap cao hon loi ich.

---

# 6. Problem Statement v1

| Field | Noi dung |
|---|---|
| **Actor** | Sinh vien/nhom sinh vien da hoan thanh phan lon san pham du an va can nop bao cao theo rubric cua giang vien. |
| **Workflow** | Gom source code, README, screenshot demo, ket qua test, rubric, reference -> lap outline -> viet cac chuong -> gan bang chung -> format Markdown/LaTeX -> review va nop. |
| **Bottleneck** | Bien nhieu thong tin rai rac thanh ban nhap bao cao co cau truc, khop voi san pham that va co bang chung cho tung claim. |
| **Impact** | Uoc luong 24-40 gio de co ban nhap dau tien; de thieu 3-5 muc/bang chung; co nguy co viet noi dung khong ton tai trong du an. |
| **Success Metric** | Trong pilot 1 bao cao: thoi gian co ban nhap dau tien giam xuong 9-16 gio; checklist thieu <= 1 muc; 100% claim quan trong co evidence hoac bi flag "can bo sung". |
| **Boundary** | AI khong tu nop, khong tu bia so lieu/tinh nang/test, khong thay sinh vien chiu trach nhiem; neu khong co evidence thi phai danh dau thieu. |
| **AI intervention point** | Sau khi sinh vien cung cap goi tai lieu du an, truoc buoc viet ban nhap bao cao. AI ho tro phan loai, tao outline, evidence matrix va draft tung phan. |
| **Muc chon** | Workflow: rule/checklist + AI draft co evidence + human review. |
| **Rui ro & nguoi that kiem tra** | Rui ro hallucination, bo sot module, dien dat qua chung chung. Sinh vien/nhom phai review tung claim, doi chieu voi repo/demo/test truoc khi nop. |

---

# 7. Final decision

| Cau hoi | Yes / Not Yet / No | Ghi chu |
|---|---|---|
| Actor va workflow da ro chua? | Yes | Actor la sinh vien lam bao cao du an; workflow da ve duoc before/after. |
| Baseline va success metric da do duoc chua? | Not Yet | Da co uoc luong, can pilot time log de xac nhan. |
| Co data/input du dung chua? | Yes cho pilot nho | Can mot repo/project mau co README, screenshot, test result, rubric. |
| Neu AI sai, hau qua co chap nhan duoc khong? | Yes neu co review | AI chi draft; sinh vien approve. |
| Co nguoi review/owner van hanh khong? | Yes | Sinh vien/nhom la owner. |
| Co cach non-AI don gian hon khong? | Co mot phan | Template/checklist nen dung kem, nhung khong du giai quyet narrative. |

**Decision:** Go voi scope nho.

**Ly do:** problem ro, workflow ro, co metric pilot, co boundary hoc thuat va khong can Agent ngay. RUI ro lon nhat la AI bia noi dung da duoc giam bang nguyen tac: khong co bang chung thi khong duoc xem la su that.

**Pilot nho nhat:**

1. Chon 1 du an sinh vien da co source code, README, 5-7 screenshot, test result va rubric.
2. Dung workflow ban thu cong: sinh vien upload/copy input vao template.
3. AI tao outline, evidence matrix va ban draft tung chuong.
4. Sinh vien do: thoi gian co draft, so muc thieu, so claim sai/khong co bang chung, muc do hai long.
5. Neu AI draft sai qua 30% claim quan trong hoac sinh vien phai viet lai gan nhu toan bo, ha scope ve template + checklist + evidence matrix.

---

# 8. Checklist tu kiem

- [x] Nhom co nhat ky hoi tu tu nhieu candidate ve 1 candidate problem.
- [x] Co validation/research va ghi ro gia dinh can kiem tiep.
- [x] Co workflow truoc/sau, actor, input, output, thoi gian va bottleneck.
- [x] Co Problem Statement v0/v1 voi metric va boundary.
- [x] Co so sanh No AI / Rule / Workflow / Agent.
- [x] Co decision Go / Not Yet / No-Go va pilot nho nhat.
- [x] Co nguyen tac human review: AI ho tro, sinh vien chiu trach nhiem.

