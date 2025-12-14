# Icon-Speeds
How to make rotating icons faster or slower, using CSS

![1](https://github.com/3ative/Icon-Speeds/blob/master/3_speeds.gif)

```yaml
color: var(--state-icon-color)
entity: input_number.fan_bedroom
icon: 'mdi:fan'
name: Bedroom
state:
  - operator: ==
    styles:
      icon:
        - color: var(--state-icon-active-color)
        - animation: rotating 5s linear infinite
    value: 1
  - operator: ==
    styles:
      icon:
        - color: var(--state-icon-active-color)
        - animation: rotating 1.2s linear infinite
    value: 2
  - operator: ==
    styles:
      icon:
        - color: var(--state-icon-active-color)
        - animation: rotating 0.5s linear infinite
    value: 3
state_display: 'on'
styles:
  card:
    - font-size: 10px
type: 'custom:button-card'
```
---

<div align="center">

### 💖 Support This Project

Found this useful? Want to say thanks and fuel future creations?

**Your support keeps the creativity flowing!** 🍺✨

<table>
  <tr>
    <td align="center">
      <a href="https://www.buymeacoffee.com/3ative">
        <img src="https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Support-yellow.svg?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white" alt="Buy Me A Coffee"/>
        <br/>
        <b>☕ Buy me a Coffee</b>
      </a>
    </td>
    <td align="center">
      <a href="https://www.patreon.com/3ative">
        <img src="https://img.shields.io/badge/Patreon-Become%20a%20Patron-red.svg?style=for-the-badge&logo=patreon&logoColor=white" alt="Patreon"/>
        <br/>
        <b>💖 Join on Patreon</b>
      </a>
    </td>
  </tr>
</table>

**Every contribution helps bring more awesome projects to life!** 🚀

</div>

---
