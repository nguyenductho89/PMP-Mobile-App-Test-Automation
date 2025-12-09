# CONFIGURATION MANAGEMENT PLAN
## Dự án: Mobile App Test Automation với Appium

---

## MỤC ĐÍCH VÀ TÁC DỤNG

**Mục đích:** Configuration Management Plan xác định cách thức quản lý các cấu hình và phiên bản của deliverables để đảm bảo traceability, consistency, và control của project artifacts.

**Tác dụng:**
- Đảm bảo traceability của các thay đổi
- Quản lý versions và baselines một cách có hệ thống
- Hỗ trợ việc rollback khi cần
- Đảm bảo consistency giữa các environments
- Bảo vệ project artifacts
- Hỗ trợ collaboration và coordination

**Đối tượng sử dụng:**
- **Project Manager:** Quản lý configuration management
- **QA Lead:** Quản lý technical configurations
- **Team Members:** Follow configuration management processes
- **DevOps:** Quản lý infrastructure configurations

**Thời điểm sử dụng:**
- Tạo trong giai đoạn Planning
- Áp dụng trong suốt vòng đời dự án
- Cập nhật khi có thay đổi về configurations

**Mối liên hệ với các tài liệu khác:**
- Liên kết với Change Management Plan
- Tích hợp với Quality Management Plan
- Hỗ trợ Version Control processes

---

## 1. THÔNG TIN DỰ ÁN

| Thông tin | Chi tiết |
|-----------|----------|
| **Tên dự án** | Mobile App Test Automation với Appium |
| **Mã dự án** | PRJ-2025-APPIUM-001 |
| **Ngày tạo** | [DD/MM/YYYY] |
| **Phiên bản** | 1.0 |

---

## 2. CONFIGURATION ITEMS (CIs)

### 2.1 Configuration Item Categories

| Category | Description | Examples |
|----------|-------------|----------|
| **Code** | Source code, test scripts | Test files, Page Objects, Utilities |
| **Documentation** | Project documents | Plans, Reports, Guides |
| **Configuration Files** | Config files | Appium config, CI/CD config |
| **Infrastructure** | Infrastructure configs | CI/CD pipelines, Environments |
| **Tools & Libraries** | Dependencies | Package.json, pom.xml, requirements.txt |

### 2.2 Key Configuration Items

| CI | Type | Location | Owner |
|----|------|----------|-------|
| **Test Framework** | Code | Git repository | QA Lead |
| **Page Objects** | Code | Git repository | QA Engineers |
| **Test Scripts** | Code | Git repository | QA Engineers |
| **CI/CD Pipeline** | Configuration | GitLab/Jenkins | DevOps |
| **Appium Config** | Configuration | Git repository | QA Lead |
| **Project Documentation** | Documentation | Confluence | Project Manager |
| **Test Data** | Data | Git repository | QA Engineers |

---

## 3. VERSION CONTROL

### 3.1 Version Control System

**Tool:** Git/GitHub/GitLab

**Repository Structure:**
```
project-root/
├── src/
│   ├── pages/          # Page Objects
│   ├── tests/          # Test scripts
│   ├── utils/          # Utilities
│   └── config/         # Configuration files
├── docs/               # Documentation
├── reports/            # Test reports
└── README.md
```

### 3.2 Branching Strategy

| Branch | Purpose | Who Can Merge |
|--------|---------|---------------|
| **main/master** | Production-ready code | QA Lead |
| **develop** | Integration branch | QA Lead |
| **feature/** | Feature development | Feature owner |
| **hotfix/** | Urgent fixes | QA Lead |

### 3.3 Version Numbering

**Format:** Major.Minor.Patch (Semantic Versioning)

- **Major:** Breaking changes
- **Minor:** New features, backward compatible
- **Patch:** Bug fixes, backward compatible

**Example:** v1.2.3

---

## 4. BASELINE MANAGEMENT

### 4.1 Baseline Definition

**Baseline:** Approved version of configuration item được sử dụng làm reference point.

### 4.2 Baseline Types

| Baseline | Description | When Created |
|----------|-------------|--------------|
| **Scope Baseline** | Approved scope | After scope approval |
| **Schedule Baseline** | Approved schedule | After schedule approval |
| **Cost Baseline** | Approved budget | After budget approval |
| **Technical Baseline** | Approved technical design | After design approval |

### 4.3 Baseline Process

1. **Develop:** Develop configuration item
2. **Review:** Review và approve
3. **Baseline:** Create baseline
4. **Control:** Control changes to baseline
5. **Update:** Update baseline khi có approved change

---

## 5. CHANGE CONTROL FOR CONFIGURATIONS

### 5.1 Configuration Change Process

1. **Request:** Submit change request
2. **Impact Assessment:** Assess impact
3. **Review:** CCB review
4. **Approve:** Approve change
5. **Implement:** Implement change
6. **Test:** Test change
7. **Baseline:** Update baseline
8. **Release:** Release new version

**Chi tiết:** Xem [Change Management Plan](Change_Management_Plan.md)

### 5.2 Configuration Change Types

| Change Type | Approval Required | Process |
|-------------|-------------------|---------|
| **Major Change** | CCB | Full change process |
| **Minor Change** | QA Lead | Simplified process |
| **Patch** | Team Lead | Quick process |

---

## 6. CONFIGURATION STATUS ACCOUNTING

### 6.1 Status Tracking

Track status của mỗi configuration item:
- **Development:** Under development
- **Review:** Under review
- **Approved:** Approved
- **Baselined:** Baselined
- **Released:** Released
- **Obsolete:** No longer used

### 6.2 Configuration Status Report

| CI | Version | Status | Owner | Last Updated |
|----|---------|--------|-------|--------------|
| Test Framework | v1.0.0 | Released | QA Lead | [Date] |
| Page Objects | v1.2.0 | Approved | QA Engineers | [Date] |
| CI/CD Pipeline | v2.1.0 | Baselined | DevOps | [Date] |

---

## 7. CONFIGURATION AUDIT

### 7.1 Audit Types

| Audit Type | Purpose | Frequency |
|------------|---------|-----------|
| **Functional Audit** | Verify CI meets requirements | Per milestone |
| **Physical Audit** | Verify CI exists và accessible | Monthly |
| **Baseline Audit** | Verify baseline integrity | Per baseline |

### 7.2 Audit Process

1. **Plan:** Plan audit
2. **Execute:** Execute audit
3. **Report:** Report findings
4. **Action:** Take corrective actions
5. **Verify:** Verify actions

---

## 8. CONFIGURATION MANAGEMENT TOOLS

### 8.1 Tools

| Tool | Purpose |
|------|---------|
| **Git** | Version control |
| **GitHub/GitLab** | Repository hosting |
| **Confluence** | Documentation management |
| **Jira** | Change tracking |
| **CI/CD Tools** | Automated builds và deployments |

### 8.2 Tool Configuration

- **Git:** Repository setup, branching strategy
- **GitHub/GitLab:** Access control, permissions
- **Confluence:** Space structure, permissions
- **Jira:** Project setup, workflows

---

## 9. CONFIGURATION MANAGEMENT ROLES & RESPONSIBILITIES

| Role | Responsibilities |
|------|------------------|
| **Configuration Manager** | Overall configuration management (PM) |
| **QA Lead** | Technical configurations, code baselines |
| **Team Members** | Follow processes, maintain configurations |
| **DevOps** | Infrastructure configurations |

---

## 10. CONFIGURATION MANAGEMENT PROCESSES

### 10.1 Check-in Process

1. Review code changes
2. Run tests
3. Update documentation
4. Commit với clear message
5. Create Pull Request
6. Code review
7. Merge to develop/main

### 10.2 Check-out Process

1. Create feature branch
2. Check out code
3. Make changes
4. Test locally
5. Commit changes
6. Push branch
7. Create Pull Request

### 10.3 Release Process

1. Finalize changes
2. Update version numbers
3. Create release branch
4. Run full test suite
5. Create release notes
6. Tag release
7. Deploy to production
8. Update documentation

---

## 11. CONFIGURATION MANAGEMENT STANDARDS

### 11.1 Naming Conventions

| Item | Convention | Example |
|------|------------|---------|
| **Branches** | feature/description, hotfix/description | feature/login-tests |
| **Tags** | vMajor.Minor.Patch | v1.2.3 |
| **Files** | camelCase hoặc kebab-case | loginPage.js, login-page.js |
| **Commits** | Verb + description | "Add login test cases" |

### 11.2 Documentation Standards

- All code must have comments
- All functions must be documented
- README files for major components
- Change logs maintained
- API documentation (nếu có)

---

## 12. CONFIGURATION MANAGEMENT RISKS & MITIGATION

### 12.1 Configuration Risks

| Risk | Impact | Mitigation |
|------|--------|------------|
| Version conflicts | Medium | Branching strategy, code reviews |
| Lost configurations | High | Version control, backups |
| Unauthorized changes | High | Access control, reviews |
| Configuration drift | Medium | Regular audits, automation |

**Chi tiết:** Xem [Risk Register](../03_Project_Documents/Risk_Register.md)

---

## 13. PHÊ DUYỆT

| Vai trò | Họ tên | Chữ ký | Ngày |
|---------|--------|--------|------|
| **Project Manager** | | | |
| **QA Lead** | | | |
| **DevOps** | | | |

---

## 14. LỊCH SỬ THAY ĐỔI

| Version | Ngày | Người thay đổi | Mô tả thay đổi |
|---------|------|----------------|----------------|
| 1.0 | [DD/MM/YYYY] | [Tên] | Khởi tạo document |

---

*Document này là một phần của Project Management Plan. Configuration management sẽ được enforced thông qua version control và change management processes.*

