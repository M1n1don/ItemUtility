# ItemUtility  
Example  
```java
final Player p = Bukkit.getPlayer("M1n1don");
p.getInventory().setItem(
    0, 
    new Item(Material.PAPER)
        .setDisplayName("紙だよ")
        .addEnchantment(Enchantment.ご自由に, 100)
        .setLore(
            "1行目ー",
            "2行目ー",
            "何行でもできます"
        )
    .build();
);
