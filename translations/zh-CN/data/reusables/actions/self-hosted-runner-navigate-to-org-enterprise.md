{% ifversion fpt %}
1. 导航到注册自托管运行器的组织主页。
2. 单击 {% octicon "gear" aria-label="The Settings gear" %} **Settings（设置）**。
{% data reusables.organizations.settings-sidebar-actions-runners %}
{% elsif ghec or ghes or ghae %}
1. 导航到自托管运行器注册的位置：
   * **在组织中**，导航到主页并单击 {% octicon "gear" aria-label="The Settings gear" %} **Settings（设置）**。
   * **如果使用企业级运行器**：

{% indented_data_reference reusables.enterprise-accounts.access-enterprise spaces=5 %}
1. 导航到 {% data variables.product.prodname_actions %} 设置：
   * **在组织中**：

{% indented_data_reference reusables.actions.settings-ui.settings-actions-runners spaces=5 %}
   * **如果使用企业级运行器**：

{% indented_data_reference reusables.enterprise-accounts.policies-tab spaces=5 %}
{% indented_data_reference reusables.enterprise-accounts.actions-tab spaces=5 %}
{% indented_data_reference reusables.enterprise-accounts.actions-runners-tab spaces=5 %}
{% endif %}
