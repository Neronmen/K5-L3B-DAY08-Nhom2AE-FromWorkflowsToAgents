# Team

## Thông tin nhóm

- Tên nhóm: Nhom2AE
- Lớp: L3A
- Repo nhóm: `K5-L3A-DAY08-TenNhom-FromWorkflowsToAgents` (xem [SUBMISSION.md](SUBMISSION.md))
- URL repo, nhánh nộp, commit chốt: https://github.com/Neronmen/K5-L3B-DAY08-Nhom2AE-FromWorkflowsToAgents, nhánh `main`, commit chốt: (ghi trong `report/team/decision_adr.md`)

## Thành viên

| STT | Họ tên | MSSV | Email | GitHub | Vai trò |
| --: | ------ | ---- | ----- | ------ | ------- |
|   1 | Phạm Nguyên Khoa | 2A202603795 |  | Neronmen | Integration + 3 shape (workflow, single, orchestrator) + crash/benchmark |
|   2 |  |  |  |  | Evaluation + ADR + research card + báo cáo nhóm |

Gợi ý chia vai:

- Nhóm 6 người: integration; workflow; single agent; orchestrator; ledger/policy/crash; eval/report.
- Nhóm 4 người: workflow + integration; single; orchestrator + handoff; ledger + evaluation.

## Bảng đóng góp

`python -m lab8.check_submission` đọc bảng này bằng máy: giữ nguyên tiêu đề `## Bảng đóng góp` và các cột. Mỗi người một dòng: commit có nội dung và ít nhất một test đã thêm hoặc sửa.

| Người | Vai | Commit | Test đã thêm hoặc sửa |
| --- | --- | --- | --- |
| Phạm Nguyên Khoa | Integration, 3 shape, crash, benchmark | `75ae9e4`, `19cd820` | `src/tests/test_team_shapes_safety.py` (15 test: crash 3 điểm × 3 shape, ticket nói dối seed 55, quét secret/PII trong trace) |

## Cá nhân

Mỗi thành viên đồng thời tạo một báo cáo riêng trong `report/` theo dạng:

```text
report/team/MSSV_HoTen.md
```

Ví dụ: `report/team/20241234_NguyenVanAn.md`.

Sao chép mục dưới đây cho từng thành viên.

## 2A202603795_PhamNguyenKhoa

### Phần việc phụ trách

- Integration, ba shape `workflow` / `single` / `orchestrator`, crash suite, benchmark.

### Đóng góp cụ thể

- Cài ba shape theo contract (`finish()`, quote đầy đủ, `crash_at` truyền vào host).
- Thêm `src/tests/test_team_shapes_safety.py` (15 test).
- Sinh `src/reports/benchmark.json` và `src/reports/crash.json`.

### Bằng chứng

- Commit `75ae9e4`, `19cd820`; báo cáo chi tiết: `report/team/2A202603795_PhamNguyenKhoa.md`.

## MSSV_HoTen

### Phần việc phụ trách

-

### Đóng góp cụ thể

-

### Bằng chứng

-
