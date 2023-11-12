Multi-Union V 0.1

This plugin performs a similar operation to the UNION tool available in the Vector -> Geoprocessing Tools menu of QGis3, but in this tool it is only possible to use two layers at a time, while in the MULTI-UNION plugin it is possible to use up to 6 layers in a single operation. Being a multiple union, the minimum number of layers is 3 layers, which must be placed in Inputs 1, 2 and 3. Optionally, 3 more layers can be used, in Inputs 4, 5 and 6. Expand the Advanced Parameters tab to choose which fields of each input layers will be included in the resulting UNION layer. Up to six layers can be used, in which case features from each layer are split at their overlap with features from the others, creating a layer (Union layer) containing all the portions from all layers. The attribute table of the Union layer is filled with attribute values from the respective original layers for non-overlapping features, and attribute values from all layers for overlapping features.

Use this plugin with QGis version 3.28 LTR or later.

Start this plugin at Processing Toolbox -> Multi-Union.
