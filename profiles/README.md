## 分享您的配置文件：

> [!WARNING]  
> **2025-03-31 之前** 的构建版本在导出时不会从 json 中去除 **profile ID (配置文件 ID)** - 该 ID 是系统特定的，可能会与其他人的 ID 冲突。请更新到最新构建版本（推荐）或在分享之前手动去除 profile ID。

配置文件名称必须在这 3 个位置保持一致，这样配置文件才能正确链接到描述（见图）：
- `profile name`.json ( json 文件的名称 )
- "name": "`profile name`", ( json 结构内部使用的名称 )
- `profile name`.md ( markdown 文件的名称 )

![image](https://github.com/user-attachments/assets/cce932b1-f4cd-45e5-afca-006e63dcc7e9)

---
*Original text:*
## Sharing your profile:

> [!WARNING]  
> Builds **before 2025-03-31** don't strip the **profile ID** from the json when exporting - the ID is system specific and might clash with other people's IDs. Update to latest build (recommended) or manually strip the profile ID before sharing.

The profile name must be the same in 3 locations so the profile is properly linked to the description (see image):
- `profile name`.json ( the name of the json file )
- "name": "`profile name`", ( the name used inside the json structure )
- `profile name`.md ( the name of the markdown file )

![image](https://github.com/user-attachments/assets/cce932b1-f4cd-45e5-afca-006e63dcc7e9)