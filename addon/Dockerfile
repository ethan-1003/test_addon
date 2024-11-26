FROM alpine:3.18

# Cài đặt Bash
RUN apk add --no-cache bash

# Tạo script cơ bản
COPY run.sh /run.sh
RUN chmod a+x /run.sh

# Chạy script khi container khởi động
CMD [ "/run.sh" ]
