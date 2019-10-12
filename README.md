# Maps, Delimitation and Gerrymandering with Python

These are the [slides](2019-10-12-PyCon-India-Maps.pptx) for my talk at [PyCon India 2019](https://in.pycon.org/2019/).

The talk is about joining geo-spatial data, and explains why this is useful, how you can do it, and what else is possible.

- [Download the slides](2019-10-12-PyCon-India-Maps.pptx)
- [View the IPython notebook](ka/merge.ipynb)

## Links

- If you're tweeting:
  - My Twitter ID is [@sanand0](https://twitter.com/sanand0)
  - The PyCon India hashtag is [#PyConIndia2019](https://twitter.com/search?q=%23pyconindia2019)
- The talk mentions [an article in The Hindu about the Muslim vote][hindu-article]
- The analysis uses geospatial joins using the [reshaper library](https://github.com/gramener/reshaper) using `merge.py`
  - This internally uses [geopandas](https://pypi.org/project/geopandas)
- [QGIS](https://www.qgis.org/) is a powerful GUI tool to process shapefiles
  - Here's a tutorial on [creating Voronoi polygons](http://djjr-courses.wikidot.com/soc128:qgis-voronoi-polygons) in QGIS. This lets you create regions from addresses or locations
- You can search for India maps on the [Datameet Google group](https://groups.google.com/forum/#!forum/datameet)

## What can you do now?

- **Have ideas?** If you have suggestions on useful geo-spatial joins to explore, [raise an issue](https://github.com/gramener/pycon2019/issues). Let's crowd-source and find out which geo-joins are useful
- **Want to try it?** Build your portfolio?
  - Search for maps on [Datameet]((https://groups.google.com/forum/#!forum/datameet))
  - Find reshaper at [reshaper library](https://github.com/gramener/reshaper)
  - Share on Twitter, tag [@sanand0](https://twitter.com/sanand0). I’ll share it with media
- **Want to learn or contribute?**
  - Email me at s.anand@gramener.com
  - I'll mail you details of the next workshop on geo-spatial joins


[hindu-article]: https://www.thehindu.com/elections/karnataka-2018/karnataka-elections-2018-the-spin-around-the-muslim-vote/article23806580.ece
