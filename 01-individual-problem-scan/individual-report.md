# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Trần Thị Thuý
- Mã học viên: 2A202602960
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): CEO doanh nghiệp SME bán lẻ nội thất nhập khẩu, quy mô ~50 nhân sự (phòng kinh doanh 30 người, phòng kế toán 5 người trong đó 2 kế toán bán hàng). Mô hình đặc thù: khách đặt hàng sớm và nhận hàng ở các mốc thời gian khác nhau (từ lấy ngay đến 3 tháng, 1–2 năm), không giao ngay.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Đọc dữ liệu báo cáo và chỉ số của các phòng ban → xác định điểm nghẽn → họp ra phương án tối ưu.
  - Nghiên cứu thị trường và đối thủ, tìm ý tưởng kinh doanh mới (chu kỳ 1 tháng/lần, khung SWOT / PESTEL).
  - Duyệt phương án vận hành, xử lý các điểm nghẽn liên phòng ban.
  - Quan sát trực tiếp workflow phòng kế toán bán hàng — nơi phát sinh phần lớn các problem trong bảng scan dưới đây.
- Công cụ đang dùng trong doanh nghiệp: MISA (CRM + kế toán), Excel, email.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại + Tốn thời gian | Kế toán bán hàng tải 3 file từ MISA (tồn kho, bán hàng, mua hàng) rồi vlookup, đối chiếu, sắp xếp lại thành bảng mã hàng × mã kho có phân trạng thái, sau đó đẩy lên CRM | 2 kế toán bán hàng | 30 phút mỗi ngày làm việc, cố định 17:30–18:00. Tách bước: **5 phút** tải 3 file, **15 phút** copy + vlookup giữa các file để ra file chuẩn (thao tác giống hệt nhau, lặp mỗi ngày), **~10 phút** còn lại gán trạng thái + sắp xếp + đẩy CRM → ~13 giờ/tháng |
| 2 | Pain từ người khác | Bảng chỉ note trạng thái nên không trả lời thẳng được "mã này bán được không". Sale phải tự lọc và tự check; ai không chắc thì quay sang hỏi trực tiếp kế toán bán hàng, biến 1 người thành điểm hỏi duy nhất cho cả phòng | 30 nhân viên kinh doanh **và** 1 kế toán bán hàng bị hỏi | Lặp lại mỗi lần chào bán một mã đang nợ. Người trong công ty mô tả bảng là "rất phức tạp khi nhìn". 30 sale thay phiên nhau hỏi một bạn kế toán → thời gian bạn ấy bị cắt vụn rải rác cả ngày, không chỉ 30 phút cuối giờ. Số lần hỏi/ngày và thời gian mỗi lần: **chưa đo — ưu tiên số 1 phải đo ở Phase 4** |
| 3 | Pain từ người khác | Sale chỉ có dữ liệu tồn đáng tin sau khi bảng lên CRM cuối giờ chiều | 30 nhân viên kinh doanh | Bảng phát hành 18:00. Hệ quả đã xảy ra: bán trúng hàng đã có chủ hoặc hứa giao rồi không giao được, tần suất ~2–3 tháng 1 lần |
| 4 | Lặp lại | Mỗi lần khách đổi mẫu hoặc số lượng, đơn phải chạy lại vòng: kế toán mở khoá → sale sửa → sale đề nghị lại → kế toán duyệt → gửi email ghi log | Kế toán bán hàng + sale | ~30/100 đơn mỗi tháng bị đổi, mỗi lần ~20 phút **tính cả thời gian chờ duyệt** → ~10 giờ/tháng. Chủ yếu đổi mẫu và đổi số lượng |
| 5 | Pain từ người khác | Sale đã đổi đơn nhưng kế toán quên ấn duyệt và nhập vào phần mềm kế toán → dữ liệu hai bên lệch nhau | Kế toán, sale, kho, và khách hàng cuối | Đã xảy ra và **đã dẫn tới thiếu hàng đúng ngày hẹn giao cho khách**. Tần suất: **chưa đo** → đưa vào Phase 4 |
| 6 | Tốn thời gian | Chốt doanh số phải áp hệ số thủ công theo chương trình riêng của từng tháng, đồng thời kiểm điều kiện cọc đủ 30% và điều kiện giao đủ – thu đủ | 1 kế toán bán hàng + 30 sale | Chốt 1 lần/tuần; riêng khâu đối chiếu mất **5 ngày mỗi tháng, 1 người làm ≈ 40 giờ/tháng** |
| 7 | Tốn thời gian + Pain từ người khác | Bảng doanh số của sale và của kế toán thường xuyên lệch, phải check chéo từng dòng | Kế toán bán hàng + 30 sale | Nằm trong 5 ngày/tháng nói trên. Số dòng lệch mỗi kỳ: **chưa đo** |
| 8 | Lặp lại | Đơn bị huỷ hoặc hoàn cọc phải truy ngược trừ doanh số ký đã chốt ở tháng trước | Kế toán bán hàng | Xảy ra đều đặn do chu kỳ giao hàng kéo dài tới 1–2 năm. Số đơn huỷ/tháng: **chưa đo** |
| 9 | Pain từ người khác | Kế toán gọi/nhắn nhắc từng khách đến hạn nhận hàng bằng tay, dựa trên ngày chứng từ tương lai trên MISA | Kế toán bán hàng + khách hàng | ~10% đơn sai hẹn hoặc bị sót trên ~100 đơn/tháng ≈ 10 đơn. Nguyên nhân gồm cả sót nội bộ lẫn đối tác giao chậm |
| 10 | Tốn thời gian | CEO phải tải file báo cáo của các phòng ban về xử lý lại, vì phần mềm không xuất đủ các góc nhìn cần xem | CEO (bản thân) | Xảy ra hằng tuần. Thời gian mỗi lần: **chưa bấm giờ** |
| 11 | Lặp lại + AI có thể tốt hơn | Nghiên cứu thị trường và đối thủ theo khung SWOT/PESTEL cố định, nhưng mỗi kỳ phải gom lại dữ liệu mới từ đầu | CEO (bản thân) | 1 lần/tháng. Format ổn định, phần biến động chỉ là dữ liệu đầu vào |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: dùng Claude Code phỏng vấn theo 4 lăng kính của worksheet — yêu cầu AI đặt câu hỏi chi tiết về workflow phòng kế toán bán hàng (ai làm, mấy bước, mất bao lâu, hậu quả nếu trễ), không cho AI tự nghĩ problem thay. Sau đó yêu cầu AI quy mọi dấu hiệu về cùng đơn vị giờ/tháng để so sánh impact giữa các problem.
- Ý dùng được: cách tách công việc kế toán bán hàng thành 4 cụm (tồn kho / đổi đơn / doanh số / theo dõi ngày giao) để thấy 4 cụm này có bản chất khác nhau chứ không phải một vấn đề chung; và việc ép bấm giờ tách bước trong 30 phút làm bảng tồn kho, nhờ đó mới lộ ra bottleneck thật.
- Ý bỏ vì không phải pain thật — **hai giả thuyết của AI đều sai một phần**:
  1. AI cho rằng cụm "đặt sớm – lấy hàng nhiều mốc" là chỗ nghẽn nặng nhất vì phần mềm không quản được. Thực tế MISA đã có ngày chứng từ tương lai, tiền cọc khớp với mã đơn ở mức cao, và 10% sai hẹn phần lớn do đối tác giao chậm — đó là vấn đề nhà cung cấp, không phải vấn đề công cụ. Tôi hạ giả thuyết này xuống ưu tiên thấp.
  2. AI cho rằng MISA không có sẵn báo cáo tồn đa trạng thái. Thực tế MISA **có** dữ liệu; cái thiếu là lớp hiển thị dễ đọc và lớp quy tắc quyết định "có được mượn hàng đang nợ khách khác hay không". Đây là khác biệt quan trọng: bài toán không phải thiếu dữ liệu, mà là dữ liệu thô chưa trả lời được câu hỏi mà người bán hàng thực sự hỏi.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính (dùng đủ cả 4)
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | #1 + #2 + #3 — Bảng tồn kho không trả lời được câu hỏi "có bán được không" | Actor rõ ở cả hai đầu: 2 kế toán bán hàng làm ra bảng, 30 nhân viên kinh doanh dùng bảng. Workflow 6 bước vẽ được ngay và đã bấm giờ tách được bước (5 phút tải, 15 phút copy/vlookup, ~10 phút gán trạng thái). Tách ra mới thấy có hai tầng nghẽn khác bản chất: 20 phút thao tác cơ học lặp y hệt mỗi ngày, và một quy tắc quyết định chưa ai viết ra — hàng đang nợ khách A có được mượn giao cho khách B trước không | Chưa đo số lần 30 sale hỏi kế toán mỗi ngày và thời gian mỗi lần — đây đang là phần impact lớn nhất của bài mà lại hoàn toàn chưa có số. Tần suất lỗi bán trúng hàng đã có chủ chỉ ~2–3 tháng/lần, một mình nó chưa đủ làm nên impact |
| 2 | #6 + #7 + #8 — Chốt doanh số tháng và đối chiếu lệch số | Impact đo được lớn nhất cả bảng: 5 ngày/tháng của 1 người ≈ 40 giờ/tháng. Ảnh hưởng trực tiếp tới thu nhập của 30 sale nên mức độ nhạy cảm cao. Là bài duy nhất có chỗ cho AI thật, vì quy tắc hệ số nằm trong văn bản chương trình thay đổi theo từng tháng | Chưa đếm số dòng lệch mỗi kỳ, nên chưa biết lệch số là do quy tắc khó hay do nhập liệu sai. Phạm vi rộng: gồm cả quy tắc hệ số, hai mốc ghi nhận, và xử lý đơn huỷ truy ngược |
| 3 | #4 + #5 — Vòng đổi thông tin đơn hàng | Tần suất cao và đã có số: 30/100 đơn/tháng, 20 phút/lần. Có hậu quả thật đã xảy ra chứ không chỉ là chậm: quên duyệt dẫn tới thiếu hàng đúng ngày hẹn giao khách | Chưa tách được trong 20 phút thì bao nhiêu là thao tác và bao nhiêu là chờ duyệt. Chưa đo tần suất quên duyệt, trong khi đây mới là phần rủi ro nhất |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Bảng tồn kho không trả lời được câu hỏi "mã này có bán được không"

```text
Problem 1 câu:
Kế toán bán hàng mất 30 phút mỗi chiều để tải 3 file MISA và vlookup thành một bảng tồn
kho theo mã hàng × mã kho, nhưng bảng đó vẫn không trả lời thẳng được câu hỏi duy nhất mà
30 nhân viên kinh doanh cần — "mã này tôi bán cho khách trước mặt được không" — nên mỗi
người vẫn phải tự tra xem hàng trong kho đang nợ ai, hẹn giao ngày nào, và có lô sắp về
kịp bù không.

Actor:
Người làm ra bảng: 2 kế toán bán hàng (trong phòng kế toán 5 người).
Người dùng bảng và chịu hậu quả: 30 nhân viên kinh doanh.

Thời điểm / bối cảnh:
Bảng được dựng 17:30–18:00 mỗi ngày làm việc rồi đẩy lên CRM. Nhân viên kinh doanh tra
bảng này mỗi lần chào bán một mã hàng, tức là nhiều lần trong ngày.

Current workflow 3-7 bước:
1. Tải 3 file từ MISA: tồn kho hiện tại, bán hàng cho khách, mua hàng vào (5 phút)
2. Copy và vlookup giữa 3 file để ra file chuẩn — chuỗi thao tác giống hệt nhau, lặp
   lại đúng như vậy mỗi ngày làm việc (15 phút)
3. Sắp xếp lại thành bảng: mã hàng là dòng, mã kho là cột
4. Gán trạng thái cho từng ô: có sẵn ở kho nào / đang nợ khách ở kho nào kèm ngày hẹn
   giao / hàng sắp về kho nào kèm ngày về dự kiến, mỗi lô một ngày khác nhau
5. Đẩy bảng lên CRM cho phòng kinh doanh (bước 3-5 còn lại ~10 phút)
6. Mỗi nhân viên kinh doanh tự lọc bảng và tự check xem có bán được hay không
7. Ai không chắc thì hỏi trực tiếp kế toán bán hàng; kế toán dừng việc đang làm để tra hộ
   — bước 6 và 7 bị đẩy ra ngoài quy trình và chưa ai đo bao giờ

Bottleneck:
Workflow này có hai tầng nghẽn khác hẳn bản chất, và cần tách ra thì mới chọn đúng giải pháp.

Tầng 1 — thao tác cơ học lặp lại (bước 1-2, 20 phút/ngày). Tải 3 file rồi copy, vlookup
giữa chúng để ra file chuẩn. Chuỗi thao tác này giống hệt nhau mỗi ngày làm việc, không có
gì phải suy nghĩ, và chiếm 2/3 tổng thời gian. Đây là phần máy làm được 100%.

Tầng 2 — bảng dừng ở mức nguyên liệu, không phải câu trả lời (bước 4 và bước 6). Kế toán
chỉ note được: mã này đang nợ khách nào, dự kiến giao ngày nào, lô nào sắp về ngày nào.
Từ mớ note đó, muốn biết một mã có bán được cho khách trước mặt hay không thì phải so ngày
hẹn giao của khách đang nợ với ngày lô hàng sắp về — tức là mượn hàng của khách giao sau để
giao cho khách cần trước. Quy tắc này không được viết ra ở đâu và không được tính sẵn, nên
việc lọc và check bị đẩy ra ngoài quy trình rồi nhân lên 30 lần: 30 nhân viên kinh doanh
mỗi người tự lọc, tự check và tự kết luận trên cùng một bảng.

Hệ quả trực tiếp của tầng 2: vì không ai tự check chắc được, 30 nhân viên kinh doanh thay
phiên nhau hỏi một bạn kế toán bán hàng. Bạn ấy trở thành điểm hỏi duy nhất của cả phòng
kinh doanh, nên thời gian bị cắt vụn rải rác suốt ngày làm việc — đây mới là phần tốn kém
nhất, và là phần chưa từng được đo.

Tầng 1 tốn 20 phút cố định mỗi ngày; tầng 2 vừa gây ra lỗi hứa sai với khách, vừa ăn mòn
thời gian của kế toán theo cách không ai nhìn thấy trên bảng chấm công.

Impact:
- Chi phí nhìn thấy được — kế toán dựng bảng: 30 phút/ngày × ~26 ngày = ~13 giờ/tháng.
- Chi phí ẩn, và nhiều khả năng lớn hơn — kế toán bị hỏi: 30 nhân viên kinh doanh thay
  phiên nhau hỏi cùng một người suốt ngày làm việc. Mỗi lần hỏi không chỉ mất thời gian
  tra mà còn cắt đứt mạch việc đang làm. Số lần hỏi/ngày: chưa đo.
- Chi phí phía kinh doanh: 30 người phải tự lọc một bảng được mô tả là "rất phức tạp khi
  nhìn", hoặc phải chờ kế toán rảnh mới hỏi được. Thời gian mỗi lần: chưa đo.
- Hậu quả đã xảy ra: bán trúng hàng đã có chủ hoặc hứa giao rồi không giao được, tần suất
  ~2-3 tháng 1 lần. Mỗi lần như vậy là một khách đã ký hợp đồng bị thất hứa.

Success metric:
- Hiện trạng: 30 phút/ngày dựng bảng (5 tải + 15 copy/vlookup + ~10 note trạng thái);
  bảng lên CRM lúc 18:00; 30 nhân viên kinh doanh tự lọc, ai không chắc thì hỏi kế toán;
  số lần hỏi/ngày chưa đo; lỗi hứa sai ~2-3 tháng/lần.
- Mục tiêu: dưới 5 phút/ngày cho kế toán; và có một chỗ duy nhất để tra — hỏi một mã thì
  hệ thống tự check chéo 3 nguồn và trả về số cuối: bán được bao nhiêu ngay bây giờ, bán
  được thêm bao nhiêu nếu hẹn giao sau ngày X. Kế toán và kinh doanh dùng chung đúng con
  số đó, không ai phải tự lọc lại.
- Metric chính: **số lần kinh doanh phải hỏi kế toán về khả năng bán của một mã, mỗi ngày**
  — mục tiêu đưa về gần 0, vì mỗi lần hỏi là một lần hệ thống không trả lời được thay người.
- Cách đo: cho kế toán gạch đầu dòng mỗi lần bị hỏi trong 5 ngày liên tiếp, ghi kèm thời
  gian mỗi lần; bấm giờ khâu dựng bảng 5 ngày trước và sau; bấm giờ 10 lần một nhân viên
  kinh doanh tra một mã đang nợ, trước và sau.
- Metric giữ chất lượng: số lần hứa sai với khách không tăng so với mức nền 2-3 tháng/lần;
  số lần kế toán và kinh doanh hiểu khác nhau về khả năng bán của cùng một mã = 0.

Non-AI alternative:
MISA đã có sẵn cả 3 nguồn dữ liệu, nên đây không phải bài toán thiếu dữ liệu.
1. Viết quy tắc mượn hàng thành công thức. Quy tắc này có tên chuẩn trong ngành là
   cumulative available-to-promise with look-ahead: với mỗi mã × kho, chỉ cho phép mượn
   phần đang nợ khách A nếu lượng hàng về tích luỹ từ nay đến ngày hẹn của A đủ bù lại.
   Lưu ý công thức ATP cơ bản (trừ thẳng toàn bộ phần đã cam kết) là SAI với mô hình này —
   nó sẽ báo hết hàng cho một mã thực tế vẫn giao được, tức tự chặn cơ hội bán.
2. Dùng Power Query hoặc script để tự gộp 3 file và tính sẵn cột kết luận đó.
3. Thiết kế lại đầu ra: thay vì phát hành một ma trận để 30 người tự lọc, dựng một điểm
   tra duy nhất trả về số cuối cho từng mã. Đây là thay đổi quan trọng nhất — nó chuyển
   đầu ra từ nguyên liệu thành câu trả lời, và bỏ được việc 30 người cùng làm lại một
   phép tính.

AI hypothesis:
Thấp. Quy tắc look-ahead nhiều bước và phải duyệt qua từng mốc ngày, nhưng vẫn hoàn toàn
xác định: cùng một bộ dữ liệu và cùng một biên an toàn thì chỉ có một đáp án đúng. Theo ma
trận độ phù hợp, đây là ô độ mơ hồ thấp × độ phức tạp cao — tức là Workflow điều phối nhiều
bước rõ ràng, chưa cần đến Agent. Việc bài toán phức tạp hơn dự kiến không đẩy nó lên mức
Agent, vì không có chỗ nào cần AI tự lập kế hoạch hay tự chọn bước tiếp theo.
Chỗ duy nhất AI có thể thêm giá trị là lớp hỏi đáp bằng ngôn ngữ tự nhiên ở trên cùng —
sale gõ "mã X còn bán được cho khách lấy tháng 12 không" thay vì phải nhập đúng mã và đúng
mốc ngày. Nhưng cần phân biệt rõ: cái sale cần là MỘT CHỖ ĐỂ HỎI, không nhất thiết là AI.
Một ô tra cứu thường trên CRM cũng giải quyết được, và rẻ hơn nhiều. AI chỉ đáng thêm nếu
sau khi đo thấy sale thực sự vướng ở khâu diễn đạt câu hỏi, chứ không phải vướng ở việc
không có câu trả lời.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 30 phút/ngày (17:30–18:00) + phần việc ẩn của 30 sale

[1 Tải 3 file MISA: 5']
→ [2 Copy + vlookup giữa 3 file để ra file chuẩn: 15']
     <-- nghẽn tầng 1: thao tác giống hệt nhau, lặp mỗi ngày, máy làm được 100%
→ [3 Sắp xếp thành ma trận mã hàng × mã kho]
→ [4 Gán trạng thái: sẵn / nợ khách + ngày giao / sắp về + ngày về]
→ [5 Đẩy lên CRM]                                  (bước 3-5 = ~10')
→ [6 Mỗi sale tự lọc + tự check: hàng này nợ ai, hẹn bao giờ, mượn được không]
→ [7 Không chắc → hỏi thẳng kế toán → kế toán dừng việc để tra hộ]
     <-- nghẽn tầng 2: 1 kế toán là điểm hỏi duy nhất cho 30 sale,
         thời gian bị cắt vụn cả ngày, chưa ai đo

FUTURE STATE — mục tiêu dưới 5 phút/ngày

[1 Script tự tải + copy/vlookup 3 nguồn MISA theo đúng chuỗi thao tác hiện tại: 0']
     ^ xoá thẳng 20 phút/ngày của tầng 1
→ [2 Rule tính khả dụng theo mốc thời gian (cumulative ATP with look-ahead):
      KHÔNG hỏi "còn lại bao nhiêu" mà hỏi "nếu mượn phần đang nợ khách A
      thì từ nay tới ngày hẹn của A, hàng về có đủ bù lại không"
      → ra số lượng bán được theo từng mốc giao]
→ [3 MỘT chỗ duy nhất để hỏi: nhập mã hàng → hệ thống tự check chéo 3 nguồn
      → trả về SỐ CUỐI: bán được bao nhiêu ngay, bao nhiêu nếu giao sau ngày X]
→ [4 Kế toán bán hàng kiểm ngoại lệ: mã mới, lô đổi ngày về, hàng lỗi: ~3']
     <-- human boundary
→ [5 Sale đọc thẳng số cuối, không tự lọc, không tự check, KHÔNG phải hỏi kế toán
      → kế toán và kinh doanh thống nhất trên cùng một con số]
      ^ bước 7 của quy trình cũ biến mất hoàn toàn — đây mới là phần tiết kiệm lớn nhất

Boundary: hệ thống chỉ áp dụng quy tắc, không đặt ra quy tắc. Ba tham số sau do người
quyết và người duyệt, không để công thức tự chọn:
  - biên an toàn bao nhiêu ngày trước hạn giao mới dám mượn (vì ~10% lô về trễ)
  - đơn nào bị cấm mượn (khách VIP, đơn đã cam kết cứng)
  - ai được duyệt ngoại lệ
Mọi ca ngoại lệ (mã mới, hàng lỗi, lô đổi ngày về) vẫn do kế toán quyết.
Fallback: nếu MISA đổi format file xuất hoặc script sai, kế toán quay lại quy trình
vlookup tay 30 phút như hiện nay — không ngày nào phòng kinh doanh mất bảng.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Chốt doanh số tháng và đối chiếu lệch số

```text
Problem 1 câu:
Mỗi tháng một kế toán bán hàng mất trọn 5 ngày làm việc để áp hệ số theo chương trình
riêng của từng tháng, kiểm hai mốc ghi nhận khác nhau, và đối chiếu từng dòng lệch với
bảng doanh số do sale tự lập.

Actor:
1 kế toán bán hàng làm khâu chốt. Bên chịu ảnh hưởng: 30 nhân viên kinh doanh, vì doanh
số quyết định thu nhập của họ.

Thời điểm / bối cảnh:
Chốt 1 lần/tuần, nhưng khâu đối chiếu dồn lại và ngốn 5 ngày mỗi tháng. Nặng nhất ở kỳ có
nhiều đơn giao và nhiều đơn huỷ hoặc hoàn cọc.

Current workflow 3-7 bước:
1. Lọc các đơn phát sinh trong kỳ từ MISA
2. Xác định mốc ghi nhận cho từng đơn: doanh số ký (tính từ thời điểm cọc đủ 30%) hay
   doanh số giao (giao hàng hoàn thiện và thu đủ tiền)
3. Áp hệ số cho từng đơn: có đúng chương trình của tháng đó không, có cắt máu không, có
   phải trả hoa hồng cho đối tác bên ngoài không
4. Đối chiếu bảng kế toán với bảng do sale tự lập, truy từng dòng lệch
5. Xử lý đơn huỷ / hoàn cọc: truy ngược trừ doanh số ký đã chốt ở tháng trước
6. Chốt và công bố

Bottleneck:
Bước 3 và 4. Quy tắc hệ số thay đổi theo từng tháng và nằm rải trong nhiều quy định nội
bộ, nên không ai áp được nhất quán ngay lần đầu. Hệ quả là bước 4 phải đối chiếu thủ công
từng dòng — và vì sale giữ một bảng riêng, luôn tồn tại hai phiên bản sự thật để lệch nhau.

Impact:
- 5 ngày làm việc mỗi tháng của 1 người ≈ 40 giờ/tháng. Đây là con số lớn nhất trong cả
  bảng scan.
- Lệch số lặp lại tạo tranh chấp giữa sale và kế toán, và làm 30 sale không tin con số
  quyết định thu nhập của chính họ.

Success metric:
- Hiện trạng: 5 ngày/tháng cho khâu áp hệ số và đối chiếu; số dòng lệch mỗi kỳ chưa đếm.
- Mục tiêu: giảm xuống dưới 2 ngày/tháng; số dòng lệch giảm ít nhất 70%.
- Cách đo: đếm số dòng lệch giữa hai bảng trong 4 kỳ liên tiếp, trước và sau; bấm giờ
  tổng thời gian khâu chốt trong 2 tháng.
- Metric giữ chất lượng: số đơn bị áp sai hệ số phát hiện sau khi đã công bố = 0.

Non-AI alternative:
1. Chuẩn hoá quy tắc hệ số thành một bảng điều kiện duy nhất, cập nhật đầu mỗi tháng,
   thay vì để rải trong nhiều quy định.
2. Bỏ cơ chế hai bảng: sale và kế toán cùng đọc một nguồn số duy nhất, sale không lập
   bảng riêng nữa — không còn hai phiên bản thì không còn gì để lệch. Đây có thể là phần
   giải quyết được nhiều nhất mà không cần công nghệ gì.

AI hypothesis:
Đây là bài duy nhất trong top 3 có chỗ cho AI thật. Mỗi tháng chương trình bán hàng được
ban hành dưới dạng văn bản; AI đọc văn bản đó và đề xuất bộ điều kiện áp hệ số để kế toán
duyệt. Việc này là đọc hiểu ngôn ngữ tự nhiên, độ mơ hồ cao, đúng chỗ AI mạnh. Còn khâu
áp số và đối chiếu bắt buộc phải là Rule — tuyệt đối không để AI tự tính tiền cho người
khác.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 5 ngày/tháng, 1 người (~40 giờ)

[1 Lọc đơn trong kỳ từ MISA]
→ [2 Xác định mốc: doanh số ký (cọc đủ 30%) / doanh số giao (giao xong + thu đủ)]
→ [3 Áp hệ số theo chương trình tháng + cắt máu + hoa hồng đối tác]   <-- bottleneck
→ [4 Đối chiếu với bảng sale tự lập, truy từng dòng lệch]             <-- bottleneck
→ [5 Trừ ngược đơn huỷ / hoàn cọc đã ghi nhận ở tháng trước]
→ [6 Chốt và công bố]

FUTURE STATE — mục tiêu dưới 2 ngày/tháng

[1 Lọc đơn trong kỳ: tự động]
→ [2 Rule áp mốc ghi nhận theo điều kiện cọc / giao: tự động]
→ [3 Rule table hệ số của tháng, kế toán duyệt một lần đầu tháng]
     └ AI đọc văn bản chương trình tháng → đề xuất bộ điều kiện   <-- AI ở đây, và chỉ ở đây
→ [4 Hệ thống chỉ bật ra các dòng bất thường, không bắt đối chiếu toàn bộ]
→ [5 Kế toán xử lý dòng ngoại lệ + đơn huỷ truy ngược]           <-- human boundary
→ [6 Chốt trên một nguồn số duy nhất — sale không lập bảng riêng nữa]

Boundary: AI không tính tiền, không chốt doanh số, không quyết hệ số.
AI chỉ đề xuất bộ điều kiện từ văn bản; kế toán duyệt trước khi áp.
Fallback: nếu bộ điều kiện AI đề xuất sai, kế toán nhập tay rule table như hiện nay,
quy trình vẫn chạy được mà không phụ thuộc AI.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Vòng đổi thông tin đơn hàng

```text
Problem 1 câu:
Mỗi lần khách đổi mẫu hoặc đổi số lượng, đơn phải chạy lại toàn bộ vòng mở khoá – sửa –
đề nghị lại – duyệt – gửi email ghi log, mất khoảng 20 phút tính cả thời gian chờ duyệt,
và đã có trường hợp kế toán quên ấn duyệt dẫn tới thiếu hàng đúng ngày hẹn giao khách.

Actor:
Kế toán bán hàng và nhân viên kinh doanh. Người chịu hậu quả cuối cùng: khách hàng đã ký
hợp đồng.

Thời điểm / bối cảnh:
Bất kỳ lúc nào khách đổi ý, trong suốt quãng chờ giao hàng kéo dài từ vài ngày đến 1–2
năm. Chờ càng lâu thì xác suất đổi càng cao.

Current workflow 3-7 bước:
1. Khách báo đổi mẫu hoặc số lượng cho sale
2. Sale đề nghị kế toán mở khoá đơn
3. Kế toán mở khoá
4. Sale sửa và đề nghị duyệt lại
5. Kế toán xem, duyệt và nhập vào phần mềm kế toán
6. Gửi email thông báo đổi để ghi log

Bottleneck:
Vì 20 phút đã bao gồm thời gian chờ duyệt, bottleneck không nằm ở thao tác sửa mà ở vòng
chờ qua lại giữa hai người: sale phải chờ kế toán mở khoá, rồi lại chờ kế toán duyệt.
Bước 5 vừa là chỗ chờ lâu nhất vừa là chỗ dễ rơi nhất — nếu kế toán quên, không có gì
nhắc, và sai lệch chảy tiếp xuống bảng tồn kho và kế hoạch giao hàng.

Impact:
- ~30 đơn bị đổi trên ~100 đơn/tháng × 20 phút ≈ 10 giờ/tháng chờ và xử lý.
- Rủi ro nặng hơn thời gian: quên duyệt ở bước 5 đã dẫn tới thiếu hàng đúng ngày hẹn giao
  cho khách. Đây là hậu quả chạm tới khách hàng, không chỉ nội bộ.

Success metric:
- Hiện trạng: ~20 phút cho một lần đổi tính cả chờ duyệt; số đơn đã đổi mà chưa duyệt
  chưa được đếm bao giờ.
- Mục tiêu: dưới 8 phút cho một lần đổi; số đơn ở trạng thái đã đổi nhưng chưa duyệt tại
  thời điểm cuối tuần = 0.
- Cách đo: bấm giờ 10 lần đổi liên tiếp, tách riêng thời gian thao tác và thời gian chờ;
  chạy một truy vấn cuối mỗi tuần đếm số đơn nằm ở trạng thái chờ duyệt quá 24 giờ.
- Metric giữ chất lượng: số lần thiếu hàng đúng ngày hẹn giao do lỗi dữ liệu = 0.

Non-AI alternative:
1. Phân quyền cho sale sửa trực tiếp một số trường giới hạn (mẫu, số lượng) khi đơn chưa
   tới mốc khoá, thay vì phải mở khoá toàn đơn — bỏ được hẳn một vòng chờ.
2. Thay email ghi log tay bằng audit log tự động của hệ thống.
3. Đặt cảnh báo tự động khi một đơn nằm ở trạng thái chờ duyệt quá 4 giờ — đây là phần
   xử lý đúng rủi ro nghiêm trọng nhất, và rẻ nhất để làm.

AI hypothesis:
Rất thấp. Đây là bài toán quy trình và phân quyền, không phải bài toán hiểu ngôn ngữ hay
phán đoán. Đưa AI vào đây sẽ là giải pháp đi tìm vấn đề.

Quick gut:
[x] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ~20 phút mỗi lần đổi (gồm cả chờ duyệt), ~30 lần/tháng

[1 Khách báo đổi cho sale]
→ [2 Sale xin kế toán mở khoá]        <-- vòng chờ 1
→ [3 Kế toán mở khoá]
→ [4 Sale sửa + đề nghị lại]
→ [5 Kế toán duyệt + nhập phần mềm kế toán]   <-- vòng chờ 2, và là bước hay bị quên
→ [6 Gửi email ghi log tay]

Đã xảy ra: quên bước 5 → thiếu hàng đúng ngày hẹn giao khách.

FUTURE STATE — mục tiêu dưới 8 phút

[1 Khách báo đổi cho sale]
→ [2 Sale sửa trực tiếp trường được phép (mẫu, số lượng) khi đơn chưa tới mốc khoá]
→ [3 Hệ thống tự ghi audit log, bỏ email tay]
→ [4 Kế toán chỉ duyệt các thay đổi vượt ngưỡng: đổi giá trị lớn, đổi sau mốc khoá]
     <-- human boundary
→ [5 Cảnh báo tự động nếu đơn nằm chờ duyệt quá 4 giờ]

Boundary: sale không được tự đổi giá, không đổi điều khoản thanh toán, không đổi đơn đã
qua mốc khoá — các trường hợp đó vẫn phải qua kế toán duyệt.
Fallback: nếu phân quyền gây sai sót, thu hẹp danh sách trường được sửa trực tiếp về 0
và quay lại quy trình duyệt toàn phần như hiện nay.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card #1 — Bảng tồn kho không trả lời được câu hỏi "mã này có bán được không".
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow chỉ 6 bước, và khi bấm giờ tách bước thì thấy 30 phút này gồm hai loại việc rất
khác nhau. 20 phút đầu là việc máy làm được 100%: 5 phút tải 3 file từ MISA, rồi 15 phút
copy và vlookup giữa các file để ra file chuẩn — chuỗi thao tác giống hệt nhau, lặp lại
đúng như vậy mỗi ngày làm việc. 10 phút còn lại mới là phần cần phán đoán, và nó kéo theo
một việc lớn hơn nhiều: vì bảng chỉ dừng ở mức liệt kê trạng thái, câu hỏi thật sự của
người bán hàng — hàng này đang nợ khách A thì mượn giao khách B trước được không — bị đẩy
hết sang 30 nhân viên kinh doanh, mỗi người tự so ngày hẹn giao với ngày lô sắp về trong
đầu, dựa trên một bảng mà chính người trong công ty mô tả là rất phức tạp khi nhìn. Hậu
quả đã xảy ra thật: cứ 2-3 tháng lại có một lần bán trúng hàng đã có chủ hoặc hứa giao rồi
không giao được cho khách đã ký hợp đồng.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Tôi đã đổi bottleneck từ "gộp file" sang "quy tắc mượn hàng" sau khi bấm giờ tách bước.
   Nhóm có thấy tôi đang tự thuyết phục mình không? Nếu quy tắc mượn hàng thực ra đơn giản
   và chỉ cần viết ra một lần rồi dán lên tường, thì bài này còn là bài đáng giải bằng công
   nghệ nữa không, hay chỉ là bài viết tài liệu quy trình?

2. Card #1 mất 13 giờ/tháng còn Card #2 mất 40 giờ/tháng, gấp ba lần. Tôi vẫn chọn pitch
   Card #1 vì workflow gọn và bottleneck rõ hơn. Nhóm có cho rằng tôi đang ưu tiên bài dễ
   làm hơn là bài đáng làm không?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: ban đầu tôi ghi bottleneck là bước gộp 3 file, nhưng khi bị hỏi tách thời gian từng bước thì lộ ra bước tải file chỉ mất 5 phút và dữ liệu đã có sẵn trên MISA — tức là giả định ban đầu sai. AI cũng chỉ ra phần impact phía phòng kinh doanh lúc đó hoàn toàn là suy luận, chưa có một con số nào.
- Tôi sửa gì: chuyển bottleneck từ "gộp file" sang đúng chỗ là quy tắc quyết định mượn hàng, và đưa bước 6 (mỗi sale tự suy) vào workflow như một bước chính thức thay vì để nó là phần việc ẩn không ai đo. Bổ sung con số 30 nhân viên kinh doanh làm hệ số nhân của impact, và ghi rõ tần suất lỗi thật là 2-3 tháng/lần thay vì để mơ hồ — kể cả khi con số đó nhỏ hơn tôi tưởng và làm bài của tôi yếu đi một chút. Những chỗ vẫn chưa đo được thì ghi thẳng là chưa đo và chuyển thành việc phải làm ở Phase 4.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
