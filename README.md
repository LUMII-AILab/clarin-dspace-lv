[![Build Status](https://travis-ci.org/ufal/clarin-dspace.svg?branch=lindat)](https://travis-ci.org/ufal/clarin-dspace)
# clarin-dspace repository

* developed at: [Institute of Formal and Applied Linguistics, Charles University](http://ufal.mff.cuni.cz/)
* primary deploy at: https://lindat.mff.cuni.cz/repository/xmlui/
* contact: https://lindat.mff.cuni.cz/en/about-lindat-clarin or better clarin's slack https://clarineric.slack.com/messages/dspace/
* wiki: https://github.com/ufal/lindat-dspace/wiki
* release notes: [Release Notes](https://github.com/ufal/lindat-dspace/wiki/ReleaseNotes)

# clarin-dspace deployments

* LINDAT/CLARIN: https://lindat.mff.cuni.cz/repository/xmlui/
* CLARINO: https://repo.clarino.uib.no/xmlui/
* CLARIN.SI: https://www.clarin.si/repository/xmlui/
* CLARIN-PL: https://clarin-pl.eu/dspace/
* CLARIN-IT
    * ILC4CLARIN: https://dspace-clarin-it.ilc.cnr.it/repository/xmlui/
    * ERCC: https://clarin.eurac.edu/repository/xmlui/
* CLARIN-ES:
* CLARIN-LT:
* SWE-CLARIN:
* CLARIN-DK: https://repository.clarin.dk/repository/xmlui/
* University of Oxford - Oxford Text Archive:
* RDA EU – ENVRI Summer School:
* Centrum orální historie ÚSD AV ČR:
* Národní filmový archiv:
* Ústav pro studium totalitních režimů:

There are several instances in other institutes which will join the list shortly.
*If you are using or plan to use clarin-dspace, please get in touch.*


# Installation instructions

First, ensure that all of the [requirements](https://github.com/ufal/clarin-dspace/wiki/Installation----Prerequisites) are met.
Afterwards, [install repository](https://github.com/ufal/clarin-dspace/wiki/Installation)

If you are familiar with vagrant and puppet then go directly to
[shell script executed by Vagrant](https://github.com/ufal/lindat-repository-vagrant/blob/master/Projects/setup.lindat.sh).
Optionally, you can also inspect our [travis integration](https://github.com/ufal/clarin-dspace/blob/lindat/.travis.yml).

Our colleagues at the [ERCC](https://clarin.eurac.edu) have developed a dockerized version of clarin-dspace. It can be found on their [gitlab](https://gitlab.inf.unibz.it/commul/docker/clarin-dspace).

## Other projects used by clarin-dspace

* https://github.com/ufal/lindat-common
* https://github.com/ufal/lindat-aai-discovery

Note: You should fork these projectbecause they will very likely require changes specific to your deployment.


## Projects somehow related to clarin-dspace repository

* https://github.com/ufal/lindat-repository-vagrant
* https://github.com/ufal/public-license-selector
* https://github.com/ufal/lr-b2safe-core
* https://github.com/ufal/lr-b2safe-dspace
* https://github.com/ufal/lindat-aai-info
* https://github.com/ufal/lindat-aai-shibbie
