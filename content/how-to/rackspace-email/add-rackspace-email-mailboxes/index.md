---
permalink: add-rackspace-email-mailboxes
audit_date: '2021-06-21'
title: Add Rackspace Email mailboxes
type: article
created_date: '2011-12-18'
created_by: William Loy
last_modified_date: '2021-06-21'
last_modified_by: Rose Morales
product: Rackspace Email
product_url: rackspace-email
---

You can add a single mailbox to your Rackspace Email account, or you can add
multiple mailboxes by using a CSV or Microsoft&reg; Excel&reg; file.

If you need to add a Microsoft Exchange&reg; mailbox, see
[Add Microsoft Exchange mailboxes](/support/how-to/adding-microsoft-exchange-mailboxes/).

### Prerequisites

- **Applies to:** Administrator
- **Difficulty:** Easy
- **Time needed:** 5 minutes to create a mailbox and 15 minutes for the mailbox
  to become accessible
- **Tools required:** Cloud Office Control Panel access

For more information about prerequisite terminology, see
[Cloud Office support terminology](/support/how-to/cloud-office-support-terminology).

### Add a single mailbox

1. Log in to the [Cloud Office Control Panel](https://cp.rackspace.com/) by using
   your Rackspace Cloud Office admin ID and password.
2. In the **Rackspace Email** section, click **Mailboxes**.

   {{<image src="CP - RSE Mailboxes.png" alt="" title="">}}

3. If you have more than one domain, select the domain to which you want to add
   a mailbox.
4. Click **Add Mailbox**.

    {{<image src="CP - RSE Mailboxes - Add.png" alt="" title="">}}

    **Note:** If the **Add Mailbox** button is unavailable, you must add the
    necessary licenses to your account before you can add a mailbox. See
    [Add a mailbox license](#add-a-mailbox-license) for instructions.

5. Enter the following information in the fields provided:

    - **First Name and Last Name** (optional): Enter the the mailbox owner's
      first and last name.
    - **Display Name** (optional): Enter the name to display when the user sends
      email.
    - **User Name:** Enter the name to use in the email address. For example, for
      a username and domain of **myname** and **yourdomainexample.com**, the email
      address is **myname@yourdomainexample.com**. **Note:** You are cannot create a
      username that already exists as an alias, group list, distribution list,
      or as another mailbox. You must remove the conflicting address from your
      account before using the same username for another purpose.
    - **Password:** Enter a password for the email account with the following
      requirements:
        - It must be at least eight characters.
        - It must use characters from at least three of the following four
          character types:
            - English alphabet uppercase letters (A-Z)
            - English alphabet lowercase letters (a-z)
            - Numerals (0-9)
            - Non-alphanumeric symbols (such as !, #, $, %)
    - **Confirm:** Retype the password that you entered in the **Password** box.

6. Click **Save**.

   **Note:** Mailbox creation in the Cloud Office Control Panel can
   take up to 15 minutes. After the mailbox is available, you can log
   in to the mailbox at [apps.rackspace.com](https://apps.rackspace.com/index.php).

The mailbox appears in the mailboxes list. To manage mailbox options such as forwarding,
autoreply, aliases, or settings, click the mailbox name and then click the
corresponding tab on the **Details** page.

### Add mailbox

**Warning:** When you add more than one mailbox, the new mailboxes take lnger to become
accessible because the system processes mailbox additions sequentially.

1. Log in to the [Cloud Office Control Panel](https://cp.rackspace.com/) by using
   your Rackspace Cloud Office admin ID and password.
2. In the **Rackspace Email** section, click **Mailboxes**.

3. If you have multiple domains, select the domain to which you want to add a
   mailbox.
4. Click **Add/Edit Multiple Mailboxes**.

    {{<image src="add-multi-mailboxes.png" alt="" title="">}}

    **Note:** If the **Add/Edit Multiple Mailboxes** button is unavailable, you
    must add the necessary number of licenses to your account before you can add
    a mailbox. See [Add a mailbox license](#add-a-mailbox-license) for
    instructions.

5. Create a CSV or Excel file(XLS) that contains the information detailed in the
   **Data Format** section of the **Import Mailboxes** page. You can download a
   template from that section to help you create a file with the correct format.

   The **Username**, **Password**, and **Enabled** fields are mandatory for all
   mailbox entries in the file. Passwords must meet the following requirements:

    - It must be at least eight characters.
    - It must use characters from at least three of the following four character
      types:
      - English alphabet uppercase letters (A-Z)
      - English alphabet lowercase letters (a-z)
      - Numerals (0-9)
      - Non-alphanumeric symbols (such as !, #, $, %)

        **Note:** You can’t create a username that already exists as an alias,
        group list, distribution list, or another mailbox. You must remove the
        conflicting address from your account before using the same username for
        another purpose.

6. In the **Import File** section of the **Import Mailboxes** page, click **Browse** or
   **Choose File**.
7. Locate and select the CSV or Excel file that you created.
8. Click **Open** and then click **Import**.

After creation, the mailboxes appear in the mailboxes list. Any errors that occur
display in the import log. Make corrections as detailed in the import log and
import again.

### Add a mailbox license

If the buttons to add one or more mailboxes are unavailable, you must add the
necessary licenses to your account before you can add a mailbox.

1. Click the **Upgrade this plan** link.

    {{<image src="add-rse-license-sc1.png" alt="" title="">}}

2. Under **Rackspace Email Mailboxes**, add the number of mailboxes you
   want to make available to your account.

    {{<image src="add-rse-license-sc2.png" alt="" title="">}}

3. Click **Continue**.
4. If the order summary looks correct, click **Complete Order**.

### References

- [Cloud Office support terminology](/support/how-to/cloud-office-support-terminology)
- [Cloud Office Control Panel](https://cp.rackspace.com/ "Cloud Office Control Panel")
- [Cloud Office Email Portal](https://apps.rackspace.com/index.php)
- [Add Microsoft Exchange mailboxes](/support/how-to/adding-microsoft-exchange-mailboxes/)
