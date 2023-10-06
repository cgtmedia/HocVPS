HocVPS-Script: Fixed Setup 06/10/2023.....
===================

HocVPS Script là 1 bash script chạy trên SSH sẽ tự động cài đặt tất cả các thành phần cần thiết nhất cho VPS với một dòng lệnh duy nhất.

Không như những Control Panel khác, HocVPS Script không hề sử dụng bất kỳ tài nguyên server (CPU, RAM) và không thể mắc lỗi bảo mật nào để hacker khai thác được nên các bạn có thể hoàn toàn yên tâm sử dụng.

Trang chủ: https://hocvps.com/script

----------

1/ Yêu cầu Hệ thống:
-------------
Install CentOS Server 6/7 x86_64: http://centos.org/

----------


2/ Cài đặt:
-------------
```
curl -sLO https://raw.githubusercontent.com/cgtmedia/HocVPS/main/install && bash install

```

– Cài đặt xong, khi connect SSH VPS bạn hãy sử dụng port 2222, không dùng port 22!

– HocVPS Script không hoạt động trên VPS chỉ có IPv6 (gói $2.5 của Vultr)

3/ Cấu hình khác:
---------------
HomePage: https://hocvps.com/script
