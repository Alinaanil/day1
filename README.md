# day1
<%@ Page Language="C#" AutoEventWireup="true" CodeFile="Default7.aspx.cs" Inherits="Default7" %>

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
    <title></title>
    <style type="text/css">

        .style1
        {
            width: 100%;
        }
    </style>
</head>
<body>
    <form id="form1" runat="server">
    <div>
    
        <table cellpadding="0" cellspacing="0" class="style1" align="center" 
            style="background-image: url('001.jpg')">
            <tr>
                <td colspan="3" style="text-align: left">
                    电子书借阅系统<asp:TextBox 
                        ID="TextBox1" runat="server"></asp:TextBox>
                    <asp:Button ID="Button1" runat="server" Text="查找" />
                </td>
            </tr>
            <tr>
                <td>
                    <a href="1">精品推荐</a></td>
                <td>
                    <a href="1">经典名著</a></td>
                <td>
                    <a href="1">文学艺术</a></td>
            </tr>
            <tr>
                <td>
                    <a href="1">政治法律</a></td>
                <td>
                    <a href="1">历史军事</a></td>
                <td>
                    <a href="1">人文科学</a></td>
            </tr>
            <tr>
                <td>
                    <a href="1">人生哲学</a></td>
                <td>
                    <a href="1">生活健康</a></td>
                <td>
                    <a href="1">教育教学</a></td>
            </tr>
            <tr>
                <td>
                    <a href="1">社会热点</a></td>
                <td>
                    <a href="1">设计艺术</a></td>
                <td>
                    <a href="1">环境保护</a></td>
            </tr>
        </table>
    
    </div>
    </form>
</body>
</html>
