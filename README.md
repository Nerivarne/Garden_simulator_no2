# Garden_simulator_no2

You are going to model a garden with watering and a gardener who picks bloomed flower.

### Flower

- Flower should have a number of blooms.

- Flower has 0 blooms by default.

- It has an `watering()` method which will increase a number of blooms.

- It has a `getStatus()` which returns something like "Type of flower: Rose, Number of blooms: 3"

### Rose

- Rose blooms by 2 blooms each time its watering.

### Lily

- Lily blooms by 1 bloom each time its watering.

### Cactus

- Cactus blooms by 1 bloom every second watering.

### Gardener

- You should be able to create a gardener with providing their name.

- It has a `canPick()` method which take a flower as parameter and returns true (if flower has 3 or more blooms and is not already picked) otherwise it returns false.

### Garden

- It should have a list of growing flowers.

- It should have a list of picked flowers.

- It has a `wateringAllGarden()` which should watering every flower in the garden.

- It has a `pickFlower(gardener)` method which should move all the growing flowers which gardener can pick into list of picked flowers (it calls another method).

- It has a `sellFlower(flower)` which removes the flower the customer chooses from the picked flowers list.
