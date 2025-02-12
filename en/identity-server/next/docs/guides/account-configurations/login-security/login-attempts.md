# Login attempts

Secure user accounts from unauthorized access by configuring the login attempts policy in {{product_name}}.

## Configuration instructions

To manage login attempts settings, do the following:

1. In the {{product_name}} Console, go to **Login & Registration** > **Login Security** > **Login Attempts**.
2. Adjust the settings according to your security requirements.
3. Click **Update** to save the changes.

![Login Attempts Configuration]({{base_path}}/assets/img/guides/account-configurations/login-attempts.png)
{: width="600" style="display: block; margin: 0 auto;"}

## Parameters

<table>
  <tr>
    <th>Parameter</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Number of Consecutive Failed Login Attempts</td>
    <td>The count of consecutive incorrect login attempts before locking the account.</td>
  </tr>
  <tr>
    <td>Account Lock Duration</td>
    <td>The time in minutes an account stays locked after reaching the failed attempt limit.</td>
  </tr>
  <tr>
    <td>Account Lock Duration Increment Factor</td>
    <td>The rate at which the lock duration increases after successive lockouts.</td>
  </tr>
</table>
