# RESOURCE MANAGEMENT PLAN
## Dự án: Mobile App Test Automation với Appium

---

## MỤC ĐÍCH VÀ TÁC DỤNG

**Mục đích:** Resource Management Plan xác định cách thức lập kế hoạch, thu hút, quản lý, và phát triển nguồn lực dự án (nhân sự, thiết bị, công cụ) để đảm bảo đủ nguồn lực khi cần và tối ưu hóa việc sử dụng.

**Tác dụng:**
- Đảm bảo đủ nguồn lực (nhân sự, thiết bị, công cụ) khi cần
- Tối ưu hóa việc sử dụng nguồn lực
- Quản lý conflicts về nguồn lực
- Phát triển team và skills
- Đảm bảo team có skills cần thiết
- Quản lý performance và motivation

**Đối tượng sử dụng:**
- **Project Manager:** Quản lý và phân bổ nguồn lực
- **QA Lead:** Quản lý team và technical resources
- **HR/Resource Managers:** Thu hút và allocate resources
- **Team Members:** Hiểu roles và responsibilities

**Thời điểm sử dụng:**
- Tạo trong giai đoạn Planning
- Cập nhật khi có thay đổi về resources
- Tham khảo trong suốt Execution

**Mối liên hệ với các tài liệu khác:**
- Liên kết với Schedule Management Plan
- Tích hợp với Cost Management Plan
- Hỗ trợ Stakeholder Engagement Plan
- Liên quan đến RACI Matrix

---

## 1. THÔNG TIN DỰ ÁN

| Thông tin | Chi tiết |
|-----------|----------|
| **Tên dự án** | Mobile App Test Automation với Appium |
| **Mã dự án** | PRJ-2024-APPIUM-001 |
| **Thời gian dự án** | 18 tuần |
| **Ngày tạo** | [DD/MM/YYYY] |
| **Phiên bản** | 1.0 |

---

## 2. NGUỒN LỰC NHÂN SỰ

### 2.1 Team Structure

| Vai trò | Số lượng | FTE | Kỹ năng yêu cầu | Key Responsibilities |
|---------|----------|-----|-----------------|----------------------|
| **QA Lead/Architect** | 1 | 100% | Appium, Java/JS, CI/CD, 5+ năm exp | Framework design, code review, team leadership |
| **Senior QA Automation** | 2 | 100% | Appium, Programming, 3+ năm exp | Test development, mentoring, technical guidance |
| **QA Automation** | 2 | 100% | Basic programming, testing knowledge | Test implementation, execution |
| **DevOps Engineer** | 1 | 50% | Jenkins, Docker, Cloud services | CI/CD setup, infrastructure |

### 2.2 Resource Allocation by Phase

| Phase | QA Lead | Senior QA (2) | QA Engineers (2) | DevOps |
|-------|---------|---------------|-------------------|--------|
| **Phase 1: Foundation** | 100% | 100% | 100% | 50% |
| **Phase 2: Android** | 100% | 100% | 100% | 25% |
| **Phase 3: iOS** | 100% | 100% | 100% | 25% |
| **Phase 4: Integration** | 100% | 100% | 100% | 50% |
| **Phase 5: Training** | 100% | 50% | 50% | 25% |

### 2.3 Skills Matrix

| Skill | QA Lead | Senior QA | QA Engineer | DevOps |
|-------|---------|-----------|-------------|--------|
| **Appium** | Expert | Advanced | Intermediate | Basic |
| **Java/JavaScript** | Expert | Advanced | Intermediate | Basic |
| **CI/CD** | Advanced | Intermediate | Basic | Expert |
| **Page Object Model** | Expert | Advanced | Intermediate | - |
| **Mobile Testing** | Expert | Advanced | Intermediate | - |
| **Test Automation** | Expert | Advanced | Intermediate | - |

---

## 3. QUY TRÌNH QUẢN LÝ NGUỒN LỰC

### 3.1 Lập kế hoạch Nguồn lực (Plan Resource Management)

**Mục đích:** Xác định nguồn lực cần thiết cho dự án.

**Quy trình:**
1. Analyze WBS và activities
2. Identify resource requirements
3. Define roles và responsibilities
4. Create resource breakdown structure
5. Document resource management plan

**Output:** Resource Management Plan (document này)

### 3.2 Ước tính Hoạt động Nguồn lực (Estimate Activity Resources)

**Mục đích:** Ước tính loại và số lượng nguồn lực cần thiết.

**Kỹ thuật:**
- Expert judgment
- Bottom-up estimating
- Analogous estimating
- Parametric estimating

**Responsible:** Project Manager, QA Lead  
**Timeline:** Week 1-2

### 3.3 Thu hút Nguồn lực (Acquire Resources)

**Mục đích:** Thu hút và assign resources cho dự án.

**Quy trình:**
1. Identify available resources
2. Negotiate với resource managers
3. Assign resources
4. Onboard resources
5. Communicate assignments

**Responsible:** Project Manager, HR  
**Timeline:** Week 1

### 3.4 Phát triển Team (Develop Team)

**Mục đích:** Cải thiện competencies và interaction của team.

**Activities:**
- Training (Appium, best practices)
- Pair programming
- Code reviews
- Knowledge sharing sessions
- Team building activities

**Responsible:** QA Lead, Project Manager  
**Frequency:** Continuous

### 3.5 Quản lý Team (Manage Team)

**Mục đích:** Theo dõi performance, resolve issues, và manage changes.

**Activities:**
- Performance reviews
- One-on-one meetings
- Conflict resolution
- Recognition và rewards
- Resource adjustments

**Responsible:** Project Manager, QA Lead  
**Frequency:** Weekly

### 3.6 Kiểm soát Nguồn lực (Control Resources)

**Mục đích:** Đảm bảo resources được sử dụng hiệu quả.

**Activities:**
- Monitor resource utilization
- Track actual vs planned
- Identify resource conflicts
- Optimize resource allocation
- Report resource status

**Responsible:** Project Manager  
**Frequency:** Weekly

---

## 4. NGUỒN LỰC THIẾT BỊ & CÔNG CỤ

### 4.1 Test Devices

| Device Type | Quantity | Purpose | Location |
|-------------|----------|---------|----------|
| **Android Devices** | 5 | Android testing | Office/Remote |
| **iOS Devices** | 3 | iOS testing | Office/Remote |
| **Emulators/Simulators** | Unlimited | Development và testing | Cloud/Local |

### 4.2 Development Tools

| Tool | Purpose | License Type |
|------|---------|--------------|
| **IDE** | IntelliJ IDEA / VS Code | Free - $500/year |
| **Version Control** | Git/GitHub/GitLab | Free - $500/year |
| **CI/CD** | Jenkins / GitLab CI | Free - $2,000/year |
| **Device Farm** | BrowserStack / Sauce Labs | $3,000 - $10,000/year |
| **Reporting** | Allure Reports | Free |

### 4.3 Infrastructure

| Infrastructure | Purpose | Location |
|---------------|---------|----------|
| **CI/CD Servers** | Automated test execution | Cloud/On-premise |
| **Test Execution Environment** | Run tests | Cloud/On-premise |
| **Device Farm** | Cloud device testing | Cloud (BrowserStack/Sauce Labs) |

---

## 5. TRAINING & DEVELOPMENT

### 5.1 Training Plan

| Training Topic | Audience | Duration | Timeline |
|----------------|----------|----------|----------|
| **Appium Fundamentals** | All QA team | 2 days | Week 1 |
| **Page Object Model** | All QA team | 1 day | Week 1 |
| **CI/CD Integration** | QA Lead, DevOps | 1 day | Week 2 |
| **Best Practices** | All team | Ongoing | Continuous |
| **Framework Architecture** | QA Lead, Senior QA | 1 day | Week 2 |

### 5.2 Knowledge Sharing

- **Weekly Tech Talks:** Team members share knowledge
- **Code Review Sessions:** Learn from reviews
- **Pair Programming:** Knowledge transfer
- **Documentation:** Maintain knowledge base

---

## 6. RESOURCE CALENDAR

### 6.1 Working Schedule

- **Working Days:** Monday - Friday
- **Working Hours:** 8 hours/day
- **Sprint Schedule:** 2-week sprints
- **Holidays:** Theo company calendar

### 6.2 Resource Availability

| Resource | Availability | Notes |
|----------|--------------|-------|
| QA Lead | 100% FTE, Full-time | Dedicated to project |
| Senior QA (2) | 100% FTE, Full-time | Dedicated to project |
| QA Engineers (2) | 100% FTE, Full-time | Dedicated to project |
| DevOps | 50% FTE, Part-time | Shared với other projects |

---

## 7. RESOURCE ROLES & RESPONSIBILITIES

### 7.1 QA Lead/Architect

- Design framework architecture
- Review code và tests
- Mentor team members
- Technical decision-making
- Quality assurance

### 7.2 Senior QA Automation

- Develop complex test scenarios
- Review code và tests
- Mentor junior engineers
- Technical guidance
- Best practices implementation

### 7.3 QA Automation Engineers

- Implement test cases
- Execute tests
- Report defects
- Maintain test documentation
- Follow coding standards

### 7.4 DevOps Engineer

- Setup CI/CD pipeline
- Maintain infrastructure
- Monitor systems
- Troubleshoot issues
- Optimize performance

**Chi tiết:** Xem [RACI Matrix](../04_Matrices_and_Metrics/RACI_Matrix.md)

---

## 8. RESOURCE CONFLICTS & RESOLUTION

### 8.1 Common Conflicts

- Resource unavailability
- Competing priorities
- Skill gaps
- Workload imbalance

### 8.2 Resolution Process

1. Identify conflict
2. Assess impact
3. Discuss với stakeholders
4. Find solution
5. Implement
6. Monitor

**Responsible:** Project Manager  
**Escalation:** Sponsor nếu cần

---

## 9. RESOURCE PERFORMANCE MANAGEMENT

### 9.1 Performance Metrics

| Metric | Description | Target |
|--------|-------------|--------|
| **Resource Utilization** | % time spent on project | 100% (dedicated) |
| **Productivity** | Tests developed per sprint | Per sprint goal |
| **Quality** | Code quality, test quality | Per quality standards |
| **On-time Delivery** | Deliverables on time | ≥ 95% |

### 9.2 Performance Reviews

- **Weekly:** One-on-one với team members
- **Sprint End:** Sprint review
- **Monthly:** Performance review với Project Manager
- **Project End:** Final performance review

---

## 10. RESOURCE RISKS & MITIGATION

### 10.1 Resource Risks

| Risk | Impact | Mitigation |
|------|--------|------------|
| Resource unavailability | High | Backup resources, cross-training |
| Skill gaps | Medium | Training, mentoring |
| Resource conflicts | Medium | Clear priorities, communication |
| Team turnover | High | Knowledge documentation, retention |

**Chi tiết:** Xem [Risk Register](../03_Project_Documents/Risk_Register.md)

---

## 11. PHÊ DUYỆT

| Vai trò | Họ tên | Chữ ký | Ngày |
|---------|--------|--------|------|
| **Project Manager** | | | |
| **QA Lead** | | | |
| **HR Manager** | | | |

---

## 12. LỊCH SỬ THAY ĐỔI

| Version | Ngày | Người thay đổi | Mô tả thay đổi |
|---------|------|----------------|----------------|
| 1.0 | [DD/MM/YYYY] | [Tên] | Khởi tạo document |

---

*Document này là một phần của Project Management Plan. Chi tiết roles và responsibilities xem tại [RACI Matrix](../04_Matrices_and_Metrics/RACI_Matrix.md).*

