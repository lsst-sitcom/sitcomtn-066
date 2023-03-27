:tocdepth: 1

.. sectnum::

.. Metadata such as the title, authors, and description are set in metadata.yaml

.. TODO: Delete the note below before merging new content to the main branch.

.. note::

   **This technote is a work-in-progress.**

Abstract
========

During observing, it has been noticed that the encoders sometimes disagree with one another by significant amounts (up to 100+ degrees). Here we look at data from several days to try to find systematic patterns.

Encoder Disagreement
====================

The following plots show the individual encoder positions as a function of time versus the "ActualPosition". The position given by the individual encoders seems to sometimes jump out of agreement with the others and to stay that way for up to a few hours. This behavior is seen in multiple encoders.

Occassionally, encoder 3 will register a 360 offset in azimuth from the other encoders. This is presumably not inherently a problem, but could affect which encoders are used to calculate the "ActualPosition". (Note that In the included plots, the startracker is also sometimes off by 360 degrees.)

The ActualPosition sometimes goes to zero, but this seems to happen independently for the azimuth and elevation. The small (<5 degree), high-frequency differences between the individual encoders and the ActualPosition seem to always happen during slews, where the encoders are sometimes all systematically offset from the ActualPosition.

03-15-2023:
.. figure:: /_static/EncoderDisagreement_03_15.png 

03-16-2023:
.. figure:: /_static/EncoderDisagreement_03_16.png 

03-17-2023:
.. figure:: /_static/EncoderDisagreement_03_16.png 

03-18-2023:
.. figure:: /_static/EncoderDisagreement_03_16.png 

03-21-2023:
.. figure:: /_static/EncoderDisagreement_03_21.png 

03-22-2023:
.. figure:: /_static/EncoderDisagreement_03_22.png 

03-23-2023:
.. figure:: /_static/EncoderDisagreement_03_23.png 

