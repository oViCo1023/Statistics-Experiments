# Statistics Experiments
**Study 1: Relationship between speed and fuel consumption of cars**
Suppose that the Ministry of Transportation is planning an information campaign for car drivers. The purpose
of the campaign is to make drivers aware of the impact of various driving behaviors onto fuel consumption. For
the campaign, the Ministry wants to create a table showing the impact of various driving speeds onto fuel
consumption, but they believe that also the temperature of the engine should be taken into account, as the
fuel consumption at various speeds may be different for cold engines and warmed-up engines. A fully warmedup
engine is usually around 95°C. For most cars, the most fuel-economic driving speed is between 60 and
80km/h (kilometers per hour).
Fuel consumption is the consumed fuel per distance traveled, which is expressed in l/100km (liters per
100 kilometers). Typical values are 𝐹𝐹𝐹𝐹 = 5 l/100km (when driving on a motorway) and 𝐹𝐹𝐹𝐹 = 7 l/100km (when
driving in a city) for small European and Asian cars, and 𝐹𝐹𝐹𝐹 = 9 l/100km (motorway) and 𝐹𝐹𝐹𝐹 = 11 l/100km
(city) for a midsize American car. The inverse of fuel consumption is the fuel economy, which is the distance
traveled (in km) per liter of fuel. In the US, they use MPG (miles per gallon) to express fuel economy.
Besides speed and engine temperature, also the type of fuel (diesel versus gasoline) affects fuel
consumption. The driver’s driving style has a big impact: frequent braking and accelerating brings down the
fuel economy considerably. And the fuel consumption is of course affected by characteristics of the vehicle,
such as its weight, the design of its engine, its aerodynamic characteristics, and its maintenance condition.

**Study 2: Heterogeneity of road surface markings**
Road markings, used to delineate traffic lanes and provide guidance or information to drivers and pedestrians,
are often made from thermoplastic paint with glass beads to provide reflectivity. Reflectivity greatly varies
between different areas on the same road marking, and engineers of the Ministry want to understand the
sources of this variation.
The idea is as follows. They want to make 10 test surfaces, where they apply paint to an area of around
1m2. Next, they want to randomly select 3 sample areas (about 1cm^2) from each test surface. Finally, they
measure the reflectivity in each sample area 2 times. The main question that they hope to answer, is: how
heterogeneous is the reflectivity of the paint over a test surface, in other words: what is the variance between
the mean reflectivity in different areas within the same test surface?

**Study 3: optimizing asphalt concrete for road pavement**
Context and objective
Asphalt has a few advantages over concrete for paving roads, such as its initial lower cost and lower noise. One
of the disadvantages, however, is that it is less strong. In this study, you will optimize the composition of
asphalt so as to maximize its strength, and the 𝑦-variable is a property called the compressive strength.
You will work with two 𝑥 variables:
- 𝑥1 (Water-to-cement ratio): 0.00 – 5.00
- 𝑥2 (Coarse-aggregate size): 0.00 – 5.00
- Hold 𝑥3 constant at the value 𝑥3 = 2.50.
Your objective: find settings for 𝑥1 and 𝑥2 that maximize 𝑦.
