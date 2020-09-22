apuntando al repo-grupo:
==> pip install paqmulti -i http://localhost:8081/repository/mirepo-group/simple

C:\gh\modulo3_test>pip install paqmulti -i http://localhost:8081/repository/mirepo-group/simple
==================

Looking in indexes: http://localhost:8081/repository/mirepo-group/simple
Collecting paqmulti
  Downloading http://localhost:8081/repository/mirepo-group/packages/paqmulti/1.0.0/paqmulti-1.0.0.tar.gz (1.4 kB)
  Building wheels for collected packages: paqmulti
  Building wheel for paqmulti (setup.py) ... done
  Created wheel for paqmulti: filename=paqmulti-1.0.0-py3-none-any.whl size=1506 sha256=0510461cdf70441406fad9c1ec2e81b9b77c530409200ffd6c5c601e29cbaa39
  Stored in directory: c:\users\mp\appdata\local\pip\cache\wheels\7a\e5\a6\4fd70bb2a3ad3304abe103fba96257d2c931a22a96ccce84c5
Successfully built paqmulti
Installing collected packages: paqmulti
Successfully installed paqmulti-1.0.0

C:\gh\modulo3_test>pip list   | find /i "paq"
paqmulti          1.0.0

#######################################################################################################################################################
apuntando al repo-hosted
pip install paqmulti -i http://localhost:8081/repository/mirepo-hosted/simple

C:\gh\modulo3_test>pip install paqmulti -i http://localhost:8081/repository/mirepo-hosted/simple
Looking in indexes: http://localhost:8081/repository/mirepo-hosted/simple
Collecting paqmulti
  Downloading http://localhost:8081/repository/mirepo-hosted/packages/paqmulti/1.0.0/paqmulti-1.0.0.tar.gz (1.4 kB)
Building wheels for collected packages: paqmulti
  Building wheel for paqmulti (setup.py) ... done
  Created wheel for paqmulti: filename=paqmulti-1.0.0-py3-none-any.whl size=1506 sha256=62cfa987bc693fdf23d5e3595072852bc16e2c559500032ac9b0c0c07e111aa2
  Stored in directory: c:\users\mp\appdata\local\pip\cache\wheels\6b\97\14\086635e6ae3cab40511290300152495cf7cab1591b1985616b
Successfully built paqmulti
Installing collected packages: paqmulti
Successfully installed paqmulti-1.0.0

#######################################################################################################################################################
#pipenv install paqmulti==1.0.0

pipenv install paqmulti -i http://localhost:8081/repository/mirepo-group/simple