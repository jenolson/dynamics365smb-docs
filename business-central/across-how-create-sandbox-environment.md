---
title: Create a Sandbox Environment| Microsoft Docs
description: Create an environment for exploring, learning, demoing, developing, and testing.
author: SusanneWindfeldPedersen

ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: sandbox, demo, develop
ms.date: 06/26/2019
ms.author: solsen

---
[!INCLUDE[d365fin_early_release](includes/d365fin_early_release.md.md)]

# Creating a Sandbox Environment
A sandbox environment (Preview) is a non-production instance of [!INCLUDE[d365fin](includes/d365fin_md.md)]. Isolated from production, a sandbox environment is the place to safely explore, learn, demo, develop, and test the service without the risk of affecting the data and settings of your production environment.

## To create a sandbox environment
You must have a subscription to [!INCLUDE[d365fin](includes/d365fin_md.md)] to be able to create a sandbox environment. There can only be one sandbox environment per subscription.

1. Sign in to your production instance of the [!INCLUDE[d365fin](includes/d365fin_md.md)] service.

2. Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Sandbox Environment**, and then choose the related link.
<!-- ![Sandbox Environment Setup](./media/across-sandbox/sandbox-environment-setup.png) -->
3. Choose the **Create** button.  

    Another tab with [!INCLUDE[d365fin](includes/d365fin_md.md)] opens where you can finish the setup of your sandbox environment.

    > [!NOTE]  
    >  If you have pop-up blocker enabled in your browser, change it to allow URLs from the *.businesscentral.dynamics.com address.

4. When the sandbox environment is ready, you will be redirected to sandbox environment's Welcome wizard.
<!-- ![Sandbox Welcome Wizard](./media/across-sandbox/sandbox-wizard.png) -->

5. Choose the **Learn more** button to read about scenarios that you can try in a sandbox environment or choose the **Close** button to continue to the Role Center of your [!INCLUDE[d365fin](includes/d365fin_md.md)] sandbox instance.

    At the top of the Role Center, a notification appears to inform you that this is a sandbox environment. You can also see the type of the environment in the title bar of the client.
    <!-- ![Sandbox RoleCenter Notification](./media/across-sandbox/sandbox-rolecenter-notification.png) -->

    > [!NOTE]
    > A sandbox environment created in this way only contains the default demonstration data for the CRONUS company. No data is copied or otherwise transferred from the production environment.<br /><br />
    > You can also create a sandbox environment containing the production data. You must do this through the administration center. For more information, see [Managing Environments](/business-central/dev-itpro/administration/tenant-admin-center-environments) in the Developer and IT-Pro help.

6. At any time, you can return to the **Sandbox Environment** page, and reset the sandbox environment.
    > [!NOTE]  
    >  Resetting the sandbox environment will remove it completely, and then create it again with the default demonstration data.  

7. To switch between your production and sandbox environments, you can use the Business Central app launcher.
<!-- ![Sandbox Dynamics365 Menu](./media/across-sandbox/sandbox-dynamics365-menu.png) -->

8. It is possible for an administrator or another user to limit or even block access for some users to the sandbox environment. This can be done by using the standard security features of the product, such as the User card, user groups, and permission sets.

<!-- ![Sandbox Permission Sets](./media/across-sandbox/sandbox-permission-sets.png) -->

## Advanced Functionality in the Sandbox Environment
### Designer
In a sandbox environment, you will find the **Designer** enabled, which you can activate by selecting the design icon ![Designer](./media/across-sandbox/sandbox-inclient-design-icon.png) on a page.

<!-- ![In-client Designer](./media/across-sandbox/sandbox-inclient-designer.png) -->

### To enable the advanced user experience
It is possible to enable and try the advanced (full) functionality of [!INCLUDE[d365fin](includes/d365fin_md.md)] in a sandbox tenant by setting the **Experience** field on the **Company Information** page.

<!-- ![Sandbox Environment Advanced](./media/across-sandbox/sandbox-advanced.png) -->

<!-- ![Sandbox Production](./media/across-sandbox/sandbox-production.png) -->

After you have enabled the advanced functionality in a sandbox tenant, you get access to all the standard profiles (roles) and Role Centers. You can also create an evaluation company that is fully set up, including demonstration data and access to the advanced areas of the product.

<!-- ![Sandbox New Company](./media/across-sandbox/sandbox-newcompany.png) -->


## See Also
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
