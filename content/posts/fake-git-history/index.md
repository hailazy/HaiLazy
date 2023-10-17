---
title: "Trở thành coder siêng năng trong chớp mắt"
date: 2023-10-17T08:46:31+07:00
lastmod: 2023-10-17T08:46:31+07:00
description: "Fake biểu đồ hoạt động GitHub của bạn chỉ vơi một dòng lệnh"
draft: false
images: []
resources:
  - name: "featured-image"
    src: "git-history.gif"

tags: ["git", "GitHub", "GitLab", "fake"]
categories: ["coding"]
hiddenFromHomePage: false

lightgallery: true

toc:
  auto: false
share:
  enable: true
comment: true
---
Xấu hổ vì activity graph trên github trống trải, bạn muốn gây ấn tượng với nhà tuyển dụng, hay để flex với khách hàng tiềm năng lịch sử commit ấn tượng.
Đừng lo, vì mình có giải pháp hoàn hảo cho bạn: **`fake-git-history`**!

<!--more-->
### Tổng quan

Đây là một command tool cho phép bạn tạo ra một biểu đồ hoạt động GitHub hoặc GitLab trông có vẻ như bạn đã lập trình đều đặn. Nó dễ sử dụng, có thể tùy chỉnh và rất giải trí. Bạn chỉ cần cài đặt Git và Node.js trên máy tính của mình, và bạn đã sẵn sàng để bắt đầu vào thế giới của sự lừa dối kỹ thuật số.

### Hướng dẫn sự dụng
Để bắt đầu tạo ra mạng lưới của mình, chỉ cần chạy lệnh đơn giản này:

```bash
npx fake-git-history
```

Lệnh này tạo ra một thư mục "my-history", init Git và thêm các lần commit cho mỗi ngày trong vòng một năm qua (dự kiến 0-3 commit mỗi ngày).

Khi bạn hoàn thành, đẩy thư mục này lên tài khoản GitHub hoặc GitLab của bạn, và voila! Bạn có một biểu đồ hoạt động đáng kinh ngạc cho thấy sự tận tâm và đam mê với lập trình của bạn.

```bash
cd my-history
git remote add origin git@github.com:<USERNAME>/my-history.git
git push -u origin master
```

Nhưng nếu bạn muốn điều chỉnh tinh chỉnh để trông real hơn nữa thì Fake-git-history sẽ giúp bạn với các tùy chọn có thể tùy chỉnh để lịch sử giả của bạn trông thực tế hơn hoặc ngớ ngẩn hơn. Dưới đây là một số ví dụ về cách bạn có thể chơi với các tùy chọn này:

###### Tạo ra các lần commit ngẫu nhiên từ 0 đến 5 lần mỗi ngày
```bash
 npx fake-git-history --commitsPerDay "0,5"
```

###### Bỏ qua các lần commit vào cuối tuần
Ngay cả những người phát triển năng suất nhât cũng cần một chút nghỉ ngơi
```bash
npx fake-git-history --workdaysOnly
```

###### Muốn tạo ra cảm giác như bạn đã lập trình đều đặn từ đầu năm 2023?
```bash
npx fake-git-history --startDate "2020/09/01" --endDate "2020/09/30"
```

Bạn có thể xem danh sách chi tiết các tuỳ chọn trên trang [GitHub của fake-git-history](https://github.com/artiebits/fake-git-history).

### It's just a joke

Trước khi bạn nhanh chóng thử công cụ này, xin lưu ý rằng đây chỉ là một trò đùa. Cẩn thận đừng lạm dụng. Mặc dù mình không khuyến khích việc gian lận, nhưng nếu ai đó đánh giá kỹ năng của bạn dựa trên biểu đồ hoạt động GitHub, họ
xứng đáng dđược thấy một biểu đồ đẹp như mơ.

Fake-git-history là một cách vui vẻ để chọc ghẹo bạn bè hoặc thậm chí bản thân bạn. Hãy sử dụng nó một cách có trách nhiệm và đạo đức. Và đừng quên chia sẻ biểu đồ hoạt động giả của bạn với mình trong phần bình luận bên dưới. Rất muốn bạn đ dùng nó để làm gì!

Happy coding!