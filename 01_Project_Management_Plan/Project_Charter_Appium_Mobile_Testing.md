# PROJECT CHARTER
## Dự án: Xây dựng Hệ thống Test Automation cho Mobile App (Android & iOS)

---

## 1. THÔNG TIN CHUNG

| Thông tin | Chi tiết |
|-----------|----------|
| **Tên dự án** | Mobile App Test Automation với Appium |
| **Mã dự án** | PRJ-2025-APPIUM-001 |
| **Ngày tạo** | 09/12/2025 |
| **Phiên bản** | 1.1 |
| **Project Sponsor** | [Tên Sponsor] - [Chức vụ] |
| **Project Manager** | [Tên PM] - [Chức vụ] |

---

## 2. MỤC ĐÍCH DỰ ÁN

Xây dựng hệ thống kiểm thử tự động (Test Automation) cho ứng dụng mobile trên cả hai nền tảng Android và iOS, sử dụng framework Appium nhằm:

- Tự động hóa quy trình kiểm thử regression
- Giảm thời gian và chi phí kiểm thử thủ công
- Nâng cao chất lượng sản phẩm trước khi release
- Phát hiện lỗi sớm trong chu trình phát triển

---

## 3. MỤC TIÊU DỰ ÁN

### 3.1 Mục tiêu SMART

| # | Mục tiêu | Chỉ số đo lường |
|---|----------|-----------------|
| 1 | Tự động hóa **80%** test cases regression | Số test cases automated / Tổng test cases |
| 2 | Giảm **60%** thời gian regression testing | Thời gian test trước vs sau automation |
| 3 | Đạt **95%** pass rate cho automated tests | Pass rate hàng tuần |
| 4 | Tích hợp CI/CD pipeline | Số builds được test tự động |
| 5 | Cover cả Android và iOS với cùng codebase | Tỷ lệ code reuse giữa 2 platforms |

### 3.2 Tiêu chí thành công

- [ ] Framework Appium được setup và hoạt động ổn định
- [ ] Tối thiểu 200 test cases được tự động hóa
- [ ] Tích hợp thành công với Jenkins/GitLab CI
- [ ] Báo cáo test tự động được generate (Allure/ExtentReports)
- [ ] Team QA được đào tạo và có thể maintain framework

---

## 4. PHẠM VI DỰ ÁN

### 4.1 Trong phạm vi (In Scope)

| # | Hạng mục | Mô tả |
|---|----------|-------|
| 1 | **Setup Framework** | Appium + WebDriverIO/Java + Page Object Model |
| 2 | **Android Testing** | Test trên Android 10+ (API 29+) |
| 3 | **iOS Testing** | Test trên iOS 14+ |
| 4 | **Test Types** | Functional, Regression, Smoke tests |
| 5 | **CI/CD Integration** | Jenkins/GitLab CI pipeline |
| 6 | **Reporting** | Allure Reports, Screenshots, Video recording |
| 7 | **Device Farm** | BrowserStack/Sauce Labs integration |
| 8 | **Documentation** | Setup guide, coding standards, best practices |

### 4.2 Ngoài phạm vi (Out of Scope)

- Performance testing (sử dụng tools khác như JMeter)
- Security testing
- Test trên các phiên bản OS cũ (Android < 10, iOS < 14)
- Desktop/Web application testing
- Manual testing processes

---

## 5. CÁC BÊN LIÊN QUAN (STAKEHOLDERS)

| Vai trò | Tên | Trách nhiệm | Mức độ tham gia |
|---------|-----|-------------|-----------------|
| **Sponsor** | [Tên] | Phê duyệt ngân sách, quyết định chiến lược | Cao |
| **Project Manager** | [Tên] | Quản lý dự án, báo cáo tiến độ | Cao |
| **QA Lead** | [Tên] | Thiết kế framework, review code | Cao |
| **QA Engineers** | [Tên] | Phát triển test scripts | Cao |
| **Dev Lead** | [Tên] | Hỗ trợ locators, app builds | Trung bình |
| **DevOps** | [Tên] | Setup CI/CD, infrastructure | Trung bình |
| **Product Owner** | [Tên] | Định nghĩa test scenarios | Thấp |

---

## 6. NGUỒN LỰC

### 6.1 Nhân sự

| Vai trò | Số lượng | FTE | Kỹ năng yêu cầu |
|---------|----------|-----|-----------------|
| QA Lead/Architect | 1 | 100% | Appium, Java/JS, CI/CD, 5+ năm exp |
| Senior QA Automation | 2 | 100% | Appium, Programming, 3+ năm exp |
| QA Automation | 2 | 100% | Basic programming, testing knowledge |
| DevOps Engineer | 1 | 50% | Jenkins, Docker, Cloud services |

### 6.2 Công cụ & Infrastructure

| Hạng mục | Tool/Service | Chi phí ước tính |
|----------|--------------|------------------|
| IDE | IntelliJ IDEA / VS Code | Free - $500/năm |
| Device Farm | BrowserStack / Sauce Labs | $3,000 - $10,000/năm |
| CI/CD | Jenkins / GitLab CI | Free - $2,000/năm |
| Test Devices | Android + iOS devices | $2,000 - $5,000 |
| Reporting | Allure Reports | Free |
| Version Control | Git/GitHub/GitLab | Free - $500/năm |

### 6.3 Ngân sách tổng quan

| Hạng mục | Chi phí ước tính |
|----------|------------------|
| Nhân sự (6 tháng) | $XX,XXX |
| Tools & Licenses | $X,XXX |
| Infrastructure | $X,XXX |
| Training | $X,XXX |
| Contingency (15%) | $X,XXX |
| **TỔNG** | **$XX,XXX** |

---

## 7. MILESTONES CHÍNH

| # | Milestone | Deliverables | Target Date |
|---|-----------|--------------|-------------|
| M1 | **Project Kickoff** | Charter approved, team onboarded | Week 1 |
| M2 | **Framework Setup** | Base framework, CI/CD pipeline | Week 4 |
| M3 | **Android Automation** | 100 test cases Android | Week 8 |
| M4 | **iOS Automation** | 100 test cases iOS | Week 12 |
| M5 | **Integration Complete** | Full CI/CD, reporting | Week 14 |
| M6 | **Training & Handover** | Documentation, team training | Week 16 |
| M7 | **Project Closure** | Final report, lessons learned | Week 18 |

---

## 8. RỦI RO CẤP CAO

| # | Rủi ro | Xác suất | Tác động | Biện pháp giảm thiểu |
|---|--------|----------|----------|---------------------|
| R1 | App thay đổi UI thường xuyên | Cao | Cao | Page Object Model, robust locators |
| R2 | Thiếu test devices | Trung bình | Cao | Sử dụng Device Farm cloud |
| R3 | Team thiếu kinh nghiệm Appium | Trung bình | Trung bình | Training, pair programming |
| R4 | iOS signing/provisioning issues | Cao | Trung bình | DevOps support, documentation |
| R5 | Flaky tests | Cao | Trung bình | Retry mechanism, stable waits |
| R6 | CI/CD pipeline không ổn định | Trung bình | Cao | Monitoring, fallback options |

---

## 9. GIẢ ĐỊNH & RÀNG BUỘC

### 9.1 Giả định

- Dev team cung cấp app builds đúng schedule
- Test devices/emulators có sẵn cho team
- App có accessibility IDs/test IDs cho automation
- Team members commit full-time cho dự án
- Infrastructure (servers, network) đã sẵn sàng

### 9.2 Ràng buộc

- Budget không vượt quá $XX,XXX
- Timeline không quá 18 weeks
- Phải support cả Android và iOS
- Phải tích hợp với CI/CD hiện có
- Tuân thủ coding standards của công ty

---

## 10. PHƯƠNG PHÁP QUẢN LÝ

| Hạng mục | Approach |
|----------|----------|
| **Methodology** | Agile/Scrum (2-week sprints) |
| **Communication** | Daily standup, Weekly status report |
| **Tools** | Jira (tracking), Confluence (docs), Slack (chat) |
| **Code Review** | Pull Request review bắt buộc |
| **Quality Gates** | Code coverage > 80%, 0 critical bugs |

---

## 11. PHÊ DUYỆT

| Vai trò | Họ tên | Chữ ký | Ngày |
|---------|--------|--------|------|
| **Project Sponsor** | | | |
| **Project Manager** | | | |
| **QA Lead** | | | |
| **IT Director** | | | |

---

## 12. LỊCH SỬ THAY ĐỔI

| Version | Ngày | Người thay đổi | Mô tả thay đổi |
|---------|------|----------------|----------------|
| 1.0 | 02/12/2025 | Project Manager | Khởi tạo document |
| 1.1 | 09/12/2025 | Project Manager | Cập nhật mã dự án và thông tin |

---

*Document này là tài liệu chính thức ủy quyền cho dự án. Mọi thay đổi phải được phê duyệt bởi Project Sponsor.*
