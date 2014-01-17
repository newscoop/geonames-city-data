geonames-city-data
==================

Separating the geonames.org city location data included with Newscoop into its own repository and packages

Check the size of the package with:

	du -sx --exclude DEBIAN geonames-city-data

Build with:

	fakeroot dpkg-deb --build geonames-city-data/

Test with:

	lintian geonames-city-data.deb
