1. Start server: 

   ``` python 
   python -m http.server
   ```

2. Open one of the pages, changing vis type, areas and distribution. [Example](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/distance/distance_far.geojson&distribution=./synthetic-data/data/distance/distance.json).

3. Cases:

   1. Animation:
      1. Distance: near ([1](http://localhost:8000/hops.html?polygon=./synthetic-data/data/distance/distance_near.geojson&distribution=./synthetic-data/data/distance/distance_1.json), [2](http://localhost:8000/hops.html?polygon=./synthetic-data/data/distance/distance_near.geojson&distribution=./synthetic-data/data/distance/distance_2.json), [3](http://localhost:8000/hops.html?polygon=./synthetic-data/data/distance/distance_near.geojson&distribution=./synthetic-data/data/distance/distance_3.json), [4](http://localhost:8000/hops.html?polygon=./synthetic-data/data/distance/distance_near.geojson&distribution=./synthetic-data/data/distance/distance_4.json)), medium ([1](http://localhost:8000/hops.html?polygon=./synthetic-data/data/distance/distance_medium.geojson&distribution=./synthetic-data/data/distance/distance_1.json), [2](http://localhost:8000/hops.html?polygon=./synthetic-data/data/distance/distance_medium.geojson&distribution=./synthetic-data/data/distance/distance_2.json), [3](http://localhost:8000/hops.html?polygon=./synthetic-data/data/distance/distance_medium.geojson&distribution=./synthetic-data/data/distance/distance_3.json), [4](http://localhost:8000/hops.html?polygon=./synthetic-data/data/distance/distance_medium.geojson&distribution=./synthetic-data/data/distance/distance_4.json)), far ([1](http://localhost:8000/hops.html?polygon=./synthetic-data/data/distance/distance_far.geojson&distribution=./synthetic-data/data/distance/distance_1.json), [2](http://localhost:8000/hops.html?polygon=./synthetic-data/data/distance/distance_far.geojson&distribution=./synthetic-data/data/distance/distance_2.json), [3](http://localhost:8000/hops.html?polygon=./synthetic-data/data/distance/distance_far.geojson&distribution=./synthetic-data/data/distance/distance_3.json), [4](http://localhost:8000/hops.html?polygon=./synthetic-data/data/distance/distance_far.geojson&distribution=./synthetic-data/data/distance/distance_4.json))
      2. Size: small ([1](http://localhost:8000/hops.html?polygon=./synthetic-data/data/size/size_small.geojson&distribution=./synthetic-data/data/size/size_1.json), [2](http://localhost:8000/hops.html?polygon=./synthetic-data/data/size/size_small.geojson&distribution=./synthetic-data/data/size/size_2.json), [3](http://localhost:8000/hops.html?polygon=./synthetic-data/data/size/size_small.geojson&distribution=./synthetic-data/data/size/size_3.json), [4](http://localhost:8000/hops.html?polygon=./synthetic-data/data/size/size_small.geojson&distribution=./synthetic-data/data/size/size_4.json)), medium ([1](http://localhost:8000/hops.html?polygon=./synthetic-data/data/size/size_medium.geojson&distribution=./synthetic-data/data/size/size_1.json), [2](http://localhost:8000/hops.html?polygon=./synthetic-data/data/size/size_medium.geojson&distribution=./synthetic-data/data/size/size_2.json), [3](http://localhost:8000/hops.html?polygon=./synthetic-data/data/size/size_medium.geojson&distribution=./synthetic-data/data/size/size_3.json), [4](http://localhost:8000/hops.html?polygon=./synthetic-data/data/size/size_medium.geojson&distribution=./synthetic-data/data/size/size_4.json)), large ([1](http://localhost:8000/hops.html?polygon=./synthetic-data/data/size/size_large.geojson&distribution=./synthetic-data/data/size/size_1.json), [2](http://localhost:8000/hops.html?polygon=./synthetic-data/data/size/size_large.geojson&distribution=./synthetic-data/data/size/size_2.json), [3](http://localhost:8000/hops.html?polygon=./synthetic-data/data/size/size_large.geojson&distribution=./synthetic-data/data/size/size_3.json), [4](http://localhost:8000/hops.html?polygon=./synthetic-data/data/size/size_large.geojson&distribution=./synthetic-data/data/size/size_4.json))
      3. Number of regions: small ([1](http://localhost:8000/hops.html?polygon=./synthetic-data/data/number_regions/number_regions_small.geojson&distribution=./synthetic-data/data/number_regions/number_regions_1.json), [2](http://localhost:8000/hops.html?polygon=./synthetic-data/data/number_regions/number_regions_small.geojson&distribution=./synthetic-data/data/number_regions/number_regions_2.json), [3](http://localhost:8000/hops.html?polygon=./synthetic-data/data/number_regions/number_regions_small.geojson&distribution=./synthetic-data/data/number_regions/number_regions_3.json), [4](http://localhost:8000/hops.html?polygon=./synthetic-data/data/number_regions/number_regions_small.geojson&distribution=./synthetic-data/data/number_regions/number_regions_4.json)), medium ([1](http://localhost:8000/hops.html?polygon=./synthetic-data/data/number_regions/number_regions_medium.geojson&distribution=./synthetic-data/data/number_regions/number_regions_1.json), [2](http://localhost:8000/hops.html?polygon=./synthetic-data/data/number_regions/number_regions_medium.geojson&distribution=./synthetic-data/data/number_regions/number_regions_2.json), [3](http://localhost:8000/hops.html?polygon=./synthetic-data/data/number_regions/number_regions_medium.geojson&distribution=./synthetic-data/data/number_regions/number_regions_3.json), [4](http://localhost:8000/hops.html?polygon=./synthetic-data/data/number_regions/number_regions_medium.geojson&distribution=./synthetic-data/data/number_regions/number_regions_4.json)), large ([1](http://localhost:8000/hops.html?polygon=./synthetic-data/data/number_regions/number_regions_large.geojson&distribution=./synthetic-data/data/number_regions/number_regions_1.json), [2](http://localhost:8000/hops.html?polygon=./synthetic-data/data/number_regions/number_regions_large.geojson&distribution=./synthetic-data/data/number_regions/number_regions_2.json), [3](http://localhost:8000/hops.html?polygon=./synthetic-data/data/number_regions/number_regions_large.geojson&distribution=./synthetic-data/data/number_regions/number_regions_3.json), [4](http://localhost:8000/hops.html?polygon=./synthetic-data/data/number_regions/number_regions_large.geojson&distribution=./synthetic-data/data/number_regions/number_regions_4.json))
   2. Dot map:
      1. Distance: near ([1](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/distance/distance_near.geojson&distribution=./synthetic-data/data/distance/distance_1.json), [2](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/distance/distance_near.geojson&distribution=./synthetic-data/data/distance/distance_2.json), [3](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/distance/distance_near.geojson&distribution=./synthetic-data/data/distance/distance_3.json), [4](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/distance/distance_near.geojson&distribution=./synthetic-data/data/distance/distance_4.json)), medium ([1](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/distance/distance_medium.geojson&distribution=./synthetic-data/data/distance/distance_1.json), [2](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/distance/distance_medium.geojson&distribution=./synthetic-data/data/distance/distance_2.json), [3](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/distance/distance_medium.geojson&distribution=./synthetic-data/data/distance/distance_3.json), [4](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/distance/distance_medium.geojson&distribution=./synthetic-data/data/distance/distance_4.json)), far ([1](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/distance/distance_far.geojson&distribution=./synthetic-data/data/distance/distance_1.json), [2](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/distance/distance_far.geojson&distribution=./synthetic-data/data/distance/distance_2.json), [3](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/distance/distance_far.geojson&distribution=./synthetic-data/data/distance/distance_3.json), [4](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/distance/distance_far.geojson&distribution=./synthetic-data/data/distance/distance_4.json))
      2. Size: small ([1](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/size/size_small.geojson&distribution=./synthetic-data/data/size/size_1.json), [2](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/size/size_small.geojson&distribution=./synthetic-data/data/size/size_2.json), [3](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/size/size_small.geojson&distribution=./synthetic-data/data/size/size_3.json), [4](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/size/size_small.geojson&distribution=./synthetic-data/data/size/size_4.json)), medium ([1](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/size/size_medium.geojson&distribution=./synthetic-data/data/size/size_1.json), [2](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/size/size_medium.geojson&distribution=./synthetic-data/data/size/size_2.json), [3](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/size/size_medium.geojson&distribution=./synthetic-data/data/size/size_3.json), [4](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/size/size_medium.geojson&distribution=./synthetic-data/data/size/size_4.json)), large ([1](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/size/size_large.geojson&distribution=./synthetic-data/data/size/size_1.json), [2](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/size/size_large.geojson&distribution=./synthetic-data/data/size/size_2.json), [3](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/size/size_large.geojson&distribution=./synthetic-data/data/size/size_3.json), [4](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/size/size_large.geojson&distribution=./synthetic-data/data/size/size_4.json))
      3. Number of regions: small ([1](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/number_regions/number_regions_small.geojson&distribution=./synthetic-data/data/number_regions/number_regions_1.json), [2](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/number_regions/number_regions_small.geojson&distribution=./synthetic-data/data/number_regions/number_regions_2.json), [3](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/number_regions/number_regions_small.geojson&distribution=./synthetic-data/data/number_regions/number_regions_3.json), [4](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/number_regions/number_regions_small.geojson&distribution=./synthetic-data/data/number_regions/number_regions_4.json)), medium ([1](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/number_regions/number_regions_medium.geojson&distribution=./synthetic-data/data/number_regions/number_regions_1.json), [2](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/number_regions/number_regions_medium.geojson&distribution=./synthetic-data/data/number_regions/number_regions_2.json), [3](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/number_regions/number_regions_medium.geojson&distribution=./synthetic-data/data/number_regions/number_regions_3.json), [4](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/number_regions/number_regions_medium.geojson&distribution=./synthetic-data/data/number_regions/number_regions_4.json)), large ([1](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/number_regions/number_regions_large.geojson&distribution=./synthetic-data/data/number_regions/number_regions_1.json), [2](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/number_regions/number_regions_large.geojson&distribution=./synthetic-data/data/number_regions/number_regions_2.json), [3](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/number_regions/number_regions_large.geojson&distribution=./synthetic-data/data/number_regions/number_regions_3.json), [4](http://localhost:8000/dotmap.html?polygon=./synthetic-data/data/number_regions/number_regions_large.geojson&distribution=./synthetic-data/data/number_regions/number_regions_4.json))
   3. Interaction:
      1. Distance: near ([1](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/distance/distance_near.geojson&distribution=./synthetic-data/data/distance/distance_1.json), [2](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/distance/distance_near.geojson&distribution=./synthetic-data/data/distance/distance_2.json), [3](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/distance/distance_near.geojson&distribution=./synthetic-data/data/distance/distance_3.json), [4](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/distance/distance_near.geojson&distribution=./synthetic-data/data/distance/distance_4.json)), medium ([1](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/distance/distance_medium.geojson&distribution=./synthetic-data/data/distance/distance_1.json), [2](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/distance/distance_medium.geojson&distribution=./synthetic-data/data/distance/distance_2.json), [3](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/distance/distance_medium.geojson&distribution=./synthetic-data/data/distance/distance_3.json), [4](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/distance/distance_medium.geojson&distribution=./synthetic-data/data/distance/distance_4.json)), far ([1](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/distance/distance_far.geojson&distribution=./synthetic-data/data/distance/distance_1.json), [2](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/distance/distance_far.geojson&distribution=./synthetic-data/data/distance/distance_2.json), [3](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/distance/distance_far.geojson&distribution=./synthetic-data/data/distance/distance_3.json), [4](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/distance/distance_far.geojson&distribution=./synthetic-data/data/distance/distance_4.json))
      2. Size: small ([1](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/size/size_small.geojson&distribution=./synthetic-data/data/size/size_1.json), [2](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/size/size_small.geojson&distribution=./synthetic-data/data/size/size_2.json), [3](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/size/size_small.geojson&distribution=./synthetic-data/data/size/size_3.json), [4](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/size/size_small.geojson&distribution=./synthetic-data/data/size/size_4.json)), medium ([1](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/size/size_medium.geojson&distribution=./synthetic-data/data/size/size_1.json), [2](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/size/size_medium.geojson&distribution=./synthetic-data/data/size/size_2.json), [3](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/size/size_medium.geojson&distribution=./synthetic-data/data/size/size_3.json), [4](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/size/size_medium.geojson&distribution=./synthetic-data/data/size/size_4.json)), large ([1](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/size/size_large.geojson&distribution=./synthetic-data/data/size/size_1.json), [2](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/size/size_large.geojson&distribution=./synthetic-data/data/size/size_2.json), [3](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/size/size_large.geojson&distribution=./synthetic-data/data/size/size_3.json), [4](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/size/size_large.geojson&distribution=./synthetic-data/data/size/size_4.json))
      3. Number of regions: small ([1](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/number_regions/number_regions_small.geojson&distribution=./synthetic-data/data/number_regions/number_regions_1.json), [2](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/number_regions/number_regions_small.geojson&distribution=./synthetic-data/data/number_regions/number_regions_2.json), [3](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/number_regions/number_regions_small.geojson&distribution=./synthetic-data/data/number_regions/number_regions_3.json), [4](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/number_regions/number_regions_small.geojson&distribution=./synthetic-data/data/number_regions/number_regions_4.json)), medium ([1](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/number_regions/number_regions_medium.geojson&distribution=./synthetic-data/data/number_regions/number_regions_1.json), [2](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/number_regions/number_regions_medium.geojson&distribution=./synthetic-data/data/number_regions/number_regions_2.json), [3](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/number_regions/number_regions_medium.geojson&distribution=./synthetic-data/data/number_regions/number_regions_3.json), [4](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/number_regions/number_regions_medium.geojson&distribution=./synthetic-data/data/number_regions/number_regions_4.json)), large ([1](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/number_regions/number_regions_large.geojson&distribution=./synthetic-data/data/number_regions/number_regions_1.json), [2](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/number_regions/number_regions_large.geojson&distribution=./synthetic-data/data/number_regions/number_regions_2.json), [3](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/number_regions/number_regions_large.geojson&distribution=./synthetic-data/data/number_regions/number_regions_3.json), [4](http://localhost:8000/interaction.html?polygon=./synthetic-data/data/number_regions/number_regions_large.geojson&distribution=./synthetic-data/data/number_regions/number_regions_4.json))

