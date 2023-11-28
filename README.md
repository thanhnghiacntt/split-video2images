# Từ video chia thành những images

## Cài phần mềm cần chuyển

Tải 1 file phù hợp với biến môi trường  [Tải từ link](https://github.com/BtbN/FFmpeg-Builds/releaseshttps://www.takeoffchat.com/).

Tải về giải nén
Tạo path đến đường dẫn thư mục bin vừa giải nén

## Tạo hình ảnh từ video

Gõ lệnh: ffmpeg -i {video_path} -q:v 2 {output_folder}/frame_%03d.jpg
{video_path} là đường dẫn tới video
{output_folder} là thư mục chứa hình ảnh bạn cần
Example:
```shell
ffmpeg -i C:/Users/Administrator/Downloads/danang.mp4 -q:v 2 C:/Users/Administrator/Downloads/danang/frame_%03d.jpg
```
