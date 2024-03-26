# Finding the best strategies for swimming's 4x100 metre Mixed Medley Relay

The 4x100m Mixed Medley Relay race in swimming was first introduced to the Olympics swimming program at the Tokyo 2020 games. Each team in this race is made up of a combination of two male and two female swimmers, and the strokes to be swum are in this order: backstroke, breaststroke, butterfly, and freestyle.

The following table contains all the possible combinations for 2 male and 2 female swimmers for this race.

|   1. Backstroke   |   2. Breaststroke   |   3. Butterfly   |   4. Freestyle   |                           | 
| ----------------- | ------------------- | ---------------- | ---------------- |---------------------------|
|    **M**ale       |    **M**ale         |    **F**emale    |    **F**emale    | (**M**-**M**-**F**-**F**) |
|    **M**ale       |    **F**emale       |    **M**ale      |    **F**emale    | (**M**-**F**-**M**-**F**) |
|    **M**ale       |    **F**emale       |    **F**emale    |    **M**ale      | (**M**-**F**-**F**-**M**) |
|    **F**emale     |    **M**ale         |    **M**ale      |    **F**emale    | (**F**-**M**-**M**-**F**) |
|    **F**emale     |    **M**ale         |    **F**emale    |    **M**ale      | (**F**-**M**-**F**-**M**) |
|    **F**emale     |    **F**emale       |    **M**ale      |    **M**ale      | (**F**-**F**-**M**-**M**) |

One possibility for working out the best possible combination for a team is to substitute the swimmers' times in the matrix above and tally them up. For example, using the world record times for each stroke would yield the following table.
