# physique

## Fat percent

I should do all these when maintaining my fat percentage. [Wikipedia](https://en.wikipedia.org/wiki/Body_fat_percentage) says that the body fat should be between `6-13%` for men athletes. The mean is `9.5%`. So I should strive to maintain the fat percentage at 9.5% (give or take 0.5%).


Hence, I should stay within `9%-10%`. So this is an algorithm that I should be following in my gym everyday:

* If my fat% is > 10%, I should run for an hour (cardio) and then workout
* If my fat% is between 9%-10%, I should just workout
* If my fat% < 9%, I should eat relatively large quantities of healthy fat after just working out



## Weight

Here I document how much I should weigh.

According to [WHO](http://apps.who.int/bmi/index.jsp?introPage=intro_3.html), the normal BMI Index should be in between `18.50` and `24.99`. Let us calculate mean:

```
(18.50 + 24.99)/2 = 21.745
```

So `21.745` should be the Ideal BMI that I should be striving for. There are two variables to calculating BMI. It is defined as the weight in kilograms divided by the square of the height in metres (kg/m2). My height is a constant `1.6m`. The variable is weight. Lets determine it.


```
KG = Ideal BMI * (height ** 2)

   = 21.745 * (1.6 ** 2)

   = 55.6672
```

Hence, I should stay within 55kg - 56kg. So this is an algorithm that I should be following in my gym everyday:

* If my weight > 56 kgs, I should run for an hour (cardio) and then workout
* If my weight is between 55-56 kgs, I should just workout
* If my weight < 56 kgs, I should eat relatively large quantities of proteins and vitamins  after just working out(i.e healthy food :P)

## Graph

| Measurement | Underweight (<55kg) | Desired Weight (55-56kg) | Overweight (>56kg) |
|  --- | --- | --- |--- |
| Lower fat (<9%) | Healthy +fat, +proteins & +vitamins; Dont run | Healthy food +fat; Dont run | light food +fat; Dont run |
| Optimal fat (9%-10%) | Healthy food, +proteins & +vitamins; Dont run | just healthy food & workout (I should strive to be here) | less food; Run for an hour |
| Higher fat (>10%) | No fat content, +proteins & +vitamins; Dont run | No fat content, regular food; Run for an hour | less food, less fat; Run for an hour |


Comments and suggestions welcomed.
