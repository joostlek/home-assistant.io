---
title: "Onboarding Home Assistant"
description: "Instructions to get Home Assistant configured."
---

Alright, you made it here. The tough part is done.

With Home Assistant installed, it's time to configure it. Here you will create the owner account of Home Assistant. This account will be an administrator and will always be able to change everything. Enter a name, username, password and select **create account**.

![Set your username and password.](/images/getting-started/username.png)

Next, you can enter a name for your home and set your location and unit system. Select **Detect** to find your location and set your time zone and unit system based on that location. If you'd rather not send your location, you can set these values manually.

![Set your location, time zone, and unit system.](/images/getting-started/location.png)

Once you are done, click **Next**. In this screen, Home Assistant will show any {% term devices %} that it has discovered on your network. Don't be alarmed if you see fewer items than shown below; you can always manually add devices later.

![Discovery of devices on your network.](/images/getting-started/devices.png)

Finally, click **Finish**. Now you're brought to the Home Assistant web interface. This screen will show all of your devices.

{% include getting-started/next_step.html step="Concepts & Terminologies" link="/getting-started/concepts-terminology/" %}
