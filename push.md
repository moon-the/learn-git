- B1: cd vào thư mục mình muốn clone project vào
- B2: clone project về máy: git clone link-repo-minh-can-clone
- B3: chạy câu lệnh git init để khởi tạo file .git
- B4: tạo branch để code (khác main): git branch ten-branch main VD: git branch code-branch main
- B5: chuyển vào branch mới tạo: git switch code-branch
- B6: xong rồi code
- Quá trình merge và push code:
- 1: tạo branch để test: git branch merge-branch
- 2: ở branch code-brannch: chuẩn bị dữ liệu để commit ghi git add .
- 3: commit code vào branch đang code: git commit -m "ND_Commit"
- 4: chuyển sang branch test: git switch merge-branch
- 5: merge branch test với branch mình code: git merge code-branch

* thành công: vào main: git switch main -> sau đó merge main với branch mình code: git merge code-branch -> git commit -m "ND commit" -> git push origin main là hoàn thành
* lỗi: thì fix merge branch sau đó làm như bên trên
