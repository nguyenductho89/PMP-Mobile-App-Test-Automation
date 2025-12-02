# HƯỚNG DẪN CẬP NHẬT TÀI LIỆU DỰ ÁN
## Dự án: Mobile App Test Automation với Appium

---

## MỤC ĐÍCH

Tài liệu này hướng dẫn chi tiết **khi nào** và **file nào** cần được cập nhật khi có các sự kiện hoặc vấn đề xảy ra trong dự án.

---

## 1. TỔNG QUAN CẤU TRÚC TÀI LIỆU

```
D:\PMP\
├── README.md                           → Điểm truy cập trung tâm
├── 01_Project_Management_Plan/         → Tài liệu nền tảng
├── 02_Management_Plans/                → Các kế hoạch quản lý
├── 03_Project_Documents/               → Tài liệu vận hành dự án
├── 04_Matrices_and_Metrics/            → Ma trận và chỉ số
├── 05_Guides/                          → Hướng dẫn (thư mục này)
└── 06_Diagrams/                        → Sơ đồ (drawio)
```

---

## 2. MA TRẬN CẬP NHẬT TÀI LIỆU

### 2.1 Khi có THAY ĐỔI PHẠM VI (Scope Change)

| Hành động | File cần cập nhật | Vị trí |
|-----------|-------------------|--------|
| 1. Tạo Change Request | `Change_Request_Log.md` | 03_Project_Documents |
| 2. Cập nhật phạm vi | `Scope_Management_Plan.md` | 02_Management_Plans |
| 3. Cập nhật WBS | `Work_Breakdown_Structure.md` | 03_Project_Documents |
| 4. Cập nhật WBS Dictionary | `WBS_Dictionary.md` | 03_Project_Documents |
| 5. Cập nhật Schedule | `Project_Schedule.md` | 03_Project_Documents |
| 6. Cập nhật Traceability | `Traceability_Matrix.md` | 04_Matrices_and_Metrics |
| 7. Ghi nhận Decision | `Decision_Log.md` | 03_Project_Documents |

**Flow:**
```
Change Request → CCB Review → If Approved → Update All Documents
```

---

### 2.2 Khi có RỦI RO MỚI (New Risk Identified)

| Hành động | File cần cập nhật | Vị trí |
|-----------|-------------------|--------|
| 1. Đăng ký rủi ro | `Risk_Register.md` | 03_Project_Documents |
| 2. Cập nhật kế hoạch (nếu cần) | `Risk_Management_Plan.md` | 02_Management_Plans |
| 3. Cập nhật Assumption Log (nếu liên quan) | `Assumption_Log.md` | 03_Project_Documents |

**Khi rủi ro xảy ra (thành Issue):**
| Hành động | File cần cập nhật |
|-----------|-------------------|
| 1. Chuyển sang Issue | `Issue_Log.md` |
| 2. Cập nhật Risk Register | `Risk_Register.md` (đánh dấu Occurred) |

---

### 2.3 Khi có VẤN ĐỀ (Issue) phát sinh

| Hành động | File cần cập nhật | Vị trí |
|-----------|-------------------|--------|
| 1. Log issue | `Issue_Log.md` | 03_Project_Documents |
| 2. Nếu cần thay đổi | `Change_Request_Log.md` | 03_Project_Documents |
| 3. Nếu ảnh hưởng schedule | `Project_Schedule.md` | 03_Project_Documents |
| 4. Báo cáo trong | `Project_Status_Report_Template.md` | 03_Project_Documents |

---

### 2.4 Khi HOÀN THÀNH Milestone

| Hành động | File cần cập nhật | Vị trí |
|-----------|-------------------|--------|
| 1. Ghi nhận acceptance | `Milestone_Acceptance_Form.md` | 03_Project_Documents |
| 2. Cập nhật schedule | `Project_Schedule.md` | 03_Project_Documents |
| 3. Ghi Lessons Learned | `Lessons_Learned_Register.md` | 03_Project_Documents |
| 4. Cập nhật trạng thái | `Traceability_Matrix.md` | 04_Matrices_and_Metrics |
| 5. Báo cáo status | `Project_Status_Report_Template.md` | 03_Project_Documents |

---

### 2.5 Khi có THAY ĐỔI SCHEDULE

| Hành động | File cần cập nhật | Vị trí |
|-----------|-------------------|--------|
| 1. Tạo Change Request | `Change_Request_Log.md` | 03_Project_Documents |
| 2. Cập nhật Schedule | `Project_Schedule.md` | 03_Project_Documents |
| 3. Cập nhật Schedule Plan | `Schedule_Management_Plan.md` | 02_Management_Plans |
| 4. Cập nhật Risk (nếu liên quan) | `Risk_Register.md` | 03_Project_Documents |
| 5. Ghi nhận Decision | `Decision_Log.md` | 03_Project_Documents |

---

### 2.6 Khi có THAY ĐỔI NGUỒN LỰC (Resource Change)

| Hành động | File cần cập nhật | Vị trí |
|-----------|-------------------|--------|
| 1. Cập nhật Resource Plan | `Resource_Management_Plan.md` | 02_Management_Plans |
| 2. Cập nhật RACI | `RACI_Matrix.md` | 04_Matrices_and_Metrics |
| 3. Cập nhật Stakeholder Register | `Stakeholder_Register.md` | 03_Project_Documents |
| 4. Cập nhật Communication Matrix | `Communication_Matrix.md` | 04_Matrices_and_Metrics |

---

### 2.7 Khi có CUỘC HỌP

| Loại họp | File cần tạo/cập nhật | Vị trí |
|----------|----------------------|--------|
| Mọi cuộc họp | `Meeting_Minutes_Template.md` (tạo mới) | 03_Project_Documents |
| Nếu có decisions | `Decision_Log.md` | 03_Project_Documents |
| Nếu có action items | Track trong Meeting Minutes | |
| Nếu có risks identified | `Risk_Register.md` | 03_Project_Documents |
| Nếu có issues | `Issue_Log.md` | 03_Project_Documents |

---

### 2.8 Khi có THAY ĐỔI YÊU CẦU CHẤT LƯỢNG

| Hành động | File cần cập nhật | Vị trí |
|-----------|-------------------|--------|
| 1. Cập nhật Quality Plan | `Quality_Management_Plan.md` | 02_Management_Plans |
| 2. Cập nhật Quality Metrics | `Quality_Metrics.md` | 04_Matrices_and_Metrics |
| 3. Cập nhật Acceptance Criteria | `Scope_Management_Plan.md` | 02_Management_Plans |

---

### 2.9 Khi có BÀI HỌC KINH NGHIỆM

| Thời điểm | File cần cập nhật | Vị trí |
|-----------|-------------------|--------|
| Sau mỗi Sprint | `Lessons_Learned_Register.md` | 03_Project_Documents |
| Sau mỗi Milestone | `Lessons_Learned_Register.md` | 03_Project_Documents |
| Khi có sự cố | `Lessons_Learned_Register.md` | 03_Project_Documents |
| Khi giải quyết Issue | `Lessons_Learned_Register.md` | 03_Project_Documents |

---

### 2.10 Khi CẬP NHẬT ASSUMPTION

| Hành động | File cần cập nhật | Vị trí |
|-----------|-------------------|--------|
| Assumption thay đổi | `Assumption_Log.md` | 03_Project_Documents |
| Assumption trở thành Risk | `Risk_Register.md` | 03_Project_Documents |
| Assumption được validate | `Assumption_Log.md` | 03_Project_Documents |

---

## 3. FREQUENCY CẬP NHẬT

### 3.1 Cập nhật HÀNG NGÀY

| File | Người phụ trách |
|------|-----------------|
| Issue Log (nếu có issues) | QA Engineers, Team |
| Risk Register (nếu có triggers) | Risk Owners |

### 3.2 Cập nhật HÀNG TUẦN

| File | Người phụ trách |
|------|-----------------|
| Project Status Report | Project Manager |
| Risk Register | Project Manager |
| Issue Log | Project Manager |
| Lessons Learned Register | Team |

### 3.3 Cập nhật SAU MỖI SPRINT

| File | Người phụ trách |
|------|-----------------|
| Project Schedule | Project Manager |
| Traceability Matrix | QA Lead |
| Quality Metrics | QA Lead |
| Lessons Learned Register | Team |

### 3.4 Cập nhật SAU MỖI MILESTONE

| File | Người phụ trách |
|------|-----------------|
| Milestone Acceptance Form | Project Manager |
| All Baseline Documents | Project Manager |
| README.md (nếu cần) | Project Manager |

### 3.5 Cập nhật KHI CÓ THAY ĐỔI

| Trigger | Files |
|---------|-------|
| Change Request | Tất cả files liên quan |
| New Risk | Risk Register, Risk Management Plan |
| New Issue | Issue Log |
| Decision Made | Decision Log |
| Meeting | Meeting Minutes |

---

## 4. QUY TRÌNH CẬP NHẬT

### 4.1 Quy trình chung

```
1. Xác định sự kiện/vấn đề
        ↓
2. Tham khảo bảng ma trận phía trên
        ↓
3. Cập nhật các files theo thứ tự
        ↓
4. Cập nhật Version và Lịch sử thay đổi
        ↓
5. Review bởi người có thẩm quyền
        ↓
6. Communicate changes đến stakeholders
```

### 4.2 Version Control

Khi cập nhật file:
1. Tăng version number (1.0 → 1.1, major changes: 1.0 → 2.0)
2. Cập nhật "Ngày cập nhật"
3. Thêm entry vào "Lịch sử thay đổi"
4. Ghi rõ "Người thay đổi" và "Mô tả thay đổi"

---

## 5. CHECKLIST CẬP NHẬT

### 5.1 Checklist cho Change Request

- [ ] Change Request Log được cập nhật
- [ ] Impact Analysis được thực hiện
- [ ] CCB đã review và approve
- [ ] Scope Management Plan được cập nhật
- [ ] WBS được cập nhật
- [ ] Schedule được cập nhật
- [ ] Cost được cập nhật (nếu ảnh hưởng)
- [ ] Stakeholders được thông báo
- [ ] Decision Log được cập nhật

### 5.2 Checklist cho New Risk

- [ ] Risk Register được cập nhật
- [ ] Risk score được tính
- [ ] Response plan được định nghĩa
- [ ] Owner được assign
- [ ] Triggers được xác định
- [ ] Risk Management Plan review (nếu cần)

### 5.3 Checklist cho Milestone Completion

- [ ] Deliverables được verify
- [ ] Acceptance criteria được check
- [ ] Milestone Acceptance Form được sign-off
- [ ] Schedule được cập nhật
- [ ] Lessons Learned được ghi nhận
- [ ] Stakeholders được thông báo
- [ ] Celebration! 🎉

---

## 6. TIPS & BEST PRACTICES

### 6.1 Dos ✅

- Cập nhật tài liệu ngay khi có thay đổi
- Giữ version control chặt chẽ
- Communicate changes đến stakeholders
- Link các tài liệu liên quan
- Review định kỳ để đảm bảo consistency

### 6.2 Don'ts ❌

- Không delay việc cập nhật tài liệu
- Không skip version control
- Không cập nhật mà không review
- Không forget stakeholder communication
- Không để tài liệu outdated

---

## 7. LIÊN HỆ HỖ TRỢ

| Vấn đề | Liên hệ |
|--------|---------|
| Document structure | Project Manager |
| Technical documents | QA Lead |
| Process questions | Project Manager |
| Tool issues | DevOps |

---

## 8. PHỤ LỤC

### A. Danh sách tất cả tài liệu

Xem tại [README.md](../README.md)

### B. Mối liên hệ giữa các file

Xem tại [Document_Relationships.drawio](../06_Diagrams/Document_Relationships.drawio)

---

## 9. LỊCH SỬ THAY ĐỔI

| Version | Ngày | Người thay đổi | Mô tả thay đổi |
|---------|------|----------------|----------------|
| 1.0 | 02/12/2025 | Project Manager | Khởi tạo document |

---

*Document này nên được tham khảo thường xuyên để đảm bảo tài liệu dự án luôn được cập nhật và nhất quán.*
