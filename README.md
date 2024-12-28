## Hủy commit nhưng giữ lại thay đổi trong code (Soft Reset)
```bash
git reset --soft HEAD~1
```
## Hủy commit và xóa toàn bộ thay đổi (Hard Reset)
```bash
git reset --hard HEAD~1
```

## Xóa commit cụ thể nếu có nhiều commit
```bash
git rebase -i HEAD~<số-lượng-commit>

```
