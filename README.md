# sgroup-buoi-4
- tổng hợp kiến thức:

  1.  slot: 
    + Với trường hợp chỉ 1 slot: Nếu không có name thì code sẽ mặc định vào slot đó
    + Với trường hợp nhiều slot: sử dung name để định danh slot đó, và sử dụng <template v-slot: > bên html
    + Code trong template sẽ ghi đè lại code trong slot bên file js
  2.  Đệ quy component: Để tạo được 1 đệ quy:
    + Tạo tree ngoài cùng
    + Bên html sử dụng v-for để in ra tất cả các phần tử cha
    + trong template của cha: sử dụng v-for để in ra các child, với mỗi child sử dụng lệnh v-if check xem child còn có chứa child nào không, nếu không có thì đó là cha, còn không thì hiển thị ra content
    + Ứng dụng: làm sidebar, cây, sử dụng trong các dự án lớn để tránh phải viết cụ thể code ra trong html
  3.  Thư viện: bootstrap-vue, element, awesome-vue
  4.  Vue CLI: là một hệ thống cung cấp các tính năng và môi trường giúp làm việc hiệu quả hơn với VueJs như: show error, runtime dependency,...
    - Tạo project: 
      + vue create [name_prj]
      + Nếu sử dụng git bash trên windows thì lệnh để chọn các options khi create project: winpty vue.cmd create project-name
      + Vue router: là 1 package hỗ trợ chuyển đổi component khi path thay đổi
      + PWA support: hỗ trợ code offline
      + vuex: sử dụng để state management
      + css pre-proccessor: scss
      + babel: là package để chuyển từ code ES6 trở lên thành Js thuần
      + eslint: là tool để viết code cho đúng
    - Run project: 
      + npm run serve
    - Sử dụng bootstrap:
      + npm install vue bootstrap-vue bootstrap
  
  
