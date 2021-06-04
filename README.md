# sgroup-buoi-4
- tổng hợp kiến thức:
- slot: 
  + Với trường hợp chỉ 1 slot: Nếu không có name thì code sẽ mặc định vào slot đó
  + Với trường hợp nhiều slot: sử dung name để định danh slot đó, và sử dụng <template v-slot: > bên html
  + Code trong template sẽ ghi đè lại code trong slot bên file js
- Đệ quy component: Để tạo được 1 đệ quy:
  + Tạo tree ngoài cùng
  + Bên html sử dụng v-for để in ra tất cả các phần tử cha
  + trong template của cha: sử dụng v-for để in ra các child, với mỗi child sử dụng lệnh v-if check xem child còn có chứa child nào không, nếu không có thì đó là cha, còn không thì hiển thị ra content
  + Ứng dụng: làm sidebar, cây, sử dụng trong các dự án lớn để tránh phải viết cụ thể code ra trong html
- Thư viện: bootstrap-vue, element
- Vue CLI: là một hệ thống cung cấp các tính năng và môi trường giúp làm việc hiệu quả hơn với VueJs như: show error, runtime dependency,...
  + Tạo project: vue create [name_prj]
  + Vue router: chuyển đổi component khi path thay đổi
- 
  
  
