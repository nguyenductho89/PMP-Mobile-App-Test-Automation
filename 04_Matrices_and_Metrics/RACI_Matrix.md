# RACI MATRIX
## Dự án: Mobile App Test Automation với Appium

---

## MỤC ĐÍCH VÀ TÁC DỤNG

**Mục đích:** RACI Matrix phân công trách nhiệm (Responsible, Accountable, Consulted, Informed) cho các công việc để làm rõ vai trò và trách nhiệm.

**Tác dụng:**
- Làm rõ vai trò và trách nhiệm
- Tránh confusion về ownership
- Đảm bảo accountability
- Improve coordination
- Reduce conflicts
- Enhance efficiency

**Đối tượng sử dụng:**
- **Project Manager:** Resource management
- **Team Members:** Understand responsibilities
- **Stakeholders:** Understand roles
- **QA Lead:** Team coordination

**Thời điểm sử dụng:**
- Tạo trong Planning phase
- Reference trong Execution
- Update khi có thay đổi roles

**Mối liên hệ với các tài liệu khác:**
- Liên kết với Resource Management Plan
- Tích hợp với WBS
- Hỗ trợ Stakeholder Register

---

## 1. THÔNG TIN DỰ ÁN

| Thông tin | Chi tiết |
|-----------|----------|
| **Tên dự án** | Mobile App Test Automation với Appium |
| **Mã dự án** | PRJ-2024-APPIUM-001 |
| **Ngày tạo** | [DD/MM/YYYY] |
| **Phiên bản** | 1.0 |

---

## 2. RACI DEFINITIONS

| Role | Definition |
|------|------------|
| **R - Responsible** | Người thực hiện công việc |
| **A - Accountable** | Người chịu trách nhiệm cuối cùng (chỉ một người) |
| **C - Consulted** | Người được tham vấn, cung cấp input |
| **I - Informed** | Người được thông báo về kết quả |

---

## 3. RACI MATRIX

### 3.1 Project Management Activities

| Activity | Sponsor | PM | QA Lead | Senior QA | QA Engineers | DevOps | Dev Lead |
|----------|---------|----|---------|-----------|--------------|--------|----------|
| **Project Planning** | A | R | C | C | I | I | I |
| **Budget Management** | A | R | I | I | I | I | I |
| **Schedule Management** | A | R | C | I | I | I | I |
| **Risk Management** | A | R | C | C | I | I | I |
| **Stakeholder Communication** | A | R | C | I | I | I | I |
| **Status Reporting** | A | R | C | I | I | I | I |

### 3.2 Framework Development Activities

| Activity | Sponsor | PM | QA Lead | Senior QA | QA Engineers | DevOps | Dev Lead |
|----------|---------|----|---------|-----------|--------------|--------|----------|
| **Framework Architecture** | I | A | R | C | I | C | C |
| **Page Object Model Design** | I | A | R | C | I | I | C |
| **Base Classes Development** | I | A | R | C | C | I | I |
| **Utility Classes Development** | I | A | R | C | R | I | I |
| **Code Review** | I | A | R | R | I | I | I |

### 3.3 CI/CD Activities

| Activity | Sponsor | PM | QA Lead | Senior QA | QA Engineers | DevOps | Dev Lead |
|----------|---------|----|---------|-----------|--------------|--------|----------|
| **CI/CD Setup** | I | A | C | I | I | R | I |
| **Pipeline Configuration** | I | A | C | I | I | R | I |
| **CI/CD Maintenance** | I | A | C | I | I | R | I |
| **Infrastructure Management** | I | A | I | I | I | R | I |

### 3.4 Test Development Activities

| Activity | Sponsor | PM | QA Lead | Senior QA | QA Engineers | DevOps | Dev Lead |
|----------|---------|----|---------|-----------|--------------|--------|----------|
| **Test Case Design** | I | A | R | R | R | I | C |
| **Page Objects Development** | I | A | R | R | R | I | C |
| **Test Implementation** | I | A | R | C | R | I | C |
| **Test Execution** | I | A | R | C | R | I | I |
| **Defect Reporting** | I | A | R | C | R | I | C |
| **Test Maintenance** | I | A | R | C | R | I | I |

### 3.5 Quality Activities

| Activity | Sponsor | PM | QA Lead | Senior QA | QA Engineers | DevOps | Dev Lead |
|----------|---------|----|---------|-----------|--------------|--------|----------|
| **Quality Planning** | A | R | R | C | I | I | I |
| **Quality Assurance** | I | A | R | R | R | I | I |
| **Quality Control** | I | A | R | R | R | I | I |
| **Quality Reporting** | A | R | R | C | I | I | I |
| **Code Reviews** | I | A | R | R | C | I | I |

### 3.6 Training & Documentation Activities

| Activity | Sponsor | PM | QA Lead | Senior QA | QA Engineers | DevOps | Dev Lead |
|----------|---------|----|---------|-----------|--------------|--------|----------|
| **Documentation** | I | A | R | R | R | I | I |
| **Training Delivery** | I | A | R | R | C | I | I |
| **Knowledge Transfer** | I | A | R | R | R | I | I |

### 3.7 Integration Activities

| Activity | Sponsor | PM | QA Lead | Senior QA | QA Engineers | DevOps | Dev Lead |
|----------|---------|----|---------|-----------|--------------|--------|----------|
| **Device Farm Integration** | I | A | C | I | I | R | I |
| **Reporting Setup** | I | A | R | C | R | C | I |
| **Performance Optimization** | I | A | R | C | C | C | I |

---

## 4. ROLES SUMMARY

### 4.1 Sponsor

**Accountable for:**
- Project approval
- Budget approval
- Strategic decisions
- Major escalations

**Informed about:**
- Project status
- Major milestones
- Budget status
- Risk escalations

### 4.2 Project Manager

**Responsible for:**
- Overall project management
- Planning và coordination
- Status reporting
- Stakeholder communication
- Risk management

**Accountable for:**
- Project delivery
- Schedule management
- Budget management
- Communication

### 4.3 QA Lead

**Responsible for:**
- Framework architecture
- Technical leadership
- Code reviews
- Quality assurance
- Team mentoring

**Accountable for:**
- Technical quality
- Framework design
- Code quality standards

**Consulted on:**
- Technical decisions
- Architecture decisions
- Quality standards

### 4.4 Senior QA Automation

**Responsible for:**
- Complex test development
- Code reviews
- Mentoring junior engineers
- Technical guidance

**Consulted on:**
- Technical decisions
- Test design
- Code reviews

### 4.5 QA Automation Engineers

**Responsible for:**
- Test implementation
- Test execution
- Defect reporting
- Documentation

**Informed about:**
- Project status
- Technical decisions
- Process changes

### 4.6 DevOps Engineer

**Responsible for:**
- CI/CD setup và maintenance
- Infrastructure management
- Tool configuration

**Consulted on:**
- Infrastructure decisions
- CI/CD configuration
- Performance optimization

### 4.7 Dev Lead

**Consulted on:**
- Integration coordination
- Technical discussions
- Locator strategy
- App builds

**Informed about:**
- Test status
- Integration status
- Change notifications

---

## 5. RACI VALIDATION

### 5.1 Validation Criteria

- [ ] Every activity has at least one Responsible (R)
- [ ] Every activity has exactly one Accountable (A)
- [ ] No activity has multiple Accountable
- [ ] Roles are clearly defined
- [ ] Matrix is reviewed và approved

### 5.2 Common Issues

- Multiple Accountable for same activity
- No Responsible assigned
- Unclear roles
- Missing stakeholders

---

## 6. PHÊ DUYỆT

| Vai trò | Họ tên | Chữ ký | Ngày |
|---------|--------|--------|------|
| **Project Manager** | | | |
| **QA Lead** | | | |
| **Project Sponsor** | | | |

---

## 7. LỊCH SỬ THAY ĐỔI

| Version | Ngày | Người thay đổi | Mô tả thay đổi |
|---------|------|----------------|----------------|
| 1.0 | [DD/MM/YYYY] | [Tên] | Khởi tạo document |

---

*Document này là một phần của Matrices and Metrics. Chi tiết resource management xem tại [Resource Management Plan](../02_Management_Plans/Resource_Management_Plan.md).*

