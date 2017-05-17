
# Debian rebuild release process. Revisit here.

1. dget http://http.debian.net/debian/pool/main/c/ceres-solver/ceres-solver_1.12.0+dfsg0-1.dsc
2. cd ceres-solver*
3. dch -Dtrusty -l"~trusty" "Rebuild for trusty"
4. debuild -S
