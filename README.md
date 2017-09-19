# Monbijou - dev-deploy

Repo for deploying dev-builds of https://github.com/monbijou/monbijou to https://adriansacchi.github.io/monbijou-devdeploy/

## HOWTO deploy

1. rebuild https://github.com/monbijou/monbijou

    ````ng build --prod --base-href "https://adriansacchi.github.io/monbijou-devdeploy/"````
2. copy output to root of https://github.com/adriansacchi/monbijou-devdeploy
3. commit and push to master

