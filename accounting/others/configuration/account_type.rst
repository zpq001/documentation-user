==================================================
什么事科目表类型及如何配置它?
==================================================

什么是科目表类型 ? 
==========================

科目类型是给定一个科目名称或代码，表示
科目的目的。

在Odoo中, 科目类型是用于信息的目的, 产生
国家指定法定报告, 设置规则来关闭年度并产生开账分。

Basically Account types categorize general account with some specific
category according to its behaviour or purpose.

Which are the account types in Odoo ?
=====================================

Odoo covers all accounting types. Therefore, you cannot create new
account types. Just pick the one related to your account.

+-----------------------------+
| **List of account types**   |
+=============================+
| Receivable                  |
+-----------------------------+
| Payable                     |
+-----------------------------+
| Bank and Cash               |
+-----------------------------+
| Current Assets              |
+-----------------------------+
| Non-current Assets          |
+-----------------------------+
| Prepayments                 |
+-----------------------------+
| Fixed Assets                |
+-----------------------------+
| Current Liabilities         |
+-----------------------------+
| Non-current Liabilities     |
+-----------------------------+
| Equity                      |
+-----------------------------+
| Current Year Earnings       |
+-----------------------------+
| Other Income                |
+-----------------------------+
| Income                      |
+-----------------------------+
| Depreciation                |
+-----------------------------+
| Expenses                    |
+-----------------------------+
| Direct Costs                |
+-----------------------------+

How do I configure my accounts ?
================================

Account types are automatically created when installing a chart of
account. By default, Odoo provides a lot of chart of accounts, just
install the one related to your country.

It will install generic accounts. But if it does not cover all your
cases, you can create your own accounts too.

.. note::

	If you are a Saas User, your country chart of account is
	automatically installed.

To create a new accounts, go to the Accounting application. Open the
menu :menuselection:`Adviser --> Chart of Accounts`, the click on the
**Create** button.

.. image:: ./media/type01.png
   :align: center

.. demo:fields:: account.action_account_form

.. demo:action:: account.action_account_form

   View *Create Account* in our Online Demonstration
