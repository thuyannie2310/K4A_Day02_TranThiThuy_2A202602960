# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Trần Thị Thuý | 2A202602960 |                                                       |
| 2   | Nguyễn Anh Tú |             |                                                       |
| 3   |           |             |                                                               |
| 4   |           |             |                                                               |

**Candidate problem nhóm chọn (1 câu):**


---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Trần Thị Thuý | Bảng tồn kho hằng ngày chỉ note trạng thái (nợ khách nào, giao ngày nào, lô nào sắp về) nên là nguyên liệu chứ chưa phải câu trả lời — sale vẫn phải tự lọc, tự check xem có mượn hàng của khách giao sau để giao cho khách cần trước được không | 2 kế toán bán hàng dựng bảng; 30 nhân viên kinh doanh dùng bảng | Hai tầng. Tầng 1: bước 2 copy/vlookup giữa 3 file MISA, 15 phút/ngày, thao tác giống hệt nhau mỗi ngày. Tầng 2: bước 6-7 sale tự check, không chắc thì hỏi kế toán — 30 người thay phiên hỏi 1 bạn nên thời gian bạn ấy bị cắt vụn cả ngày (chưa đo). Tổng dựng bảng 30 phút/ngày; hậu quả 2-3 tháng/lần bán trúng hàng đã có chủ | |
| 2 | Trần Thị Thuý | Chốt doanh số cho sale phải áp hệ số theo chương trình riêng của từng tháng, kiểm hai mốc ghi nhận khác nhau (doanh số ký / doanh số giao), rồi đối chiếu với bảng do sale tự lập | 1 kế toán bán hàng làm khâu chốt; 30 nhân viên kinh doanh bị ảnh hưởng thu nhập | Bước 3-4: áp hệ số rồi truy từng dòng lệch giữa hai bảng, mất 5 ngày/tháng của 1 người ≈ 40 giờ/tháng | |
| 3 | Trần Thị Thuý | Mỗi lần khách đổi mẫu hoặc số lượng, đơn phải chạy lại toàn bộ vòng mở khoá – sale sửa – đề nghị lại – kế toán duyệt – gửi email ghi log | Kế toán bán hàng và nhân viên kinh doanh; khách hàng đã ký hợp đồng chịu hậu quả cuối | Bước 5 chờ kế toán duyệt: 20 phút/lần (gồm cả chờ) × 30 đơn trên 100 đơn/tháng ≈ 10 giờ/tháng; đã có ca quên duyệt dẫn tới thiếu hàng đúng ngày hẹn giao khách | |
| 4 | Nguyễn Anh Tú | Debug lỗi giao tiếp giữa các service không có log tập trung | Dev duy nhất vừa code vừa vận hành các service | Bước 2-3: dò log rải rác + đoán nguyên nhân thủ công, trung bình 45 phút/lần | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A | | | |
| B | | | |
| C | | | |
| D (nếu có) | | | |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| | | |
| | | |
| | | |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

> **Bản nháp tự chấm của Thuý cho 3 candidate của mình — chưa phải điểm đồng thuận.** Nhóm chấm lại khi họp, kể cả chấm thấp hơn. Mục đích của bảng này là ép nói rõ vì sao cho 5 và vì sao cho 2.

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #1 Bảng tồn kho không trả lời được "bán được không" | 5 | 5 | 3 | 4 | 5 | 5 | 2 | **29** |
| #2 Chốt doanh số tháng + đối chiếu lệch số | 4 | 4 | 4 | 5 | 2 | 4 | 2 | **25** |
| #3 Vòng đổi thông tin đơn hàng | 4 | 5 | 3 | 4 | 4 | 3 | 2 | **25** |
| | | | | | | | | |

**Giải thích các điểm cực đoan (tự chấm):**

- **#1 được 5 ở "Workflow rõ"**: đã bấm giờ tách được từng bước — 5 phút tải file, 15 phút copy/vlookup, ~10 phút note trạng thái. Không phải ước lượng.
- **#1 được 5 ở "So sánh R/W/A được"**: bài này có hai tầng nghẽn khác bản chất, tầng 1 là Rule thuần còn tầng 2 là Workflow, nên so sánh được ngay trên cùng một bài.
- **#1 chỉ được 3 ở "Pain có evidence"**: phần impact lớn nhất — 30 sale thay phiên hỏi 1 kế toán — hiện chưa có số nào. Đây là điểm yếu thật, phải đo ở Phase 4.
- **#2 được 5 ở "Impact đo được"** nhưng **chỉ 2 ở "Làm trong lab"**: 40 giờ/tháng là con số lớn nhất cả bảng, nhưng bài gồm quy tắc hệ số theo tháng, hai mốc ghi nhận và xử lý đơn huỷ truy ngược — quá rộng cho 4 tiếng.
- **#3 chỉ được 3 ở "So sánh R/W/A được"**: gần như chắc chắn là No AI + process fix, nên không có nhiều để so giữa ba mức.
- **Cả ba đều chỉ được 2 ở "Nhóm hiểu domain"**: đây là điểm yếu chung. Chỉ Thuý ở trong ngành bán lẻ nội thất và hiểu mô hình đặt trước – lấy sau; các thành viên còn lại phải tin vào mô tả của một người. Nhóm cần cân nhắc điểm này khi chọn.

**Candidate nhóm chọn (1 bài duy nhất):**

```text

```

**Vì sao chọn (4-5 câu):**

```text

```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text

```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text

```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview — kế toán bán hàng | 2 | **Số lượt bị ngắt**: "khoảng 3-5 nhân sự hỏi, rải rác trong ngày không cố định giờ giấc", mỗi lượt "mất tầm 5-10 phút" → ~15-50 phút/ngày, trung bình ~30 phút. **Buộc phải dừng việc**: "dừng lại để phản hồi kinh doanh vì cần ưu tiên để tư vấn bán hàng". **Câu hỏi lặp nhiều nhất**: "mã sản phẩm này, có giao được không". **Về 30 phút dựng bảng**: "cơ bản là không phải suy nghĩ mà toàn bộ là máy móc trích xuất và sửa". **Khi được hỏi nếu giải quyết được thì sao**: "các bạn tự tra và đảm bảo câu trả lời đúng, tự động lấy file từ phần mềm về được thì hầu như giải phóng toàn bộ sức cho phần này rồi" | Số lượt hỏi là **3-5 lần/ngày**, thấp hơn hẳn hình dung ban đầu của nhóm là "30 sale thay phiên nhau hỏi cả ngày" | Bỏ cách nói "30 người thay phiên hỏi", thay bằng số thật 3-5 lượt/ngày × 5-10 phút. Đồng thời sửa mô tả bước dựng bảng: **toàn bộ 30 phút là cơ học**, không phải 20 phút như nhóm ghi lúc đầu — phần phán đoán không nằm ở kế toán mà nằm ở sale |
| Interview — nhân viên kinh doanh | 2 | **Quy trình thật khi cần bán**: "check trên file tồn kho kế toán gửi, nếu tồn có thì bán, nếu tồn có nhưng nợ khách thì hỏi kế toán xem khách nợ bao giờ lấy, có lấy trước được không". **Nguyên nhân gốc phải hỏi**: "em tự tra trên file, nhưng nếu gặp 1 vài trường hợp thì phải hỏi kế toán **vì em không có dữ liệu đó**". **Lỗi do định dạng bảng**: "thỉnh thoảng hơi sai do **dò sai dòng**". **Đã hứa sai với khách**: "có rồi, **vì nhìn sai tồn kho**". **Yêu cầu bổ sung**: "cần biết đang ở **kho nào**, bán được không" | Sale nói **đa số tự tra được và thường chắc chắn với kết quả**, chỉ "một vài trường hợp" mới phải hỏi. Tức là bảng không khó đọc với mọi tình huống như nhóm giả định | Thu hẹp problem lại cho đúng: pain **không** nằm ở việc bảng khó đọc nói chung, mà nằm gọn ở **đúng một tình huống** — tồn có nhưng đang nợ khách. Và nguyên nhân không phải giao diện xấu, mà là **thiếu hẳn một trường dữ liệu**: ngày khách đang nợ sẽ đến lấy hàng, thứ mà sale không có trong file |
| Log / ticket / review (nếu có) | — | Chưa có. Đang triển khai phiếu đếm 5 ngày để kế toán gạch đầu dòng mỗi lần bị hỏi, nhằm thay số ước lượng 3-5 lượt/ngày bằng số đếm thật | — | Nếu số đếm thật lệch nhiều so với ước lượng, nhóm sẽ chỉnh lại baseline trước khi chốt metric |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain thật hẹp hơn và rõ hơn nhiều so với giả định ban đầu của nhóm. Sale đa số tự tra được
và thường chắc chắn với kết quả; họ chỉ tắc ở đúng một tình huống — mã có tồn nhưng đang nợ
khách. Lúc đó họ thiếu đúng MỘT trường dữ liệu: khách đang nợ sẽ đến lấy hàng ngày nào.
Không có trường đó thì không thể tự trả lời "có lấy trước được không", nên buộc phải hỏi
kế toán. Đây là nguyên nhân gốc, không phải chuyện bảng khó nhìn.

Hai số đo thu được: kế toán bị ngắt 3-5 lượt/ngày, mỗi lượt 5-10 phút (~30 phút/ngày), và
phải dừng việc ngay vì ưu tiên hỗ trợ bán hàng. Cộng với 30 phút dựng bảng cuối ngày mà
chính bạn ấy mô tả là "toàn bộ là máy móc trích xuất và sửa", tổng chi phí rơi vào khoảng
1 giờ/ngày của một người ≈ 26 giờ/tháng.

Validation cũng bác bỏ hai chỗ nhóm nói quá: không phải "30 người thay phiên hỏi cả ngày"
mà là 3-5 lượt/ngày; và không phải 20 trong 30 phút là cơ học, mà là cả 30 phút.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

> Research làm theo hướng candidate #1 (bảng tồn kho). Nếu nhóm chốt bài khác thì phần này làm lại.

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Available-to-Promise (ATP)** — pattern chuẩn của ngành chuỗi cung ứng | [mecalux.com](https://www.mecalux.com/blog/available-to-promise-atp) · [redstagfulfillment.com](https://redstagfulfillment.com/available-to-promise/) | Đúng bước 6-7 trong workflow hiện tại: trả lời câu "bán được bao nhiêu, và khi nào giao được" | Có công thức rõ ràng: **ATP = Tồn thực tế + Hàng sắp về − Hàng đã cam kết − Đơn đang nợ**. Đây chính xác là phép tính mà 30 sale đang làm trong đầu mỗi ngày | **Công thức trừ thẳng này SAI với mô hình của công ty.** Khách đang nợ có thể còn 1-2 năm nữa mới lấy hàng, trong khi có lô về tháng 9, 10, 12. Nếu trừ thẳng toàn bộ phần đã cam kết thì hệ thống sẽ báo "hết hàng" cho một mã thực tế vẫn giao được — tức là tự tay chặn cơ hội bán. Phải dùng ATP theo mốc thời gian | Bài toán này đã có tên và có công thức chuẩn — không cần phát minh lại. Việc của nhóm là viết quy tắc ra thành công thức và áp theo từng mốc ngày, không phải nghĩ ra logic mới |
| **Odoo Inventory — Forecasted Report** | [odoo.com/documentation](https://www.odoo.com/documentation/18.0/applications/inventory_and_mrp/inventory/warehouses_storage/reporting/forecast.html) | Bước 3-5: hiển thị sẵn *Forecasted = On-hand + Incoming − Outgoing*, kèm bảng replenishment cho biết lô hàng sắp về có kịp đáp ứng một đơn cụ thể hay không | Đúng thứ đang thiếu, và đã là tính năng có sẵn trong một ERP thương mại. Mỗi lần đổi ngày dự kiến về thì báo cáo tự cập nhật lại | Đổi ERP là một dự án lớn. Công ty đang chạy MISA, chi phí và rủi ro chuyển đổi vượt xa mức tiết kiệm ~13 giờ/tháng | Chứng minh đây là **tính năng tiêu chuẩn của ERP**, không phải nhu cầu lạ. Vì vậy việc đầu tiên phải làm là hỏi MISA, chứ không phải tự build hay đổi phần mềm |
| **MISA AMIS — bộ báo cáo kho đang dùng** | [helpamis.misa.vn](https://helpamis.misa.vn/amis-kho-hang/kb/bao-cao-kho/) · [helpact.misa.vn](https://helpact.misa.vn/kb/bao-cao-tong-hop-ton-kho/) | Bước 1: cung cấp dữ liệu nhập – xuất – tồn theo kho, nhóm VTHH, số lô, hạn sử dụng | Dữ liệu đã có sẵn và công ty đang khai thác đúng nguồn này. Không phải bài toán thiếu dữ liệu | **Đã kiểm chứng trực tiếp trong hệ thống: MISA không có tính năng này.** Bộ báo cáo là góc nhìn **kế toán kho** (nhập – xuất – tồn tại một thời điểm), không phải góc nhìn **bán hàng** (bán được bao nhiêu, giao được khi nào) | Khoảng trống đã được xác nhận, không còn là giả định: MISA cho **nguyên liệu**, không cho **câu trả lời**. Vì vậy hướng đi không phải cấu hình lại MISA, mà là dựng một lớp tính ATP đặt trên dữ liệu MISA xuất ra |

| **Cumulative ATP with look-ahead** — biến thể ATP theo mốc thời gian | [docs.infor.com (M3)](https://docs.infor.com/m3udi/16.x/en-us/m3beud/scplanhs/cts090.html) · [Microsoft Learn — Dynamics 365](https://learn.microsoft.com/en-us/dynamics365/supply-chain/sales-marketing/delivery-dates-available-promise-calculations) | Đúng bước 6-7: quyết định có mượn hàng của khách đang nợ để giao cho khách cần trước hay không | Đây chính là tên chuẩn của quy tắc mà 30 sale đang làm trong đầu. Cơ chế **look-ahead** là phần quan trọng nhất: chỉ cho mượn khi lượng hàng về tích luỹ trước ngày hẹn của khách đang nợ đủ bù lại phần đã mượn. Nó vừa mở ra cơ hội bán, vừa tự chặn việc bán quá tay | Công thức giả định lô hàng về **đúng ngày dự kiến**. Thực tế của công ty là ~10% đơn bị sai hẹn, một phần do đối tác giao chậm. Nếu áp máy móc thì sẽ mượn hàng dựa trên một lô không về kịp, và biến một khách thất hứa thành hai | Quy tắc viết ra phải có 3 tham số do **con người** quyết, không phải công thức tự quyết: biên an toàn bao nhiêu ngày trước hạn giao, đơn nào bị cấm mượn (khách VIP, đã cam kết cứng), và ai được duyệt ngoại lệ |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Bài toán của nhóm có tên chuẩn trong ngành là Available-to-Promise, nhưng dạng ATP cơ bản
KHÔNG dùng được. Công thức cơ bản trừ thẳng toàn bộ phần đã cam kết, trong khi khách đang
nợ của công ty có thể còn 1-2 năm nữa mới lấy hàng và trong khoảng đó đã có lô về tháng 9,
tháng 10, tháng 12. Áp công thức cơ bản thì hệ thống sẽ báo hết hàng cho một mã thực tế
vẫn giao được — tự tay chặn cơ hội bán, đúng cái mà công ty đang tránh bằng cách cho sale
tự suy trong đầu.

Dạng đúng là Cumulative ATP with look-ahead: không hỏi "còn bao nhiêu", mà hỏi "nếu mượn
phần hàng đang nợ khách A thì từ nay đến ngày hẹn của A có đủ hàng về để bù lại không".
Đây là thứ phải build, vì đã kiểm chứng trực tiếp là MISA không có tính năng này.

KHÔNG build: hệ thống tồn kho mới, hoặc đổi ERP. Odoo có sẵn góc nhìn này nhưng chi phí
chuyển đổi vượt xa mức tiết kiệm; MISA vẫn là nguồn sự thật của công ty.

NÊN build: một lớp tính ATP mỏng đặt trên đúng dữ liệu MISA đang xuất ra, trả về số cuối
theo từng mốc giao, cộng một chỗ duy nhất để sale tra.

Giả định chưa chắc — phải kiểm trước khi chốt: công thức look-ahead giả định lô hàng về
đúng ngày dự kiến, nhưng thực tế ~10% đơn sai hẹn và một phần do đối tác giao chậm. Nhóm
chưa biết trong 10% đó bao nhiêu là do đối tác. Nếu tỷ lệ trễ cao thì biên an toàn phải
rộng, và phần "mượn được" sẽ hẹp hơn nhiều so với lý thuyết.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
[1 ...: __' - ai làm] → [2 ...: __'] → [3 ...: __'] → [4 ... bottleneck: __'] → ...
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |

**Bottleneck chính (2-3 câu):**

```text

```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 ...: __' - máy] → [2 AI ...: __'] → [3 ... review: __' - boundary] → [4 ... gửi]

Fallback: ...
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | | | |
| Số bước | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Risk mới | | | |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | |
| **Workflow** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** | |
| **Boundary** | |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ:
- Tôi sửa gì:

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [ ] Cao (nhiều cách trả lời vẫn OK) — Vì sao:
- Độ phức tạp: [ ] Thấp (1-2 bước) / [ ] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao:

**Bài toán nhóm nằm ở ô nào:**

```text

```

**Vì sao (2-3 câu):**

```text

```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không?
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh?
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không?
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?
5. Có hạ được từ Agent → Workflow → Rule không?

**Mức chọn:**

```text
[Rule / Workflow / Agent]
```

**Vì sao chọn (3-4 câu):**

```text

```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text

```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | |
| **Workflow** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** | |
| **Boundary** (làm / không làm) | |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | | |
| Baseline + metric đo được chưa? | | |
| Data/input đủ dùng chưa? | | |
| AI sai, hậu quả chấp nhận được không? | | |
| Có người review/owner không? | | |
| Có cách non-AI đơn giản hơn không? | | |

**Decision:**

```text
[Go / Not Yet / No-Go]
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text

```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text

```

**Nếu Not Yet — cần validate gì trước:**

```text

```

**Nếu No-Go — làm gì thay AI:**

```text

```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text

```

---

### Self-check nộp phần 02 (nhóm)
- [ ] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [ ] Có validation (quote thật) + research (link kiểm được)
- [ ] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [ ] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [ ] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
