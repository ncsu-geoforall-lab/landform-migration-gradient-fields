Mapping gradient fields of landform migration
=============================================

These are slides for presentation of mapping gradient fields of landform
migration and spatio-temporal contour evolution project.


Authors
-------

* Vaclav Petras, NCSU OSGeoREL
* Helena Mitasova, NCSU OSGeoREL
* Anna Petrasova, NCSU OSGeoREL


Presentation online and at conferences
--------------------------------------

Slides online:

* http://ncsu-geoforall-lab.github.io/landform-migration-gradient-fields/

Events where some version of slides was used or will be used:

* `Geomorphometry 2015 <http://geomorphometry.org/content/geomorphometry-2015-programme>`_
* `MEAS 2014-2015 Seminar and Defense Series <http://www.meas.ncsu.edu/05-seminars.html>`_


Presented software
------------------

* https://github.com/ncsu-geoforall-lab/spatio-temporal-contour-evolution


Building the slides
-------------------

To build the presentation slides with instructions::

    mkdir build
    ./build.sh

The open the file ``build/index.html``.


Building and publishing pages for this repository
-------------------------------------------------

Clone the repository::

    git clone repository-url repository-name

Create a build directory with gh-pages branch using a dedicated script.
This will clone again into a subdirectory directory and switch
to ``gh-pages`` branch in this clone.

::

    ./get-gh-pages-branch.sh

To build the presentation during writing use::

    ./build.sh

Once your are ready to publish presentation as as website, use::

    ./publish.sh

You have to commit and push all your local changes before that.

Rarely, if you change the Reveal.js files, use::

    ./copy-common-files.py --dst-dir=build


About format of slides
----------------------

Presentation is using on Reveal.js HTML Presentation Framework.

* http://lab.hakim.se/reveal-js/#/
* https://github.com/hakimel/reveal.js/

Learn more about used template:

* https://github.com/ncsu-geoforall-lab/lecture-slides-template
