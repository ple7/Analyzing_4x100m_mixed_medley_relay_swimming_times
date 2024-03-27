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

| 1. Backstroke | 2. Breaststroke | 3. Butterfly | 4. Freestyle | Total        |           |
|:-------------:|:---------------:|:------------:|:------------:|:------------:|:---------:|
| 00:51.60      | 00:56.88        | 00:55.48     | 00:51.71     | **03:35.67** | (M-M-F-F) |
| 00:51.60      | 01:04.13        | 00:49.95     | 00:51.71     | 03:37.39     | (M-F-M-F) |
| 00:51.60      | 01:04.13        | 00:55.48     | 00:46.86     | 03:38.07     | (M-F-F-M) |
| 00:57.33      | 00:56.88        | 00:49.95     | 00:51.71     | **03:35.87** | (F-M-M-F) |
| 00:57.33      | 00:56.88        | 00:55.48     | 00:46.86     | **03:36.55** | (F-M-F-M) | 
| 00:57.33      | 01:04.13        | 00:49.95     | 00:46.86     | 03:38.27     | (F-F-M-M) |

