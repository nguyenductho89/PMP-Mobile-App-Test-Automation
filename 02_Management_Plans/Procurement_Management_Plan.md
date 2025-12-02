# PROCUREMENT MANAGEMENT PLAN
## Dự án: Mobile App Test Automation với Appium

---

## MỤC ĐÍCH VÀ TÁC DỤNG

**Mục đích:** Procurement Management Plan xác định cách thức mua sắm hàng hóa và dịch vụ từ bên ngoài để đảm bảo đáp ứng nhu cầu dự án với giá trị tốt nhất.

**Tác dụng:**
- Đảm bảo mua sắm đúng nhu cầu, đúng giá
- Quản lý contracts và vendors một cách hiệu quả
- Giảm thiểu rủi ro trong procurement
- Đảm bảo compliance với company policies
- Tối ưu hóa chi phí và value
- Quản lý vendor relationships

**Đối tượng sử dụng:**
- **Project Manager:** Quản lý procurement process
- **Procurement Team:** Execute procurement
- **Finance Team:** Approve và process payments
- **Vendors:** Hiểu requirements và expectations

**Thời điểm sử dụng:**
- Tạo trong giai đoạn Planning
- Áp dụng khi cần mua sắm
- Review trong các procurement reviews

**Mối liên hệ với các tài liệu khác:**
- Liên kết với Cost Management Plan
- Tích hợp với Risk Management Plan
- Hỗ trợ Resource Management Plan

---

## 1. THÔNG TIN DỰ ÁN

| Thông tin | Chi tiết |
|-----------|----------|
| **Tên dự án** | Mobile App Test Automation với Appium |
| **Mã dự án** | PRJ-2024-APPIUM-001 |
| **Ngày tạo** | [DD/MM/YYYY] |
| **Phiên bản** | 1.0 |

---

## 2. PROCUREMENT REQUIREMENTS

### 2.1 Goods & Services Needed

| Item | Type | Description | Estimated Cost | Priority |
|------|------|-------------|----------------|----------|
| **Test Devices** | Goods | 5 Android + 3 iOS devices | $X,XXX | High |
| **Device Farm Subscription** | Service | BrowserStack/Sauce Labs | $X,XXX/year | High |
| **IDE Licenses** | Service | IntelliJ IDEA licenses | $500/year | Medium |
| **Training Services** | Service | Appium training courses | $X,XXX | High |
| **Consulting Services** | Service | External consultant (nếu cần) | $X,XXX | Low |
| **CI/CD Infrastructure** | Service | Cloud infrastructure | $X,XXX/year | High |

### 2.2 Procurement Timeline

| Item | Procurement Start | Expected Delivery | Critical Path |
|------|-------------------|-------------------|---------------|
| Test Devices | Week 1 | Week 2 | Yes |
| Device Farm Subscription | Week 1 | Week 2 | Yes |
| Training Services | Week 1 | Week 2 | Yes |
| IDE Licenses | Week 1 | Week 2 | No |
| CI/CD Infrastructure | Week 2 | Week 3 | Yes |

---

## 3. PROCUREMENT PROCESS

### 3.1 Plan Procurements

**Mục đích:** Xác định what to procure và how.

**Activities:**
1. Identify procurement needs
2. Define procurement requirements
3. Determine make-or-buy decisions
4. Select procurement approach
5. Prepare procurement documents

**Responsible:** Project Manager, Procurement Team  
**Timeline:** Week 1

### 3.2 Conduct Procurements

**Mục đích:** Obtain responses từ vendors, select vendors, award contracts.

**Process:**
1. **Request for Quotation (RFQ):** Send RFQ to vendors
2. **Vendor Evaluation:** Evaluate proposals/quotes
3. **Negotiation:** Negotiate terms và pricing
4. **Selection:** Select vendor
5. **Contract Award:** Award contract
6. **Contract Signing:** Sign contract

**Responsible:** Project Manager, Procurement Team  
**Timeline:** Week 1-2

### 3.3 Control Procurements

**Mục đích:** Manage procurement relationships, monitor contract performance, make changes và corrections.

**Activities:**
1. Monitor vendor performance
2. Track deliverables
3. Manage contract changes
4. Process payments
5. Resolve issues
6. Close contracts

**Responsible:** Project Manager  
**Frequency:** Ongoing

### 3.4 Close Procurements

**Mục đích:** Complete each procurement.

**Activities:**
1. Verify deliverables
2. Finalize payments
3. Close contracts
4. Document lessons learned
5. Archive documents

**Responsible:** Project Manager  
**Timeline:** End of project

---

## 4. PROCUREMENT APPROACH

### 4.1 Make-or-Buy Analysis

| Item | Make | Buy | Decision | Reason |
|------|------|-----|----------|--------|
| Test Devices | ❌ | ✅ | Buy | Not core competency |
| Device Farm | ❌ | ✅ | Buy | Cost-effective, scalable |
| Framework Development | ✅ | ❌ | Make | Core competency, knowledge retention |
| Training | ❌ | ✅ | Buy | External expertise |
| CI/CD Setup | ✅ | ❌ | Make | Internal capability |

### 4.2 Procurement Methods

| Method | When to Use | Items |
|--------|-------------|-------|
| **Direct Purchase** | Standard items, low value | Test devices, licenses |
| **RFQ (Request for Quotation)** | Multiple vendors, competitive | Device Farm, Training |
| **RFP (Request for Proposal)** | Complex services | Consulting (nếu cần) |

---

## 5. VENDOR MANAGEMENT

### 5.1 Vendor Selection Criteria

| Criteria | Weight | Description |
|----------|--------|-------------|
| **Price** | 30% | Competitive pricing |
| **Quality** | 25% | Quality of products/services |
| **Experience** | 20% | Relevant experience |
| **Support** | 15% | Support và service quality |
| **Reputation** | 10% | Vendor reputation |

### 5.2 Vendor Evaluation Process

1. **Initial Screening:** Check basic requirements
2. **Proposal Evaluation:** Evaluate proposals/quotes
3. **Reference Checks:** Check vendor references
4. **Negotiation:** Negotiate terms
5. **Final Selection:** Select vendor
6. **Contract Award:** Award contract

### 5.3 Vendor Management

**Activities:**
- Regular communication
- Performance monitoring
- Issue resolution
- Relationship management
- Contract compliance

---

## 6. CONTRACT MANAGEMENT

### 6.1 Contract Types

| Type | Description | When to Use |
|------|-------------|-------------|
| **Fixed Price** | Fixed total price | Well-defined scope |
| **Time & Materials** | Pay for time/materials | Uncertain scope |
| **Cost Plus** | Cost + fee | High risk |

### 6.2 Contract Terms

**Key Terms:**
- Scope of work
- Deliverables
- Payment terms
- Timeline
- Quality requirements
- Support và maintenance
- Termination clauses

### 6.3 Contract Administration

**Activities:**
- Monitor contract performance
- Track deliverables
- Process payments
- Manage changes
- Resolve disputes
- Maintain documentation

---

## 7. PROCUREMENT RISKS & MITIGATION

### 7.1 Procurement Risks

| Risk | Impact | Mitigation |
|------|--------|------------|
| Vendor delays | Medium | Early procurement, buffer time |
| Quality issues | High | Vendor evaluation, SLAs |
| Cost overruns | Medium | Fixed-price contracts, monitoring |
| Vendor unavailability | High | Multiple vendors, backups |
| Contract disputes | Medium | Clear contracts, communication |

**Chi tiết:** Xem [Risk Register](../03_Project_Documents/Risk_Register.md)

---

## 8. PROCUREMENT DOCUMENTATION

### 8.1 Required Documents

- Procurement plan
- RFQ/RFP documents
- Vendor proposals/quotes
- Evaluation reports
- Contracts
- Purchase orders
- Invoices
- Payment records

### 8.2 Documentation Storage

- **Procurement System:** Company procurement system
- **Shared Drive:** Procurement documents
- **Confluence:** Procurement documentation

---

## 9. PROCUREMENT APPROVALS

### 9.1 Approval Authority

| Amount | Approval Required From |
|--------|------------------------|
| **< $X,XXX** | Project Manager |
| **$X,XXX - $XX,XXX** | Sponsor |
| **> $XX,XXX** | CFO, Sponsor |

### 9.2 Approval Process

1. Prepare procurement request
2. Submit for approval
3. Review và approve
4. Execute procurement
5. Document approval

---

## 10. PROCUREMENT ROLES & RESPONSIBILITIES

| Role | Responsibilities |
|------|------------------|
| **Project Manager** | Overall procurement management |
| **Procurement Team** | Execute procurement process |
| **Finance Team** | Approve và process payments |
| **Legal Team** | Contract review (nếu cần) |

---

## 11. PROCUREMENT SCHEDULE

| Procurement Item | Start | Complete | Critical |
|------------------|-------|----------|----------|
| Test Devices | Week 1 | Week 2 | Yes |
| Device Farm | Week 1 | Week 2 | Yes |
| Training | Week 1 | Week 2 | Yes |
| Licenses | Week 1 | Week 2 | No |
| Infrastructure | Week 2 | Week 3 | Yes |

---

## 12. PHÊ DUYỆT

| Vai trò | Họ tên | Chữ ký | Ngày |
|---------|--------|--------|------|
| **Project Manager** | | | |
| **Procurement Manager** | | | |
| **Finance Manager** | | | |

---

## 13. LỊCH SỬ THAY ĐỔI

| Version | Ngày | Người thay đổi | Mô tả thay đổi |
|---------|------|----------------|----------------|
| 1.0 | [DD/MM/YYYY] | [Tên] | Khởi tạo document |

---

*Document này là một phần của Project Management Plan. Procurement activities sẽ được tracked trong project tracking system.*

