# Biên dịch

Từ thư mục `translate`, chạy XeLaTeX hai lượt:

```powershell
xelatex -interaction=nonstopmode -halt-on-error main.tex
xelatex -interaction=nonstopmode -halt-on-error main.tex
```

Tài liệu dùng đường dẫn tương đối, vì vậy có thể di chuyển toàn bộ thư mục
`translate` sang máy có bản phân phối TeX đầy đủ rồi chạy lại hai lệnh trên.
