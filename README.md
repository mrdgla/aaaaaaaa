PREFIX: '&aShop > &f'
LANG:
  CONSOLE: Console
MSG:
  ERROR: Error occured, please contact the server owner.
  INGAMEONLY: This command can be used only in the game.
  NOACCESS: You don't have access to do this.
  NOTLOADED: Your data isn't loaded yet, please try again later.
  NOTLOADEDTARGET: This player's data isn't loaded yet, please try again later.
  RELOADED: Configuration reloaded!
  USAGE:
    SUBCOMMAND: 'Invalid command usage. Correct usage: %usage%'
  CMD:
    SHOP:
      ADDMODIFIER:
        ITEM:
          USAGE: /shop addmodifier item <player> <shop> <item> <value> [buy|sell]
          ADDED: You set &c%player%&f's %type% price modifier for the %item% item in %shop% shop to &c%modifier%&f.
          ADDEDBY: Your %type% price modifier for the %item% item in %shop% shop was set to &c%modifier%&f by &c%player%&f.
        SHOP:
          USAGE: /shop addmodifier shop <player> <shop> <value> [buy|sell]
          ADDED: You set &c%player%&f's %type% price modifier for all items in %shop% shop to &c%modifier%&f.
          ADDEDBY: Your %type% price modifier for all items in %shop% shop was set to &c%modifier%&f by &c%player%&f.
        GLOBAL:
          USAGE: /shop addmodifier global <player> <value> [buy|sell]
          ADDED: You set &c%player%&f's %type% price modifier to &c%modifier%&f.
          ADDEDBY: Your %type% price modifier was set to &c%modifier%&f by &c%player%&f.
      CHECKMODIFIERS:
        VIEW:
          VIEW: |-
            &c%player%&f's modifiers:
            Global modifiers:
            %global%
            Shop modifiers:
            %shop%
            Item modifiers:
            %item%
          ENTRY:
            ITEM: 'Item: &c%item%&f, shop: &c%shop%&f, buy: &c%buy%&f, sell: &c%sell%&f'
            SHOP: 'Shop: &c%shop%&f, buy: &c%buy%&f, sell: &c%sell%&f'
            GLOBAL: 'Buy: &c%buy%&f, sell: &c%sell%&f'
      RESETMODIFIER:
        ITEM:
          USAGE: /shop resetmodifier item <player> <shop> <item> [buy|sell]
          RESET: You reset &c%player%&f's %type% price modifier for the %item% item in %shop% shop.
          RESETBY: Your %type% price modifier for the %item% item in %shop% shop was reset by &c%player%&f.
        SHOP:
          USAGE: /shop resetmodifier shop <player> <shop> [buy|sell]
          RESET: You reset &c%player%&f's %type% price modifier for all items in %shop% shop.
          RESETBY: Your %type% price modifier for all items in %shop% shop was set to by &c%player%&f.
        GLOBAL:
          USAGE: /shop resetmodifier global <player> [buy|sell]
          RESET: You reset &c%player%&f's %type% price modifier.
          RESETBY: Your %type% price modifier was set to &c%modifier%&f by &c%player%&f.
  MODIFIER:
    INVALIDAMOUNT: Invalid modifier value specified. Valid values are for instance 0.50 which is 50%, 2.0 which is 200% etc.
    INVALIDTYPE: Invalid modifier type specified. Valid values are buy, sell and both.
    BUY: buy
    SELL: sell
    BOTH: buy & sell
  INVALIDPLAYER: Invalid player name specified.
  INVALIDSHOP: Shop with ID &c%shop%&f not found.
  INVALIDITEM: Item with ID &c%item%&f not found in &c%shop%&f.
  NOACCESSTOSHOP: You don't have access to &c%shop%&f shop.
  NODIRECTACCESSTOSHOP: You can't access the &c%shop%&f shop.
  MAINMENUDISABLED: You can't use this command. Please use /shop <id> instead.
  WORLDBANNED: You can't access the shop in this world.
  WORLDBANNEDTARGET: '%player% can''t access the shop in that world.'
  GAMEMODEBANNED: You can't access the shop when in gamemode %gamemode%.
  GAMEMODEBANNEDTARGET: '%player% can''t access the shop when in gamemode %gamemode%.'
  ITEM:
    FULLINVENTORY: You don't have enough free space in your inventory.
    CANNOTAFFORD: You need &c%price%$&f to buy &c%amount% x %item%&f.
    CANNOTBUY: You can't buy this item.
    CANNOTSELL: You can't sell this item.
    BOUGHT: You bought &c%amount% x %item%&f for &c%price%$&f.
    BOUGHTFREE: You received &c%amount% x %item%&f.
    NOTENOUGH: You don't have &c%amount% x %item%&f to sell.
    SOLD: You sold &a%amount% x %item%&f for &a%price%$&f.
    SOLDFREE: You gave away &a%amount% x %item%&f.
    SOLDALL: You sold all %item%&f (&a%amount% x %item%&f) for &a%price%$&f.
    SOLDALLFREE: You gave away all %item%&f (&a%amount% x %item%&f).
    NOACCESS: You don't have access to this item.
  ENCHANT:
    CANNOTAPPLY: Enchantment &c%enchantment%&f cannot be applied to the item you're holding.
    ALREADYAPPLIED: This item already has &c%enchantment%&f applied.
    LEVELDIFF: You need an item with at least &c%enchantment% %level%&f applied.
    CANNOTAFFORD: You need &c%price%$&f to buy &c%enchantment%&f.
    MAX: This item already has the maximum amount of enchantments (%amount%).
    TOOMANY: You can't enchant more than %amount% items at once.
    BOUGHT: You bought &c%enchantment%&f enchantment for &c%price%$&f.
  PERMISSION:
    PERMISSIONSDISABLED: Permissions are disabled, please contact server's owner.
    ALREADYHAVE: You already have the &c%permission%&f permission.
    CANNOTAFFORD: You need &c%price%$&f to buy &c%permission%&f.
    BOUGHT: You bought &c%permission%&f permission for &c%price%$&f.
  COMMAND:
    BOUGHT: You bought the command for &c%price%$&f.
    CANNOTAFFORD: You need &c%price%$&f to buy this command.
DIALOG:
  AMOUNTSELECTION:
    BUY:
      NAME: '&2Buying %item%'
    SELL:
      NAME: '&cSelling %item%'
