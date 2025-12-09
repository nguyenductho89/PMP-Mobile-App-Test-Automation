# SCOPE MANAGEMENT PLAN
## Dự án: Mobile App Test Automation với Appium

---

## MỤC ĐÍCH VÀ TÁC DỤNG

**Mục đích:** Scope Management Plan xác định cách thức quản lý phạm vi dự án, bao gồm việc thu thập yêu cầu, định nghĩa phạm vi, tạo WBS, validate phạm vi, và kiểm soát thay đổi phạm vi.

**Tác dụng:**
- Ngăn chặn scope creep (phạm vi bị mở rộng không kiểm soát)
- Đảm bảo chỉ thực hiện công việc trong phạm vi đã được phê duyệt
- Quản lý các yêu cầu thay đổi một cách có kiểm soát thông qua Change Control Board
- Đảm bảo deliverables đáp ứng yêu cầu ban đầu
- Cung cấp cơ sở để đo lường performance và progress

**Đối tượng sử dụng:**
- **Project Manager:** Sử dụng để quản lý và kiểm soát phạm vi
- **Team Members:** Hiểu rõ công việc cần làm và không cần làm
- **Stakeholders:** Hiểu rõ những gì được bao gồm và không bao gồm trong dự án
- **Change Control Board:** Sử dụng để đánh giá các yêu cầu thay đổi phạm vi

**Thời điểm sử dụng:**
- Tạo trong giai đoạn Planning
- Tham khảo thường xuyên trong Execution để đảm bảo không vượt quá phạm vi
- Cập nhật khi có thay đổi phạm vi được phê duyệt

**Mối liên hệ với các tài liệu khác:**
- Dựa trên Project Charter (phần phạm vi)
- Liên kết với WBS và WBS Dictionary
- Tích hợp với Change Management Plan
- Hỗ trợ Requirements Management Plan

---

## 1. THÔNG TIN DỰ ÁN

| Thông tin | Chi tiết |
|-----------|----------|
| **Tên dự án** | Mobile App Test Automation với Appium |
| **Mã dự án** | PRJ-2025-APPIUM-001 |
| **Ngày tạo** | 09/12/2025 |
| **Phiên bản** | 1.1 |

---

## 2. PHẠM VI DỰ ÁN

### 2.1 Trong phạm vi (In Scope)

| # | Hạng mục | Mô tả chi tiết |
|---|----------|----------------|
| 1 | **Setup Framework** | Appium + WebDriverIO/Java + Page Object Model |
| 2 | **Android Testing** | Test trên Android 10+ (API 29+) |
| 3 | **iOS Testing** | Test trên iOS 14+ |
| 4 | **Test Types** | Functional, Regression, Smoke tests |
| 5 | **CI/CD Integration** | Jenkins/GitLab CI pipeline |
| 6 | **Reporting** | Allure Reports, Screenshots, Video recording |
| 7 | **Device Farm** | BrowserStack/Sauce Labs integration |
| 8 | **Documentation** | Setup guide, coding standards, best practices |

### 2.2 Ngoài phạm vi (Out of Scope)

- Performance testing (sử dụng tools khác như JMeter)
- Security testing
- Test trên các phiên bản OS cũ (Android < 10, iOS < 14)
- Desktop/Web application testing
- Manual testing processes
- API testing (nếu không liên quan đến mobile app flows)
- Load testing
- Stress testing

---

## 3. QUY TRÌNH QUẢN LÝ PHẠM VI

### 3.1 Thu thập Yêu cầu

**Mục đích:** Xác định và tài liệu hóa các yêu cầu của stakeholders.

**Quy trình:**
1. Phỏng vấn stakeholders (QA Lead, Dev Lead, Product Owner)
2. Review Project Charter và Business Case
3. Phân tích yêu cầu hiện tại và tương lai
4. Tài liệu hóa yêu cầu trong Requirements Management Plan
5. Validate yêu cầu với stakeholders

**Công cụ:**
- Interviews
- Workshops
- Document analysis
- Prototyping (nếu cần)

**Responsible:** QA Lead, Project Manager  
**Frequency:** Trong giai đoạn Planning và khi có yêu cầu mới

### 3.2 Định nghĩa Phạm vi

**Mục đích:** Tạo Project Scope Statement chi tiết.

**Quy trình:**
1. Phân tích yêu cầu đã thu thập
2. Xác định deliverables chính
3. Xác định acceptance criteria
4. Tạo Project Scope Statement
5. Phê duyệt bởi Sponsor và key stakeholders

**Deliverables:**
- Project Scope Statement
- In Scope và Out of Scope list
- Acceptance criteria

**Responsible:** Project Manager, QA Lead  
**Frequency:** Một lần trong Planning, cập nhật khi có thay đổi

### 3.3 Tạo Work Breakdown Structure (WBS)

**Mục đích:** Phân rã công việc thành các components nhỏ hơn, có thể quản lý được.

**Quy trình:**
1. Xác định các phases chính (5 phases)
2. Phân rã mỗi phase thành work packages
3. Xác định deliverables cho mỗi work package
4. Tạo WBS Dictionary
5. Phê duyệt WBS

**Công cụ:**
- WBS template
- Mind mapping
- Decomposition technique

**Responsible:** Project Manager, QA Lead  
**Frequency:** Một lần trong Planning, refine khi cần

**Chi tiết:** Xem [Work Breakdown Structure](../03_Project_Documents/Work_Breakdown_Structure.md)

### 3.4 Validate Phạm vi

**Mục đích:** Đảm bảo deliverables đáp ứng yêu cầu và được stakeholders chấp nhận.

**Quy trình:**
1. Review deliverables với stakeholders
2. Kiểm tra acceptance criteria
3. Thực hiện user acceptance testing (nếu áp dụng)
4. Thu thập feedback và sign-off
5. Cập nhật documentation nếu cần

**Responsible:** Project Manager, QA Lead  
**Frequency:** Sau mỗi milestone và khi có deliverable chính

### 3.5 Kiểm soát Phạm vi

**Mục đích:** Giám sát phạm vi và quản lý các thay đổi phạm vi.

**Quy trình:**
1. Theo dõi công việc thực tế vs kế hoạch
2. Nhận diện các yêu cầu thay đổi phạm vi
3. Đánh giá impact của thay đổi (schedule, cost, resources)
4. Submit Change Request đến Change Control Board
5. Thực hiện thay đổi nếu được phê duyệt
6. Cập nhật WBS và documentation

**Công cụ:**
- Change Request Form
- Impact Assessment Template
- Change Control Board (CCB)

**Responsible:** Project Manager  
**Frequency:** Liên tục trong Execution phase

**Chi tiết:** Xem [Change Management Plan](Change_Management_Plan.md)

---

## 4. ACCEPTANCE CRITERIA

### 4.1 Framework Setup (Milestone M2)

- [ ] Appium framework được cài đặt và cấu hình thành công
- [ ] CI/CD pipeline hoạt động với sample tests
- [ ] Base utilities và Page Object Model được implement
- [ ] Documentation setup guide hoàn chỉnh
- [ ] 10 sample tests chạy thành công trên cả Android và iOS

### 4.2 Android Automation (Milestone M3)

- [ ] 100 test cases Android được implement
- [ ] Pass rate ≥ 90%
- [ ] Critical flows được cover
- [ ] Test reports được generate đầy đủ

### 4.3 iOS Automation (Milestone M4)

- [ ] 100 test cases iOS được implement
- [ ] Pass rate ≥ 90%
- [ ] Platform-specific cases được handle
- [ ] Code reuse ≥ 70% giữa Android và iOS

### 4.4 Integration Complete (Milestone M5)

- [ ] Tests tự động chạy trong CI pipeline
- [ ] Reporting system hoạt động đầy đủ
- [ ] Device Farm integration thành công
- [ ] Performance tuning hoàn tất

### 4.5 Training & Handover (Milestone M6)

- [ ] Team được đào tạo và có thể maintain framework
- [ ] Documentation đầy đủ và dễ hiểu
- [ ] Knowledge transfer hoàn tất
- [ ] Support plan được thiết lập

---

## 5. DELIVERABLES CHÍNH

| # | Deliverable | Mô tả | Milestone |
|---|-------------|-------|-----------|
| 1 | Appium Framework | Base framework với Page Object Model | M2 |
| 2 | CI/CD Pipeline | Automated testing pipeline | M2 |
| 3 | Android Test Suite | 100 automated test cases cho Android | M3 |
| 4 | iOS Test Suite | 100 automated test cases cho iOS | M4 |
| 5 | Reporting System | Allure reports với screenshots và videos | M5 |
| 6 | Documentation | Setup guide, coding standards, best practices | M6 |
| 7 | Training Materials | Training slides, videos, hands-on exercises | M6 |

---

## 6. EXCLUSIONS (Loại trừ)

Các hạng mục sau **KHÔNG** nằm trong phạm vi dự án:

1. **Performance Testing:** Sử dụng tools chuyên dụng như JMeter
2. **Security Testing:** Nằm trong scope của Security team
3. **Legacy OS Support:** Chỉ support Android 10+ và iOS 14+
4. **Desktop/Web Testing:** Chỉ focus vào mobile apps
5. **Manual Testing:** Không bao gồm manual test execution
6. **API Testing:** Chỉ test API nếu liên quan trực tiếp đến mobile app flows
7. **Load/Stress Testing:** Nằm trong scope của Performance team

---

## 7. CHANGE CONTROL PROCESS

### 7.1 Change Request Form

Khi có yêu cầu thay đổi phạm vi, phải điền Change Request Form với:
- Mô tả thay đổi
- Lý do thay đổi
- Impact assessment (schedule, cost, resources)
- Alternatives considered
- Recommendation

### 7.2 Change Control Board (CCB)

**Thành viên:**
- Project Sponsor (Chair)
- Project Manager
- QA Lead
- Dev Lead (nếu liên quan)

**Quy trình:**
1. Submit Change Request
2. CCB review và đánh giá impact
3. Quyết định: Approve, Reject, hoặc Defer
4. Nếu approve: Cập nhật scope, WBS, schedule, budget
5. Communicate decision đến stakeholders

**Chi tiết:** Xem [Change Management Plan](Change_Management_Plan.md)

---

## 8. SCOPE VERIFICATION

### 8.1 Phương thức Verification

- **Milestone Reviews:** Review deliverables tại mỗi milestone
- **User Acceptance Testing:** Stakeholders test và approve deliverables
- **Sign-off:** Formal sign-off từ Sponsor và key stakeholders
- **Documentation Review:** Đảm bảo documentation đầy đủ và chính xác

### 8.2 Schedule

| Milestone | Verification Date | Responsible |
|-----------|-------------------|-------------|
| M2: Framework Setup | End of Week 4 | QA Lead, Sponsor |
| M3: Android Automation | End of Week 8 | QA Lead, Dev Lead |
| M4: iOS Automation | End of Week 12 | QA Lead, Dev Lead |
| M5: Integration Complete | End of Week 14 | QA Lead, DevOps |
| M6: Training & Handover | End of Week 16 | Project Manager, Sponsor |

---

## 9. SCOPE BASELINE

**Version:** 1.0  
**Date:** [DD/MM/YYYY]  
**Approved by:** [Project Sponsor]

Scope baseline này bao gồm:
- In Scope items (8 hạng mục)
- Out of Scope items (7 hạng mục)
- WBS với 5 phases
- 7 milestones
- Acceptance criteria

**Lưu ý:** Mọi thay đổi phạm vi phải được phê duyệt bởi Change Control Board và cập nhật baseline.

---

## 10. PHÊ DUYỆT

| Vai trò | Họ tên | Chữ ký | Ngày |
|---------|--------|--------|------|
| **Project Sponsor** | | | |
| **Project Manager** | | | |
| **QA Lead** | | | |

---

## 11. LỊCH SỬ THAY ĐỔI

| Version | Ngày | Người thay đổi | Mô tả thay đổi |
|---------|------|----------------|----------------|
| 1.0 | 02/12/2025 | Project Manager | Khởi tạo document |
| 1.1 | 09/12/2025 | Project Manager | Cập nhật mã dự án |

---

*Document này là một phần của Project Management Plan. Mọi thay đổi phạm vi phải tuân thủ Change Control Process.*

