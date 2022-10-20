# 第1次隨堂-隨堂-QZ1
>
>學號：109111116
><br />
>姓名：朱羿安
><br />
>作業撰寫時間：60 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2022/10/20
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容


下段程式碼則為使用後結果：

```csharp
namespace _111_1QZ1
{
    public partial class Bomb : System.Web.UI.Page
    {
        protected void Page_Load(object sender, EventArgs e)
        {
            string[,] ia_Map = new string[10, 10];
            int[] ia_MIndex = new int[10] { 0, 7, 13, 28, 44, 62, 74, 75, 87, 90 };

            for (int Q = 0; Q<ia_MIndex.Length; Q++)
            {
                int X = ia_MIndex[Q] /ia_MIndex.Length;
                int Y = ia_MIndex[Q] %ia_MIndex.Length;
                ia_Map[X, Y]="*";

            }
            for (int R = 0; R<ia_Map.GetLength(0);R++)
            {
                for (int E = 1; E<ia_Map.GetLength(1); E++)
                {
                    if (ia_Map[R, E]!="*") ia_Map[R, E]="?";
                    Response.Write(ia_Map[R, E]+"  ");
                }
                Response.Write("<br>");
            }
        }
    }
}

```

下段程式碼則為使用後結果：

```html
<%@ Page Language="C#" AutoEventWireup="true" CodeBehind="Bomb.aspx.cs" Inherits="_111_1QZ1.Bomb" %>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
        </div>
    </form>
</body>
</html>
```


## 個人認為完成作業須具備觀念

先設定二維以及一維陣列，儲存BOMB的位置到對應的二維陣列。

