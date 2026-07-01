---
layout: page
title: Privacy Policy
permalink: /privacy-policy/
---

# Wander Privacy Policy

**Effective date:** June 30, 2026  
**Last updated:** June 30, 2026  
**App:** Wander  
**Developer / Operator:** Yi Da 
**Contact:** [chuanhaigogogo@gmail.com](mailto:chuanhaigogogo@gmail.com)  
**Applicable users:** United States and global users

This Privacy Policy explains how Wander handles data. Wander is a no-login, no-account iOS content discovery app. It helps you choose one small thing to read, watch, listen to, notice, or do when you do not know what to do next.

Wander does **not** collect your real identity information. Wander does process limited anonymous functional data so the app can work: daily suggestion limits, favorites, completed items, duplicate prevention, retry safety, and content diversity.

## 1. What Wander does not collect

Wander does not require registration or login. Wander does not collect:

- Name
- Email address
- Phone number
- Precise location
- Contacts
- Photos or videos
- Camera or microphone content
- Health data
- Payment information
- IDFA or advertising identifiers

Wander does not use advertising tracking, does not sell user data, and does not share user data with data brokers.

## 2. Local data stored on your device

Wander may store the following data locally on your device:

- `wander.user.uuid`: an anonymous content identity used for favorites, completed items, seen items, and the in-app clear data flow.
- `wander.quota.uuid`: an anonymous quota identity used to enforce the limit of 10 suggestions per 24-hour window.
- `wander.favorites.cache.v1.<user_uuid>`: a local offline cache of favorites so your favorites can still be displayed when network access is limited.

These identifiers are not your name, email address, or phone number. They are anonymous functional identifiers used only to operate the app.

## 3. Server-side functional data

Wander may process and store the following server-side functional data:

- `user_uuid`
- `quota_id`
- `request_id`
- `ji_id`
- `scenario`
- `liked_ji_ids`
- `done_ji_ids`
- `seen_ji_ids`
- `seen_timestamps`
- `draw_count`
- `window_started_at`
- `reset_at`
- `created_at`
- `updated_at`

This data is used for app functionality, not advertising tracking.

## 4. How Wander uses data

Wander uses anonymous functional data to:

- Draw and display suggestions.
- Save favorites.
- Save completed counts.
- Prevent repeated or overly similar suggestions.
- Enforce the limit of 10 suggestions per 24-hour window.
- Make network retries idempotent so a failed retry does not consume extra quota.
- Support content diversity.
- Maintain app safety, reliability, and service stability.

## 5. Content embeddings and recommendation logic

Wander may store embeddings generated from Wander’s own suggestion content. These embeddings help filter similar suggestions and support content diversity.

- Embeddings are used for similarity filtering and diversity.
- Embeddings are not returned to the app client.
- Embeddings are not used for advertising tracking.
- Favorites, completed items, and seen items are used only for app functionality and recommendation behavior, not for ads.

## 6. Third-party services

Wander uses third-party service providers to operate the app:

- **Vercel**: hosts Wander’s backend API.
- **Supabase**: stores Wander’s anonymous functional data and content data.
- **Apple**: provides App Store distribution, TestFlight, and Apple-managed app analytics or crash reports where applicable under Apple’s own settings and policies.

If Wander later adds online AI API calls, analytics, crash reporting, payments, advertising, accounts, or third-party login, this Privacy Policy and App Store privacy disclosures will be updated before or when those changes are released.

## 7. Clear My Data

You can use **Clear My Data** inside the app to clear favorites, completed records, and server-side data associated with the current anonymous content identity.

After clearing data:

- The local favorites cache for the current content identity is cleared.
- Favorites and completed records associated with the current content identity are cleared.
- A new anonymous content identity may be generated.
- The current 24-hour suggestion quota is **not** reset.

To prevent bypassing the 10-suggestions-per-24-hour limit, the anonymous quota identity and minimal quota-window records may be retained until the current quota window naturally expires.

Clear My Data is not an account deletion feature because Wander does not create user accounts.

## 8. Data retention

Wander retains anonymous functional data only as needed to operate the app and maintain service reliability.

- Favorites, completed records, and seen records associated with the current content identity are cleared when you use Clear My Data, where applicable.
- `user_uuid` may be reset after Clear My Data.
- `quota_id` is retained locally and is not reset by Clear My Data.
- Current quota-window records are retained until the current 24-hour quota window naturally expires.
- Vercel and Supabase may keep server logs for security, debugging, abuse prevention, and service stability according to their own infrastructure settings. Wander aims to minimize these logs where practical.

If Wander later introduces long-term analytics, this policy will be updated.

## 9. Your privacy choices and rights

You may:

- Clear favorites and completed records inside the app.
- Contact us to ask privacy questions or request data access, correction, or deletion where applicable.
- Request information about how Wander handles your data.

California users and other users with applicable privacy rights may contact us to exercise rights such as access, deletion, correction, and opting out of sale or sharing where applicable. Wander does not sell personal data and does not share data for cross-app or cross-site advertising tracking.

Because Wander does not require accounts or collect contact information, we may have limited ability to identify a specific user record unless you provide enough information to locate the relevant anonymous app data.

## 10. Children

Wander is intended for users who are at least 18 years old. Wander is not designed for children or minors and is not marketed to them. Wander does not knowingly collect personal information from children under 13.

## 11. Changes to this Privacy Policy

We may update this Privacy Policy from time to time. If the changes are material, we will update the Last updated date and, where appropriate, provide notice through the app or App Store metadata.

## 12. Contact

For privacy questions, contact:

[chuanhaigogogo@gmail.com](mailto:chuanhaigogogo@gmail.com)

---

# Wander 隐私政策

**生效日期：** 2026 年 6 月 30 日  
**最后更新：** 2026 年 6 月 30 日  
**App：** Wander  
**开发者 / 运营者：** Yi Da 
**联系邮箱：** [chuanhaigogogo@gmail.com](mailto:chuanhaigogogo@gmail.com)  
**适用用户：** 美国及全球用户

本隐私政策说明 Wander 如何处理数据。Wander 是一个不注册、不登录、无账号的 iOS 内容发现 App。当你不知道接下来做什么时，Wander 会给你一件可以读、看、听、观察或尝试的小事。

Wander 不收集你的真实身份信息。Wander 会处理有限的匿名功能数据，用于 App 功能、每日额度、防重复抽取、收藏、完成记录、网络重试幂等和内容多样性。

## 1. Wander 不收集什么

Wander 不要求注册或登录。Wander 不收集：

- 姓名
- 邮箱地址
- 手机号
- 精确位置
- 通讯录
- 相册、照片或视频
- 相机或麦克风内容
- 健康数据
- 支付信息
- IDFA 或广告标识符

Wander 不使用广告追踪，不出售用户数据，也不与数据经纪人共享用户数据。

## 2. 本地数据

Wander 可能在你的设备本地保存以下数据：

- `wander.user.uuid`：匿名内容身份，用于收藏、完成、已看过内容和 App 内清除数据流程。
- `wander.quota.uuid`：匿名额度身份，用于执行每 24 小时最多 10 条锦囊的限制。
- `wander.favorites.cache.v1.<user_uuid>`：收藏离线缓存，用于在网络受限时显示收藏。

这些标识符不是你的姓名、邮箱或手机号。它们是仅用于 App 运行的匿名功能标识符。

## 3. 服务端功能数据

Wander 可能处理和保存以下服务端功能数据：

- `user_uuid`
- `quota_id`
- `request_id`
- `ji_id`
- `scenario`
- `liked_ji_ids`
- `done_ji_ids`
- `seen_ji_ids`
- `seen_timestamps`
- `draw_count`
- `window_started_at`
- `reset_at`
- `created_at`
- `updated_at`

这些数据用于 App 功能，不用于广告追踪。

## 4. 数据用途

Wander 使用匿名功能数据来：

- 抽取并展示锦囊。
- 保存收藏。
- 保存已完成计数。
- 避免重复或过于相似的推荐。
- 维护每 24 小时最多 10 条锦囊的额度。
- 处理网络重试幂等，避免重复扣次数。
- 支持反算法内容多样性。
- 维护 App 安全、可靠性和服务稳定性。

## 5. Embedding 和推荐逻辑

Wander 可能保存由 Wander 自有锦囊内容生成的 embedding。这些 embedding 用于相似度过滤和内容多样性。

- embedding 用于相似度过滤和多样性。
- embedding 不返回客户端。
- embedding 不用于广告追踪。
- 收藏、完成和已看过记录仅用于 App 功能和推荐，不用于广告。

## 6. 第三方服务

Wander 使用以下第三方服务来运行 App：

- **Vercel**：托管 Wander 后端 API。
- **Supabase**：保存 Wander 的匿名功能数据和内容数据。
- **Apple**：提供 App Store 分发、TestFlight，以及在适用情况下由 Apple 管理的 App Analytics 或崩溃报告。

如果 Wander 未来加入在线 AI API 调用、分析、崩溃统计、支付、广告、账号或第三方登录，本隐私政策和 App Store 隐私披露会在发布相关变更前或发布时更新。

## 7. 清除我的数据

你可以在 App 内使用「清除我的数据」来清除收藏、完成记录，以及当前匿名内容身份相关的服务端数据。

清除后：

- 当前内容身份对应的本地收藏缓存会被清除。
- 当前内容身份相关的收藏和完成记录会被清除。
- 系统可能生成新的匿名内容身份。
- 当前 24 小时锦囊额度不会重置。

为防止绕过每 24 小时最多 10 条锦囊的限制，匿名额度身份和最小额度窗口记录可能会保留至当前额度窗口自然失效。

「清除我的数据」不是删除账号功能，因为 Wander 不创建用户账号。

## 8. 数据保留

Wander 仅在运行 App 和维护服务可靠性所需范围内保留匿名功能数据。

- 当前内容身份相关的收藏、完成和已看过记录会在你使用「清除我的数据」时清除，适用情况下如此处理。
- `user_uuid` 可能在清除数据后重置。
- `quota_id` 保留在本地，不会因清除数据而重置。
- 当前额度窗口记录会保留至当前 24 小时额度窗口自然结束。
- Vercel 和 Supabase 可能根据其基础设施设置保留服务器日志，用于安全、调试、防滥用和服务稳定。Wander 会在可行范围内尽量最小化此类日志。

如果 Wander 未来加入长期分析，本政策会更新。

## 9. 用户隐私选择和权利

你可以：

- 在 App 内清除收藏和完成记录。
- 通过邮箱联系我们，提出隐私问题，或在适用情况下请求访问、更正或删除数据。
- 请求了解 Wander 如何处理你的数据。

加州用户和其他享有适用隐私权利的用户，可以联系我们行使访问、删除、更正、选择退出出售或共享等适用权利。Wander 不出售个人数据，也不为跨 App 或跨网站广告追踪而共享数据。

由于 Wander 不要求账号，也不收集联系方式，如果你没有提供足够信息定位相关匿名 App 数据，我们可能无法识别某一特定用户记录。

## 10. 儿童

Wander 面向至少 18 岁以上用户。Wander 不是儿童 App，也不面向儿童或未成年人营销。Wander 不会故意收集 13 岁以下儿童的个人信息。

## 11. 隐私政策变更

我们可能不时更新本隐私政策。如有重大变化，我们会更新「最后更新」日期，并在适当情况下通过 App 或 App Store 元数据提供通知。

## 12. 联系方式

如有隐私问题，请联系：
[chuanhaigogogo@gmail.com](mailto:chuanhaigogogo@gmail.com)
