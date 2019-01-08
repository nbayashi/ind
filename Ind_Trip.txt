var viewer = new Cesium.Viewer('cesiumContainer');
viewer.dataSources.add(Cesium.KmlDataSource.load('Ind_Trip.kml'),{
         camera: viewer.scene.camera,
         canvas: viewer.scene.canvas
});

