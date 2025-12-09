# SCHEDULE MANAGEMENT PLAN
## Dự án: Mobile App Test Automation với Appium

---

## MỤC ĐÍCH VÀ TÁC DỤNG

**Mục đích:** Schedule Management Plan xác định các quy trình và công cụ để quản lý tiến độ dự án, bao gồm lập kế hoạch tiến độ, định nghĩa activities, ước tính duration, phát triển schedule, và kiểm soát tiến độ.

**Tác dụng:**
- Đảm bảo dự án hoàn thành đúng thời hạn (18 tuần)
- Quản lý dependencies giữa các tasks và activities
- Theo dõi và báo cáo tiến độ thực tế vs kế hoạch
- Nhận diện sớm các vấn đề về tiến độ
- Hỗ trợ resource allocation và optimization
- Cung cấp baseline để đo lường performance

**Đối tượng sử dụng:**
- **Project Manager:** Quản lý và kiểm soát tiến độ
- **Team Members:** Hiểu timeline và deadlines
- **Stakeholders:** Theo dõi progress và milestones
- **Sponsor:** Đánh giá tiến độ dự án

**Thời điểm sử dụng:**
- Tạo trong giai đoạn Planning
- Cập nhật hàng tuần trong Execution
- Review trong các sprint reviews và milestone reviews

**Mối liên hệ với các tài liệu khác:**
- Dựa trên WBS và WBS Dictionary
- Liên kết với Resource Management Plan
- Tích hợp với Risk Management Plan
- Hỗ trợ Cost Management Plan

---

## 1. THÔNG TIN DỰ ÁN

| Thông tin | Chi tiết |
|-----------|----------|
| **Tên dự án** | Mobile App Test Automation với Appium |
| **Mã dự án** | PRJ-2025-APPIUM-001 |
| **Thời gian dự án** | 18 tuần |
| **Methodology** | Agile/Scrum (2-week sprints) |
| **Ngày tạo** | 09/12/2025 |
| **Phiên bản** | 1.1 |

---

## 2. SCHEDULE MODELING

### 2.1 Methodology

**Agile/Scrum với 2-week sprints:**
- 9 sprints trong tổng số 18 tuần
- Sprint Planning: Đầu mỗi sprint
- Daily Standup: Hàng ngày, 15 phút
- Sprint Review: Cuối sprint
- Sprint Retrospective: Cuối sprint

### 2.2 Scheduling Approach

- **Top-down:** Phân rã từ phases xuống work packages
- **Bottom-up:** Estimate từng task rồi tổng hợp
- **Critical Path Method (CPM):** Xác định critical path
- **Buffer Management:** Sử dụng buffers cho uncertainties

---

## 3. QUY TRÌNH QUẢN LÝ TIẾN ĐỘ

### 3.1 Lập kế hoạch Tiến độ (Plan Schedule Management)

**Mục đích:** Xác định policies, procedures, và documentation cho quản lý tiến độ.

**Output:** Schedule Management Plan (document này)

### 3.2 Định nghĩa Activities (Define Activities)

**Mục đích:** Xác định các activities cần thiết để tạo deliverables.

**Quy trình:**
1. Decompose work packages từ WBS thành activities
2. Xác định activity attributes
3. Tạo activity list
4. Update WBS Dictionary

**Responsible:** Project Manager, QA Lead  
**Timeline:** Week 1-2

**Chi tiết:** Xem [Work Breakdown Structure](../03_Project_Documents/Work_Breakdown_Structure.md)

### 3.3 Sắp xếp thứ tự Activities (Sequence Activities)

**Mục đích:** Xác định dependencies giữa các activities.

**Dependency Types:**
- **Finish-to-Start (FS):** Activity B bắt đầu sau khi Activity A kết thúc
- **Start-to-Start (SS):** Activity B bắt đầu cùng lúc với Activity A
- **Finish-to-Finish (FF):** Activity B kết thúc cùng lúc với Activity A
- **Start-to-Finish (SF):** Activity B kết thúc khi Activity A bắt đầu

**Tool:** Precedence Diagramming Method (PDM)  
**Responsible:** Project Manager, QA Lead

### 3.4 Ước tính Duration (Estimate Activity Durations)

**Mục đích:** Ước tính thời gian cần thiết để hoàn thành mỗi activity.

**Kỹ thuật:**
- **Expert Judgment:** Dựa trên kinh nghiệm
- **Analogous Estimating:** Dựa trên dự án tương tự
- **Parametric Estimating:** Sử dụng công thức/tham số
- **Three-point Estimating:** Optimistic, Pessimistic, Most Likely
- **Bottom-up Estimating:** Estimate từng task rồi tổng hợp

**Contingency:** 15% buffer cho uncertainties

**Responsible:** Team Members, QA Lead  
**Timeline:** Week 2-3

### 3.5 Phát triển Schedule (Develop Schedule)

**Mục đích:** Tạo project schedule với timeline chi tiết.

**Quy trình:**
1. Input: Activity list, durations, dependencies, resources
2. Apply scheduling techniques (CPM, Agile)
3. Identify critical path
4. Optimize schedule (resource leveling, fast-tracking, crashing)
5. Create schedule baseline
6. Get approval

**Tool:** Jira, Microsoft Project, Excel  
**Responsible:** Project Manager  
**Timeline:** Week 3-4

**Chi tiết:** Xem [Project Schedule](../03_Project_Documents/Project_Schedule.md)

### 3.6 Kiểm soát Tiến độ (Control Schedule)

**Mục đích:** Giám sát tiến độ và quản lý thay đổi schedule.

**Quy trình:**
1. Track actual progress vs planned
2. Measure schedule performance (SV, SPI)
3. Identify variances
4. Analyze root causes
5. Take corrective/preventive actions
6. Update schedule nếu cần
7. Communicate status

**Frequency:** Daily standup, Weekly status report  
**Responsible:** Project Manager

---

## 4. PROJECT SCHEDULE OVERVIEW

### 4.1 Phases và Timeline

| Phase | Mô tả | Duration | Start Week | End Week |
|-------|-------|----------|------------|----------|
| **Phase 1** | Foundation | 4 tuần | Week 1 | Week 4 |
| **Phase 2** | Android Automation | 4 tuần | Week 5 | Week 8 |
| **Phase 3** | iOS Automation | 4 tuần | Week 9 | Week 12 |
| **Phase 4** | Integration & Optimization | 4 tuần | Week 13 | Week 16 |
| **Phase 5** | Training & Handover | 2 tuần | Week 17 | Week 18 |

### 4.2 Milestones

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

## 5. SCHEDULE BASELINE

**Version:** 1.0  
**Date:** [DD/MM/YYYY]  
**Approved by:** [Project Sponsor]

Schedule baseline này bao gồm:
- 5 phases với tổng 18 tuần
- 7 milestones
- Critical path
- Resource assignments
- Dependencies

**Lưu ý:** Mọi thay đổi schedule phải được phê duyệt và cập nhật baseline.

---

## 6. SCHEDULE PERFORMANCE MEASUREMENT

### 6.1 Key Performance Indicators (KPIs)

| KPI | Mô tả | Target |
|-----|-------|--------|
| **Schedule Variance (SV)** | EV - PV | 0 (on schedule) |
| **Schedule Performance Index (SPI)** | EV / PV | ≥ 1.0 |
| **Milestone Achievement Rate** | Milestones achieved / Total milestones | 100% |
| **On-time Delivery** | Deliverables on time / Total deliverables | ≥ 95% |

### 6.2 Reporting Frequency

- **Daily:** Standup updates
- **Weekly:** Status report với schedule metrics
- **Sprint End:** Sprint review với schedule analysis
- **Milestone:** Milestone review và sign-off

---

## 7. SCHEDULE CONTROL PROCESS

### 7.1 Variance Thresholds

| Variance Level | Action |
|----------------|--------|
| **< 5%** | Monitor, no action needed |
| **5-10%** | Investigate root cause, plan corrective action |
| **> 10%** | Escalate to Sponsor, implement recovery plan |

### 7.2 Corrective Actions

Khi có schedule variance:

1. **Analyze Root Cause:** Tại sao delay?
2. **Evaluate Options:**
   - Fast-tracking (parallel activities)
   - Crashing (thêm resources)
   - Scope reduction (nếu được phê duyệt)
   - Schedule extension (nếu được phê duyệt)
3. **Implement Action:** Execute recovery plan
4. **Monitor:** Track effectiveness
5. **Update Schedule:** Nếu cần thiết

### 7.3 Change Control

Mọi thay đổi schedule phải:
- Submit Change Request
- CCB review và approve
- Update schedule baseline
- Communicate đến stakeholders

**Chi tiết:** Xem [Change Management Plan](Change_Management_Plan.md)

---

## 8. CRITICAL PATH

### 8.1 Critical Path Activities

Critical path là chuỗi activities dài nhất xác định duration của dự án. Các activities trên critical path không có float (slack).

**Key Critical Path Activities:**
1. Framework Setup (Week 1-4)
2. Android Automation (Week 5-8)
3. iOS Automation (Week 9-12)
4. Integration & Optimization (Week 13-16)
5. Training & Handover (Week 17-18)

### 8.2 Float Management

- **Critical Path:** 0 float
- **Near-Critical Path:** Low float, cần monitor
- **Non-Critical Path:** High float, có thể delay

---

## 9. RESOURCE CALENDAR

### 9.1 Working Calendar

- **Working Days:** Monday - Friday
- **Working Hours:** 8 hours/day
- **Holidays:** Theo company calendar
- **Sprint Schedule:** 2-week sprints

### 9.2 Resource Availability

| Resource | Availability | Notes |
|----------|--------------|-------|
| QA Lead | 100% FTE | Full-time |
| Senior QA (2) | 100% FTE | Full-time |
| QA Engineers (2) | 100% FTE | Full-time |
| DevOps | 50% FTE | Part-time |

---

## 10. SCHEDULE RISKS & MITIGATION

### 10.1 Schedule Risks

| Risk | Impact | Mitigation |
|------|--------|------------|
| Activities take longer than estimated | High | 15% buffer, regular monitoring |
| Resource unavailability | Medium | Resource backup plan |
| Dependencies delay | Medium | Early identification, buffer time |
| Scope creep | High | Strict change control |
| Technical issues | Medium | Contingency planning |

**Chi tiết:** Xem [Risk Register](../03_Project_Documents/Risk_Register.md)

---

## 11. TOOLS & TECHNIQUES

### 11.1 Scheduling Tools

- **Jira:** Task tracking và sprint planning
- **Microsoft Project:** Detailed scheduling (nếu cần)
- **Excel:** Schedule tracking và reporting
- **Confluence:** Schedule documentation

### 11.2 Techniques

- Precedence Diagramming Method (PDM)
- Critical Path Method (CPM)
- Agile/Scrum methodology
- Burndown charts
- Velocity tracking

---

## 12. SCHEDULE REPORTING

### 12.1 Report Types

| Report | Frequency | Audience | Content |
|--------|-----------|----------|---------|
| **Daily Standup** | Daily | Team | Progress, blockers |
| **Weekly Status** | Weekly | PM, Stakeholders | Progress, metrics, risks |
| **Sprint Review** | Bi-weekly | All stakeholders | Sprint achievements |
| **Milestone Report** | Per milestone | Sponsor, PM | Milestone status |

### 12.2 Report Format

- Executive Summary
- Progress Summary (planned vs actual)
- Schedule Metrics (SV, SPI)
- Upcoming Activities
- Risks and Issues
- Recommendations

---

## 13. PHÊ DUYỆT

| Vai trò | Họ tên | Chữ ký | Ngày |
|---------|--------|--------|------|
| **Project Sponsor** | | | |
| **Project Manager** | | | |
| **QA Lead** | | | |

---

## 14. LỊCH SỬ THAY ĐỔI

| Version | Ngày | Người thay đổi | Mô tả thay đổi |
|---------|------|----------------|----------------|
| 1.0 | 02/12/2025 | Project Manager | Khởi tạo document |
| 1.1 | 09/12/2025 | Project Manager | Cập nhật mã dự án |

---

*Document này là một phần của Project Management Plan. Chi tiết schedule xem tại [Project Schedule](../03_Project_Documents/Project_Schedule.md).*

