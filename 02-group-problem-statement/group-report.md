# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Phan Duy Bảo | 2A202602767 | _(chờ nhóm phân vai)_ |
| 2   | Nguyễn Anh Tú | 2A202602881 | _(chờ nhóm phân vai)_ |
| 3   | Trần Thị Thuý | 2A202602960 | _(chờ nhóm phân vai)_ |
| 4   | Nguỵ Khắc Phi Long | 2A202602532 | _(chờ nhóm phân vai)_ |
| 5   | Đoàn Duy Bách | 2A202602515 | _(chờ nhóm phân vai)_ |

> **Trạng thái:** nhóm đủ 5 thành viên, đã gom đủ **15 candidate** ở mục 3.1, và **đã chốt candidate là bài #1 của Phan Duy Bảo**. Phase 5 và Phase 6 do Phan Duy Bảo soạn trên Problem Card #1 của bạn ấy; mục 3.2–3.4 và Phase 4 được bổ sung sau.
>
> **Lưu ý cần xác nhận với giảng viên:** worksheet ghi nhóm gồm **3-4 người**, nhóm này đang có **5 người**. Cần hỏi lại xem để 5 người hay tách bớt, vì nó ảnh hưởng tới số candidate (5 người × 3 bài = 15, trong khi bảng 3.1 và 3.2 của template viết theo mức 9-12).
>
> **⚠ Một mâu thuẫn nhóm cần chốt trước khi nộp:** tài liệu `Báo cáo giải pháp AI — Điều phối sự cố bảo trì` (cũng do Phan Duy Bảo viết) đánh giá độ mơ hồ là **CAO** và chọn mức **Workflow có AI**, trong khi mục 6.0 của file này đánh giá độ mơ hồ **THẤP** và chọn **Rule / No AI**. Hai bản đang xét hai thứ khác nhau — bản kia xét việc *đọc tin nhắn tự do của khách* (mơ hồ cao), bản này xét *nội dung cần ghi lại* là phòng nào và hỏng gì (mơ hồ thấp). Cả hai đều có lý, nhưng phải thống nhất một kết luận, nếu không người chấm sẽ đọc thành nhóm tự mâu thuẫn. Đề xuất cách hoà: giữ kết luận **Rule / No AI** của file này làm quyết định chính thức, và chuyển tài liệu kia thành phụ lục "phương án nếu sau này Rule không đủ".

**Candidate problem nhóm chọn (1 câu):**

Khách báo hỏng qua 3 kênh rời rạc (Zalo riêng, điện thoại, nhóm Zalo chung) và mọi yêu cầu đều dồn về một mình quản lý để phân việc cho 2 thợ, không có chỗ ghi nhận tập trung, nên thỉnh thoảng có vụ bị trôi và khách phải nhắc lần 2.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Phan Duy Bảo | Điều phối sự cố bảo trì: khách báo hỏng qua 3 kênh rời rạc, dồn hết về tôi phân việc cho 2 thợ | Khách thuê, tôi (quản lý), 2 thợ kỹ thuật | Khâu NHẬN yêu cầu: 3 kênh đổ về 1 người, không có chỗ ghi nhận tập trung nên vụ bị trôi. 5-15 vụ/tháng, 15-30 phút/vụ = 1,5-7,5 tiếng/tháng | _(chờ nhóm)_ |
| 2 | Phan Duy Bảo | Chốt điện nước cuối tháng: tự chụp ảnh công tơ 30-60 phòng, nhập tay Excel, nhắn riêng hóa đơn từng phòng | Tôi (quản lý), toàn bộ khách thuê | Bước nhắn riêng 30-60 phòng: thao tác lặp cơ học. 1-3 tiếng/tháng x 12 lần/năm | _(chờ nhóm)_ |
| 3 | Phan Duy Bảo | Sale gặp câu hỏi chưa nắm phải quay lại hỏi tôi mới trả lời được khách | Bạn sale, tôi, khách đang cân nhắc thuê | Hỏi nhiều nhất là mức giảm giá được phép chốt. Sale không được tự quyết bất kỳ mức nào → gốc là THIẾU PHÂN QUYỀN, không phải thiếu thông tin. 2-5 lần/tuần | _(chờ nhóm)_ |
| 4 | Nguyễn Anh Tú | Debug lỗi giao tiếp giữa các service khi không có log tập trung | Tôi — dev duy nhất vừa code vừa vận hành các service | Bước 2-3 — dò log rải rác ở nhiều nơi rồi đoán nguyên nhân thủ công: **~45 phút/lần**. _Thiếu: mấy lần/tuần, nên chưa quy ra được tổng giờ/tháng để so với các bài khác_ | _(chờ nhóm)_ |
| 5 | Nguyễn Anh Tú | Viết README / docs API bị trì hoãn tới lúc đã quên mất chi tiết | Tôi (chủ repo) và người đọc lại repo sau này | Quy trình **không có bước "viết docs ngay" sau khi code xong**, nên docs bị bỏ qua liên tục. _**Thiếu toàn bộ số đo** — cần: mấy repo đang thiếu docs, mỗi lần phải đọc lại code không docs mất bao lâu, bao nhiêu người đọc lại repo_ | _(chờ nhóm)_ |
| 6 | Nguyễn Anh Tú | Thiếu diagram kiến trúc khi demo nên bị hỏi lại nhiều lần | Tôi (người demo) và bạn/mentor (người nghe demo) | Không chuẩn bị diagram trước buổi demo, phải giải thích lại giữa chừng làm gián đoạn mạch demo. _**Thiếu toàn bộ số đo** — cần: mấy buổi demo/tháng, mỗi buổi bị hỏi lại mấy lần, mất thêm bao nhiêu phút_ | _(chờ nhóm)_ |
| 7 | Trần Thị Thuý | Bảng tồn kho hằng ngày chỉ note trạng thái (nợ khách nào, giao ngày nào, lô nào sắp về) nên mới là **nguyên liệu chứ chưa phải câu trả lời**: sale vẫn phải tự lọc, tự check xem có mượn được hàng của khách giao sau để giao cho khách cần trước không | 2 kế toán bán hàng dựng bảng; 30 nhân viên kinh doanh dùng bảng | **Hai tầng.** Tầng 1 — bước 2: copy/vlookup giữa 3 file MISA, 15 phút/ngày, thao tác giống hệt nhau mỗi ngày. Tầng 2 — bước 6-7: sale tự check, không chắc thì hỏi kế toán; **đã phỏng vấn: 3-5 lượt/ngày, mỗi lượt 5-10 phút**. Tổng dựng bảng 30 phút/ngày. Hậu quả: 2-3 tháng/lần bán trúng hàng đã có chủ | _(chờ nhóm)_ |
| 8 | Trần Thị Thuý | Chốt doanh số tháng cho sale: áp hệ số theo chương trình riêng của từng tháng, kiểm hai mốc ghi nhận khác nhau (doanh số ký / doanh số giao), rồi đối chiếu với bảng do sale tự lập | 1 kế toán bán hàng làm khâu chốt; 30 nhân viên kinh doanh bị ảnh hưởng vì doanh số quyết định thu nhập | Bước 3-4 — áp hệ số rồi truy từng dòng lệch giữa hai bảng: **5 ngày/tháng của 1 người ≈ 40 giờ/tháng**. Đây là con số lớn nhất trong toàn bộ 15 candidate | _(chờ nhóm)_ |
| 9 | Trần Thị Thuý | Mỗi lần khách đổi mẫu hoặc số lượng, đơn phải chạy lại toàn bộ vòng: mở khoá → sale sửa → đề nghị lại → kế toán duyệt → gửi email ghi log | Kế toán bán hàng và nhân viên kinh doanh; khách đã ký hợp đồng là bên chịu hậu quả cuối | Bước 5 — chờ kế toán duyệt: 20 phút/lần (gồm cả thời gian chờ) x 30 đơn trên tổng 100 đơn/tháng ≈ **10 giờ/tháng**. Đã có ca **quên duyệt** dẫn tới thiếu hàng đúng ngày hẹn giao khách | _(chờ nhóm)_ |
| 10 | Nguỵ Khắc Phi Long | Onboard vào codebase công ty: đọc code cũ để hiểu một module trước khi sửa được dòng đầu tiên | Intern/người mới trong 4-6 tuần đầu; senior phải dừng việc để giải thích lại. Team nhận 2-3 người mới/quý | Bước 3 — lần theo luồng gọi trong code lạ từ entry point: ~150 phút/module. Tổng ~4 tiếng mới sửa được dòng code đầu tiên | _(chờ nhóm)_ |
| 11 | Nguỵ Khắc Phi Long | Điều tra và tái hiện bug từ ticket mô tả sơ sài, phải lần log qua nhiều service | Dev/intern trực ticket; QA phải chờ kết quả điều tra mới test tiếp được | Bước 3-4 — lọc log rồi lần theo request id qua các service: ~40 phút/ticket, vì **mỗi query tiếp theo phụ thuộc kết quả query trước** nên không làm song song được. Tổng ~85 phút/ticket x ~3 ticket/tuần = ~4,25 tiếng/tuần | _(chờ nhóm)_ |
| 12 | Nguỵ Khắc Phi Long | Intern phải hỏi lại mentor cùng một loại câu hỏi (setup, quy trình deploy, ai phụ trách service nào) vì không có chỗ tra tập trung | Intern mới; mentor bị ngắt mạch công việc đang làm | Bước 5 — chờ mentor trả lời, và **câu trả lời trôi vào DM không được lưu lại** nên lần sau hỏi lại từ đầu: 4-5 lần/tuần. Intern mất ~100 phút/tuần, mentor mất ~50 phút/tuần = ~2,5 tiếng/tuần cho cả hai | _(chờ nhóm)_ |
| 13 | Đoàn Duy Bách | Thông báo và deadline nằm rải rác ở 3 kênh: Discord / Vlearn / Outlook. Mỗi tuần phải mở cả 3 kênh, lọc tin nào có deadline, rồi tự ghi vào lịch | Học viên trong lớp (số đo lấy trên chính người đưa ra bài) | Bước 2 — lọc tin có deadline giữa 3 kênh: 30 phút/tuần, lặp lại y hệt mỗi tuần. Hậu quả: vẫn **suýt bỏ lỡ 3 thông báo trong 1 tuần**. So sánh được Rule (bật notification, tạo Outlook rule) với AI trích deadline. _Chưa chắc: mới đo 1 tuần và chỉ trên 1 người, có thể chỉ cần Rule là đủ_ | _(chờ nhóm)_ |
| 14 | Đoàn Duy Bách | Học viên hỏi lại trên Discord đúng những lỗi đã từng được trả lời khi làm lab, nên TA phải trả lời lại từ đầu | Học viên đang kẹt lỗi; TA phải trả lời lặp | Bước search — **gõ từ khoá trên Discord không ra được câu trả lời cũ**, nên người hỏi tưởng chưa ai hỏi. Đếm được: **3/5 câu hỏi trong tuần là lỗi đã có lời giải**. _Chưa chắc: mẫu nhỏ (5 tin, 1 tuần), và chưa rõ người hỏi tìm không thấy hay không tìm trước khi hỏi_ | _(chờ nhóm)_ |
| 15 | Đoàn Duy Bách | Vlearn trên điện thoại chỉ hiển thị nửa màn hình khi xem bài và khi làm quiz | Học viên học bằng điện thoại — đã xác nhận ít nhất 3 bạn gặp cùng lỗi | Bước xem bài / làm quiz — giao diện vỡ nên phải xoay, zoom, tải lại: **+5 phút/lần x 7 lần/tuần = 35 phút/tuần**, và **3 quiz phải hoãn hoặc làm lại**. Có screenshot làm bằng chứng. Workflow ngắn, dễ vẽ; khả năng cao là No AI, chỉ cần Vlearn sửa giao diện. _Chưa chắc: lỗi xảy ra trên mọi máy hay chỉ một số điện thoại/trình duyệt_ | _(chờ nhóm)_ |

> **Điểm Phan Duy Bảo mang ra pitch với nhóm:** cả 3 candidate ở dòng 1-3 đều chung một nguyên nhân gốc — mọi việc đều phải đi qua một mình quản lý, nên cái gì đến đúng lúc đang bận thì trôi mất ("nhắn tôi trôi tin nhắn hoặc khách nhắn lúc tôi đang bận" ở #1, "không online thì trôi" ở #3). Có thể bài toán thật không phải từng khâu lẻ, mà là "giảm số việc bắt buộc phải qua một người".

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

> Bản nháp gom cụm trên đủ 15 candidate. **Nhóm xác nhận lại khi họp.**

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| **A — Thông tin nằm rải rác nhiều kênh, không có nguồn tập trung** | #1, #4, #11, #12, #13, #14 | Dữ liệu có tồn tại nhưng nằm phân tán ở nhiều nơi và không nơi nào là nguồn chính thức. Mỗi lần cần thì người xử lý phải đi gom lại từ đầu. Câu trả lời cũ không tìm lại được nên bị hỏi lại | Cụm đông nhất — 6/15 bài. Đây là cụm nhóm chốt |
| **B — Một người giữ hết quyền nên thành nút cổ chai** | #1, #3, #9, #12 | Mọi việc bắt buộc đi qua đúng một người. Người đó bận hoặc quên thì việc dừng lại, và thường không ai biết là đã dừng | #1 nằm ở cả A và B — đó là một lý do nó nổi lên so với các bài khác |
| **C — Dữ liệu thô chưa thành câu trả lời** | #7, #8, #10 | Dữ liệu đã có và đã tập trung, nhưng dừng ở dạng nguyên liệu. Người đọc vẫn phải tự lọc, tự suy ra kết luận | Khác cụm A ở chỗ: không thiếu dữ liệu, thiếu lớp diễn giải |
| **D — Thao tác lặp cơ học, hoặc quy trình thiếu hẳn một bước** | #2, #5, #6, #15 | Việc lặp y hệt mỗi kỳ mà không ai đặt câu hỏi tại sao vẫn làm tay; hoặc quy trình thiếu một bước bắt buộc nên bước đó bị bỏ qua liên tục | #15 hơi khác nhóm: là lỗi sản phẩm chứ không phải lỗi quy trình, gần như chắc chắn No AI |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

> Bản nháp. **Nhóm xác nhận lại khi họp.**

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **#1 — Điều phối sự cố bảo trì** (Bảo) | Nằm ở giao của hai cụm đông nhất là A và B, nên giải nó là chạm vào pattern chung của nhiều bài khác. Actor rõ tới từng người và đủ nhỏ để vẽ hết: 1 quản lý, 1 sale, 2 thợ, khách thuê. Nguyên nhân gốc đã tách sạch khỏi triệu chứng, kèm bằng chứng phủ định rõ ràng là thợ luôn báo lại ngay nên khâu thi công không phải vấn đề | Toàn bộ bằng chứng là tự quan sát của chính quản lý, chưa phỏng vấn ai. Chỉ số quan trọng nhất — số vụ khách phải nhắc lần 2 — vẫn là "thi thoảng", chưa đếm được |
| **#7 — Bảng tồn kho** (Thuý) | Bằng chứng mạnh nhất trong 15 bài: đã bấm giờ tách bước và **đã phỏng vấn 4 người** ở cả hai đầu quy trình. Bottleneck thu hẹp được xuống đúng một trường dữ liệu bị thiếu. Có hai tầng nghẽn khác bản chất nên so sánh Rule / Workflow / Agent rất rõ | Chỉ một thành viên trong nhóm ở trong ngành và hiểu mô hình đặt trước – lấy sau. Bốn người còn lại phải tin vào mô tả của một người, nên khó challenge sâu |
| **#11 — Điều tra bug từ ticket sơ sài** (Long) | Số đo đầy đủ nhất phía nhóm dev: ~85 phút/ticket × ~3 ticket/tuần ≈ 4,25 tiếng/tuần. Có một đặc điểm kỹ thuật đáng giá: mỗi query phụ thuộc kết quả query trước nên không song song hoá được — đây là lập luận tốt cho phần chọn mức | Ba bạn trong nhóm hiểu domain dev, hai bạn còn lại thì không. Và giải pháp nhiều khả năng là hạ tầng log tập trung chứ không phải AI, nên phần so sánh R/W/A có thể nhạt |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

> Bản nháp chấm trên 3 bài đã shortlist. **Nhóm chấm lại, kể cả chấm khác.**

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #1 Điều phối sự cố bảo trì (Bảo) | 5 | 5 | 2 | 3 | 5 | 5 | 5 | **30** |
| #7 Bảng tồn kho (Thuý) | 5 | 5 | 4 | 4 | 5 | 5 | 2 | **30** |
| #11 Điều tra bug từ ticket (Long) | 4 | 4 | 3 | 4 | 4 | 4 | 4 | **27** |

**Giải thích các điểm cực đoan:**

- **#1 và #7 hoà nhau ở 30 điểm.** Điểm tổng không phân định được, nên phải nhìn vào từng tiêu chí.
- **#1 được 5 ở "Nhóm hiểu domain" còn #7 chỉ được 2**: ai cũng từng đi thuê nhà và từng báo hỏng nên cả 5 người challenge được; còn mô hình bán lẻ nội thất đặt trước – lấy sau thì chỉ một người trong nhóm hiểu. **Đây là tiêu chí phân định.**
- **#1 chỉ được 2 ở "Pain có evidence" còn #7 được 4**: #7 đã phỏng vấn 4 người và có số đo cụ thể; #1 mới là tự quan sát của một người, và chỉ số quan trọng nhất vẫn là "thi thoảng". Chính người đưa ra bài đã ghi đây là lỗ hổng lớn nhất.
- **#1 được 5 ở "So sánh R/W/A được"**: bài tách sẵn thành hai lớp có bản chất khác nhau — bảng theo dõi là Rule, còn đọc tin nhắn Zalo mới là chỗ có thể cần AI — nên so sánh được ngay trên cùng một bài.
- **#1 chỉ được 3 ở "Impact đo được"**: 1,5-7,5 tiếng/tháng là phép nhân của hai ước lượng, biên độ rộng gấp 5 lần nên chưa dùng làm baseline được.
- **#11 được 4 đều ở hầu hết tiêu chí nhưng không nhất ở tiêu chí nào**: bài chắc chắn nhưng không có điểm mạnh nổi bật để nhóm đồng thuận nhanh.

**Candidate nhóm chọn (1 bài duy nhất):**

```text
#1 — Điều phối sự cố bảo trì: khách báo hỏng qua 3 kênh rời rạc, không có chỗ ghi nhận
tập trung, nên vụ rơi vào lúc quản lý bận thì bị trôi và khách phải nhắc lần 2.
```

**Vì sao chọn (4-5 câu):**

```text
Điểm tổng của #1 hoà với #7, nên nhóm phải nhìn vào từng tiêu chí thay vì cộng điểm. Tiêu
chí phân định là "nhóm hiểu domain": cả 5 người đều từng đi thuê nhà và từng báo hỏng nên
ai cũng challenge được vào chi tiết, trong khi bài tồn kho thì chỉ một người trong nhóm ở
trong ngành và bốn người còn lại chỉ có thể gật theo mô tả. Một bài mà bốn người không vặn
được thì sẽ thành một người làm, bốn người ngồi xem.

#1 cũng nằm ở giao của hai cụm đông nhất — A (thông tin rải rác) và B (một người giữ hết
quyền) — nên giải nó là chạm vào pattern chung của 8 trong 15 candidate, chứ không chỉ giải
một ca lẻ.

Cuối cùng, #1 là bài duy nhất đã tách sạch nguyên nhân gốc khỏi triệu chứng và có bằng chứng
phủ định rõ ràng: thợ luôn nhắn báo lại ngay khi sửa xong, nên khâu thi công chắc chắn không
phải chỗ nghẽn. Nhờ vậy nhóm không mất thời gian tranh cãi xem nên sửa ở đâu.

Nhóm chấp nhận điểm yếu đã biết của #1 là bằng chứng còn mỏng, và đưa việc đếm baseline
thành điều kiện bắt buộc ở Phase 6 thay vì lờ đi.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
#7 Bảng tồn kho (Thuý): bài mạnh nhất về bằng chứng — đã bấm giờ tách bước và phỏng vấn 4
người ở cả hai đầu quy trình. Nhưng chỉ một thành viên hiểu mô hình đặt trước – lấy sau, nên
nhóm không challenge sâu được. Bài tốt nhưng sai nhóm.

#8 Chốt doanh số (Thuý): impact lớn nhất trong cả 15 bài, 40 giờ/tháng. Nhưng phạm vi gồm
quy tắc hệ số thay đổi theo từng tháng, hai mốc ghi nhận doanh số, và xử lý đơn huỷ truy
ngược sang tháng trước — quá rộng, làm không xong trong một lab 4 tiếng.

#9 Vòng đổi đơn hàng (Thuý) và #2 Chốt điện nước (Bảo): workflow rõ và có số, nhưng gần như
chắc chắn là bài của process fix và thao tác lặp, không phải bài của AI. Chọn chúng thì phần
so sánh Rule / Workflow / Agent sẽ nhạt vì không có gì để cân nhắc.

#11 Điều tra bug (Long): số đo đầy đủ nhất phía dev, nhưng hai bạn trong nhóm không có nền
kỹ thuật để challenge, và giải pháp nhiều khả năng là hạ tầng log tập trung chứ không phải
AI.

#4, #5, #6 (Tú) và #13, #14 (Bách): thiếu số đo ở mức khác nhau — #5 và #6 thiếu toàn bộ số
đo, #4 thiếu tần suất nên không quy ra được giờ/tháng để so với bài khác, #13 và #14 mới đo
1 tuần trên mẫu rất nhỏ. Không có số thì không chấm được tiêu chí impact và không bảo vệ
được khi bị hỏi.

#3 (Bảo), #10, #12 (Long), #15 (Bách): mỗi bài đều hợp lệ nhưng đứng sau #1 ở ít nhất hai
tiêu chí. Riêng #15 là lỗi sản phẩm của bên thứ ba, nhóm không có quyền sửa nên không làm
được vòng before/after thật.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
[nhóm điền — ai đã phản đối điều gì, nhóm xử lý ra sao. Có bất đồng mà ghi lại là ĐƯỢC điểm,
không phải mất điểm. Gợi ý chỗ nhiều khả năng có bất đồng thật: #1 và #7 hoà điểm, và #1 lại
là bài có bằng chứng yếu hơn hẳn — ai đã lên tiếng về chuyện này, và nhóm chốt ra sao?]
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Tự quan sát của quản lý (người trong cuộc) | 1 | Nguyên văn khi tự soi lại: **"Thi thoảng bị trôi, do nhắn tôi trôi tin nhắn hoặc khách nhắn lúc tôi đang bận."** Câu này chỉ ra hai điều kiện gây lỗi và **cả hai đều nằm ở khâu tiếp nhận**: tin bị trôi lẫn trong hàng trăm tin Zalo, và yêu cầu đến đúng lúc người nhận đang bận | Thợ **luôn nhắn báo lại ngay** khi sửa xong — khâu bàn giao ngược chạy tốt. Vụ bị trôi là vụ **chưa bao giờ tới tay thợ**, không phải vụ thợ làm chậm | Loại bỏ mọi hướng giải pháp nhắm vào tốc độ hoặc năng suất của thợ. Khoanh problem về đúng khâu tiếp nhận |
| Kiểm lại giả định về thiệt hại | — | — | Bản nháp đầu ghi "sửa chậm làm mất khách, mỗi khách đi mất 1,5-3 triệu tiền phòng". Kiểm lại thực tế: khách **chỉ càu nhàu nhẹ**, nhắc lại là xong, và **chưa có ai trả phòng** vì lý do sửa chữa chậm | **Bỏ hẳn lập luận "mất khách"** khỏi bài. Giá trị thật chỉ còn nằm ở giờ công của quản lý và ở việc không để khách phải nhắc lần 2 |
| Phản biện nội bộ trong lúc viết PS v0 | — | Câu hỏi ngược: **"nếu chỉ mình anh được ghi, thì lúc anh bận ai ghi?"** | Boundary bản v0 ghi "chỉ quản lý được ghi và đóng vụ" — mâu thuẫn trực tiếp với chính bottleneck đã xác định | **Thay đổi lớn nhất giữa v0 và v1:** tách quyền GHI NHẬN khỏi quyền QUYẾT ĐỊNH. Mở quyền ghi cho cả sale và thợ, giữ quyền phân thợ và đóng vụ cho quản lý |
| Interview 1 sale + 2 thợ | **0 — chưa thực hiện** | — | — | **Lỗ hổng lớn nhất của bài.** Lab yêu cầu tối thiểu 2-3 người; ba người này làm việc cùng quản lý mỗi ngày nên hỏi được ngay. Cần hỏi: có bao giờ khách báo hỏng trực tiếp với họ không, lúc đó họ làm gì với thông tin đó |
| Log / chat — đếm baseline từ lịch sử Zalo | **0 — chưa thực hiện** | — | — | Chỉ số quan trọng nhất, số vụ khách phải nhắc lần 2, vẫn là "thi thoảng". Dữ liệu **nằm sẵn trong lịch sử chat, chỉ cần ngồi đếm**. Đây là điều kiện để chuyển Not Yet thành Go |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain nằm ở khâu TIẾP NHẬN, không nằm ở khâu thi công. Bằng chứng phủ định rõ ràng: thợ luôn
nhắn báo lại ngay khi sửa xong, và vụ bị trôi là vụ chưa bao giờ tới được tay thợ. Vì vậy
mọi giải pháp nhắm vào tốc độ sửa chữa đều sai chỗ.

Nguyên nhân gốc là không có nơi nào ghi nhận yêu cầu ngay tại thời điểm nhận, nên vụ nằm chờ
trong trí nhớ của một người, và trí nhớ đó hỏng đúng lúc người ấy đang bận.

Phát hiện quan trọng nhất đến từ một câu phản biện chứ không từ số liệu: nếu chỉ quản lý
được ghi vào bảng, thì lúc quản lý bận vẫn không ai ghi, và vụ vẫn trôi y như cũ. Nghĩa là
cái bảng chỉ đổi chỗ chứa trí nhớ chứ không sửa được gốc. Đó là lý do phải tách quyền ghi
nhận khỏi quyền quyết định — và đây mới là lõi của giải pháp, không phải bản thân cái bảng.

Điểm yếu phải nói thẳng: toàn bộ bằng chứng hiện tại là tự quan sát của chính người trong
cuộc. Chưa phỏng vấn 1 sale và 2 thợ, chưa đếm baseline từ lịch sử chat Zalo.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **CMMS / phần mềm bảo trì cho chủ nhà nhỏ** (DoorLoop, Property Meld, MaintainX) | [doorloop.com](https://www.doorloop.com/blog/best-property-management-maintenance-software) · [getmaintainx.com](https://www.getmaintainx.com/industries/property-management) | Đúng bước 2 và bước 5: cổng tiếp nhận yêu cầu, tạo và theo dõi work order, gán thợ, nhắc vụ quá hạn, lưu lịch sử | Bảng theo dõi trạng thái vụ việc là **chuẩn ngành đã có sẵn**, không cần thiết kế lại từ đầu. Tài liệu cũng nói thẳng: chỉ danh mục lớn mới cần CMMS riêng, chủ nhà nhỏ dùng tính năng có sẵn là đủ | Các công cụ này đòi khách **vào portal riêng để báo hỏng**. Khách của toà đang báo qua Zalo và gọi điện — bắt khách đổi kênh là phần khó nhất và dễ thất bại nhất | Lấy **cấu trúc bảng** của họ (Mới / Đã phân thợ / Đang sửa / Xong) nhưng **giữ nguyên 3 kênh của khách**. Xác nhận đúng nguyên tắc nhóm đã đặt ở Boundary: không ép khách đổi thói quen |
| **Zendesk — Intelligent triage** | [support.zendesk.com](https://support.zendesk.com/hc/en-us/articles/4550640560538-Automatically-classifying-tickets-with-intelligent-triage) | Bước có thể dùng AI: đọc tin tự do, phân loại theo chủ đề và mức khẩn, trích xuất thực thể | Cho thấy "đọc tin nhắn tự do rồi tự tạo và phân loại vụ" là **bài toán tiêu chuẩn đã được giải**, không phải nhu cầu lạ. Nếu sau này nhóm cần thì có đường đi sẵn | Thiết kế cho khối lượng hàng nghìn ticket. Với **5-15 vụ/tháng**, chi phí thiết lập và duy trì gần như chắc chắn vượt lợi ích | **Củng cố quyết định No AI của nhóm**: công cụ tồn tại, nhưng quy mô của toà nhà thấp hơn ngưỡng mà nó phục vụ tới hai bậc. Chọn Rule không phải vì không biết AI có gì, mà vì biết rõ nó dành cho quy mô nào |
| **Human-in-the-loop: ngưỡng độ tin cậy + đường lùi** | [moveworks.com](https://www.moveworks.com/us/en/resources/blog/helpdesk-ticketing-system-ai-automation) | Cơ chế an toàn cho trường hợp về sau có đưa AI vào bước trích yêu cầu | Nguyên tắc: khi độ tin cậy dưới ngưỡng thì đẩy sang người xem kèm lý do, thay vì tự quyết. Chính đường lùi này mới làm hệ thống đáng tin lúc mới chạy | Cần định nghĩa ngưỡng và cần người thật soát hàng đợi, nếu không hàng đợi "cần người xem" sẽ đọng lại và tái tạo đúng lỗi cũ | **Bổ sung một điều kiện cho điều khoản "nếu sau này dùng AI"** ở mục 6.2: AI không được phép im lặng bỏ qua tin nó không chắc, mà phải gắn cờ "cần người xem". Im lặng bỏ qua chính là painpoint gốc |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Không build: một hệ thống theo dõi bảo trì mới. Cấu trúc bảng trạng thái vụ việc là chuẩn
ngành, DoorLoop và MaintainX đã có sẵn. Nhóm chỉ cần chép lại cấu trúc đó vào Google Sheets.

Không làm: bắt khách vào một portal riêng để báo hỏng. Đây là điểm các công cụ thương mại
khác nhóm nhiều nhất, và cũng là chỗ dễ thất bại nhất — khách đang dùng Zalo và điện thoại,
đổi hành vi của khách khó hơn nhiều so với đổi cách làm nội bộ.

Research củng cố quyết định No AI chứ không lật lại nó: công cụ AI triage tồn tại và đã
trưởng thành, nhưng phục vụ quy mô hàng nghìn ticket. Với 5-15 vụ/tháng thì công kiểm lại
kết quả của AI còn lâu hơn công tự ghi vào bảng.

Bổ sung vào điều khoản dự phòng: nếu về sau có dùng AI thì bắt buộc phải có ngưỡng độ tin
cậy và trạng thái "cần người xem". AI không được im lặng bỏ qua tin nó không chắc, vì im
lặng bỏ qua đúng là painpoint gốc của bài này.

Giả định chưa chắc: chưa kiểm chi phí thực tế của các công cụ trên ở quy mô 30-60 phòng, nên
chưa khẳng định được "tự dựng Google Sheets rẻ hơn mua công cụ có sẵn".
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

> Phase 5 và Phase 6 do Phan Duy Bảo soạn trên Problem Card #1 của bạn ấy, là bài nhóm đã chốt.

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
CURRENT STATE — 5-15 vụ/tháng, 1-3 ngày mỗi vụ, quản lý tốn 15-30 phút/vụ

[1 Khách báo hỏng qua 3 kênh: Zalo riêng / gọi điện / nhóm Zalo chung - khách]
→ [2 Quản lý đọc và tự ghi nhớ, KHÔNG ghi ra đâu cả]        <-- BOTTLENECK
→ [3 Quản lý phân việc cho 1 trong 2 thợ: 15-30' - quản lý]  -- handoff 1
→ [4 Thợ đi sửa: 1-3 ngày - thợ]
→ [5 Thợ nhắn báo xong: ngay khi xong - thợ]                 -- handoff 2, khâu này KHÔNG lỗi
→ [6 Quản lý báo lại khách và đóng vụ - quản lý]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Khách thuê | Phát hiện hỏng (điện, nước, máy lạnh, nóng lạnh) | Tin nhắn hoặc cuộc gọi báo hỏng | 5-15 vụ/tháng | 3 kênh song song. Cuộc gọi KHÔNG để lại dấu vết văn bản nào |
| 2 | Quản lý | Tin nhắn / cuộc gọi từ khách | Chỉ nằm trong trí nhớ, không ghi ra đâu | Ngay khi nhận, nếu đang rảnh | **BOTTLENECK** — không có chỗ ghi nhận tập trung |
| 3 | Quản lý | Yêu cầu đã nhận | Phân việc cho 1 trong 2 thợ | 15-30 phút/vụ (tính cả theo dõi, nhắc lại, báo khách) | **Handoff 1**: quản lý → thợ. Mọi vụ bắt buộc đi qua quản lý |
| 4 | Thợ kỹ thuật | Việc được phân | Sửa xong | 1-3 ngày tính từ lúc khách báo | |
| 5 | Thợ kỹ thuật | Kết quả sửa | Tin nhắn báo xong cho quản lý | Ngay khi xong | **Handoff 2**: thợ → quản lý. Khâu này không phải vấn đề, thợ luôn báo lại ngay |
| 6 | Quản lý | Xác nhận từ thợ | Báo lại khách, đóng vụ | | |
| 7 | — | — | — | — | _(workflow chỉ có 6 bước)_ |

**Bottleneck chính (2-3 câu):**

```text
Bottleneck nằm ở bước 2 — khâu NHẬN và GHI NHẬN yêu cầu, không phải ở khâu thi công.
Ba kênh báo hỏng cùng đổ về một người, yêu cầu nằm lẫn trong hàng trăm tin nhắn Zalo, còn
cuộc gọi điện thoại thì không để lại dấu vết văn bản nào để tìm lại. Nói bằng lời của chính
quản lý: "thi thoảng bị trôi, do nhắn tôi trôi tin nhắn hoặc khách nhắn lúc tôi đang bận".

Bằng chứng cho thấy khâu thi công KHÔNG phải vấn đề: thợ luôn nhắn báo lại ngay khi sửa
xong (bước 5 chạy tốt). Vụ bị trôi là vụ chưa bao giờ tới được tay thợ, chứ không phải vụ
thợ làm chậm. Vì vậy mọi giải pháp nhắm vào tốc độ của thợ đều sai chỗ.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
FUTURE STATE — mục tiêu 0 vụ bị trôi, phân thợ trong vòng 2 tiếng

[1 Khách báo hỏng - vẫn để nguyên 3 kênh, KHÔNG ép khách đổi thói quen]
→ [2 NGƯỜI NÀO NHẬN ĐƯỢC TIN TRƯỚC thì người đó ghi ngay vào bảng        <-- CHỖ SỬA CHÍNH
     theo dõi (quản lý, sale hoặc thợ - người nào cũng ghi được)
     bảng có cột trạng thái: Mới / Đã phân thợ / Đang sửa / Xong]         -- Rule, không cần AI
→ [3 Quản lý phân thợ + đặt hạn xử lý - CHỈ quản lý]                      <-- HUMAN BOUNDARY
→ [4 Thợ sửa, báo lại như hiện nay - thợ]
→ [5 Vụ quá hạn tự nổi lên đầu bảng để quản lý nhắc - Rule: lọc theo hạn]
→ [6 Quản lý xác nhận với khách rồi mới đóng vụ - CHỈ quản lý]            <-- HUMAN BOUNDARY

NGUYÊN TẮC THIẾT KẾ QUAN TRỌNG NHẤT — tách quyền GHI NHẬN khỏi quyền QUYẾT ĐỊNH:
- Quyền GHI NHẬN (bước 2): mở cho cả quản lý, sale và thợ. Ai nghe khách báo trước thì ghi.
  Mở quyền này chính là thứ bịt được chỗ rơi việc, vì lúc quản lý đang bận vẫn có người ghi.
- Quyền QUYẾT ĐỊNH (bước 3 và 6): chỉ quản lý. Phân thợ nào và đóng vụ hay chưa vẫn do
  quản lý nắm, không chia cho ai.
Nếu gộp hai quyền này làm một như hiện nay thì cái bảng chỉ đổi chỗ chứa trí nhớ của quản
lý chứ không sửa được nguyên nhân gốc.

Bước nào là máy (Rule): bước 2 lưu trạng thái, bước 5 lọc vụ quá hạn theo ngày.
Bước nào là AI: KHÔNG CÓ. Xem mục 6.1 để biết vì sao bài này không cần AI.
Bước nào là người: bước 3 phân thợ và bước 6 đóng vụ - đều là quyết định, giữ cho người.

Fallback: nếu bảng theo dõi không được cập nhật đều thì quay về cách cũ (quản lý tự nhớ),
nhưng bắt buộc mọi vụ phải có ít nhất 1 tin nhắn trong nhóm Zalo chung để còn tìm lại được.
Nếu sau 1 tháng bảng vẫn bị bỏ trống thì dừng hẳn, vì một cái bảng sai còn nguy hiểm hơn
không có bảng — nhìn vào tưởng không còn việc tồn, thực tế thì có.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Thời gian quản lý tốn mỗi vụ | 15-30 phút | Dưới 10 phút | Bấm giờ 10 vụ liên tiếp, so với 10 vụ trước đó |
| Tổng thời gian điều phối/tháng | 1,5-7,5 tiếng | Dưới 2,5 tiếng | Số vụ trong tháng x thời gian mỗi vụ |
| Số vụ khách phải nhắc lần 2 | "Thi thoảng" (chưa đếm được) | 0 vụ/tháng | Đếm trên bảng theo dõi; baseline lấy bằng cách đếm lại lịch sử chat Zalo 1 tháng gần nhất |
| Thời gian từ lúc khách báo tới lúc thợ nhận việc | Chưa đo | Dưới 2 tiếng | Ghi 2 mốc giờ trên bảng: giờ khách báo, giờ phân thợ |
| Số bước | 6 | 6 | Mục tiêu KHÔNG phải giảm số bước, mà là không để rơi việc ở bước 2 |
| Số bước thủ công | 6/6 | 4/6 | Bước 2 lưu trạng thái và bước 5 lọc quá hạn do máy làm |
| Bottleneck chính | Bước 2 — ghi nhận trong trí nhớ | Bước 3 — quản lý phân thợ | Bottleneck mới chấp nhận được vì đó là điểm ra quyết định, không phải điểm rơi việc |
| Risk mới | Không có | Bảng không được cập nhật đều | Một cái bảng sai còn nguy hiểm hơn không có bảng: nhìn vào tưởng hết việc tồn |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Quản lý một tòa cho thuê 30-60 phòng, là người duy nhất điều phối việc sửa chữa cho 2 thợ kỹ thuật. Hai bên cùng chịu ảnh hưởng: khách thuê phải chờ hoặc phải nhắc lại, và quản lý bị ngắt quãng công việc. |
| **Workflow** | Khách báo hỏng qua 1 trong 3 kênh (Zalo riêng, gọi điện, nhóm Zalo chung) → quản lý đọc và tự ghi nhớ → quản lý phân việc cho 1 trong 2 thợ → thợ đi sửa → thợ nhắn báo xong → quản lý báo lại khách và đóng vụ. Lặp 5-15 lần mỗi tháng, không theo lịch cố định. |
| **Bottleneck** | Bước 2 — khâu nhận và ghi nhận yêu cầu. Ba kênh đổ về một người mà không có chỗ ghi nhận tập trung; cuộc gọi không để lại dấu vết văn bản. Vụ nào không xử lý ngay lúc nhận thì trôi mất: "nhắn tôi trôi tin nhắn hoặc khách nhắn lúc tôi đang bận". Khâu thi công không phải vấn đề vì thợ luôn báo lại ngay khi xong. |
| **Impact** | Có bằng chứng: quản lý tốn 15-30 phút/vụ x 5-15 vụ/tháng = 1,5-7,5 tiếng/tháng (~18-90 tiếng/năm) chỉ để làm trung gian chuyển việc; khách chờ 1-3 ngày, thỉnh thoảng phải nhắc lần 2. Chưa có bằng chứng: giả định "sửa chậm làm mất khách" đã bị loại bỏ, vì thực tế khách mới chỉ càu nhàu nhẹ và chưa có ai trả phòng vì lý do này. |
| **Success Metric** | (1) Số vụ khách phải nhắc lần 2: hiện "thi thoảng" → mục tiêu 0 vụ/tháng. (2) Thời gian từ lúc khách báo tới lúc thợ nhận việc: hiện chưa đo → mục tiêu dưới 2 tiếng. (3) Thời gian quản lý tốn mỗi vụ: hiện 15-30 phút → mục tiêu dưới 10 phút. Cách lấy baseline: đếm lại lịch sử chat Zalo 1 tháng gần nhất, và ghi 2 mốc giờ cho từng vụ trong 2 tuần tới. |
| **Boundary** | LÀM: gom mọi yêu cầu vào một bảng theo dõi có trạng thái; mở quyền GHI NHẬN cho cả quản lý, sale và thợ (ai nhận tin trước thì ghi); tự động đẩy vụ quá hạn lên đầu bảng. KHÔNG LÀM: không ép khách đổi kênh báo hỏng; quyền phân thợ và quyền đóng vụ chỉ quản lý được làm, không chia cho ai; không tự hứa thời hạn sửa với khách; không tự đóng vụ khi chưa có xác nhận; không đụng tới khâu thi công của thợ vì khâu đó đang chạy tốt. |

**Câu hỏi AI phản biện v0 (nếu có):**

- **Field nào mơ hồ:**
  1. **Success Metric** — baseline mới là "thi thoảng", chưa phải một con số. Không có baseline thì sau này không chứng minh được là có cải thiện hay không.
  2. **Impact** — bản nháp đầu tiên có câu "sửa chậm làm mất khách, mỗi khách đi mất 1,5-3 triệu". Không có bằng chứng nào đỡ cho con số đó.
  3. **Boundary** — bản v0 đầu tiên ghi "chỉ quản lý được ghi và đóng vụ". Điều này mâu thuẫn với chính bottleneck: nếu chỉ quản lý mới được ghi vào bảng, thì lúc quản lý đang bận vẫn không ai ghi, và vụ vẫn trôi y như cũ. Cái bảng lúc đó chỉ đổi chỗ chứa trí nhớ chứ không sửa được nguyên nhân gốc.

- **Tôi sửa gì:**
  1. Ghi thẳng cách lấy baseline vào metric (đếm lịch sử Zalo 1 tháng + ghi 2 mốc giờ trong 2 tuần), và chấp nhận rằng quyết định cuối phải là **Not Yet** chứ không phải Go.
  2. Tách Impact thành 2 phần rõ ràng: phần CÓ BẰNG CHỨNG (giờ công) và phần CHỈ LÀ GIẢ ĐỊNH (mất khách) — rồi bỏ hẳn phần giả định ra khỏi lập luận.
  3. Sửa hẳn Boundary: **tách quyền GHI NHẬN khỏi quyền QUYẾT ĐỊNH**. Mở quyền ghi cho cả sale và thợ để bịt chỗ rơi việc, nhưng giữ nguyên quyền phân thợ và quyền đóng vụ cho một mình quản lý. Đây là thay đổi lớn nhất giữa v0 và v1, và nó đến từ việc bị hỏi ngược đúng một câu: "nếu chỉ mình anh được ghi, thì lúc anh bận ai ghi?". Đáng chú ý là bài học này trùng với bài học ở Problem Card #3 của tôi — chỗ nào một mình tôi giữ hết quyền thì chỗ đó thành nút cổ chai.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Thấp (có đúng/sai rõ) / [ ] Cao — Vì sao: một yêu cầu bảo trì chỉ có 3 thông tin và cả 3 đều có đáp án đúng/sai rõ ràng: phòng số mấy, hỏng cái gì, đã xong hay chưa. Không có chuyện hai người ghi hai kiểu mà vẫn cùng đúng.
- Độ phức tạp: [x] Thấp (1-2 bước) / [ ] Cao — Vì sao: chuỗi đi thẳng một đường 6 bước, không rẽ nhánh, chỉ một nguồn dữ liệu là lời khách báo. Bước sau không phụ thuộc vào kết quả suy luận của bước trước.

> **Nhóm cần chốt:** tài liệu `Báo cáo giải pháp AI` đánh giá độ mơ hồ là CAO vì xét việc *đọc tin nhắn tự do của khách*. Ô đánh dấu ở đây xét *nội dung cần ghi lại*. Hai cách xét đều hợp lệ nhưng dẫn tới hai mức chọn khác nhau, nên phải thống nhất một bản trước khi nộp.

**Bài toán nhóm nằm ở ô nào:**

```text
Ô "Độ mơ hồ THẤP + Độ phức tạp THẤP" — tức ô mà chính ma trận nói rằng
"Rule hoặc workflow đơn giản thường là đủ".
```

**Vì sao (2-3 câu):**

```text
Vì bài toán này không có chỗ nào cần phán đoán. Ghi lại "phòng 203 hỏng nóng lạnh, nhận
lúc 9h" là việc chép đúng nguyên văn, không phải việc hiểu ẩn ý hay tổng hợp nhiều nguồn.

Ba câu tự kiểm của worksheet đều cho ra cùng một hướng: output KHÔNG được phép khác nhau
mỗi lần (phải ghi đúng phòng, đúng lỗi) nên độ mơ hồ thấp; chỉ có 1 nguồn dữ liệu và 6 bước
tuyến tính nên độ phức tạp thấp; và không có bước nào cần tự quyết định bước tiếp theo nên
không cần tới Agent.

Điểm đáng chú ý: cái thiếu ở đây là MỘT CHỖ ĐỂ GHI, không phải một bộ óc để suy nghĩ.
Đó là lý do bài này nằm ở ô đơn giản nhất của ma trận.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Một bảng theo dõi (Google Sheets) có cột trạng thái Mới / Đã phân thợ / Đang sửa / Xong, cộng một quy tắc lọc để vụ quá hạn tự nổi lên đầu bảng | Đủ khi cái thiếu chỉ là MỘT CHỖ ĐỂ GHI và một cách nhìn ra vụ nào đang tồn. Đúng hiện trạng | Bảng không được cập nhật đều thì thành bảng sai — nhìn vào tưởng hết việc tồn, nguy hiểm hơn không có bảng | **CHỌN** — dùng cho bước 2 (ghi nhận) và bước 5 (lọc vụ quá hạn) |
| **Workflow** | Thêm AI đọc luồng tin nhắn Zalo lẫn lộn, tự nhận ra đâu là tin báo hỏng, trích ra "phòng số mấy + hỏng gì" rồi đẩy vào bảng | Chỉ đủ lý do nếu chủ tòa không thể tự ghi tay, hoặc lượng tin lớn tới mức đọc không xuể | AI hiểu sai lời khách, ghi nhầm phòng hoặc bỏ sót tin. Với 5-15 vụ/tháng thì công kiểm lại còn lâu hơn công tự ghi | Không chọn — xem lý do ở dưới |
| **Agent** | Agent tự đọc tin, tự quyết giao cho thợ nào, tự nhắn hẹn lịch với khách, tự đóng vụ | Chỉ cần khi có hàng trăm vụ/tháng, nhiều thợ, nhiều tòa, lịch phức tạp phải tự sắp xếp | Tự hứa sai thời hạn với khách, giao nhầm thợ, đóng vụ khi chưa sửa xong. Đều là mất uy tín thật với khách đang ở | Không chọn — vượt xa nhu cầu |

**5 câu hỏi chốt (trả lời câu đầy đủ):**

1. **Rule có giải được 70-80% case không?** Có, và nhiều hơn thế. Nguyên nhân làm vụ bị trôi là không có chỗ ghi nhận, nên chỉ cần có một bảng ghi nhận là đã chạm đúng gốc. Ước tính Rule giải được khoảng 90% số vụ; 10% còn lại là những vụ khách gọi điện lúc quản lý đang bận và quên ghi vào bảng — nhưng phần đó cũng không phải AI giải được, mà là thói quen con người.

2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?** Đi thẳng một đường: nhận → ghi → phân thợ → sửa → báo xong → đóng vụ. Không có nhánh nào phụ thuộc vào kết quả suy luận của bước trước.

3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?** Không. Với 5-15 vụ/tháng và đúng 2 thợ, việc chọn giao cho thợ nào là quyết định trong vài giây của người quản lý, không phải bài toán lập kế hoạch. Giao cho Agent là giao sai việc.

4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?** Câu trả lời trung thực là **khách phát hiện trước, không phải tôi** — và đó chính là lý do đáng lo nhất. Nếu AI ghi sót một tin báo hỏng thì không ai biết là đã sót, cho tới khi khách nhắc lần 2. Tức là AI sai đúng vào kiểu lỗi mà bài toán này đang muốn diệt. Đây là lập luận mạnh nhất để không dùng AI ở đây.

5. **Có hạ được từ Agent → Workflow → Rule không?** Có, và đã hạ hai bậc. Ban đầu nghĩ tới việc dùng AI đọc Zalo, sau đó nhận ra chỉ cần một cái bảng là đủ.

**Mức chọn:**

```text
Rule — và nói chính xác hơn thì đây là No AI / process fix.
Không có bước nào trong workflow mới cần tới AI.
```

**Vì sao chọn (3-4 câu):**

```text
Vì nguyên nhân gốc là thiếu MỘT CHỖ ĐỂ GHI, chứ không phải thiếu khả năng hiểu ngôn ngữ.
Một bảng theo dõi có cột trạng thái giải đúng vào chỗ đó, chi phí gần bằng không, làm được
trong một buổi, và ai trong nhà cũng dùng được ngay vì đã quen Excel.

Bài toán nằm ở ô "mơ hồ thấp, phức tạp thấp" của ma trận — đúng ô mà Rule là lựa chọn hợp lý.

Quan trọng nhất: nếu AI ghi sót một tin báo hỏng thì người phát hiện ra lại chính là khách,
khi họ phải nhắc lần 2. Mà "khách phải nhắc lần 2" chính là thứ bài toán này sinh ra để diệt.
Dùng AI ở đây là đưa thêm rủi ro vào đúng chỗ đang muốn bảo vệ.

Research củng cố thêm: công cụ AI triage như Zendesk intelligent triage có tồn tại và đã
trưởng thành, nhưng phục vụ quy mô hàng nghìn ticket — cao hơn quy mô của toà nhà tới hai
bậc. Chọn Rule không phải vì không biết AI làm được gì, mà vì biết rõ nó dành cho quy mô nào.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Không còn mức nào đơn giản hơn Rule để hạ xuống nữa. Mức dưới Rule là giữ nguyên hiện trạng
(quản lý tự nhớ), và chính hiện trạng đó đang làm vụ bị trôi.

Có một phương án trông đơn giản hơn là ép khách chỉ báo hỏng qua một kênh duy nhất. Nhưng
phương án này bị loại vì nó đẩy chi phí sang phía khách: khách đang ở trọ, quen gọi điện và
nhắn riêng, ép họ đổi thói quen sẽ làm trải nghiệm tệ đi. Nguyên tắc đặt ra là giữ nguyên
3 kênh cho khách, chỉ thay đổi cách bên trong xử lý. Research xác nhận đây đúng là chỗ các
công cụ CMMS thương mại hay thất bại: chúng đòi khách vào portal riêng để báo hỏng.
```

**Một mâu thuẫn đã phát hiện và đã xử lý trong lúc làm bài:**

```text
Phương án ban đầu là "chỉ quản lý được ghi và đóng vụ". Khi bị hỏi ngược "nếu chỉ mình anh
được ghi, thì lúc anh bận ai ghi?" thì lộ ra mâu thuẫn: bottleneck đúng là "khách nhắn lúc
quản lý đang bận thì trôi", nên nếu chỉ quản lý được ghi thì vụ vẫn trôi y như cũ. Cái bảng
khi đó chỉ đổi chỗ chứa trí nhớ chứ không sửa được nguyên nhân gốc.

Cách xử lý đã chốt — TÁCH QUYỀN GHI NHẬN KHỎI QUYỀN QUYẾT ĐỊNH:
- Quyền ghi nhận: mở cho quản lý, sale và thợ. Ai nhận được tin của khách trước thì ghi.
- Quyền phân thợ và đóng vụ: vẫn chỉ quản lý, vì đó là quyết định chứ không phải ghi chép.

Vì sao cách này đúng: chỗ rơi việc nằm ở khâu GHI, còn thứ cần kiểm soát lại nằm ở khâu
QUYẾT. Gộp hai thứ vào một người là vừa không bịt được chỗ hở, vừa không thêm được gì cho
việc kiểm soát.

Ghi chú: đây là bài học trùng với Problem Card #3 trong phần scan cá nhân của tôi — ở đó
sale phải hỏi lại quản lý 2-5 lần/tuần cũng vì quản lý giữ hết quyền quyết mức giảm giá.
Hai bài khác nhau nhưng cùng một gốc: chỗ nào một người giữ hết quyền, chỗ đó thành nút cổ chai.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Quản lý một tòa cho thuê 30-60 phòng (giá dưới 3 triệu/phòng, đang lấp đầy 100%), là người duy nhất điều phối việc sửa chữa cho 2 thợ kỹ thuật. Người chịu ảnh hưởng gồm cả khách thuê đang chờ sửa và chính quản lý bị ngắt quãng công việc. |
| **Workflow** | 6 bước: khách báo hỏng qua 1 trong 3 kênh (Zalo riêng, gọi điện, nhóm Zalo chung) → quản lý đọc và tự ghi nhớ → quản lý phân việc cho 1 trong 2 thợ → thợ đi sửa → thợ nhắn báo xong → quản lý báo lại khách và đóng vụ. Lặp 5-15 lần/tháng, không theo lịch cố định, có vụ báo lúc tối hoặc cuối tuần. |
| **Bottleneck** | Bước 2 — khâu nhận và ghi nhận yêu cầu, KHÔNG phải khâu thi công. Ba kênh đổ về một người mà không có chỗ ghi nhận tập trung; cuộc gọi không để lại dấu vết văn bản nào để tìm lại. Bằng chứng khâu thi công không lỗi: thợ luôn nhắn báo lại ngay khi xong. Vụ bị trôi là vụ chưa bao giờ tới tay thợ. |
| **Impact** | CÓ BẰNG CHỨNG: 15-30 phút/vụ x 5-15 vụ/tháng = 1,5-7,5 tiếng/tháng (~18-90 tiếng/năm) quản lý tốn chỉ để làm trung gian; khách chờ 1-3 ngày; thỉnh thoảng phải nhắc lần 2. ĐÃ LOẠI BỎ: giả định "sửa chậm làm mất khách, mỗi khách đi mất 1,5-3 triệu" — vì thực tế khách mới chỉ càu nhàu nhẹ, chưa có ai trả phòng vì lý do này. Không có bằng chứng thì không được đưa vào lập luận. |
| **Success Metric** | (1) Số vụ khách phải nhắc lần 2: "thi thoảng" → 0 vụ/tháng. (2) Thời gian từ lúc khách báo tới lúc thợ nhận việc: chưa đo → dưới 2 tiếng. (3) Thời gian quản lý tốn mỗi vụ: 15-30 phút → dưới 10 phút. CÁCH LẤY BASELINE (chưa có, phải làm trước): đếm lại lịch sử chat Zalo 1 tháng gần nhất để ra số vụ bị nhắc lần 2; ghi 2 mốc giờ (giờ khách báo, giờ phân thợ) cho mọi vụ trong 2 tuần tới. |
| **Boundary** (làm / không làm) | LÀM: một bảng theo dõi duy nhất có cột trạng thái Mới / Đã phân thợ / Đang sửa / Xong; mở quyền GHI NHẬN cho cả quản lý, sale và thợ; tự động đẩy vụ quá hạn lên đầu bảng. KHÔNG LÀM: không ép khách đổi kênh báo hỏng (giữ nguyên cả 3 kênh); quyền phân thợ và quyền đóng vụ chỉ quản lý; không tự hứa thời hạn sửa với khách; không đóng vụ khi chưa có xác nhận; không đụng tới khâu thi công của thợ. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | **KHÔNG CÓ điểm can thiệp AI nào trong phương án được chọn.** Nếu sau này vẫn muốn thử thì điểm duy nhất hợp lý là ngay sau bước 1 và trước bước 2: AI đọc luồng tin nhắn Zalo, nhận ra đâu là tin báo hỏng, trích ra "phòng số mấy + hỏng gì" rồi đẩy vào bảng. Chỉ được xét tới khi bảng theo dõi đã chạy ổn định mà vẫn còn vụ bị trôi. **Và khi đó bắt buộc phải có ngưỡng độ tin cậy: tin nào AI không chắc thì gắn cờ "cần người xem", tuyệt đối không được im lặng bỏ qua — vì im lặng bỏ qua chính là painpoint gốc của bài này.** |
| **Mức chọn** (Rule + 1 câu vì sao) | **Rule — chính xác hơn là No AI / process fix.** Vì cái thiếu ở đây là một chỗ để ghi chứ không phải một bộ óc để suy nghĩ: bài toán nằm ở ô "mơ hồ thấp, phức tạp thấp" của ma trận, và một bảng Google Sheets có cột trạng thái đã chạm đúng nguyên nhân gốc với chi phí gần bằng không. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | RỦI RO LỚN NHẤT: bảng không được cập nhật đều → thành bảng sai, nhìn vào tưởng hết việc tồn trong khi thực tế còn. Bảng sai nguy hiểm hơn không có bảng. RỦI RO THỨ HAI (lý do không dùng AI): nếu AI ghi sót một tin báo hỏng thì người phát hiện đầu tiên lại là khách khi họ nhắc lần 2 — đúng kiểu lỗi mà bài toán này sinh ra để diệt. NGƯỜI KIỂM TRA: quản lý, mỗi sáng mở bảng soát các vụ trạng thái "Mới" và các vụ quá hạn; cuối tuần đối chiếu bảng với nhóm Zalo chung xem có vụ nào khách báo mà chưa lên bảng không. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | **Yes** | Actor là quản lý tòa 30-60 phòng, workflow 6 bước có đủ actor, input, output, thời gian và 2 điểm handoff. Bottleneck chỉ được đúng một bước là bước 2. |
| Baseline + metric đo được chưa? | **Not Yet** | Đây là chỗ yếu nhất của bài. Metric đã định nghĩa được và có cách đo, nhưng baseline hiện mới là "thi thoảng có vụ bị trôi" — đó chưa phải một con số. Không có baseline thì sau này không chứng minh được là có cải thiện hay không. |
| Data/input đủ dùng chưa? | **Not Yet** | Dữ liệu để lấy baseline thì đã có sẵn và không tốn chi phí: lịch sử chat Zalo 1 tháng gần nhất. Nhưng chưa ai ngồi đếm. Riêng phần khách gọi điện thì không có dấu vết văn bản nên baseline sẽ hụt một phần, phải chấp nhận. |
| AI sai, hậu quả chấp nhận được không? | **Không áp dụng — và chính là lý do loại AI** | Phương án được chọn không dùng AI. Nếu có dùng thì hậu quả KHÔNG chấp nhận được: AI ghi sót một tin báo hỏng thì người phát hiện đầu tiên là khách khi họ nhắc lần 2, đúng kiểu lỗi mà bài toán này sinh ra để diệt. |
| Có người review/owner không? | **Yes** | Quản lý là owner: mỗi sáng soát các vụ trạng thái "Mới" và các vụ quá hạn; cuối tuần đối chiếu bảng với nhóm Zalo chung. Quyền phân thợ và đóng vụ cũng chỉ quản lý. |
| Có cách non-AI đơn giản hơn không? | **Yes — và đó chính là phương án được chọn** | Một bảng Google Sheets có cột trạng thái, cộng với việc mở quyền ghi nhận cho sale và thợ. Chi phí gần bằng không, làm xong trong một buổi, cả nhà đã quen Excel nên không cần đào tạo. |

**Decision:**

```text
Not Yet — chưa chốt Go, phải đếm baseline trong 2 tuần rồi mới quyết.
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Bài toán đã rõ ở gần hết mọi mặt: actor rõ, workflow 6 bước vẽ được, bottleneck chỉ đúng
một bước, nguyên nhân gốc nói được bằng một câu, và giải pháp thì rẻ và ít rủi ro.

Nhưng có đúng một chỗ chưa đạt, và nó lại là chỗ quan trọng: baseline. Hiện tôi mới chỉ nói
được "thi thoảng có vụ bị trôi" chứ chưa đếm được số thật. Nếu chốt Go ngay bây giờ thì một
tháng sau tôi sẽ không có cách nào chứng minh cái bảng có tác dụng hay không — mà đúng kiểu
lỗi này thì rất dễ tự huyễn hoặc là đã tốt lên.

Quan trọng hơn, chi phí để có baseline gần bằng không: dữ liệu đã nằm sẵn trong lịch sử
chat Zalo, chỉ cần ngồi đếm. Khi một việc rẻ như vậy mà chưa làm thì chưa có lý do gì để
bỏ qua nó và nhảy thẳng sang triển khai.

Chọn Not Yet ở đây không phải vì bài toán yếu, mà vì bằng chứng chưa đủ chặt.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
(Áp dụng ngay sau khi có baseline. Pilot này chạy tay hoàn toàn, không cần công cụ mới.)

Data: lịch sử chat Zalo 1 tháng gần nhất + toàn bộ vụ báo hỏng phát sinh trong 1 tháng thử.
Chạy tay: 1 file Google Sheets đúng 6 cột — Ngày giờ khách báo / Phòng / Hỏng gì / Người ghi
/ Thợ được phân / Trạng thái. Quản lý, sale và thợ đều được ghi vào. Không tự động hóa gì cả
ở giai đoạn này.
Đo đúng 3 số: (1) số vụ khách phải nhắc lần 2, (2) số phút trung bình từ lúc khách báo tới
lúc thợ nhận việc, (3) số vụ khách báo mà KHÔNG được ghi lên bảng — số thứ ba quan trọng
nhất vì nó đo xem thói quen ghi có thật sự hình thành hay không.
```

**Nếu Not Yet — cần validate gì trước:**

```text
Đây là nhánh đang chọn. Ba việc phải làm trong 2 tuần, đều không tốn chi phí:

1. Lấy baseline quá khứ: mở lại lịch sử chat Zalo (nhóm chung + tin nhắn riêng) của 1 tháng
   gần nhất, đếm số lần khách phải nhắn nhắc lại lần 2 về cùng một vụ hỏng. Dữ liệu có sẵn,
   chỉ cần ngồi đếm.
2. Lấy baseline hiện tại: trong 2 tuần tới, mỗi lần nhận báo hỏng thì ghi lại 2 mốc giờ —
   giờ khách báo và giờ thợ nhận việc.
3. Phỏng vấn 1 sale và 2 thợ. Toàn bộ bằng chứng hiện tại là tự quan sát của đúng một người,
   trong khi lab yêu cầu tối thiểu 2-3 người. Câu cần hỏi: có bao giờ khách báo hỏng trực
   tiếp với họ không, và lúc đó họ làm gì với thông tin đó — câu trả lời quyết định việc mở
   quyền ghi nhận cho họ có thật sự bịt được chỗ hở hay không.

Ba việc này cho ra con số thật cho cả 3 metric. Có số rồi mới quyết Go hay không.

Ngoài ra còn một giả định chưa kiểm: tôi cho rằng vụ bị trôi là do không có chỗ ghi. Nhưng
cũng có thể có vụ đã ghi rồi mà vẫn quên phân thợ. Việc ghi 2 mốc giờ ở trên sẽ phân biệt
được hai trường hợp này, và nếu là trường hợp sau thì giải pháp phải khác.
```

**Nếu No-Go — làm gì thay AI:**

```text
Không chọn nhánh này, nhưng nếu sau khi đếm mà baseline cho thấy số vụ bị trôi thực ra rất
nhỏ (ví dụ dưới 1 vụ/tháng) thì kết luận đúng phải là No-Go với cả cái bảng theo dõi.

Khi đó việc nên làm thay là thứ rẻ hơn nữa: đặt một quy ước duy nhất là mọi vụ báo hỏng
đều phải có ít nhất 1 tin nhắn trong nhóm Zalo chung, kể cả khi khách gọi điện thì quản lý
tự nhắn lại một câu vào nhóm. Như vậy mọi vụ đều có dấu vết tìm lại được mà không cần thêm
bất cứ công cụ nào.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Phương án được chọn không có AI, nên đây là điều kiện dừng cho chính cái bảng theo dõi:

- Nếu sau 1 tháng mà có trên 30% số vụ khách báo không được ghi lên bảng, thì dừng. Một cái
  bảng chỉ đúng một phần còn nguy hiểm hơn không có bảng: nhìn vào tưởng hết việc tồn trong
  khi thực tế vẫn còn vụ đang trôi ở ngoài.
- Nếu sau 1 tháng số vụ khách nhắc lần 2 không giảm so với baseline, thì giả định ban đầu
  sai — vấn đề không nằm ở chỗ ghi nhận — và phải quay lại vẽ lại workflow chứ không phải
  cố sửa cái bảng.
- Khi dừng thì quay về cách cũ nhưng giữ lại đúng một thứ đã chứng minh là rẻ và có ích:
  quy ước mọi vụ phải có 1 tin nhắn trong nhóm Zalo chung để còn tìm lại được.

Về sau nếu có đưa AI vào bước trích yêu cầu thì điều kiện dừng là: chỉ cần AI ghi sót 1 vụ
mà khách phải nhắc lần 2, là bỏ, vì đó đúng là lỗi bài toán này sinh ra để diệt.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score) — **đủ 15 candidate, có cluster, shortlist và score. Còn thiếu: cột "cảm nhận nhanh của nhóm" và ô Disagreement**
- [x] Có validation (quote thật) + research (link kiểm được) — **research đủ 3 nguồn có link. Validation có quote thật nhưng mới từ 1 người trong cuộc; cần phỏng vấn thêm 1 sale + 2 thợ**
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do

> **Ba việc còn lại trước khi nộp:**
> 1. Chốt mâu thuẫn độ mơ hồ Thấp/Cao giữa file này và `Báo cáo giải pháp AI` (xem ghi chú ở đầu file và ở mục 6.0).
> 2. Điền cột "Cảm nhận nhanh của nhóm" ở mục 3.1 và ô Disagreement ở mục 3.4.
> 3. Phỏng vấn 1 sale + 2 thợ, và đếm baseline từ lịch sử chat Zalo.
