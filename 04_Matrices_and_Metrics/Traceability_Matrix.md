# REQUIREMENTS TRACEABILITY MATRIX
## Dự án: Mobile App Test Automation với Appium

---

## MỤC ĐÍCH VÀ TÁC DỤNG

**Mục đích:** Traceability Matrix liên kết requirements với deliverables, test cases, và các artifacts khác để đảm bảo không bỏ sót yêu cầu.

**Tác dụng:**
- Đảm bảo tất cả requirements được implement
- Trace requirements đến test cases
- Hỗ trợ impact analysis khi có changes
- Verify coverage của requirements
- Đảm bảo không có gold plating (thêm features không yêu cầu)

**Đối tượng sử dụng:**
- **QA Lead:** Verify coverage
- **Project Manager:** Track requirements status
- **Team Members:** Understand requirements linkage

**Mối liên hệ với các tài liệu khác:**
- Liên kết với Requirements Management Plan
- Tích hợp với WBS
- Hỗ trợ Scope Management

---

## 1. THÔNG TIN DỰ ÁN

| Thông tin | Chi tiết |
|-----------|----------|
| **Tên dự án** | Mobile App Test Automation với Appium |
| **Mã dự án** | PRJ-2025-APPIUM-001 |
| **Ngày tạo** | 02/12/2025 |
| **Phiên bản** | 1.0 |

---

## 2. REQUIREMENTS TRACEABILITY MATRIX

### 2.1 Functional Requirements

| Req ID | Requirement | Priority | Source | WBS | Design | Test Case | Status | Verified |
|--------|-------------|----------|--------|-----|--------|-----------|--------|----------|
| FR-001 | Framework phải support Android 10+ | High | Charter | 1.1.2 | FW-Design-001 | TC-001-005 | In Progress | ☐ |
| FR-002 | Framework phải support iOS 14+ | High | Charter | 1.3.1 | FW-Design-002 | TC-101-105 | Planned | ☐ |
| FR-003 | Page Object Model implementation | High | Tech Spec | 1.1.2 | FW-Design-003 | TC-010-015 | In Progress | ☐ |
| FR-004 | CI/CD Integration với Jenkins | High | Charter | 1.1.3 | CI-Design-001 | TC-CI-001-010 | Planned | ☐ |
| FR-005 | Allure Reporting integration | Medium | Charter | 1.4.2 | RP-Design-001 | TC-RP-001-005 | Planned | ☐ |
| FR-006 | Device Farm integration | Medium | Charter | 1.4.3 | DF-Design-001 | TC-DF-001-005 | Planned | ☐ |
| FR-007 | Video recording cho failed tests | Low | Stakeholder | 1.4.2 | RP-Design-002 | TC-RP-010 | Planned | ☐ |
| FR-008 | Screenshot capture | Medium | Stakeholder | 1.4.2 | RP-Design-003 | TC-RP-015 | Planned | ☐ |
| FR-009 | Retry mechanism cho flaky tests | High | Tech Spec | 1.1.4 | FW-Design-010 | TC-020 | Planned | ☐ |
| FR-010 | Parallel test execution | Medium | Charter | 1.4.4 | PE-Design-001 | TC-PE-001-005 | Planned | ☐ |

### 2.2 Non-Functional Requirements

| Req ID | Requirement | Priority | Source | WBS | Design | Test Case | Status | Verified |
|--------|-------------|----------|--------|-----|--------|-----------|--------|----------|
| NFR-001 | Test execution time < 30 phút | Medium | Charter | 1.4.4 | PE-Design-002 | TC-PERF-001 | Planned | ☐ |
| NFR-002 | Code coverage > 80% | High | Quality Plan | 1.2.3 | - | TC-COV-001 | Planned | ☐ |
| NFR-003 | Test pass rate ≥ 95% | High | Quality Plan | 1.2.4 | - | TC-QUAL-001 | Planned | ☐ |
| NFR-004 | Framework stability ≥ 99% | High | Quality Plan | 1.4.4 | - | TC-STAB-001 | Planned | ☐ |
| NFR-005 | Documentation completeness 100% | Medium | Charter | 1.5.1 | - | - | Planned | ☐ |

### 2.3 Test Automation Requirements

| Req ID | Requirement | # Test Cases | Covered | Status |
|--------|-------------|--------------|---------|--------|
| TAR-001 | Login flow automation | 10 | 0 | Planned |
| TAR-002 | Registration flow automation | 8 | 0 | Planned |
| TAR-003 | Main navigation automation | 15 | 0 | Planned |
| TAR-004 | Search functionality automation | 12 | 0 | Planned |
| TAR-005 | Profile management automation | 10 | 0 | Planned |
| TAR-006 | Settings automation | 8 | 0 | Planned |
| TAR-007 | Notifications automation | 5 | 0 | Planned |
| TAR-008 | Payment flow automation | 15 | 0 | Planned |
| TAR-009 | Order management automation | 12 | 0 | Planned |
| TAR-010 | Logout flow automation | 5 | 0 | Planned |

---

## 3. COVERAGE SUMMARY

### 3.1 Requirements Coverage

| Category | Total | Covered | Not Covered | % Coverage |
|----------|-------|---------|-------------|------------|
| Functional | 10 | 0 | 10 | 0% |
| Non-Functional | 5 | 0 | 5 | 0% |
| Test Automation | 10 | 0 | 10 | 0% |
| **TOTAL** | **25** | **0** | **25** | **0%** |

### 3.2 Test Case Coverage

| Platform | Planned | Implemented | Passed | % Complete |
|----------|---------|-------------|--------|------------|
| Android | 100 | 0 | 0 | 0% |
| iOS | 100 | 0 | 0 | 0% |
| **TOTAL** | **200** | **0** | **0** | **0%** |

---

## 4. STATUS DEFINITIONS

| Status | Mô tả |
|--------|-------|
| **Planned** | Requirement đã được xác định, chưa bắt đầu implement |
| **In Progress** | Đang được implement |
| **Implemented** | Đã implement, chưa verify |
| **Verified** | Đã verify và pass |
| **Deferred** | Tạm hoãn |
| **Cancelled** | Đã hủy |

---

## 5. CHANGE HISTORY

| Date | Req ID | Change | Reason | Impact |
|------|--------|--------|--------|--------|
| | | | | |

---

## 6. LỊCH SỬ THAY ĐỔI

| Version | Ngày | Người thay đổi | Mô tả thay đổi |
|---------|------|----------------|----------------|
| 1.0 | 02/12/2025 | Project Manager | Khởi tạo document |

---

*Document này là một phần của Matrices and Metrics. Cập nhật regularly trong quá trình implement.*
