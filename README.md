# osd-tile-loading

`254.dzi` is a deep zoom image with
* tile size = 254
* height = 1000
* width = 1000
* overlap = 1

`500.dzi` is a deep zoom image with
* tile size = 500
* height = 1000
* width = 1000
* overlap = 1

When `test.html` opens `254.dzi` the lowest layer image loaded is `8/0_0.jpeg`

When `test.html` opens `500.dzi` the lowest layer image loaded is `0/0_0.jpeg`
