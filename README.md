
DMX Thymeleaf
=============

A DMX plugin for server-side HTML generation based on the Thymeleaf template engine.

DMX is a platform for collaboration and knowledge management.
<https://git.dmx.systems/dmx-platform/dmx-platform>

Thymeleaf template engine:  
<http://www.thymeleaf.org/>

License
-------

DMX Thymeleaf is available freely under the GNU General Public License, version 3 or later.

All third party components incorporated into the DMX Thymeleaf Software are licensed under the original license provided by the owner of the applicable component. Thymeleaf 2.1.3, OGNL 3.0.6, Unbescape 1.1.3 are Apache-2.0 licensed. Java Assist 3.11.0-GA and 3.16.1-GA are MPL-1.1 licensed.

Version History
---------------

**0.8.0** -- Jul 23, 2019

* Compatible with DMX 5.0-beta-4
* Added GPL License to Repository

**0.7.0** -- Apr 25, 2019

* Adapted to be compatible with DMX 5.0-beta-2
* Changed groupId to systems.dmx
* Changed artifactOId to dmx-thymeleaf

**0.6.2** -- Mar 31, 2018

* Added custom events for 3rd party _viewData()_ usage
* Exposes _AbstractContext_ to 3rd party plugins

**0.6.1** -- Aug 05,2016

* Makes overriding template by filename across many bundle resource resolvers work as expected again

**0.6** -- Aug 04, 2016

* Support for setting up many `BundleResourceResolvers`
* Resolve included th:fragments by their template name only
* Thymeleaf Upgrade: 2.0.18 -> 2.1.3

**0.5** -- Apr 17, 2016

* Renamed from "DM4 Web Activator" to "DM4 Thymeleaf".
* Compatible with DeepaMehta 4.8

**0.4.6** -- Oct 24, 2015

* Compatible with DeepaMehta 4.7

**0.4.5** -- Aug 19, 2015

* Compatible with DeepaMehta 4.6

**0.4.4** -- Dec 2, 2014

* Fix: Thymeleaf logging via SLF4J works.
* Compatible with DeepaMehta 4.4

**0.4.3** -- Jun 8, 2014

* Compatible with DeepaMehta 4.3

**0.4.2** -- Feb 18, 2014

* Compatible with DeepaMehta 4.2

**0.4.1** -- Dec 14, 2013

* Compatible with DeepaMehta 4.1.3

**0.4** -- Sep 2, 2013

* Access session attributes from within template.
* Concurrent requests to the same web application.
* Deployment of more than one web application at the same time.
* Updated Thymeleaf 2.0.16 -> 2.0.18
* Compatible with DeepaMehta 4.1.1

**0.3.1** -- Mar 19, 2013

* Updated Thymeleaf 2.0.14 -> 2.0.16
* Uses deepamehta-plugin-parent as the parent POM.
* Compatible with DeepaMehta 4.1

**0.3** -- Dec 24, 2012

* Compatible with DeepaMehta 4.0.13

**0.2** -- Nov 17, 2012

* Hides Thymeleaf from the webapp developer. Uses Jersey's Viewable abstraction instead.
* The WebActivatorPlugin base class replaces the ThymeleafService.
* Project is renamed to "DeepaMehta 4 Web Activator" (formerly "DeepaMehta 4 Thymeleaf").
* Compatible with DeepaMehta 4.0.13-SNAPSHOT (branch "master" or "neo4j-1.8")

**0.1** -- Nov 16, 2012

* Provides ThymeleafService
* Compatible with DeepaMehta 4.0.13-SNAPSHOT (branch "master" or "neo4j-1.8")


Authors
-------

Copyright (C) 2012-2014 Jörg Richter <jri@dmx.berlin><br/>
Copyright (C) 2013 Danny Gräf <github@dagnu.de><br/>
Copyright (C) 2015, 2016, 2018 Malte Reißig <malte@mikromedia.de><br/>
Copyright (C) 2019 DMX Systems <https://dmx.systems><br/>
