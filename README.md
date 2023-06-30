# Mô tả thủ tục

### 👩‍💻 Proc_GetAllCategory_byCategoryIDParent_Opt

Mô tả: Lấy tất cả Danh mục con trong lĩnh vực

```
{{BASEURL}}/api?proc=Proc_GetAllCategory_byCategoryIDParent_Opt
```
Param:
- @CategoryIDParent uniqueidentifier.
```
[
    {
        "name":"CategoryIDParent",
        "type":"guid",
        "value":"DC74C8BC-F4A2-49B0-A11A-7BA1D519904E"
    }
]
```

### 👩‍💻 Proc_GetAllCategory_Opt

Mô tả: Lấy tất cả Lĩnh vực (sử dụng tại trang chủ)

```
{{BASEURL}}/api?proc=Proc_GetAllCategory_Opt
```
Param:
- Không có đối số
```
[]
```
### 👩‍💻 Proc_GetCategoryDetail_byCategoryID_Opt

Mô tả: Lấy thông tin chi tiết của lĩnh vực/danh mục

```
{{BASEURL}}/api?proc=Proc_GetCategoryDetail_byCategoryID_Opt
```
Param:
- @CategoryID uniqueidentifier.
```
[
    {
        "name":"CategoryID",
        "type":"guid",
        "value":"DC74C8BC-F4A2-49B0-A11A-7BA1D519904E"
    }
]
```
