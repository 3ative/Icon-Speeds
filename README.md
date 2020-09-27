# Icon-Speeds
How to make rotating icons faster or slower, using CSS


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
