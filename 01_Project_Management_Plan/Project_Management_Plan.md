# PROJECT MANAGEMENT PLAN
## Dự án: Mobile App Test Automation với Appium

---

## MỤC ĐÍCH VÀ TÁC DỤNG

**Mục đích:** Project Management Plan là tài liệu master tích hợp tất cả các knowledge areas, cung cấp framework tổng thể cho việc thực thi, giám sát, và kiểm soát dự án.

**Tác dụng:**
- Tổng hợp và liên kết tất cả các kế hoạch quản lý (scope, schedule, cost, quality, etc.)
- Cung cấp baseline cho việc đo lường performance dự án
- Đảm bảo tính nhất quán giữa các knowledge areas
- Làm cơ sở cho việc ra quyết định trong suốt vòng đời dự án
- Phục vụ như một roadmap cho team và stakeholders

**Đối tượng sử dụng:**
- **Project Manager:** Sử dụng làm tài liệu chính để quản lý dự án
- **Team Members:** Tham khảo để hiểu cách thức làm việc
- **Stakeholders:** Hiểu tổng quan về cách dự án được quản lý
- **Sponsor:** Đánh giá tính khả thi và approach của dự án

**Thời điểm sử dụng:**
- Tạo trong giai đoạn Planning (sau khi Charter được phê duyệt)
- Cập nhật khi có thay đổi lớn về approach hoặc strategy
- Tham khảo thường xuyên trong suốt Execution và Monitoring & Controlling

**Mối liên hệ với các tài liệu khác:**
- Dựa trên Project Charter và Business Case
- Tích hợp tất cả các Management Plans (Scope, Schedule, Cost, Quality, etc.)
- Tham chiếu đến các Project Documents (WBS, Schedule, Risk Register, etc.)

---

## 1. THÔNG TIN DỰ ÁN

| Thông tin | Chi tiết |
|-----------|----------|
| **Tên dự án** | Mobile App Test Automation với Appium |
| **Mã dự án** | PRJ-2025-APPIUM-001 |
| **Ngày tạo** | 09/12/2025 |
| **Phiên bản** | 1.1 |
| **Project Sponsor** | [Tên Sponsor] - [Chức vụ] |
| **Project Manager** | [Tên PM] - [Chức vụ] |
| **Thời gian dự án** | 18 tuần |
| **Methodology** | Agile/Scrum (2-week sprints) |

---

## 2. TỔNG QUAN DỰ ÁN

### 2.1 Mục đích dự án

Xây dựng hệ thống kiểm thử tự động (Test Automation) cho ứng dụng mobile trên cả hai nền tảng Android và iOS, sử dụng framework Appium nhằm:

- Tự động hóa quy trình kiểm thử regression
- Giảm thời gian và chi phí kiểm thử thủ công
- Nâng cao chất lượng sản phẩm trước khi release
- Phát hiện lỗi sớm trong chu trình phát triển

### 2.2 Mục tiêu SMART

| # | Mục tiêu | Chỉ số đo lường |
|---|----------|-----------------|
| 1 | Tự động hóa **80%** test cases regression | Số test cases automated / Tổng test cases |
| 2 | Giảm **60%** thời gian regression testing | Thời gian test trước vs sau automation |
| 3 | Đạt **95%** pass rate cho automated tests | Pass rate hàng tuần |
| 4 | Tích hợp CI/CD pipeline | Số builds được test tự động |
| 5 | Cover cả Android và iOS với cùng codebase | Tỷ lệ code reuse giữa 2 platforms |

---

## 3. CÁC KẾ HOẠCH QUẢN LÝ TÍCH HỢP

Project Management Plan này tích hợp các kế hoạch quản lý sau:

### 3.1 Scope Management Plan
**File:** [Scope_Management_Plan.md](../02_Management_Plans/Scope_Management_Plan.md)

Xác định cách thức quản lý phạm vi dự án, bao gồm:
- Thu thập và phân tích yêu cầu
- Định nghĩa phạm vi (In Scope và Out of Scope)
- Kiểm soát thay đổi phạm vi

### 3.2 Requirements Management Plan
**File:** [Requirements_Management_Plan.md](../02_Management_Plans/Requirements_Management_Plan.md)

Xác định cách thức:
- Thu thập và tài liệu hóa yêu cầu
- Traceability của yêu cầu
- Validation và verification

### 3.3 Schedule Management Plan
**File:** [Schedule_Management_Plan.md](../02_Management_Plans/Schedule_Management_Plan.md)

Xác định:
- Quy trình lập kế hoạch tiến độ
- Công cụ và kỹ thuật sử dụng
- Cách thức kiểm soát tiến độ

### 3.4 Cost Management Plan
**File:** [Cost_Management_Plan.md](../02_Management_Plans/Cost_Management_Plan.md)

Xác định:
- Quy trình ước tính và lập ngân sách
- Kiểm soát chi phí
- Báo cáo tài chính

### 3.5 Quality Management Plan
**File:** [Quality_Management_Plan.md](../02_Management_Plans/Quality_Management_Plan.md)

Xác định:
- Tiêu chuẩn chất lượng
- Quy trình đảm bảo chất lượng (QA)
- Quy trình kiểm soát chất lượng (QC)

### 3.6 Resource Management Plan
**File:** [Resource_Management_Plan.md](../02_Management_Plans/Resource_Management_Plan.md)

Xác định:
- Lập kế hoạch nguồn lực
- Thu hút và phân bổ nguồn lực
- Quản lý team

### 3.7 Communications Management Plan
**File:** [Communications_Management_Plan.md](../02_Management_Plans/Communications_Management_Plan.md)

Xác định:
- Ai cần thông tin gì, khi nào
- Phương thức truyền đạt
- Frequency và format của reports

### 3.8 Risk Management Plan
**File:** [Risk_Management_Plan.md](../02_Management_Plans/Risk_Management_Plan.md)

Xác định:
- Quy trình nhận diện và phân tích rủi ro
- Kế hoạch ứng phó rủi ro
- Monitoring và controlling rủi ro

### 3.9 Procurement Management Plan
**File:** [Procurement_Management_Plan.md](../02_Management_Plans/Procurement_Management_Plan.md)

Xác định:
- Hàng hóa và dịch vụ cần mua sắm
- Quy trình procurement
- Quản lý contracts

### 3.10 Stakeholder Engagement Plan
**File:** [Stakeholder_Engagement_Plan.md](../02_Management_Plans/Stakeholder_Engagement_Plan.md)

Xác định:
- Chiến lược engagement với stakeholders
- Communication approach
- Quản lý expectations

### 3.11 Change Management Plan
**File:** [Change_Management_Plan.md](../02_Management_Plans/Change_Management_Plan.md)

Xác định:
- Quy trình quản lý thay đổi
- Change Control Board (CCB)
- Impact assessment

### 3.12 Configuration Management Plan
**File:** [Configuration_Management_Plan.md](../02_Management_Plans/Configuration_Management_Plan.md)

Xác định:
- Quy trình quản lý cấu hình
- Version control
- Baselines

---

## 4. TÀI LIỆU DỰ ÁN CHÍNH

### 4.1 Work Breakdown Structure (WBS)
**File:** [Work_Breakdown_Structure.md](../03_Project_Documents/Work_Breakdown_Structure.md)

Cấu trúc phân rã công việc dự án thành 5 phases:
- Phase 1: Foundation (Week 1-4)
- Phase 2: Android Automation (Week 5-8)
- Phase 3: iOS Automation (Week 9-12)
- Phase 4: Integration & Optimization (Week 13-16)
- Phase 5: Training & Handover (Week 17-18)

### 4.2 Project Schedule
**File:** [Project_Schedule.md](../03_Project_Documents/Project_Schedule.md)

Lịch trình chi tiết với 7 milestones và timeline 18 tuần.

### 4.3 Risk Register
**File:** [Risk_Register.md](../03_Project_Documents/Risk_Register.md)

Đăng ký tất cả rủi ro đã được nhận diện với kế hoạch ứng phó.

### 4.4 Stakeholder Register
**File:** [Stakeholder_Register.md](../03_Project_Documents/Stakeholder_Register.md)

Danh sách stakeholders với thông tin về vai trò và mức độ quan tâm.

---

## 5. PHƯƠNG PHÁP QUẢN LÝ

### 5.1 Methodology

**Agile/Scrum với 2-week sprints:**
- Sprint Planning: Đầu mỗi sprint
- Daily Standup: Hàng ngày, 15 phút
- Sprint Review: Cuối sprint
- Sprint Retrospective: Cuối sprint

### 5.2 Tools

| Hạng mục | Tool |
|----------|------|
| **Project Tracking** | Jira |
| **Documentation** | Confluence |
| **Communication** | Slack |
| **Version Control** | Git/GitHub/GitLab |
| **Code Review** | Pull Request process |

### 5.3 Quality Gates

- Code coverage > 80%
- 0 critical bugs
- All automated tests pass
- Documentation complete

---

## 6. MILESTONES CHÍNH

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

## 7. NGUỒN LỰC

### 7.1 Nhân sự

| Vai trò | Số lượng | FTE | Kỹ năng yêu cầu |
|---------|----------|-----|-----------------|
| QA Lead/Architect | 1 | 100% | Appium, Java/JS, CI/CD, 5+ năm exp |
| Senior QA Automation | 2 | 100% | Appium, Programming, 3+ năm exp |
| QA Automation | 2 | 100% | Basic programming, testing knowledge |
| DevOps Engineer | 1 | 50% | Jenkins, Docker, Cloud services |

### 7.2 Công cụ & Infrastructure

| Hạng mục | Tool/Service |
|----------|--------------|
| IDE | IntelliJ IDEA / VS Code |
| Device Farm | BrowserStack / Sauce Labs |
| CI/CD | Jenkins / GitLab CI |
| Reporting | Allure Reports |
| Version Control | Git/GitHub/GitLab |

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

Chi tiết xem tại [Risk Register](../03_Project_Documents/Risk_Register.md).

---

## 9. GIẢ ĐỊNH & RÀNG BUỘC

### 9.1 Giả định

- Dev team cung cấp app builds đúng schedule
- Test devices/emulators có sẵn cho team
- App có accessibility IDs/test IDs cho automation
- Team members commit full-time cho dự án
- Infrastructure (servers, network) đã sẵn sàng

Chi tiết xem tại [Assumption Log](../03_Project_Documents/Assumption_Log.md).

### 9.2 Ràng buộc

- Budget không vượt quá $XX,XXX
- Timeline không quá 18 weeks
- Phải support cả Android và iOS
- Phải tích hợp với CI/CD hiện có
- Tuân thủ coding standards của công ty

---

## 10. PHÊ DUYỆT

| Vai trò | Họ tên | Chữ ký | Ngày |
|---------|--------|--------|------|
| **Project Sponsor** | | | |
| **Project Manager** | | | |
| **QA Lead** | | | |
| **IT Director** | | | |

---

## 11. LỊCH SỬ THAY ĐỔI

| Version | Ngày | Người thay đổi | Mô tả thay đổi |
|---------|------|----------------|----------------|
| 1.0 | 02/12/2025 | Project Manager | Khởi tạo document |
| 1.1 | 09/12/2025 | Project Manager | Cập nhật mã dự án và thông tin |

---

*Document này là tài liệu chính thức quản lý dự án. Mọi thay đổi phải được phê duyệt bởi Project Sponsor và cập nhật version.*

