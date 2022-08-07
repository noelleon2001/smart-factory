# Smart Packaging Factory

This just a demo of the smart factory I designed for EAMMSS EAnnovate 2022 competition.

## Description
This factory has been designed according to the theme of the competition, which is Mooncake ordering and packing.

Features added:

* **Discord Bot**
  1. Added a menu/list for the user to order. 
  2. The previous program requires the user to enter the code of the mooncake when using the !order command. Now the user can instead view a menu and select the mooncake they like. This increases the interactiveness of the bot and completely eliminates typing error when ordering. (The previous feature is still included for debugging purposes)
  3. Added confirmation response after the user places order.
  4. Increase the aesthetics of all the responses from the discord bot using emojis and better formatting.

* **Node-red Dashboard**
  1. Added line graph that shows the number of orders completed vs time. The graph will give a visual representation of the status of the factory.
  2. Added line graph that shows the performance of the factory, ie the number of orders completed in 10 seconds. 
  3. Added a pie chart that shows the number of mooncakes of each type that are dispensed. 
  4. The graph will give a visual representation of the preferences of which mooncake the users like. It can also show how many mooncakes have been dispensed and from there we can determine the stock level of each mooncakes if required.
  5. Added emergency stop button.

* **Factory IO**
  1. Increased the number of concurrent orders being processed in the factory from 1 to 3. Now the factory can process up to a maximum of 3 orders at the same time. This will greatly increase both the energy efficiency and speed of the mooncake being made by 2-3 times the original design.
  2. The belt conveyors are placed higher to prevent any collision with the stackable box.
Green and Red buttons are added to allow the operator to start(continue) and stop the factory on-site. The green button will light up when the factory is running and the red button will light up when the factory is halted.
  3. Added an emergency stop button that will stop all the conveyor and all the process regardless of whether there is anything on the conveyor. This increases the safety level of the factory.
  4. Added a yellow indicator light that will flash when the stop button is pressed, and the factory is clearing the roller conveyor. The operator should not press the green button when it is flashing.
  5. Added 2 digit displays that show the number of orders. The left display shows the number of orders that are completed, while the right shows the number of orders that are currently processed in the factory. The 2 numbers should match when there is no order processing on the conveyor.
  6. Added safeguard and platforms to increase safety when working around the machine.

## Node-RED palette used
```bash
node-red-contrib-discord-advanced
node-red-node-sqlite
node-red-contrib-opcua
```

## Images

