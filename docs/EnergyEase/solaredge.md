---
title: SolarEdge
description: How to Get SolarEdge Client ID and Client Secret
---

# How to Get SolarEdge Client ID and Client Secret

Before using SolarEdge devices, please update your Energy Ease App to the latest version.

When connecting SolarEdge in the Energy Ease App, you need to enter your **Client ID** and **Client Secret** first. After entering them, the Energy Ease App will redirect you to the SolarEdge page. Log in to your SolarEdge account and complete the authorization.

> **Note**
>
> The free SolarEdge API plan provides **2,000 credits per month**, so device data is updated approximately every **15 minutes** by default.

## How to Get SolarEdge Client ID and Client Secret?

### Step 1

Go to the [SolarEdge Developer Console](https://developer.solaredge.com/) and sign in with your existing SolarEdge account.

### Step 2

Create an application of type **Site Access** in the Developer Console.

<img src={require("./img/solaredge_step2.png").default} />

### Step 3

Click the name of the application you created to open the **Settings** page.

<img src={require("./img/solaredge_step3.png").default} />

On the **Settings** page, set the following two URLs to the Energy Ease domain:

- **Allowed Redirect URL(s)**: `https://manosdatahubse.energy-ease.com`
- **Allowed Returned URL(s) (Optional)**: `https://manosdatahubse.energy-ease.com`

> **Note**
>
> Make sure the URLs above are entered correctly. Otherwise, the SolarEdge authorization may fail.

### Step 4

Go to the **Credentials** page to view your **Client ID** and **Client Secret**.

<img src={require("./img/solaredge_step4.png").default} />

If you cannot find the **Client Secret**, click **Regenerate Secret** to generate a new one.

> **Note**
>
> After regenerating the Client Secret, use the new Client Secret to complete the subsequent authorization.