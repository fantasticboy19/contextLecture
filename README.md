# contextLecture
## 我们使用了三个用于go协程通讯的方式
---
1. 第一个是使用了waitgroup的方式
2. 使用了通道+select的方式
3. 使用了context的方式，可以很方便的实现对多个协程进行通知，
