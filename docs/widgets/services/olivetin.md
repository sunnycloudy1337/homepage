---
title: OliveTin
description: OliveTin Widget Configuration
---

Learn more about [OliveTin](https://www.olivetin.app/).

![image](https://github.com/sunnycloudy1337/homepage/assets/163424707/09e3ad1f-dfc4-4476-b1a8-214c92c35953)

OliveTin gives safe and simple access to predefined shell commands from a web interface.

All actions must have a id specified that matches the one from the OliveTin configuration

!!! note

    Currently there is no feedback after triggering an action.

```yaml
widget:
  type: olivetin
  url: http://olivetin.host.or.ip:port
  actions:
    - id: volume_down # Required, the action id from OliveTin (https://docs.olivetin.app/action-ids.html)
      label: 🔉
      class: text-xl # Optional, default is "font-thin text-sm"
    - id: volume_toggle
      label: 🔇
      class: text-xl
    - id: volume_up
      label: 🔊
      class: text-xl
```
