---
title: 支払いサイクル期間の変更
intro: アカウントのプランや、その他有料機能、有料製品は、月次または年次のサイクルで支払うことができます。
redirect_from:
  - /github/setting-up-and-managing-billing-and-payments-on-github/changing-the-duration-of-your-billing-cycle
  - /articles/monthly-and-yearly-billing
  - /articles/switching-between-monthly-and-yearly-billing-for-your-personal-account
  - /articles/switching-between-monthly-and-yearly-billing-for-your-organization
  - /articles/changing-the-duration-of-your-billing-cycle
  - /github/setting-up-and-managing-billing-and-payments-on-github/managing-your-github-billing-settings/changing-the-duration-of-your-billing-cycle
versions:
  fpt: '*'
  ghec: '*'
type: how_to
topics:
  - Organizations
  - Repositories
  - User account
shortTitle: 支払いサイクル
---

支払いサイクル期間を変更すると、{% data variables.product.prodname_dotcom %}のプランおよびその他の有料機能、有料製品は、次の支払日から新しい支払いサイクルに移行します。

## 個人アカウントの支払いサイクル期間の変更

{% data reusables.user_settings.access_settings %}
{% data reusables.user_settings.billing_plans %}
{% data reusables.dotcom_billing.change_plan_duration %}
{% data reusables.dotcom_billing.confirm_duration_change %}

## Organization の支払いサイクル期間の変更

{% data reusables.dotcom_billing.org-billing-perms %}

### ユーザ単位プランの期間の変更

{% data reusables.organizations.billing-settings %}
{% data reusables.dotcom_billing.change_plan_duration %}
{% data reusables.dotcom_billing.confirm_duration_change %}

### 過去のリポジトリ単位プランの期間の変更

{% data reusables.organizations.billing-settings %}
4. [Billing overview] で、[**Change plan**] をクリックします。 ![[Billing overview] の [Change plan] ボタン](/assets/images/help/billing/billing_overview_change_plan.png)
5. ページの右上で [**Switch to monthly billing**] または [**Switch to yearly billing**] をクリックします。 ![支払い情報セクション](/assets/images/help/billing/settings_billing_organization_plans_switch_to_yearly.png)
