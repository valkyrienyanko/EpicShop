# ShopGUIReborn

WIP

```yml
# Shops.yml
catalog:
  name: '&c&lCategories'
  rows: 1
  categories:
    food:
      category_item:
        material: APPLE
        quantity: 1
        name: '&cFood'
        lore:
        - '&tThis is the &qfood&t category!'
        - '&tFood is &qdelicious&t!'
        item_flags:
        - HIDE_ENCHANTS
        enchants:
          luck_of_the_sea:
            level: 3
        slot: 1
      category:
        name: "&c&lFood"
        rows: 3
        command: food
        items:
          '1':
            keep-open: false
            material: BREAD
            quantity: 2
            name: '&qBread'
            lore:
            - '&tBread is &qgood&t.'
            - '&tBread is &qlife&t.'
            price:
              xp-levels: 1
              buy: 10
              sell: 5
            slot: 1
    blocks:
      category_item:
        material: GRASS_BLOCK
        name: '&2Grass'
        lore:
        - '&tGrass category.'
        slot: 2
      category:
        name: '&2&lGrass'
        rows: 2
        items:
          '1':
            material: GRASS_BLOCK
            price:
              buy: 2
              sell: 1
            slot: 1
          '2':
            material: STONE
            price:
              buy: 4
              sell: 2
            slot: 11
```
