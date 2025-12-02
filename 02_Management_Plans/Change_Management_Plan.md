# CHANGE MANAGEMENT PLAN
## Dự án: Mobile App Test Automation với Appium

---

## MỤC ĐÍCH VÀ TÁC DỤNG

**Mục đích:** Change Management Plan xác định quy trình quản lý các thay đổi trong dự án để đảm bảo thay đổi được đánh giá, phê duyệt, và thực hiện một cách có kiểm soát.

**Tác dụng:**
- Kiểm soát các thay đổi một cách có hệ thống
- Đánh giá tác động của thay đổi (scope, schedule, cost)
- Đảm bảo chỉ những thay đổi được phê duyệt mới được thực hiện
- Giảm thiểu scope creep và uncontrolled changes
- Bảo vệ project baselines
- Đảm bảo traceability của changes

**Đối tượng sử dụng:**
- **Project Manager:** Quản lý change process
- **Change Control Board (CCB):** Review và approve changes
- **Team Members:** Submit change requests
- **Stakeholders:** Request changes

**Thời điểm sử dụng:**
- Tạo trong giai đoạn Planning
- Áp dụng trong suốt Execution
- Cập nhật khi có thay đổi về process

**Mối liên hệ với các tài liệu khác:**
- Liên kết với Scope Management Plan
- Tích hợp với Schedule và Cost Management Plans
- Hỗ trợ Configuration Management Plan

---

## 1. THÔNG TIN DỰ ÁN

| Thông tin | Chi tiết |
|-----------|----------|
| **Tên dự án** | Mobile App Test Automation với Appium |
| **Mã dự án** | PRJ-2024-APPIUM-001 |
| **Ngày tạo** | [DD/MM/YYYY] |
| **Phiên bản** | 1.0 |

---

## 2. CHANGE MANAGEMENT APPROACH

### 2.1 Change Philosophy

- **Controlled:** Tất cả changes phải qua change control process
- **Documented:** Mọi changes phải được document
- **Assessed:** Impact assessment bắt buộc
- **Approved:** CCB approval required
- **Tracked:** Changes được track và monitor

### 2.2 Types of Changes

| Change Type | Description | Examples |
|-------------|-------------|----------|
| **Scope Change** | Thay đổi phạm vi dự án | Add/remove features, deliverables |
| **Schedule Change** | Thay đổi timeline | Extend deadline, change milestones |
| **Cost Change** | Thay đổi budget | Increase/decrease budget |
| **Resource Change** | Thay đổi nguồn lực | Add/remove team members |
| **Technical Change** | Thay đổi kỹ thuật | Change tools, architecture |
| **Process Change** | Thay đổi quy trình | Change methodology, processes |

---

## 3. CHANGE CONTROL BOARD (CCB)

### 3.1 CCB Composition

| Role | Name | Responsibility |
|------|------|----------------|
| **Chair** | Project Sponsor | Final decision authority |
| **Member** | Project Manager | Change evaluation, recommendation |
| **Member** | QA Lead | Technical evaluation |
| **Member** | Dev Lead | Technical evaluation (nếu liên quan) |

### 3.2 CCB Responsibilities

- Review change requests
- Evaluate impact
- Make approve/reject/defer decisions
- Prioritize changes
- Monitor change implementation
- Review change effectiveness

### 3.3 CCB Meeting Schedule

- **Regular:** Monthly hoặc as needed
- **Emergency:** As needed for urgent changes
- **Quorum:** Minimum 3 members (including Chair)

---

## 4. CHANGE REQUEST PROCESS

### 4.1 Change Request Workflow

```
1. Identify Change
   ↓
2. Document Change Request
   ↓
3. Impact Assessment
   ↓
4. Submit to CCB
   ↓
5. CCB Review
   ↓
6. Decision (Approve/Reject/Defer)
   ↓
7. Implement (if approved)
   ↓
8. Update Baselines
   ↓
9. Communicate
   ↓
10. Monitor & Close
```

### 4.2 Change Request Form

**Required Information:**
- Change Request ID
- Date submitted
- Submitted by
- Change description
- Reason for change
- Change type (Scope/Schedule/Cost/Resource/Technical/Process)
- Impact assessment:
  - Scope impact
  - Schedule impact
  - Cost impact
  - Resource impact
  - Risk impact
- Alternatives considered
- Recommendation
- Priority (High/Medium/Low)
- CCB decision
- Implementation date
- Status

---

## 5. IMPACT ASSESSMENT

### 5.1 Impact Assessment Process

1. **Scope Impact:**
   - What deliverables affected?
   - What work added/removed?
   - Impact on acceptance criteria?

2. **Schedule Impact:**
   - Timeline changes?
   - Milestone impacts?
   - Critical path impacts?

3. **Cost Impact:**
   - Budget changes?
   - Resource cost impacts?
   - Infrastructure cost impacts?

4. **Resource Impact:**
   - Resource requirements?
   - Skill requirements?
   - Availability impacts?

5. **Risk Impact:**
   - New risks introduced?
   - Existing risk changes?
   - Mitigation impacts?

6. **Quality Impact:**
   - Quality standard impacts?
   - Testing impacts?

### 5.2 Impact Assessment Template

| Impact Area | Current State | Proposed Change | Impact | Mitigation |
|-------------|---------------|-----------------|--------|------------|
| Scope | | | | |
| Schedule | | | | |
| Cost | | | | |
| Resources | | | | |
| Risks | | | | |
| Quality | | | | |

---

## 6. CHANGE REQUEST EVALUATION CRITERIA

### 6.1 Evaluation Criteria

| Criteria | Weight | Description |
|----------|--------|-------------|
| **Business Value** | 30% | Value to business |
| **Impact** | 25% | Impact on project |
| **Urgency** | 20% | How urgent is change? |
| **Feasibility** | 15% | Can it be done? |
| **Cost-Benefit** | 10% | Cost vs benefit |

### 6.2 Decision Matrix

| Score | Rating |
|-------|--------|
| **8-10** | High Priority - Approve |
| **5-7** | Medium Priority - Consider |
| **< 5** | Low Priority - Reject/Defer |

---

## 7. CHANGE REQUEST STATUS

### 7.1 Status Flow

```
Submitted → Under Review → Impact Assessment → CCB Review → 
Approved/Rejected/Deferred → Implementation → Closed
```

### 7.2 Status Definitions

| Status | Description |
|--------|-------------|
| **Submitted** | Change request submitted |
| **Under Review** | Being reviewed |
| **Impact Assessment** | Impact being assessed |
| **CCB Review** | Under CCB review |
| **Approved** | Approved by CCB |
| **Rejected** | Rejected by CCB |
| **Deferred** | Deferred for later |
| **Implementation** | Being implemented |
| **Closed** | Implemented và closed |

---

## 8. CHANGE IMPLEMENTATION

### 8.1 Implementation Process

1. **Plan Implementation:**
   - Develop implementation plan
   - Assign resources
   - Set timeline

2. **Execute:**
   - Implement change
   - Monitor progress
   - Address issues

3. **Update Baselines:**
   - Update scope baseline
   - Update schedule baseline
   - Update cost baseline
   - Update documentation

4. **Verify:**
   - Verify change implemented
   - Validate results
   - Get sign-off

5. **Close:**
   - Document completion
   - Update change log
   - Communicate closure

### 8.2 Baseline Updates

When change is approved:
- Update Scope Management Plan
- Update Project Schedule
- Update Cost Management Plan
- Update WBS (if scope change)
- Update Risk Register (if risk change)
- Update other relevant documents

---

## 9. EMERGENCY CHANGES

### 9.1 Emergency Change Process

For urgent changes:
1. **Immediate Action:** Take immediate action nếu needed
2. **Document:** Document change request ASAP
3. **Fast-track Review:** CCB fast-track review (within 24 hours)
4. **Approve/Reject:** CCB decision
5. **Implement:** Implement if approved
6. **Retrospective:** Review process after

### 9.2 Emergency Criteria

Changes qualify as emergency if:
- Threat to project success
- Threat to safety
- Critical bug/issue
- Regulatory compliance
- Security issue

---

## 10. CHANGE TRACKING & REPORTING

### 10.1 Change Log

Maintain change log với:
- Change Request ID
- Date submitted
- Submitted by
- Description
- Status
- Decision
- Implementation date

### 10.2 Change Reporting

| Report | Frequency | Audience | Content |
|--------|-----------|----------|---------|
| **Change Status Report** | Weekly | PM, CCB | Change status summary |
| **Change Impact Report** | Per change | CCB | Impact assessment |
| **Change Summary** | Monthly | Sponsor, PM | Monthly change summary |

---

## 11. CHANGE MANAGEMENT TOOLS

### 11.1 Tools

- **Jira:** Change request tracking
- **Confluence:** Change documentation
- **Excel:** Change log
- **Email:** Change notifications

### 11.2 Templates

- Change Request Form
- Impact Assessment Template
- CCB Meeting Minutes Template
- Change Implementation Plan Template

---

## 12. CHANGE MANAGEMENT ROLES & RESPONSIBILITIES

| Role | Responsibilities |
|------|------------------|
| **Change Requestor** | Submit change request, provide information |
| **Project Manager** | Evaluate changes, manage process |
| **CCB** | Review và approve/reject changes |
| **Team Members** | Implement approved changes |
| **QA Lead** | Technical evaluation |

---

## 13. CHANGE MANAGEMENT RISKS & MITIGATION

### 13.1 Change Management Risks

| Risk | Impact | Mitigation |
|------|--------|------------|
| Too many changes | High | Strict evaluation, prioritization |
| Change delays | Medium | Fast-track process, clear timeline |
| Poor impact assessment | High | Templates, expert review |
| Unauthorized changes | High | Clear process, monitoring |

**Chi tiết:** Xem [Risk Register](../03_Project_Documents/Risk_Register.md)

---

## 14. PHÊ DUYỆT

| Vai trò | Họ tên | Chữ ký | Ngày |
|---------|--------|--------|------|
| **Project Sponsor** | | | |
| **Project Manager** | | | |
| **QA Lead** | | | |

---

## 15. LỊCH SỬ THAY ĐỔI

| Version | Ngày | Người thay đổi | Mô tả thay đổi |
|---------|------|----------------|----------------|
| 1.0 | [DD/MM/YYYY] | [Tên] | Khởi tạo document |

---

*Document này là một phần của Project Management Plan. Tất cả changes phải tuân thủ process này.*

