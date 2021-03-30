## System Architecture

- Lastest update
  - CH is the best chance in the past years
  - Tech Stack (Agora, could computing). https://www.infoq.cn/article/LmZT9SxS6k7OZRBZ5LsH
  - I found a Designer who truely understand the product! https://mp.weixin.qq.com/s/VEdY5bpphIAskNuYgiYEqw

- Our goal:
  1. Make the user experience better than CH(Zoom vs Bluejeans, webex): system latency, sounds clearness, UI fluent (with incremental improvement).
  2. 差异化，寻找新的应用场景(https://docs.agora.io/cn/Interactive%20Broadcast/product_live?platform=Web)。

- [ ] Overall sysstem design
  - Possible to go with serverless + Kubernetes?
    - https://serverless-stack.com/chapters/zh/what-is-serverless.html
    - https://time.geekbang.org/column/intro/116
  - Could we draft a chart of the system?
![system_design](images/2_system_design.PNG)

- [ ] Evaluate different RTC/Cloud provider

- A system that can control how many user can get access, open gradually to different users

- Design with extensibility in mind + easy to onboard other developers

- Architecture review?

- Make a video for our project and branding it.

- API contract

- A lix system to turn on/off lix

- A model system. That is easy to communicate with different client.
  - Ember's default is JSON API?
  - Is LI's solution applicable?
