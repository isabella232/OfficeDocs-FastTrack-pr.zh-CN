**Windows 虚拟桌面**

<table>
<thead>
<tr class="header">
<th><strong>服务</strong></th>
<th><strong>FastTrack 指南详细信息</strong></th>
<th><strong>对源环境的预期</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Windows 虚拟桌面</td>
<td><p>FastTrack 提供了 Windows 虚拟桌面部署指南，可帮助你轻松实现此桌面和应用虚拟化服务的使用，同时充分利用 Windows 10 多会话体验，针对使用集成安全性和管理的 Microsoft 365 企业版的 M365 应用程序进行了优化。</p>
<p>你可与 FastTrack 专家协作：</p>
<ul>
<li><p>使用以下各项为企业版部署具有 Windows 10 企业版多会话 + M365 应用程序的 WVD 环境：</p>
<ul>
<li><p>Azure Marketplace 图像</p></li>
<li><p>共享图像</p></li>
<li><p>Office 部署工具包 (ODT) </p></li>
</ul></li>
<li><p>配置 FSLogix</p>
<ul>
<li><p>使用配置文件容器部署 FSLogix 代理</p></li>
<li><p>使用 Office 容器部署 FSLogix 代理</p></li>
<li><p>配置包含内容排除的 FSLogix 文件夹</p></li>
</ul></li>
<li><p>部署 Microsoft Edge</p></li>
<li><p>部署 Microsoft 团队</p></li>
<li><p>使用 Windows 虚拟桌面客户端连接</p></li>
</ul>
<p><strong>以下项超出范围</strong></p>
<ul>
<li><p>客户的 Windows 虚拟桌面部署的项目管理。</p></li>
<li><p>现场支持。</p></li>
<li><p>第三方应用程序虚拟化/部署。</p></li>
<li><p>自定义图像。</p></li>
<li><p>涉及 VMware 和 Citrix 的迁移和方案。</p></li>
<li><p>Linux 应用场景。</p></li>
<li><p>用户配置文件的转换或迁移。</p></li>
</ul>
<p>联系 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a>   以获取有关这些服务的帮助。</p></td>
<td><p>您应该已经具备以下各项：</p>
<ul>
<li><p><a href="https://docs.microsoft.com/en-us/azure/virtual-desktop/overview#requirements">WVD 许可要求</a></p></li>
<li><p>Azure 网络：</p>
<ul>
<li><p>VNET 创建 &amp; 子网</p></li>
<li><p>防火墙/网络安全组</p></li>
<li><p>VPN/ExpressRoute</p></li>
<li><p>从本地路由到 Azure</p></li>
<li><p>允许连接到 WVD 的防火墙规则</p>
<ul>
<li><p><a href="https://docs.microsoft.com/en-us/azure/virtual-desktop/overview#supported-remote-desktop-clients">文档参考</a></p></li>
</ul></li>
</ul></li>
<li><p>Azure Active Directory 常规安装程序</p>
<ul>
<li><p>标识策略 <strong> (仅选择以下3个选项中的1个) </strong></p>
<ul>
<li><p>Azure AD Connect in Azure 中的 Active Directory</p></li>
<li><p>使用 VPN/ER 的本地连接 Azure AD 的 Active Directory</p></li>
<li><p>Active Directory 域服务</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
