Example Usage
~~~~~~~~~~~~~
Example usage of ``activity-description`` within a ``location`` of an ``iati-activity``.:

.. literalinclude:: ../../../activity-standard-example-annotated.xml
	:language: xml
	:start-after: <!--location-single starts-->
	:end-before: <!--location ends-->
	:emphasize-lines: 10, 12
	

Changelog
~~~~~~~~~

2.01
^^^^
Freetext is no longer allowed with this element.  It should `now be declared <http://iatistandard.org/upgrades/integer-upgrade-to-2-01/2-01-changes/#narrative-new-elements>`__  with the new child ``narrative`` element.

1.04
^^^^
The ``activity-description`` element was introduced in 1.04.
