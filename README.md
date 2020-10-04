# Synical's Guns

A Datapack for Minecraft 1.16.2 and above.

## Usage

To use the datapacks API, for weapons all you need is a gun model(optional), a limit to how far iot can shoot(range), damage ratio, spray pattern, and a scope setting for either true or false. Example is below.
```
scoreboard players set @a[nbt={SelectedItem:{id:"minecraft:carrot_on_a_stick",tag:{gunType:{"EXAMPLE"}}}}] range 10
scoreboard players set @a[nbt={SelectedItem:{id:"minecraft:carrot_on_a_stick",tag:{gunType:{"EXAMPLE"}}}}] dmRATIO 10
scoreboard players set @a[nbt={SelectedItem:{id:"minecraft:carrot_on_a_stick",tag:{gunType:{"EXAMPLE"}}}}] sprayRand 5
scoreboard players set @a[nbt={SelectedItem:{id:"minecraft:carrot_on_a_stick",tag:{gunType:{"EXAMPLE"}}}}] scope 0
```
0 is equal to false, while 1 is equal to true.
