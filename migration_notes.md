git clone git@github.com:lh3/bwa
master @ 139f68fc4c3747813783a488aef2adc86626b01b
git branch apache2_update
git cherry-pick -x 55329cd89224638b437311f4a4e8bfb46bf5be1f
manually merge in other changes in Apache2 branch, excluding changes to
bwamem.c 
git commit ...
apache2_update @ 0459f92cfaff3d571cf95b85ee0e49e5fd1f9200
