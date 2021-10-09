# common problem

1. What is this app used for?
  -It is used to record where you are, how much traffic you use and display it on the map. Let you know how to use your traffic.
2. Will this app collect my internet history and location information?
  - will not. All recorded traffic data and location information are all stored in your phone.
  -After all, there is no money to buy a server
3. If the app is deleted, can the data be recovered?
  -If it is deleted, it cannot be restored. Can only be recollected
4. Does this app collect traffic information in real time?
  -No, this app will only wake up the app to record traffic information once when you move more than x meters (that is, the minimum update distance in the settings), and the recording operation is very small. It will not be running all the time.
5. Why are there few data points displayed on my map? Or the map is not displayed?
  -It is recommended to go to `Settings`--->`trafficState`--->`Location`--->`Always allow`, enable this option, the app can better record your location.
  -[10-second video tutorial](https://www.bilibili.com/video/BV1cr4y127Jj?share_source=copy_web)
6. Where can I download it?
  -It is currently under test and can only be downloaded from testflight, [click me to download](https://testflight.apple.com/join/jwzpPVQ3)
7. Where can I report questions?
  -Use testfilght to give feedback. If there are other inconvenient feedback through testFlight, there is a `Share your ideas` button in the app to share your product suggestions.
8. Why is there this app?
  -Learn the by-products of swift and swiftUI
  
## [Set up related issues](https://github.com/IFuny/trafficStatDocument/blob/main/feature.md)


## Follow-up planning:
1. Add chart analysis
2. Back up the data to your icloud. Even if you delete the app in the future, you can back up your data through your icloud (the data is not available here, but Apple officially backs up your data to the cloud for you) ,Safe and reliable)
3. Add widget to make statistics more accurate
4. Add users to customize app color matching

# 常见问题

1. 这个app是干什么用的？
  - 用来记录你在什么地方，使用了多少流量并显示在地图上。让你对自己的流量使用做到心里有数。
2. 这个app会不会收集我的上网记录，定位信息？
  - 不会。所有记录的流量数据，定位信息全都存在你手机里。
  - 毕竟没钱买服务器
3. 如果删除了app，这些数据还能恢复吗？
  - 如果删除了，那就不能恢复了。只能重新收集
4. 这个app是不是会实时收集流量信息？
  - 不会，这个app只有当你移动大于x米（即在设置中设置里最小更新距离），iPhone会唤醒app来记录一次流量信息，记录操作很小。不会一直在运行中。
5. 为什么我的地图上显示的数据点很少？或者没有显示地图？
  - 建议到`设置`--->`trafficState`--->`位置`--->`始终允许`,开启这个选项，则app能更好的记录您的位置。
  - [10秒视频教程](https://www.bilibili.com/video/BV1cr4y127Jj?share_source=copy_web)
6. 哪里可以下载？
  - 目前还在测试中，只能从testflight中下载，[点我下载](https://testflight.apple.com/join/jwzpPVQ3)
7. 哪里可以反馈问题？
  - 用testfilght就能反馈，如果有其他不方便通过testFlight反馈，app内有个`分享你的创意`按钮可以分享你对产品的建议。
8. 为什么有这个app？
  - 学习swift和swiftUI的副产品

## 设置相关问题
1. 开启始终访问位置，是不是会很耗电？
  - 不会，本app只会在你设置的'最小更新距离'发生时，唤醒记录一下数据。
  - 比如你设置'最小更新距离'为10米，那么当你移动了20米，那么本app最多只会唤醒2次记录数据。
  - 如果不相信，可以点开'设置 -> 电池 -> 流量地图'，查看它的'App的电池用量'
  - 如何确认app是否耗电:[10秒视频教程](https://www.bilibili.com/video/BV1FL411x7sn?share_source=copy_web)


## [后续规划](https://github.com/IFuny/trafficStatDocument/blob/main/feature.md)
