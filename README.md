# Integrated Pipeline Demo Cartridge 
The purpose of this repository is to define an [ADOP cartridge](https://accenture.github.io/adop-cartridges-cookbook/) that demonstrates [this technique](https://markosrendell.wordpress.com/2014/05/28/reducing-continuous-delivery-impedance-part-2-solution-complexity/) (as also described in [this video](https://www.youtube.com/watch?v=p98wXeHc9hk&t=8s)).

## Stucture
A cartridge is broken down into the following sections:

 * infra
  * For infrastructure-related items
 * jenkins
  * For Jenkins-related items
 * src
  * For source control-related items

## Metadata
Each cartridge should contain a "metadata.cartridge" file that specifies the following metadata:

 * `CARTRIDGE_SDK_VERSION`
  * This defines the version of the Cartridge SDK that the cartridge conforms to
 
## Using this Repository
Start [here](https://accenture.github.io/adop-docker-compose/docs/quickstart/) and progress to [here](http://accenture.github.io/adop-docker-compose/docs/operating/cartridges/).
