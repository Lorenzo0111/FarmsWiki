# Using addons

## WorldGuard

```yaml
worldguard:
  enabled: true
```

## Vault

With this settings you can edit the price of a farm and of a Level Up.

```yaml
vault:
  enabled: true
  price: 1
  # The math expression will be newLevel * levelUp
  # For example if you set to 100 the levelUp price to level 5 will be 500
  levelUp: 100
```

