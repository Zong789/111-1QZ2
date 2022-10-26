# 第2次隨堂-隨堂-QZ2
>
>學號：109111106
><br />
>姓名：陳宗鋕
><br />
>作業撰寫時間：30 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2022/10/26
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容

先在左邊工具箱拉一個Label及Button，並分別命名為lb_Msg及btn_Submit。

```csharp
<body>
    <form id="form1" runat="server">
        <div>
            <asp:Label ID="lb_Msg" runat="server" Text="Label"></asp:Label>
            <asp:Button ID="btn_Submit" runat="server" Text="送出" Height="40px" Width="40px" OnClick="btn_Submit_Click" />
        </div>
        
    </form>
</body>

```

之後打上Label顯示的文字，已及點擊Button會顯示的文字

```csharp
  public partial class Test : System.Web.UI.Page
    {
        protected void Page_Load(object sender, EventArgs e)
        {
            lb_Msg.Text = "Page_Load";
        }

        protected void btn_Submit_Click(object sender, EventArgs e)
        {
            lb_Msg.Text = "btn_Event";
        }
    }
}

```




## 個人認為完成作業須具備觀念

開始寫說明，需要說明本次作業個人覺得需學會那些觀念 (需寫成文章，需最少50字，
並且文內不得有你、我、他三種文字)

這次的隨堂需了解工具箱裡的Label及Button的用法，並知曉ButtonClick的用法。

