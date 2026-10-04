# BÁO CÁO PHÂN TÍCH AUDIT EDOCTOR, GAP ANALYSIS & ĐỀ XUẤT ACTION CHIẾN LƯỢC

**Môn học:** EC204 – Marketing Điện Tử  
**Học phần:** Bài tập Tuần 03 (Google Trends → Search Intent → Decision → Action)  
**Nhóm:** Dr.Strange | **Thương hiệu:** eDoctor  
**Người thực hiện:** **Trần Quang Huy – MSSV: 24520706**  
**Phụ trách:** Mục D (Audit eDoctor · Landing-page gap · Đề xuất Action/Mockup · Chuẩn bị Trang 3 PDF)  
**Người kiểm tra chéo:** Phạm Trường Giang – 24520422  

---

## I. MỤC TIÊU VÀ TỔNG QUAN DỰ ÁN

Dự án tuần 3 tập trung giải quyết câu hỏi marketing cốt lõi:  
> **"Nhu cầu chăm sóc sức khỏe B2C nào trên môi trường số đang có xu hướng gia tăng và có intent chuyển đổi rõ nét nhất mà eDoctor có thể khai thác để tối ưu hóa trải nghiệm chuyển đổi trên Landing Page?"**

Dựa trên dữ liệu Search Intent & SERP do **Phạm Trường Giang** thu thập và dữ liệu Google Trends của **Võ Duy Mạnh**, tài liệu này thực hiện:
1. Xây dựng **Ma trận chấm điểm từ khóa** (`04_KEYWORD_SCORE`) để chốt 01 từ khóa chiến lược duy nhất.
2. Thực hiện **Audit Landing Page eDoctor** theo bộ 8 tiêu chí UX/Marketing chuẩn.
3. **Phân tích đối đầu (Gap Analysis)** với các đối thủ hàng đầu (**Medlatec**, **Nhà thuốc Long Châu**, **Vinmec**).
4. Chỉ ra **3 khoảng cách (Gap) lớn nhất** khiến eDoctor đánh mất khách hàng tiềm năng.
5. Đề xuất **01 Action chiến lược duy nhất**, khả thi và đo lường được, kèm **Wireframe/Copywriting** và **Giao diện Mockup tương tác HTML5**.

---

## II. MA TRẬN CHẤM ĐIỂM VÀ LỰA CHỌN TỪ KHÓA ƯU TIÊN (`04_KEYWORD_SCORE`)

Theo quy tắc tại Mục 5 của [PCCV.md](file:///d:/Marketing_Tuan3/PCCV.md), nhóm không chọn từ khóa chỉ vì "đường biểu đồ Trends cao" mà phải cân nhắc tổng hòa 4 tiêu chí có trọng số:

$$\text{Tổng điểm} = (\text{Trends} \times 30\%) + (\text{Intent} \times 25\%) + (\text{Năng lực eDoctor} \times 25\%) + (\text{Gap cạnh tranh} \times 20\%)$$

### 1. Bảng chấm điểm chi tiết (Thang điểm 1 – 5)

| Tiêu chí | Trọng số | Khám sức khỏe tổng quát | Xét nghiệm máu tại nhà | Bác sĩ online | Nguồn bằng chứng & Cơ sở đánh giá |
| :--- | :---: | :---: | :---: | :---: | :--- |
| **1. Mức quan tâm & Xu hướng Google Trends** | 30% | **4.5** / 5 | **4.0** / 5 | **3.0** / 5 | - *Khám tổng quát*: Volume cao nhất, ổn định quanh năm.<br>- *Xét nghiệm tại nhà*: Tăng trưởng đều đặn tại HN & TP.HCM.<br>- *Bác sĩ online*: Hạ nhiệt sau dịch, nhu cầu phân tán ngách. |
| **2. Search Intent gần chuyển đổi (Transactional)** | 25% | **3.5** / 5 | **5.0** / 5 | **4.0** / 5 | - *Khám tổng quát*: Commercial/Informational (khảo sát giá, danh mục).<br>- *Xét nghiệm tại nhà*: **Transactional cực cao** ("bảng giá", "gọi lấy mẫu", "bao lâu có kết quả").<br>- *Bác sĩ online*: Khách tìm kiếm hỗ trợ tức thời, hay tìm app miễn phí. |
| **3. Mức độ phù hợp năng lực eDoctor (Fit)** | 25% | **3.0** / 5 | **5.0** / 5 | **3.5** / 5 | - *Khám tổng quát*: eDoctor không có BV lớn để làm trọn gói MRI/CT phức tạp.<br>- *Xét nghiệm tại nhà*: **Dịch vụ cốt lõi B2C của eDoctor** (đội điều dưỡng lấy mẫu tận nhà + trả kết quả qua app).<br>- *Bác sĩ online*: Khó tạo doanh thu B2C đột phá so với xét nghiệm. |
| **4. Khoảng trống nội dung & Khả năng tạo khác biệt (Gap)** | 20% | **2.5** / 5 | **4.0** / 5 | **3.5** / 5 | - *Khám tổng quát*: Các BV lớn (Vinmec, Chợ Rẫy, ĐH Y Dược) chiếm lĩnh SERP.<br>- *Xét nghiệm tại nhà*: Medlatec mạnh nhưng eDoctor có thể tạo đột phá bằng **trải nghiệm số, minh bạch giá và tư vấn 1-1**.<br>- *Bác sĩ online*: Cạnh tranh gắt gao với YouMed, Medpro trên kho App Store. |
| **TỔNG ĐIỂM CÓ TRỌNG SỐ** | **100%** | **3.48 / 5.0** | <mark>**4.50 / 5.0**</mark> | **3.48 / 5.0** | **XÉT NGHIỆM MÁU TẠI NHÀ THẮNG TUYỆT ĐỐI** |

### 2. Biện luận Logic (Data → Insight → Decision)
- **DATA (Quan sát):** Từ khóa *"Xét nghiệm máu tại nhà"* có Search Intent mang tính giao dịch (Transactional) cao nhất trong 3 từ khóa (theo SERP analysis của Giang: người dùng chủ động tìm kiếm *"Bảng giá xét nghiệm tại nhà"*, *"Xét nghiệm tại nhà bao lâu có kết quả"*, *"dịch vụ lấy máu tận nơi"*).
- **INSIGHT (Diễn giải):** Khách hàng tìm kiếm từ khóa này không chỉ "đọc cho biết" mà đang có **nhu cầu phát sinh thực tế ngay lập tức** cho bản thân hoặc người thân (người già, trẻ nhỏ, phụ nữ mang thai ngại đến bệnh viện đông đúc). Rào cản lớn nhất của họ là **lo sợ chi phí không minh bạch** và **nghi ngại quy trình lấy mẫu/bảo quản có chuẩn y khoa không**.
- **DECISION (Quyết định):** Nhóm Dr.Strange chính thức lựa chọn từ khóa **"Xét nghiệm máu tại nhà"** làm từ khóa chiến lược số 1 để thực hiện Landing Page Audit và đề xuất Action cải tiến.

---

## III. AUDIT LANDING PAGE EDOCTOR VÀ BENCHMARK ĐỐI THỦ (`03_LP_AUDIT`)

### 1. Thông tin khảo sát
- **Trang eDoctor khảo sát:** `https://edoctor.io/xet-nghiem-tai-nha.html` (Trang giới thiệu Dịch vụ Lấy mẫu xét nghiệm tại nhà của eDoctor).
- **Đối thủ Benchmark 1 (Thống trị thị phần):** Medlatec (`https://medlatec.vn/dich-vu/xet-nghiem-lay-mau-tai-nha`)
- **Đối thủ Benchmark 2 (Niềm tin & Quy trình):** Nhà thuốc Long Châu (`https://nhathuoclongchau.com.vn/bai-viet/dich-vu-lay-mau-mau-xet-nghiem-tai-nha-ha-noi-quy-trinh-va-nhung-luu-y-khi-thuc-hien.html`)
- **Đối thủ tham chiếu (Minh bạch giá):** Vinmec (`https://www.vinmec.com/vie/bai-viet/kham-suc-khoe-dinh-ky-gom-nhung-gi-vi`)

### 2. Bảng đối chiếu Audit 8 thành phần cốt lõi kèm Bằng chứng thực tế

| STT | Thành phần UX / Marketing | Hiện trạng eDoctor (Current) & Bằng chứng | Mô hình đối thủ (Medlatec / Long Châu / Vinmec) & Bằng chứng | Đánh giá Khoảng cách (Gap) |
| :---: | :--- | :--- | :--- | :--- |
| **1** | **Title / H1 & Hero Headline** | - Tiêu đề mờ nhạt: *"LẤY MẪU XÉT NGHIỆM TẠI NHÀ"*, nút *"Đăng ký ngay"*, hình minh họa 2D chung chung.<br>- Chưa có Value Proposition về tốc độ hay cam kết y tế.<br>📸 [Ảnh eDoctor: 01_hero_headline.png](file:///d:/Marketing_Tuan3/audit_evidence/edoctor/01_hero_headline.png) | - **Medlatec:** Khẳng định vị thế *"Đơn vị y tế đầu tiên tại Việt Nam đạt tiêu chuẩn chất lượng xét nghiệm Mỹ (CAP) & ISO 15189"*, slogan *"Gọi là có ngay - Sống khỏe trong tầm tay"*, Hotline 1900 565656.<br>- **Long Châu:** Tiêu đề chuẩn SEO trực diện kèm Hotline 1800 6928.<br>📸 [Ảnh Medlatec: 01_hero_headline.png](file:///d:/Marketing_Tuan3/audit_evidence/medlatec/01_hero_headline.png)<br>📸 [Ảnh Long Châu: 01_hero_headline.png](file:///d:/Marketing_Tuan3/audit_evidence/longchau/01_hero_headline.png) | **Gap nghiêm trọng:** eDoctor thiếu tuyên ngôn giá trị định lượng (Bao lâu có mặt? Bao lâu có kết quả? Tiêu chuẩn gì?). |
| **2** | **Hero Value Proposition & Trust Badges** | - 4 icon lợi ích cơ bản: Nhanh chóng, Kết quả chính xác, Nhận kết quả Online, Nhanh chóng (*lỗi lặp từ*).<br>- Ở mục "Kết quả chính xác" lại ghi xét nghiệm thực hiện bởi Medlatec & Medic Hòa Hảo (*vô tình giới thiệu đối thủ*).<br>📸 [Ảnh eDoctor: 01_hero_headline.png](file:///d:/Marketing_Tuan3/audit_evidence/edoctor/01_hero_headline.png) | - **Medlatec:** Nêu bật ngay *"Phí đi lại chỉ 10.000 VNĐ"*, *"Hẹn lấy mẫu chỉ từ 30 phút"*, 4 huy hiệu an toàn: An toàn - Chính xác - Tiện lợi - Bảo mật.<br>📸 [Ảnh Medlatec: 01_hero_headline.png](file:///d:/Marketing_Tuan3/audit_evidence/medlatec/01_hero_headline.png) | **Mất niềm tin ban đầu:** Không giữ chân được người dùng trong 5 giây đầu; bounce rate cao. |
| **3** | **Bảng giá & Danh mục gói (Pricing Matrix)** | - Các gói xét nghiệm hiển thị dạng slider trượt ngang (850k, 870k, 3.090k...) chỉ có nút *"Xem chi tiết"*.<br>- **Không bóc tách danh mục chỉ số y khoa** ngay tại trang (khách không rõ gói gồm xét nghiệm gì).<br>📸 [Ảnh eDoctor: 03_content_section2.png](file:///d:/Marketing_Tuan3/audit_evidence/edoctor/03_content_section2.png)<br>📸 [Ảnh eDoctor: 04_content_section3.png](file:///d:/Marketing_Tuan3/audit_evidence/edoctor/04_content_section3.png) | - **Medlatec:** Phân nhóm gói rõ ràng (Sức khỏe tổng quát, Bệnh mãn tính, Tầm soát ung thư, Thai kỳ...) và liệt kê chi tiết từng chỉ số (Glucose, Ure, Creatinin, AST, ALT, Acid Uric, HbA1c, AFP...).<br>- **Vinmec:** Bóc tách 100% từng hạng mục khám và xét nghiệm chuyên sâu.<br>📸 [Ảnh Medlatec: 04_content_section3.png](file:///d:/Marketing_Tuan3/audit_evidence/medlatec/04_content_section3.png)<br>📸 [Ảnh Vinmec: 03_danh_muc_xet_nghiem.png](file:///d:/Marketing_Tuan3/audit_evidence/vinmec/03_danh_muc_xet_nghiem.png) | **GAP 1 (CỰC LỚN):** Thiếu minh bạch chi phí và danh mục chỉ số, khiến khách hàng nghi ngại phát sinh chi phí hoặc gói không đủ nhu cầu. |
| **4** | **Bằng chứng an toàn & Trust Signals** | - Thiếu chứng chỉ Lab (ISO 15189), thiếu hình ảnh thực tế về quy trình vô trùng.<br>- Chỉ có con số tĩnh (200.000+ người dùng, 90% hài lòng) và 1 trích dẫn testimonial.<br>📸 [Ảnh eDoctor: 04_content_section3.png](file:///d:/Marketing_Tuan3/audit_evidence/edoctor/04_content_section3.png) | - **Medlatec:** Song hành 2 chứng chỉ quốc tế CAP và ISO 15189:2012; có video thực tế phòng Lab và điều dưỡng.<br>- **Long Châu:** Ảnh thực tế điều dưỡng mang găng tay y tế, sát khuẩn, lấy máu bằng kim bướm và ống nghiệm chân không vô trùng 1 lần.<br>📸 [Ảnh Medlatec: 01_hero_headline.png](file:///d:/Marketing_Tuan3/audit_evidence/medlatec/01_hero_headline.png)<br>📸 [Ảnh Long Châu: 02_quy_trinh_an_toan.png](file:///d:/Marketing_Tuan3/audit_evidence/longchau/02_quy_trinh_an_toan.png) | **GAP 2 (TÂM LÝ):** Khách hàng lo lắng về độ chính xác và nguy cơ lây nhiễm chéo khi lấy máu tại nhà. |
| **5** | **Call To Action (CTA) & Quy trình đặt lịch** | - Form điền thông tin truyền thống ở chân trang (*Họ tên, SĐT, Email, Tỉnh/Thành*) thiếu chọn gói hay chọn khung giờ trực tiếp.<br>📸 [Ảnh eDoctor: 05_content_section4.png](file:///d:/Marketing_Tuan3/audit_evidence/edoctor/05_content_section4.png) | - **Medlatec:** Tích hợp form đặt hẹn nhanh trực tiếp ngay trên trang: Chọn loại xét nghiệm, SĐT, giới tính, ngày sinh và địa chỉ lấy mẫu; có Hotline gọi tức thì.<br>📸 [Ảnh Medlatec: 06_content_section5.png](file:///d:/Marketing_Tuan3/audit_evidence/medlatec/06_content_section5.png) | **GAP 3 (FRICTION):** Form thiếu thông tin gói dịch vụ làm tăng thời gian tư vấn lại qua điện thoại, giảm tỷ lệ chốt đơn tự động. |
| **6** | **Quy trình thực hiện (Process Steps)** | - Trình bày rời rạc, không có timeline / flowchart trực quan các bước từ lúc đặt đến khi nhận kết quả.<br>📸 [Ảnh eDoctor: 00_fullpage.png](file:///d:/Marketing_Tuan3/audit_evidence/edoctor/00_fullpage.png) | - **Medlatec:** Mô hình 4 bước rõ ràng: *1. Đăng ký lịch hẹn → 2. Lấy mẫu tận nơi → 3. Phân tích tại Lab → 4. Tư vấn kết quả*.<br>- **Long Châu:** Quy trình 5 bước chuẩn hóa từ chuẩn bị, lấy mẫu, dây chuyền lạnh đến trả kết quả.<br>📸 [Ảnh Medlatec: 05_content_section4.png](file:///d:/Marketing_Tuan3/audit_evidence/medlatec/05_content_section4.png)<br>📸 [Ảnh Long Châu: 03_luu_y_xet_nghiem.png](file:///d:/Marketing_Tuan3/audit_evidence/longchau/03_luu_y_xet_nghiem.png) | Người dùng không chủ động nắm bắt được lịch trình điều dưỡng đến và thời gian nhịn ăn sáng. |
| **7** | **Hậu mãi: Đọc kết quả & Tư vấn Bác sĩ** | - Chỉ ghi dòng chữ: *"Trả kết quả trực tuyến trong 5 tiếng..."*, chưa truyền thông thế mạnh Bác sĩ gọi điện tư vấn 1-1.<br>📸 [Ảnh eDoctor: 01_hero_headline.png](file:///d:/Marketing_Tuan3/audit_evidence/edoctor/01_hero_headline.png) | - **Medlatec:** Cam kết tại Bước 4: *"Khi có kết quả, khách hàng sẽ được các GS, TS giàu kinh nghiệm tư vấn về kết quả và đưa ra chế độ dinh dưỡng hợp lý"*.<br>📸 [Ảnh Medlatec: 06_content_section5.png](file:///d:/Marketing_Tuan3/audit_evidence/medlatec/06_content_section5.png) | Bỏ phí vũ khí bán hàng mạnh nhất của eDoctor là nền tảng Telemedicine với mạng lưới bác sĩ tư vấn chuyên sâu. |
| **8** | **FAQ (Giải tỏa rào cản tâm lý)** | - **Landing Page eDoctor hoàn toàn KHÔNG CÓ khối FAQ** giải đáp thắc mắc người dùng.<br>📸 [Ảnh eDoctor: 06_content_section5.png](file:///d:/Marketing_Tuan3/audit_evidence/edoctor/06_content_section5.png) | - **Long Châu:** Giải đáp chi tiết các câu hỏi: *Xét nghiệm tại nhà là gì? Có chính xác không? Quy trình an toàn thế nào? Cần nhịn ăn gì?*<br>📸 [Ảnh Long Châu: 02_quy_trinh_an_toan.png](file:///d:/Marketing_Tuan3/audit_evidence/longchau/02_quy_trinh_an_toan.png)<br>📸 [Ảnh Long Châu: 03_luu_y_xet_nghiem.png](file:///d:/Marketing_Tuan3/audit_evidence/longchau/03_luu_y_xet_nghiem.png) | Đánh mất cơ hội giải tỏa nỗi sợ nhịn ăn/chính xác và bỏ lỡ vị trí FAQ Rich Snippets trên Google SERP. |

### 3. Cấu trúc Thư mục Bằng chứng Hình ảnh (`audit_evidence`)

Toàn bộ ảnh chụp màn hình độ phân giải cao được lưu trữ tại thư mục [d:\Marketing_Tuan3\audit_evidence](file:///d:/Marketing_Tuan3/audit_evidence):

```text
d:\Marketing_Tuan3\audit_evidence\
├── edoctor\                      # Bằng chứng Landing Page hiện trạng eDoctor
│   ├── 00_fullpage.png           # Toàn cảnh trang eDoctor
│   ├── 01_hero_headline.png      # Hero banner và 4 icon lợi ích (lỗi lặp từ)
│   ├── 02_content_section1.png   # Chi tiết lợi ích & thông tin Medlatec/Medic
│   ├── 03_content_section2.png   # Danh sách gói liên quan (chưa bóc tách)
│   ├── 04_content_section3.png   # Giá gói và khối số liệu thống kê
│   ├── 05_content_section4.png   # Form đăng ký lấy mẫu truyền thống
│   └── 06_content_section5.png   # Chân trang (không có FAQ)
├── medlatec\                     # Bằng chứng Benchmark Đối thủ số 1 Medlatec
│   ├── 00_fullpage.png           # Toàn cảnh trang Medlatec
│   ├── 01_hero_headline.png      # Banner chuẩn CAP/ISO & Phí 10k & 30 phút
│   ├── 02_content_section1.png   # 4 trụ cột cam kết dịch vụ
│   ├── 03_content_section2.png   # Video và hình ảnh thực tế phòng Lab
│   ├── 04_content_section3.png   # Bảng danh mục bóc tách từng chỉ số y khoa
│   ├── 05_content_section4.png   # Quy trình 4 bước lấy mẫu
│   └── 06_content_section5.png   # Cam kết Bác sĩ tư vấn & Form đặt hẹn nhanh
├── longchau\                     # Bằng chứng Benchmark Quy trình & An toàn Long Châu
│   ├── 00_fullpage.png           # Toàn cảnh bài viết dịch vụ Long Châu
│   ├── 01_hero_headline.png      # Tiêu đề SEO và Hotline tư vấn 1800 6928
│   ├── 02_quy_trinh_an_toan.png  # Hình ảnh thực tế lấy máu vô trùng & Giải thích
│   └── 03_luu_y_xet_nghiem.png   # 5 bước quy trình & Hướng dẫn nhịn ăn chuẩn y khoa
└── vinmec\                       # Bằng chứng Benchmark Minh bạch xét nghiệm Vinmec
    ├── 00_fullpage.png           # Toàn cảnh trang Vinmec
    ├── 01_hero_headline.png      # Tiêu đề và giao diện tham vấn Bác sĩ
    ├── 02_content_section1.png   # Nội dung khám sức khỏe định kỳ
    ├── 03_danh_muc_xet_nghiem.png# Bóc tách danh mục xét nghiệm chuyên khoa
    └── 04_chi_tiet_chuyen_sau.png# Chi tiết các chỉ số xét nghiệm chuyên sâu
```

---

## IV. TỔNG KẾT 3 KHOẢNG CÁCH (GAP) LỚN NHẤT CỦA EDOCTOR

1. **GAP 1 - Thiếu minh bạch danh mục chỉ số và bảng giá bóc tách:**  
   Người dùng tìm kiếm mang tính thương mại luôn muốn so sánh giá và quyền lợi. eDoctor chưa bóc tách rõ từng chỉ số xét nghiệm trong gói, gây cảm giác "mập mờ chi phí".
2. **GAP 2 - Thiếu Trust Signals về quy trình vô trùng & chứng nhận Lab:**  
   Xét nghiệm máu là dịch vụ xâm lấn y tế nhạy cảm. Việc eDoctor thiếu các badge chứng chỉ ISO 15189, hình ảnh ống lấy mẫu chân không vô trùng một lần khiến khách hàng lo ngại về độ chính xác và an toàn.
3. **GAP 3 - Ma sát quy trình đặt hẹn (Friction) & chưa làm nổi bật đặc quyền Bác sĩ 1-1:**  
   Ép người dùng tải app ngay trên trang web làm đứt gãy luồng chuyển đổi. Đồng thời, eDoctor chưa truyền thông rõ rệt quyền lợi độc quyền: *"Miễn phí 100% Bác sĩ chuyên khoa gọi điện tư vấn phân tích kết quả qua App"*.

---

## V. ĐỀ XUẤT 01 ACTION CHIẾN LƯỢC DUY NHẤT & MOCKUP THỰC THI

### 1. Tuyên bố Action Chiến lược (Action Statement)
> **Tên Action:** *"Tái cấu trúc Hero Section & Bảng danh mục Xét nghiệm Tương tác (Interactive Pricing Matrix) kết hợp Cam kết An toàn Y tế 3 Chuẩn và Đặt lịch Siêu tốc 3 Bước trên Landing Page eDoctor."*

### 2. Chi tiết 4 Phân hệ Nâng cấp trên Landing Page

#### Phân hệ 1: Hero Section Định vị Giá trị Tức thì (High-Conversion Hero)
- **H1 Headline:** *"Xét Nghiệm Máu Tại Nhà Chuẩn Y Khoa – Điều Dưỡng Đến Sau 30 Phút, Kết Quả Trả Qua App Trong 2-4 Giờ"*
- **Sub-headline:** *"Hơn 150.000 gia đình tin chọn. 100% mẫu được phân tích tại Phòng Lab đạt chuẩn ISO 15189. Bác sĩ chuyên khoa gọi điện tư vấn chi tiết kết quả miễn phí."*
- **Quick Booking Bar:** Cho phép nhập `[Chọn gói xét nghiệm]` + `[Số điện thoại]` + `[Địa chỉ lấy mẫu]` → Bấm `[Đặt Lịch Lấy Mẫu Ngay]` trong 10 giây.
- **Trust Badges:** `✓ Lab chuẩn ISO 15189` | `✓ Kim & Ống nghiệm chân không 1 lần` | `✓ Bác sĩ tư vấn 1-1 miễn phí` | `✓ Phí đi lại 0đ`.

#### Phân hệ 2: Bảng Giá Tương Tác Bóc Tách 100% Chỉ Số (Interactive Pricing Matrix)
Phân loại 4 tab nhu cầu thông minh:
1. **Gói Tổng Quát Cơ Bản (12 chỉ số):** Kiểm tra đường huyết, mỡ máu, chức năng gan (AST/ALT), thận (Ure/Creatinine), công thức máu. Giá niêm yết: **490.000 đ**.
2. **Gói Tầm Soát Toàn Diện (24 chỉ số):** Bổ sung Acid Uric (Gout), Canxi, Viêm gan B/C, Tuyến giáp (TSH). Giá niêm yết: **990.000 đ**.
3. **Gói Chăm Sóc Người Cao Tuổi & Bệnh Mãn Tính:** Chuyên sâu Tim mạch, Tiểu đường (HbA1c), Mỡ máu toàn phần. Giá niêm yết: **1.250.000 đ**.
4. **Gói Mẹ Bầu & Nhi Khoa:** Dị ứng, Vi chất, Thiếu máu, Beta-hCG. Giá niêm yết: **750.000 đ**.
*Mỗi gói đều có nút "Xem chi tiết từng chỉ số" mở rộng dạng Accordion minh bạch 100%.*

#### Phân hệ 3: Module "Quy Trình 4 Bước Chuẩn An Toàn Vô Trùng" (Safety & Process)
- **Bước 1 (00:00):** Đặt lịch qua Web/App – Nhận xác nhận điều dưỡng trong 5 phút.
- **Bước 2 (+00:30):** Điều dưỡng mang hộp bảo quản lạnh chuyên dụng đến tận nơi, sát khuẩn và lấy mẫu nhẹ nhàng bằng kim bướm siêu mảnh.
- **Bước 3 (+02:00 - 04:00):** Mẫu máu chuyển về Lab trung tâm đạt chuẩn ISO 15189. Kết quả tự động đồng bộ lên App eDoctor kèm cảnh báo chỉ số bất thường.
- **Bước 4 (Hậu mãi):** Bác sĩ chuyên khoa chủ động gọi video/thoại 1-1 giải thích cặn kẽ kết quả và hướng dẫn phác đồ sinh hoạt/dinh dưỡng.

#### Phân hệ 4: Bộ FAQ Chuẩn Hóa Giải Tỏa Rào Cản Tâm Lý
1. *Xét nghiệm máu tại nhà có chính xác bằng tại bệnh viện lớn không?* → Trả lời khẳng định độ chính xác 99.9% nhờ phòng Lab trung tâm đối tác đạt ISO 15189 cùng hệ thống máy phân tích tự động của Roche / Abbott.
2. *Tôi có cần nhịn ăn sáng trước khi lấy máu không?* → Hướng dẫn chi tiết từng nhóm xét nghiệm cần nhịn ăn 8-10 tiếng (Đường huyết, Mỡ máu) và nhóm không cần nhịn ăn.
3. *Sau bao lâu thì có kết quả và tôi xem ở đâu?* → Có kết quả sau 2–4 giờ, thông báo qua SMS và mở xem file PDF có chữ ký số bác sĩ ngay trên App eDoctor.

---

## VI. NỘI DUNG TỔNG HỢP CHO TRANG 3 CỦA BẢN PDF NỘP BÀI

Dưới đây là phần nội dung đã được cô đọng, sẵn sàng để trưởng nhóm **Nguyễn Vũ Quang Huy** đưa trực tiếp vào **Trang 3 (Decision & Action)** của bản PDF 3–4 trang:

> ### **TRANG 3: QUYẾT ĐỊNH CHIẾN LƯỢC & ACTION CẢI TIẾN EDOCTOR**
> 
> **1. Quyết định lựa chọn Từ khóa (Decision Log):**
> * Dựa trên ma trận chấm điểm 4 tiêu chí có trọng số, nhóm lựa chọn từ khóa **"Xét nghiệm máu tại nhà" (Điểm số 4.50/5.0)** làm ưu tiên số 1 vì:
>   - Search Intent mang tính giao dịch cao nhất (người dùng có nhu cầu gọi dịch vụ tức thời).
>   - Phù hợp 100% với năng lực vận hành B2C của eDoctor (đội điều dưỡng lấy mẫu tận nơi).
> 
> **2. Ba khoảng trống (Gap) lớn của Landing Page eDoctor hiện tại:**
> * **Gap 1 (Chi phí):** Thiếu bảng giá bóc tách chi tiết từng chỉ số xét nghiệm, gây lo ngại phát sinh chi phí.
> * **Gap 2 (Niềm tin):** Chưa làm nổi bật tiêu chuẩn phòng Lab (ISO 15189) và quy trình bảo quản vô trùng tại nhà.
> * **Gap 3 (Chuyển đổi):** Ma sát cao do ép tải app khi đặt lịch; chưa nêu bật đặc quyền Bác sĩ gọi điện tư vấn 1-1 miễn phí.
> 
> **3. Đề xuất 01 Action Cụ thể:**
> * **Tái thiết kế Landing Page Dịch vụ Xét nghiệm máu tại nhà:**
>   - *Hero Section*: Đổi H1 cam kết *"Lấy mẫu sau 30 phút – Kết quả qua App 2-4h"*, tích hợp Quick Booking Bar 3 bước.
>   - *Interactive Pricing*: Phân 4 tab nhu cầu, minh bạch 100% chỉ số y khoa và bảng giá trọn gói cạnh tranh.
>   - *Trust Signals*: Bổ sung Badge Lab ISO 15189, minh họa quy trình lấy mẫu chuẩn 4 bước và cam kết Bác sĩ tư vấn 1-1 miễn phí.
> * **Minh chứng Mockup:** Xem giao diện mẫu tại `mockup_edoctor_action.html` hoặc phụ lục Drive nhóm.

---

## VII. BỘ CÂU HỎI VẤN ĐÁP BẢO VỆ ĐIỂM 10 DÀNH CHO TRẦN QUANG HUY

Khi giảng viên hoặc hội đồng hỏi chất vấn về Phần D, trả lời tự tin theo đúng cấu trúc 5 bước: **Nguồn → Thiết lập → Dữ liệu quan sát → Diễn giải → Giới hạn**:

1. **Hỏi: Vì sao bạn chọn đề xuất Action cho "Xét nghiệm máu tại nhà" mà không phải "Khám tổng quát" có volume tìm kiếm cao hơn?**
   - *Trả lời:* Mặc dù "Khám tổng quát" có volume cao trên Trends, nhưng Search Intent chủ yếu là Informational/Commercial và khách hàng có xu hướng đến các bệnh viện công/tư lớn có máy móc nặng (MRI/CT). Trong khi đó, "Xét nghiệm máu tại nhà" có Intent Transactional rất cao (khách tìm bảng giá, gọi lấy mẫu) và là dịch vụ cốt lõi mà đội ngũ điều dưỡng eDoctor có thể trực tiếp phục vụ ngay tại nhà, mang lại tỷ lệ chuyển đổi ROI thực tế cao hơn.

2. **Hỏi: Bằng chứng nào chứng minh eDoctor đang bị thua thiệt về mặt niềm tin (Trust Signals) so với đối thủ?**
   - *Trả lời:* Qua SERP Audit của Giang, đối thủ Medlatec chiếm trọn niềm tin người dùng nhờ 30 năm kinh nghiệm và mạng lưới Lab rộng lớn, còn Long Châu tập trung giải quyết nỗi sợ nhiễm khuẩn bằng bài viết quy trình vô trùng. Khảo sát Landing Page eDoctor cho thấy trang web thiếu hoàn toàn chứng chỉ chất lượng Lab (ISO 15189) và thiếu mô tả quy trình dây chuyền lạnh, khiến người dùng ngần ngại đặt lịch lấy mẫu tại nhà.

3. **Hỏi: Vì sao Action này là một thay đổi cụ thể đo lường được chứ không phải là khẩu hiệu chung chung "Tối ưu SEO"?**
   - *Trả lời:* Action của nhóm là một bản thiết kế UI/UX và Content Landing Page cụ thể gồm 4 phân hệ: Tối ưu Hero với Quick Booking Bar giảm 50% thao tác đặt lịch; Xây dựng Bảng giá tương tác minh bạch 100% chỉ số; Bổ sung Khối chứng chỉ Lab ISO 15189 và Cam kết Bác sĩ tư vấn 1-1. Các chỉ số này có thể đo lường trực tiếp qua Conversion Rate (CR), Bounce Rate và Time on Page trên Google Analytics.

---
**Tài liệu được lập và lưu trữ tại:** [d:\Marketing_Tuan3\AUDIT_AND_ACTION.md](file:///d:/Marketing_Tuan3/AUDIT_AND_ACTION.md)
