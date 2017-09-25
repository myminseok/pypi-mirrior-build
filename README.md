split -b 100000000 R_buildpack-cached-v0.1.0.zip "R_buildpack-cached-v0.1.0.zip.part"

cat R_buildpack-cached-v0.1.0.zip.part* > R_buildpack-cached-v0.1.0.zip

