TileSize sets the tiling size of the ImageLabel. The default `UDim2` values are 1,0,1,0. The scale component of the UDim2 will scale the tile based on the size of the ImageLabel. The offset is in raw pixels. The tiling starts at the upper left-hand corner of the image. For example a scale of 0.5 will mean the tile will be half the size of the ImageLabel (in the corresponding axis).

This property is only active if the ScaleType for the ImageLabel is set to Tile instead of Slice or Stretch.